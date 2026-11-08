---
name: handsom-apply
version: 3
description: Apply a brand's policies, documents and interview notes to its Handsom store from your own agent, or change how Handsom handles a kind of ticket. Use when the user has a brand's policies or notes to put into Handsom, or asks to change its rules, instructions, knowledge or voice.
---

# Apply a brand to Handsom

Before any call, read the guide: the Handsom connector's `get_guide` tool. It holds the procedure, what isn't a rule and how to finish. It changes as Handsom does, so read it each time.

If the guide's `min_skill_version` is above this skill's `version`, tell the user to update it: `claude plugin update handsom@handsom`.

If the guide names a tool your connector doesn't have, the connector still has its list from before an update: tell the user to reconnect it (in Claude Code, `/mcp`, then handsom), then carry on.

**Setup.** You sign in with your Handsom account when you first use the connector.
