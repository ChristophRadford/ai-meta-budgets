# AI Meta Budgets

Automation tooling for managing **Meta (Facebook/Instagram) campaign budgets** at scale.

This project is designed to help media and media-ops teams:
- Ingest campaign / ad set data
- Apply rules-based and/or model-driven budget recommendations
- Export a clean file that can be uploaded or pushed back into platforms or workflow tools

> Built as part of operational automation work for Meta campaigns at PHD.

---

## Features

- ✅ Ingest Meta performance & budget data from CSV (e.g. exported from platform or reporting tool)
- ✅ Apply configurable business rules (guardrails, floors/ceilings, pacing logic)
- ✅ Output a transformed CSV ready for upload or further automation
- ✅ Simple CLI / script entry point via `app.py`

*(Update this list to reflect what the script actually does.)*

---

## Project Structure

```text
ai-meta-budgets/
├─ app.py                # Main entry point for running the automation
├─ Test Meta Budget Automation.csv  # Example / test input file
├─ requirements.txt      # Python dependencies
└─ README.md             # Documentation
