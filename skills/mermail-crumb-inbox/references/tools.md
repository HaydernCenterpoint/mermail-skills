# Tool routing

This skill does not own Mermail MCP tools.

- List/search/read mail: `$mermail-manage-inbox`
- Draft/reply/send: `$mermail-compose-email` after an exact preview and approval
- Wallet/PayBox: out of scope. Never invoke from this skill.

Pass MCP arguments as native JSON objects, never stringified JSON. Prefer mailbox `public_id` as `mailboxId`.
