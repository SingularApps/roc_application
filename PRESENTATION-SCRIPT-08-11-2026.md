# Presentation Script — Bi-Weekly Update · Aug 11, 2026

**Deck:** `08-11-2026.html` · v0.9.1
**Presenter:** Isa
**Runtime:** ~28 min

The regular text below is written to be read out loud — it's the actual speech, section by section. Lines in brackets `[ ]` are stage cues, not spoken.

---

## Cover (~1 min)

"Hi everyone, thanks for joining. This is our bi-weekly update for the ROC Application, covering Jul 28 through today. Quick heads-up on where the energy is this cycle: Incident Management has moved from build into validation, we turned the Jul 28 feedback directly into scoped work, PCR — our next major module — is about to start development, and Kiosk is coming out of its exploration spike into design. But the real focus today is testing: Phase 1 is scheduled for next Tuesday, Aug 18. Let's get into it."

[Advance to Agenda.]

---

## Agenda (~2 min)

"Here's the shape of the session. Quick roadmap check. Then what shipped and what's in review right now. A short one on how the Jul 28 feedback turned into backlog. Then what's building next — PCR and Kiosk. And then the main event: testing and rollout — where Phase 1 stands."

[Advance to Roadmap.]

---

## Roadmap (~3 min)

"Quick snapshot — we're at Aug 11 now, right here on the board. Incident Report is fully delivered. Incident View is one step behind, in review. PCR is now active — the UI design set opened this sprint and runs through September. Event Page Improvements is now in development, a shorter one-month push. And you'll notice Languages is split into two lines — the app rollout finished back on Jun 30, and the web rollout just wrapped in the last two weeks."

[Advance to Deliveries.]

---

## Deliveries — Shipped & In Review (~4 min)

"Let's go through what actually landed. On Command Center, this was mostly finishing touches on the last round of integrations — the weather menu, race clock, emergency-contact shortcuts for WhatsApp and WeChat, and fleet data, all tightened up now. On Incident Management: the web creation flow and its integration are done, mobile got creation and view adjustments plus a proper list and detail UI — and on mobile we also built offline sync behavior, so incidents captured without connectivity queue up and sync automatically once you're back online. Athlete tracking got a mobile refresh, and Event Page improvements shipped too, looking good. On the design side, the Post-Event Dashboard and the Post-Race Incident export are both complete and queued for build.

In review right now: Incident View and the web i18n foundation. Ready to test today: the athlete tracking redesign, the incident-flow improvements from stakeholder requests, and the offline notice states."

[Advance to Feedback.]

---

## Feedback → Action (~2 min)

"Quick one — two weeks ago you gave us feedback, and it didn't just get logged, it got built. Offline-first, flagged as must-have for remote courses — delivered on mobile. GPS accuracy, editable location and drag-to-correct — scoped. Incident notes, text, photo, or GPS pin — scoped. Map and list usability, bib on the dot, type filter — scoped."

[Advance to Next Up.]

---

## Now Building & Next (~4 min)

"Two things moving right now. First, PCR — final definitions are wrapping up with TK, design is ready, and development starts this week. That's the form, the vitals and labs modals, view and edit history, discharge and close, list and filters — targeting completion before October so we can field-test it at Kona.

Behind that, the backend and access model: global roles at login, event-scoped positions, and the position-to-tier permission config everything else depends on.

And second — Kiosk is bigger than a line item now. The exploration spike is wrapping up and it's heading into design. This is athlete-facing self-service for event registration and check-in, ending in bib and kit pickup, QR-driven off the ticket email, iPad as the primary device. The spike surfaced the biggest opportunity: team and relay management is so cumbersome today that staff cancel and recreate the whole relay order just to swap a captain. That's exactly what the new design needs to fix. Five screens are going into design next: kiosk configuration, athlete check-in, ticket type change, walk-up registration, and relay and team management."

[Advance to Testing & Rollout.]

---

## Testing & Rollout (~8 min)

"This is the focus for today. Phase 1 is scheduled — Tuesday, August 18th. The plan is approved, four phases, crawl-walk-run, each gated by feedback and a go/no-go call. This first session is a general end-to-end test of the overall flow — login, profile, dashboard, race and event page, chat, live comms — and if time allows, we'll touch briefly on incident management too. PCR, kiosk, and slot allocations get their own focused sessions later with the teams that own them.

Session is locked: one hour, remote, ten minutes setup, thirty-five guided tasks, fifteen live feedback — Zoom, LogRocket, and UserBoard for live capture. Guest list is confirmed: Drew Wolff, Ken High, Keats McGonigal, Beth Atnip, Courtney Smith, Robert Cerniglia, and Pat Riley.

Two related tracks: PCR gets its own tabletop with TK and the medical team — they're highly engaged, and Kona in October is a real field-test opportunity. And Slot Allocations gets tested as its own isolated module once core flows are validated — we had a coordination touchpoint on that earlier today.

One thing to carry into Tuesday: confirming licensed-event access for non-ironman.com domains — that matters for LatAm."

[Advance to Close.]

---

## Close (~1 min)

"So: Incident Management is in validation, feedback turned into real backlog, PCR starts development this week, Kiosk is heading into design, and Phase 1 testing is locked for Tuesday. Nothing's blocking it. That's it from me — happy to take questions."

---

### Timing at a glance

| Block | Owner | Time |
|---|---|---|
| Cover + Agenda | Isa | 3 min |
| Roadmap | Isa | 3 min |
| Deliveries | Isa | 4 min |
| Feedback → Action | Isa | 2 min |
| Now Building & Next | Isa | 4 min |
| Testing & Rollout | Isa | 8 min |
| Close + Q&A | Isa | 1 min+ |
