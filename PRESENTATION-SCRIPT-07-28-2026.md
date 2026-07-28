# Presentation Script — Bi-Weekly Update · Jul 28, 2026

**Deck:** `07-28-2026.html` · v0.9.0
**Presenter:** Isa · **Live demo:** Leo & Hyago (dev team)
**Runtime:** ~30 min

This is a speaking script that follows the deck section by section. Regular text is what you say; lines marked **Demo** are cues for the live demonstration and the handoff to Leo and Hyago.

---

## Cover (~1 min)

Open by welcoming everyone and framing the session. This is the bi-weekly update for the ROC Application, now on version 0.9.0. Set expectations early: the highlight today is a live demo — Incident Management running end-to-end with the real integration — and Leo and Hyago will drive that part. Flag as well that at the end of the session we'll discuss and give updates on the testing sections — the adoption plan and what we need to move it forward. Keep it short and move straight into the agenda.

---

## Agenda (~2 min)

Walk through the four blocks so people know where the session is going. Roadmap first — where we are and what's coming through Q3. Then the main event, Demo & Completed Items, where the dev team shows Incident Management live on both the app and the Command Center. After that, Next Developments — PCR, Roles & Permissions, Staff Onboarding with QR, and Live Activities. And finally the discussion: adoption planning, where you cover the four-phase testing approach, Phase 1 scope, the participant list, and the one thing the team needs set up by Friday.

---

## Roadmap (~4 min)

Give a quick snapshot of the timeline — each column is a two-week sprint, and we're at Jul 28, marked on the board. Everything on the left is already shipped: Tracking, Slot Allocation, Edit Race, Broadcasting 1.0, and the Global Dashboard.

The big change this cycle is that OEA-104 Incident Report and OEA-105 Incident View are now done and integrated — and that's exactly what we're about to demo. Call out PCR (OEA-11) as the next move: TK Miller approved the design, so it enters development this sprint and runs for roughly three sprints. Close the section by pointing further out — Live Activities in September, then Kiosk, Event Page Improvements, and Languages — and note that Broadcast 2.0 has been pushed, TBD for now.

---

## Demo & Completed Items — Live Demo (~10 min)

This is the heart of the session and the handoff to Leo and Hyago. You set it up, the dev team drives.

Frame it clearly: this cycle's headline is that Incident Management is live and integrated — not just screens, the real thing. The full field-to-command lifecycle now runs on live data, on both the app and the Command Center. Walk briefly through the two pieces before handing off. The Command Center is the web view for supervisors — all active events, the live incident feed, and athlete counts, now driven by real data coming in from the field. The Incident View covers the full lifecycle, from a field report through to command-center resolution, with a live course map and athlete medical context; V1 handles Medical, Weather, Transportation, and Others.

Then hand off: rather than talk through it, let's see it live — over to Leo and Hyago.

**Demo (Leo & Hyago).** Suggested flow to cover end-to-end: a staff member reports an incident on the app, picking an incident type; that incident appears live in the Command Center feed on web; a coordinator opens the Incident View and shows the course map, athlete medical context, and resource tracking (medics, ambulances, vehicles); and finally the incident is moved through to resolution, closing the field-to-command loop.

Once they wrap, close the section yourself — that's the whole loop live, on real data, from field report to command center to resolution — and thank Leo and Hyago before moving on.

---

## Next Developments (~4 min)

With incidents shipped, lay out what's next in a natural sequence. Roles & Permissions comes next sprint — adapting the whole app to the permissions matrix so every screen, action, and data view respects each user's role, using the same matrix we'll apply to the test-event permissions. PCR (OEA-11) follows: the design is approved by TK Miller, validation is done, and development starts next week, delivering post-incident reporting and medical documentation for event day. Then Staff Onboarding with QR in Q3 — fast credential and role assignment plus asset tracking at check-in — and Live Activities (OEA-103) in September, with the real-time feed of athletes in the water, on the bike, and on the run, aid stations, and course clearance. Wrap by mentioning what's coming up after that: Kiosk, Event Page Improvements, and Broadcast 2.0 further down the line.

---

## Discussion — Testing & Adoption Planning (~9 min)

Transition into how we actually roll this out, and anchor it with credibility: you validated the plan yesterday with John Bertsch and James Hines.

Start with the four-phase approach. Adoption goes in four phases, each gated by a feedback round and a go/no-go checkpoint before advancing. Phase 1 is a hybrid tabletop plus guided tasks, with no real race scenarios yet. Phase 2 keeps the same format but extends to a broader team beyond the core group. Phase 3 is a field test in shadow mode alongside a live race, and Phase 4 is a pilot at a chosen event with the app running live.

Then go into Phase 1 in detail. It's a one-hour remote session — roughly ten minutes for setup, thirty-five for guided tasks, and fifteen for live feedback — using Teams for facilitation, a FigJam board for feedback, and LogRocket to record and analyze the sessions afterward. In scope: login, profile, home dashboard, race page, chat, and live communications; incident management, PCR, and kiosk are reserved for later phases with the responsible ops teams. Web and app run in parallel, with leadership mostly on web and field staff on the app. To advance to Phase 2 we need no critical blocking bugs, a solid operational-confidence score from participants, and all improvement needs mapped and confirmed non-blocking.

Cover the participants briefly: Phase 1 stays tight, core group only — Drew Wolff, Ken High, Keats McGonigal, Beth Atnip, Courtney Smith, Robert Cerniglia, and Pat Riley — and the next step is scheduling the first session.

Land the asks clearly, because this is what you need out of the meeting. The key one is for Pat: we need the test event set by Friday. Pat owns the race data — CRM, timing, databases — and the test data has to reflect a realistic race scenario; once the event is set, we assign roles and permissions for the group. The second ask is for everyone: download the app, following the instructions already sent by email and chat.

---

## Close (~1 min)

Recap the three things that matter. Incident Management is live and integrated — they saw it end-to-end today. PCR is approved and starting. The testing plan is set, and the one item on the critical path is the test event by Friday. Thank everyone and open the floor for questions.

---

### Timing at a glance

| Block | Owner | Time |
|---|---|---|
| Cover + Agenda | Isa | 3 min |
| Roadmap | Isa | 4 min |
| Demo & Completed | Leo & Hyago | 10 min |
| Next Developments | Isa | 4 min |
| Discussion / Testing | Isa | 9 min |
| Close + Q&A | Isa | 1 min+ |
