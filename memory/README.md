# Jean Claude Memory

This folder is the persistent memory for the Jean Claude cloud routine. Each
run is a fresh, isolated session with no memory of previous runs except what
is committed here — so the routine reads these files at the start of a run
and writes back any updates (new facts, resolved reminders, new reminders)
before finishing, committing the change to this repo.

- `notebook.md` — durable facts about Will and his preferences (semantic
  memory). Update when something changes; don't duplicate entries.
- `reminders.md` — active reminders/to-dos with target dates. Remove an
  item once it's been surfaced and handled; don't let it grow unbounded.
- `artifact.md` — the stable URL for the styled visual "daily dispatch"
  page and how to redeploy it each morning. See that file for the exact
  read-edit-republish flow.

Keep entries short and dated. This is a notebook, not a transcript — prune
stale or completed items rather than appending forever.

Will has said he does NOT want intra-day urgent alerts (tried and removed
2026-09-09) — just the one daily 6am report. Don't suggest or re-add any
kind of alert/check-in routine unless he explicitly asks for it again.

Will has said Jean Claude can have broader email access (reading full
thread content, not just headline scanning) when useful for the daily
briefing. Drafting replies is fine when it helps; do not send email on
Will's behalf autonomously — surface the draft and let him decide, unless
he explicitly says otherwise.
