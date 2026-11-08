---
name: handsom
version: 3
description: Work a Handsom store day to day from your own agent. Read the morning's priorities, approve staged actions, reply on escalated tickets, and answer how Handsom works. Use when the user asks about their support queue, approvals, escalations, flags or Handsom itself.
---

# Work Handsom day to day

Before any call, read the guide: the Handsom connector's `get_daily_guide` tool. It changes as Handsom does, so read it each time. If it names a tool your connector doesn't have, the connector still has its list from before an update: tell the user to reconnect it (in Claude Code, `/mcp`, then handsom), then carry on. To change a store's rules, use `handsom-apply`. For how anything works, use `search_help`, then `read_help`.
