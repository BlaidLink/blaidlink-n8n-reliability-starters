# Blaidlink n8n Reliability Starters

Three credential-free n8n workflow templates for testing reliable automation patterns before connecting production systems.

## Included workflows

### Resilient REST API Sync

`workflows/resilient-rest-api-sync.json`

- Fetches sample API records.
- Normalizes and validates the response.
- Separates successful output from sanitized failure evidence.
- Demonstrates bounded retries without embedding credentials.

### Automation Lead Intake Scorer

`workflows/lead-intake-scope-scorer.json`

- Scores a sample automation request for fit and delivery risk.
- Produces a transparent recommendation instead of a black-box score.
- Helps decide whether to quote, clarify, phase, or decline a project.

### Website Change Monitor

`workflows/website-change-monitor.json`

- Compares controlled before-and-after page content.
- Produces deterministic fingerprints and structured change evidence.
- Separates added and removed terms for downstream review.

## Quick start

1. Download or clone this repository.
2. In n8n, choose **Import from File**.
3. Import one JSON file from `workflows/`.
4. Read the sticky notes before running it.
5. Run it with the included sample data.
6. Replace samples only after you understand the data and access boundaries.

These templates are designed to run without passwords, API keys, production data, or paid services. Test with fixtures first. If you later connect real systems, use least-privilege credentials stored in n8n's native credential manager.

## What these templates are—and are not

They are educational workflow starters and reproducible proof assets. They are not legal, security, privacy, tax, compliance, or financial advice. They do not guarantee uptime, revenue, or suitability for a production environment.

Never place passwords, private keys, recovery codes, seed phrases, or customer data directly in workflow JSON.

## Want the client-facing files?

- [Free: 7 n8n Failure Patterns](https://blaidlink.gumroad.com/l/n8n-failure-patterns-free?utm_source=github&utm_medium=repository&utm_campaign=n8n_reliability&utm_content=readme_free)
- [n8n Reliability Starter Kit — $12](https://blaidlink.gumroad.com/l/n8n-reliability-kit?utm_source=github&utm_medium=repository&utm_campaign=n8n_reliability&utm_content=readme_paid)
- [Automation Client Intake & Scope Kit — $15](https://blaidlink.gumroad.com/l/automation-client-scope-kit?utm_source=github&utm_medium=repository&utm_campaign=n8n_reliability&utm_content=readme_scope)

Need a bounded workflow review instead? [View the live n8n, Make, and Zapier audit service](https://www.fiverr.com/blaidlink/audit-troubleshoot-and-fix-your-n8n-make-or-zapier-workflow?utm_source=github&utm_medium=repository&utm_campaign=n8n_reliability&utm_content=readme_service).

## License

MIT. See [LICENSE](LICENSE).
