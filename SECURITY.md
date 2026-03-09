# Security Policy

## Reporting a Vulnerability

Open a [GitHub Security Advisory](https://github.com/AgriciDaniel/automated-business-analysis-workflow/security/advisories/new) on this repo or contact the maintainer directly.

## Supported Versions

Only the latest version receives security updates.

## Credential Handling

Workflow JSON files use **placeholder values** for webhook IDs and API credentials. Before importing into n8n:

1. Replace `YOUR-WEBHOOK-ID-HERE` with your own webhook ID
2. Replace `YOUR-API-KEY` with your actual API keys
3. Configure your own API credentials in n8n's credential store (Firecrawl, Perplexity, Google Gemini, Google Workspace)
4. Never commit real API keys, webhook UUIDs, or passwords to this repository
