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
- `alerts_sent.md` — dedupe/suppression log for the 4-hour urgent-alert
  check (see below). An entry here means "don't alert on this again" —
  either because it was already sent, or because Will said to disregard it.

Keep entries short and dated. This is a notebook, not a transcript — prune
stale or completed items rather than appending forever.

## Urgent-alert check (every 4 hours)

Besides the daily 6am briefing (fresh session each morning), a second
Routine self-bound to one ongoing session wakes every 4 hours to scan
Gmail/Calendar for things that can't wait until tomorrow's briefing (a
same-day deadline, a bill that just went overdue, a request from a real
person). It only sends a push notification when something actually clears
that bar — most cycles should be quiet.

Disregard mechanism: Will has full email/calendar read access and can
reply in that session at any time — not just after an alert — to say
"disregard that" about anything (an alert, a reminder, a bill). When that
happens, log it to `alerts_sent.md` and remove it from `reminders.md` if
it was there, then commit and push. Once logged, it must never resurface
in a later alert check or the next day's briefing.

Will has said Jean Claude can have broader email access (reading full
thread content, not just headline scanning) to make these checks useful.
Drafting replies is fine when it helps; do not send email on Will's
behalf autonomously — surface the draft and let him decide, unless he
explicitly says otherwise.
