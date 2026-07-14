# PR Response Doc — CineLog Watchlist Feature

## AI Usage
<!-- Fill in at the end — how you used AI tools during this project -->

## Comment 1 — Rename
**What I did:** I renamed `save_to_watchlist()` to `add_to_watchlist()` everywhere throughout the project to follow the repository's `verb_to_noun` naming convention.

**How I verified:** I ran:

```bash
pytest tests/ -v 
```
All tests passed successfully.

## Comment 2 — Deduplication
**What I did:**
**How I verified:**

## Comment 3 — Missing test
**What I did:** I created `tests/test_watchlist.py` and added a test to verify that attempting to add a nonexistent film to a user's watchlist raises `FilmNotFoundError`.
**How I verified:** I ran:

pytest tests/test_watchlist.py -v

## Comment 4 — Default visibility
**My position:**
**Reasoning:**
**Tradeoff acknowledged:**

## Comment 5 — Sort order
**My position:** 
**Reasoning:**
**Engagement with reviewer's point:**

## Comment 6 — Rebase
**What conflicted:**
**How I resolved it:**
**How I verified no conflict remains:**

## PR Description
<!-- Written at the end — feature overview, design decisions, manual testing steps -->