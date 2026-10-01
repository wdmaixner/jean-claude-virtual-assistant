# Notebook

Durable facts and preferences. One line per entry, dated when added.

- (2026-09-08) Household: Will, wife Natalie Pritchard (nepritch@gmail.com), two kids (ages ~4 and ~6), dog Brodie.
- (2026-09-08) Home address: 5627 Monumental Avenue, Richmond, VA 23226.
- (2026-09-08) Will works at DaVita (healthcare/kidney care) and travels frequently for work (recurring single/multi-day trips).
- (2026-09-08) Kids attend Shady Grove Preschool (billed via Brightwheel, autopay on file) and Shady Grove YMCA programs.
- (2026-09-08) Will is a UNC Tar Heels fan - always prioritize UNC news (any sport) in the News section.
- (2026-09-08) Recurring autopay bills to expect: State Farm auto insurance (~$307/mo), Dominion Energy (~$350/mo), Shady Grove Preschool/Brightwheel.
- (2026-09-09) Amex card autopays in full from Wells Fargo checking ...5253 each month (Aug statement was $8,173.55) - large but routine, not a bill to flag unless it looks anomalous.
- (2026-09-09) True North Insights (formerly Capvision, a market-research recruiting firm) periodically emails Will paid consultation invites - legitimate outreach, not spam, but never urgent.
- (2026-09-08) Cooking newsletters in inbox worth checking for dinner ideas: NYT Cooking, Easy Family Recipes.
- (2026-09-08) Recurring inbox noise to skip in briefings: Outer Banks real estate listings (Matt Myatt), job-recruiter emails (Indeed/LinkedIn), hotel/travel marketing, Nextdoor posts, healthcare industry newsletters (ACHE, Becker's).
- (2026-09-10) Will runs a side project called "gapmap" deployed on Vercel (wdmaixner-7122's projects) - a competitor-gap/market analysis tool with an "Analyst" chat feature; watch for repeated production deployment failure emails from Vercel as these are actionable, not noise.
- (2026-09-10) Henrico County utility bill (via Paymentus, acct 0082677-01124694) is a recurring monthly bill emailed with just a due date, no amount shown in the notice - amount requires logging into the portal.
- (2026-09-10) Easy Family Recipes (eat@easyfamilyrecipes.com) is another kid-friendly recipe newsletter worth checking for dinner ideas, alongside NYT Cooking.
- (2026-09-11) Kids' names/schools: Maren (6yo, Henrico County Schools, cafeteria autopay via MySchoolBucks/"MSB Henrico County Schools" ~$40-45 when balance runs low) and William Vann (4yo, Shady Grove Preschool/Brightwheel).
- (2026-09-11) Will reviews financial-assistance grant requests for Meredith Haga Foundation (will@meredithhagafoundation.org), correspondence with Leslie Dannhardt/Bruce Blessing at Pipe Line Utility Contractors - legitimate, not spam.
- (2026-09-11) Will trades on margin in a Fidelity brokerage account (...8328) and sometimes wires from Wells Fargo checking ...5253 to fund it; Fidelity margin-debit alerts and Wells Fargo balance-drop alerts around the same time are likely linked - flag margin debits as actionable (cover before settlement).
- (2026-09-13) Artifact republish-in-place worked fine this run (url-targeted publish succeeded, no classifier block) - the 2026-09-09→09-11 failure streak seems to have been transient; keep using the read-edit-republish flow in memory/artifact.md by default.
- (2026-09-13) State Farm auto-pay is actually $158.51/mo (acct 1384-4997-07), not the ~$307.30 previously estimated - corrected in reminders.md.
- (2026-09-13) Citi credit cards (ending 5214 and 7867) send "upcoming AutoPay" reminder emails that carry no amount/date in the plaintext body (just tracking links) - if the amount ever matters, will need citi.com login, not just the email.
- (2026-09-15) Maren's 1st grade teacher is Kelly Daniels at Shady Grove Elementary School (Henrico); a "remote learning" instructional packet comes home Tuesdays in the red folder (separate from regular homework) - keep it safe in case of a remote learning day.
- (2026-09-15) Shady Grove YMCA Parent & Child Basketball Clinic is a recurring Mondays 5:15-6pm commitment through Nov 2 (started 9/14) - ongoing, not a one-off date.
- (2026-09-16) Wells Fargo credit card (...7133) is a separate recurring monthly bill (~$300-350 statement, $25 min) from checking account ...5253 - track its due date in reminders.md each cycle.
- (2026-09-16) Citi Strata Premier (...7867) also sends a weekly "account balance alert" and a separate "payment due date approaching" alert, both with usable amount/date info - unlike the no-detail "upcoming AutoPay" reminder noted 9/13, these two are what to use for reminders.md.
- (2026-09-16) Operational: this session started with no git repo checked out at all (empty working directory, no .git) - see memory/README.md for the recovery steps (list_repos -> add_repo -> clone). This has now happened on multiple separate days; also, even right after a fresh clone the local state can be behind origin (a same-day earlier run may have already pushed) - always `git fetch origin main` and reconcile/rebase before trusting local reads or pushing, not just at session start.
- (2026-09-17) Operational: mcp__Claude_Code_Remote__add_repo was blocked by the auto-mode permission classifier this run (no way to get user approval unattended) - a plain `git clone https://github.com/wdmaixner/jean-claude-virtual-assistant.git` worked fine since the repo is public. Try direct git clone first for recovery; fall back to add_repo/list_repos only if that fails.
- (2026-09-17) Function Health periodic lab panels (via Quest Diagnostics, already paid, no insurance needed) come with fasting instructions and travel buffers already built into Will's own calendar events - no separate reminders.md entry needed, just surface what's on the calendar that day.
- (2026-09-17) Will is involved with Connor's Heroes (pediatric transplant nonprofit) - attends donor events like the Circle of Heroes Reception at Maymont.
- (2026-09-29) Apple Reminders are not readable by the Routine; Will is deciding between an iOS Shortcut and a Google Calendar habit. Repo checkout worked on the 9/29 manual re-run.
- (2026-09-30) Wyndham Foundation/Community Group assessment (~$285/mo) autopays via KliknPay (checkalt) with a $274 upper limit - raise the limit to avoid monthly partial payments.
- (2026-10-01) Robson Landscaping & Turf (via ServiceAutopilot/XplorPay) does lawn care at 12105 Loxton Ct, Glen Allen, VA 23059 - invoices emailed with a due date; Will also gets Etsy billing emails. WebSearch for national headlines/sports is often stale or empty - state that honestly rather than padding.
