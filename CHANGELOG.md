# Handsom connector changes

Tools that were renamed or removed, newest first. New tools aren't listed: your agent sees them once it reconnects. After a change here, reconnect the connector (in Claude Code, `/mcp`, then handsom).

## Tools version 2 (8 November 2026)

- `read_help_centre` is now `read_articles`.
- `read_answers`, `add_answer`, `edit_answer` and `remove_answer` are gone. Answers are articles now: write one with a `helpArticle` item in `save_change`, and turn on `exactWords` for wording that must be sent as written.
