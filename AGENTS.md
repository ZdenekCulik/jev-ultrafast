# Jev Ultrafast

- One TypeSafe request chooses the operation and speculative operation-specific target heads from observed indexed elements; consume only the selected operation's target. No site-specific plans, hardcoded field values, invented selectors or executable model output.
- TYPE_TEXT uses the text LLM; reuse generated values on stale-page retries only while the entire helper input is unchanged. Never retry browser mutations; log execution before observation.
- Screenshots are optional and never consumed by the model.
- DONE needs independent outcome verification. Keep evidence/call counts honest and demo speed unchanged.
- Credentials stay server-side; keep `.env` ignored; tests make no paid calls. No commit/push unless requested.
- Checks: `uv run ruff check .`, `uv run pytest`, `node --check jev_ultrafast/static/app.js`, `node --check jev_ultrafast/snapshot.js`, `uv build`.
