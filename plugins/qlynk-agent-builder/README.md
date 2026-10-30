# Qlynk Agent Builder

Qlynk Agent Builder helps freelancers, agencies, consultants, and businesses turn approved company information into an accurate, maintainable Qlynk Agent.

It runs a guided Quick or Advanced client interview, identifies missing or contradictory information, maps approved knowledge into Qlynk's configuration fields, prepares facts and FAQs, creates launch tests, and produces a client-owned handoff.

## What it produces

- A client discovery and approval record
- Agent purpose, audience, scope, tone, and behavior
- Copy-ready facts and FAQs
- Approved documents and website sources
- Uncertainty, blocked-topic, and human-handoff rules
- A minimum 12-question launch test
- A client ownership and maintenance handoff

## Example prompts

### Quick client setup

> Use Qlynk Agent Builder to create a Qlynk Agent for a local air-conditioning company. Use Quick setup, ask one short question at a time, and prepare a Build Pack before publishing anything.

### Advanced setup

> Use Advanced setup to design a Qlynk Agent for a boutique hotel. Identify the audiences, approved guest information, restricted topics, escalation routes, and launch criteria. Do not publish without approval.

### Review an existing knowledge base

> Review these company FAQs for a Qlynk Agent. Separate verified information from drafts, contradictions, missing approvals, and sensitive material. Then prepare copy-ready facts, FAQs, boundaries, and a launch-test checklist.

## Using the plugin

Install it in Claude Code 2.1.275 or later:

```text
/plugin install qlynk-agent-builder --marketplace randomzzguy/qlynk-agent-builder
```

In Claude chat or Cowork, ask naturally:

> Build a Qlynk Agent for my client using the Quick setup.

In Claude Code, invoke:

```text
/qlynk-agent-builder:build-qlynk-agent
```

## Data handling and permissions

This plugin is a human-readable instructional bundle. It contains no MCP server, hooks, executable code, analytics, telemetry, or automatic network requests.

It may process business information and contact details that the user intentionally supplies in the active Claude conversation. It instructs Claude to exclude passwords, payment information, API keys, one-time codes, identity documents, private customer records, and unnecessary personal data.

The plugin does not independently store information. If the user explicitly asks Claude to enter approved content into Qlynk through an authorized browser session, that content is handled according to the [Qlynk Privacy Policy](https://www.qlynk.site/privacy). Publishing, billing changes, and live website installation require confirmation.

## Ownership

The client should control the Qlynk account email, account recovery, billing, source files, public username, and final approval. Freelancers may charge separately for discovery, configuration, testing, installation, training, and maintenance.

## Support and policies

- [Documentation](https://www.qlynk.site/agent-builder)
- [Support](https://github.com/randomzzguy/qlynk-agent-builder/issues)
- [Privacy](https://www.qlynk.site/privacy)
- [Terms](https://www.qlynk.site/terms)

## License

MIT License. See [LICENSE](./LICENSE).
