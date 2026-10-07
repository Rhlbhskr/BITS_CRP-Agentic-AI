# Feedback

Date: 2026-09-27

- Add your name to a file in this folder as your repo has a different name.
- Missing a Problem folder or file with the actual problem you want to solve. Please add one.
- No secrets found, good.
- Added a Python `.gitignore`.

## Week 1 skeleton review (2026-09-27)

Overall: 01–06 complete and clean; 07 (optional) not attempted.

- 01, 02: Done.
- 03: Done. *Automated PR Reviewer & Test Runner* is well scoped, with signatures and a checkable `done_when` that includes the failure path.
- 04: Done.
- 05: Done. `reflect()` returns `"CONFIRM"` on an empty reply (line 68); fail closed instead (e.g. `"REVISE: reflection unavailable"`).
- 06: Done.
- 07: Not attempted. Your 06 `dispatch` maps directly onto a `TOOLS` schema, so it's a good next step.
- Nice addition: Gemini 429 retry in `utils/llm_client.py`.

## Follow-up review (2026-10-07)

**Previous feedback:** Not implemented. There are no new commits since 26 Sep (last push: "Complete Week 2 activities"). Still open:
- Your name in a file in this repo: missing.
- Problem statement file: missing.
- 05: `reflect()` still returns `"CONFIRM"` on an empty reply; fail closed (e.g. `"REVISE: reflection unavailable"`).
- `main` still has the old `.gitignore`: merge the `feedback` branch (`git pull origin feedback`).

Please address the points above first, then push the rest of Week 2 (labs 00–06 were due Mon 5 Oct; the `project/` milestone is due Sat 10 Oct).
