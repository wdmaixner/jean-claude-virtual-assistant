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

Keep entries short and dated. This is a notebook, not a transcript — prune
stale or completed items rather than appending forever.
