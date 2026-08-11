<p align="center">
  <h1 align="center">Can Models Hide Problems From Light Oversight</h1>
  <p align="center"><strong>Test whether models can produce code/data that looks fine under shallow review but fails deeper checks.</strong></p>
</p>

---

## Overview

This repository implements experimental profiles for **Can Models Hide Problems From Light Oversight**. Config, caching, hooks, metrics, ablations, reporting, and CI support local pilots on small open-weight models.

Hypothesis (one line): Test whether models can produce code/data that looks fine under shallow review but fails deeper checks.

## Status

Shared infrastructure is in place; domain stages must pass harness validation before any measured claim.

| Command | Purpose |
|---|---|
| `make install-dev` | editable install + pinned requirements |
| `make test` | full unit suite |
| `make ci` | lint + test + typecheck |
| `make pilot` | end-to-end pilot profile |
