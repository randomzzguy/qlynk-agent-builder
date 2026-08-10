# Qlynk Agent Builder

Build accurate, client-owned Qlynk Agents with a guided AI workflow.

The Qlynk Agent Builder interviews a client, turns approved company information into Qlynk's exact configuration fields, prepares facts and FAQs, tests difficult questions, and creates a professional handoff. It includes a five-question Quick setup and an Advanced path for complex or high-stakes agents.

## Who it is for

- Freelancers and consultants selling AI-agent setup services
- Web designers adding a Qlynk Agent to a client website
- Agencies standardizing client discovery and quality assurance
- Businesses building their own Qlynk Agent

The client should own the Qlynk account, recovery email, source files, billing, and final approval. The freelancer charges separately for discovery, setup, testing, embedding, and optional maintenance.

## Install as a plugin

Add this repository as a marketplace and install the plugin:

```text
codex plugin marketplace add randomzzguy/qlynk-agent-builder
codex plugin add qlynk-agent-builder@qlynk
```

Start a new Codex session after installation, then use:

```text
Use $build-qlynk-agent to build a Qlynk Agent for my client.
```

## Install the standalone skill

Copy `standalone/build-qlynk-agent` to:

- Personal: `$HOME/.agents/skills/build-qlynk-agent`
- Repository: `<repository>/.agents/skills/build-qlynk-agent`

Restart Codex if the skill does not appear. In Codex CLI or the IDE extension, use `/skills` or type `$` to select it.

## What it produces

- A source and approval ledger
- Qlynk identity, role, scope, and response settings
- Ready-to-paste facts and FAQs
- Approved document and website-source lists
- Public-page and website-widget configuration
- A minimum 12-question launch test
- A client ownership and maintenance handoff

## Example

```text
Use $build-qlynk-agent to create a Qlynk Agent for a local air-conditioning company. Use the five-question Quick setup and produce a client Build Pack before anything is published.
```

## Safety and accuracy

The workflow never treats an AI draft as a verified client fact. Prices, policies, guarantees, safety instructions, regulated advice, credentials, and private information require explicit approved sources or are omitted. Publishing, billing changes, and live website installation require confirmation.

## Learn more

- Qlynk Agent Builder: https://www.qlynk.site/agent-builder
- Create a Qlynk account: https://www.qlynk.site/auth/signup
- Privacy: https://www.qlynk.site/privacy
- Terms: https://www.qlynk.site/terms
- Support: info@qlynk.site

Copyright Qlynk AI. Public licensing terms will be added before third-party redistribution is formally opened.
