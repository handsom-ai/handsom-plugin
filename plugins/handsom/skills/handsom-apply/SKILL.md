---
name: handsom-apply
version: 2
description: Apply a brand's policies, documents and interview notes to its Handsom store from your own agent, or change how Handsom handles a kind of ticket. Use when the user has a brand's policies or notes to put into Handsom, or asks to change its rules, instructions, knowledge or voice.
---

# Apply a brand to Handsom

Before any call, read the guide: the Handsom connector's `get_guide` tool. It holds the procedure, what isn't a rule and the handover format. It changes as Handsom does, so read it each time.

If the guide's `min_skill_version` is above this skill's `version`, tell the user to update it: `claude plugin update handsom@handsom`.

**Setup.** You sign in with your Handsom account when you first use the connector.
