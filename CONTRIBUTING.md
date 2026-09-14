# Contributing to Contami

Org-wide defaults. A repo can override these with its own `CONTRIBUTING.md`.

## How we work

- English for code, docs, and analysis. Romanian only for legal documents
  between Romanian parties.
- Every change starts in a fresh worktree cut from updated `origin/main`, on a
  dedicated branch. Never in the bare checkout, never directly on `main`.
- Conventional commits (`feat:`, `fix:`, `chore:`, `refactor:`, `test:`,
  `docs:`), imperative subject, one logical change per commit.
- Tests for anything you add or change. Run them, plus lint and typecheck,
  before claiming done.
- Open a PR for every change, however small. CI green before merge.

## Rules that don't bend

- Never commit credentials, tokens, `.env` files, or personal data of real
  people (CNP, IBAN, addresses, invoices, signed contracts). Document
  templates use blanks (`________`).
- Fail loud and early. No silent catches.
- No dead code, no commented-out blocks, no TODO litter. Delete it or turn it
  into a tracked task.
