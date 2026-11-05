# Handsom

Set up and change your Handsom store from your own agent: rules, instructions, knowledge and voice, on your own model. This works for one store or, for a partner, every store that has approved you.

## Connect

Everything connects to one address, and you sign in with your Handsom account:

```
https://api.handsom.ai/mcp
```

**Claude Code.** This installs the connector and the skill that tells your agent how to apply a brand:

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

**ChatGPT and other agents.** Add the address above as a connector.

## Use it

Give your agent the brand's documents or interview notes, and ask it to apply them to the store. It reads the guide, checks each change, saves it and writes a handover. Changes to rules can be undone.

The guide is at https://api.handsom.ai/api/guide.
