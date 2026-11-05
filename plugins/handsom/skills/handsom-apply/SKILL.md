---
name: handsom-apply
version: 1
description: Apply a brand's policies, documents and interview notes to its Handsom store from your own agent, or change how Handsom handles a kind of ticket. Use when the user has a brand's policies or notes to put into Handsom, or asks to change its rules, instructions, knowledge or voice.
---

# Apply a brand to Handsom

Before any call, read the guide: the Handsom connector's `get_guide` tool, or `curl -fsSL https://api.handsom.ai/api/guide`. It holds the procedure, what isn't a rule and the handover format. It changes as Handsom does, so read it each time.

If the guide's `min_skill_version` is above this skill's `version`, tell the user to update it: `curl -fsSL https://api.handsom.ai/api/skills/install.sh | sh`.

**Setup.** With the Handsom connector, you sign in when you first use it. Without it, `HANDSOM_API_KEY` in the environment: a key made under Account in Handsom, which reaches every store you work on, or one made under a store's Settings → API keys, for that store alone. Every call: `Authorization: Bearer $HANDSOM_API_KEY`.
