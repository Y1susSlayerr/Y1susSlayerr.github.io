# n8n Workflow Reliability Resources

Free, privacy-first resources for reviewing exported n8n workflows before production.

- **Browser-only workflow audit:** https://workflow-hardening-lab.yisuspablo.chatgpt.site
- **Production error-handling guide:** https://y1susslayerr.github.io/n8n-error-handling.html
- **Webhook idempotency guide:** https://y1susslayerr.github.io/n8n-webhook-duplicates.html
- **Fixed-scope audit and hardening service:** https://www.fiverr.com/pablo_cif/audit-and-harden-your-n8n-workflows

The scanner runs entirely in the browser; workflow JSON is not uploaded. It checks for silent error continuation, missing retry settings, exposed webhooks, disconnected nodes, and credential-like values embedded in node parameters.

## Safety boundary

Static analysis cannot guarantee zero failures. Credentials, infrastructure, quotas, external-service behavior, and actual executions must be tested separately. Keep marketplace payments and communication inside Fiverr.

Independent project. Not affiliated with n8n or Fiverr.
