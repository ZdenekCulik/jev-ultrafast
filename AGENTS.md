# Jev Ultrafast

- Goal → observed indexed elements → one TypeSafe operation + matching target. No site-specific plans, invented selectors or executable model output.
- TYPE_TEXT uses the text LLM; reuse retries only for identical helper inputs. Never retry browser mutations; log execution before observation.
- DONE needs independent outcome verification. Keep evidence/call counts honest and demo speed unchanged.
- Credentials stay server-side; tests make no paid calls. No commit/push unless requested.
- Checks: `uv run ruff check .`, `uv run pytest`, `node --check jev_ultrafast/static/app.js`, `uv build`.
