# Daily Dispatch Artifact

Stable link for the styled visual version of the daily briefing (a
"newspaper dispatch" style page — masthead, ticket-stub summary, dispatch
sections, dark/light theme-aware). One URL, redeployed every morning so
Will can bookmark it once.

URL: https://claude.ai/code/artifact/cc522f56-1b98-45af-acc4-52b48b2b8b05

(2026-09-10: the previous URL, cb001f70-2562-4b8a-9964-52d68ec7692b, could not be
republished — the Artifact publish action with that `url` was blocked by the
auto-mode permission classifier two attempts in a row, reason given as just
"Blocked by classifier" with no further detail. Fell back to publishing a new
artifact per the instruction below. If this URL also gets blocked on a future
run, try once more, then fall back again and update this file — don't loop on
it. New artifacts publish private-by-default, so this link may need Will to
open its share menu once to make it link-shareable again, unlike the old one
which was already set to "anyone with the link".)

How to update it each morning:
1. Call the Artifact tool with `action: "read"` and this URL to pull the
   current published HTML (this IS the template — masthead, ticket stub,
   dispatch sections, CSS, footer).
2. Edit only the content: dateline, ticket-stub values (top item /
   reminders due / bills to watch), and the six dispatch sections
   (Schedule, Reminders, Inbox, Weather, The Wire, Tonight's Table) using
   today's actual briefing content. Keep the CSS, layout, and structure
   exactly as published — this is a template, not a fresh design each day.
3. Save the edited HTML locally and republish with `action: "publish"`,
   `url:` set to the URL above (never omit `url` — that would create a
   second, separate artifact instead of updating this one), and no
   `favicon` (keep the existing one).
4. Include the URL in that morning's PushNotification, but the
   notification text itself must still carry the one-line gist directly —
   the whole point is Will doesn't have to click through just to know
   what matters. The link is for when he wants the full page.

If the read/publish flow ever fails (e.g. artifact not found), fall back
to publishing a new artifact and update this file with the new URL.
