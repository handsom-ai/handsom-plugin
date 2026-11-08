# Handsom

Run your Handsom store from your own agent: the queue, approvals and replies, and the rules, instructions, knowledge and voice, on your own model. This works for one store or, for a partner, every store that has approved you.

## Connect

Everything connects to one address, and you sign in with your Handsom account:

```
https://api.handsom.ai/mcp
```

**Claude Code.** This installs the connector and the skills that tell your agent how to work:

```
claude plugin marketplace add handsom-ai/handsom-plugin
claude plugin install handsom@handsom
```

**Claude.** Go to Customize > Plugins > Add > Add marketplace and enter this repository's URL. Then connect Handsom from the plugin's Connectors tab.

**Codex.**

```
codex mcp add handsom --url https://api.handsom.ai/mcp
codex mcp login handsom
```

**ChatGPT.** Add the address above as a custom MCP server, signing in with OAuth using Client ID Metadata Documents (CIMD).

## Use it

Ask your agent what needs you this morning, or how something in Handsom works. Give it a brand's documents or interview notes and ask it to apply them to the store: it reads the guide, checks each change, saves it and finishes with a short note: your questions, and what to check. Changes to rules can be undone.
