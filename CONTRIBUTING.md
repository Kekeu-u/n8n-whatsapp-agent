# Contributing

Thanks for helping improve this project.

This repo is focused on practical WhatsApp AI automation with n8n, WAHA, Redis, OpenAI and Supabase. Contributions should make the workflow easier to run, safer in production or clearer for other builders.

## How to contribute

1. Open an issue for bugs, ideas or larger changes.
2. Keep pull requests focused on one improvement.
3. Explain what changed and why it matters.
4. If you change `workflow.json`, make sure it imports cleanly in n8n.
5. Do not commit credentials, tokens, webhook IDs or private endpoints.

## Useful contribution areas

- Workflow reliability and error handling
- Safer credential and webhook setup
- Docker Compose and deployment examples
- Supabase schema improvements
- Human handoff patterns
- WAHA to WhatsApp Cloud API migration guides
- README examples, screenshots and troubleshooting notes

## Security

Never include real secrets in issues, pull requests or screenshots.

Before opening a pull request, scan your changes for obvious secrets:

```bash
rg "sk-|AIza|api.?key.*=.*['\"][a-zA-Z0-9]" --type-not md
```

If you find a security issue, avoid posting sensitive details publicly. Open a minimal issue saying there is a security concern so we can coordinate privately.
