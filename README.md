# My Assignments (W1–W8)

Isolated `uv` project and Git repo for the 8-week AI Engineering Fast-Track assignments, keeping the parent starter kit untouched.

## Setup
1. Fill in `OPENAI_API_KEY` and `OPENAI_MODEL` in `.env` (already gitignored).
2. Run commands from `my_assignments/` with `uv run`:
   - `uv run python ../scripts/smoke_test.py`
   - `uv run pytest -q ../tests/test_mock_jira.py`
   - `uv run pytest` (for tests added in `my_assignments/tests/`)

## Branches
- `main`: clean baseline environment
- `week-1` .. `week-8`: weekly branches (`week-1` and `week-2` are standalone; for `week-3`–`week-8`, merge/rebase the prior week or `main` as you progress).
