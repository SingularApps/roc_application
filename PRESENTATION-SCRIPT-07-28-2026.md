# Presentation Script — Bi-Weekly Update · Jul 28, 2026

**Deck:** `07-28-2026.html` · v0.9.0
**Presenter:** Isa · **Live demo:** Leo & Hyago (dev team)
**Runtime:** ~30 min

The regular text below is written to be read out loud — it's the actual speech, section by section. Lines in brackets `[ ]` are stage cues, not spoken.

---

## Cover (~1 min)

"Hi everyone, thanks for joining. This is our bi-weekly update for the ROC Application — we're now on version 0.9.0. Before we start, a quick word on what to expect today. The highlight is a live demo: Incident Management is now running end-to-end with the real integration, and Leo and Hyago are going to walk us through it. And at the very end, we'll come back to the testing side — I'll give you an update on the adoption plan and what we need from the team to move it forward. Let's jump in."

[Advance to Agenda.]

---

## Agenda (~2 min)

"So here's how the session is laid out. We'll start with the Roadmap, just to place where we are and what's coming through Q3. Then we get to the main event — the demo — where the dev team shows Incident Management live, on both the app and the Command Center. After that, I'll cover what's next: PCR, Roles & Permissions, Staff Onboarding with QR, and Live Activities. And we'll close with the discussion — the testing and adoption plan, where I'll walk you through the four phases, what Phase 1 looks like, who's involved, and the one thing we need set up by Friday."

[Advance to Roadmap.]

---

## Roadmap (~4 min)

"Quick snapshot of where things stand. Each column here is a two-week sprint, and we're right here, at Jul 28. Everything on the left is already shipped — Tracking, Slot Allocation, Edit Race, Broadcasting 1.0, and the Global Dashboard are all done.

The big move this cycle is right here: Incident Report and Incident View — OEA-104 and 105 — are now done and integrated. That's exactly what we're about to show you live. Right after that comes PCR: TK Miller approved the design, so it goes into development this sprint and runs for about three sprints. And further out we've got Live Activities in September, then Kiosk, Event Page Improvements, and Languages. Broadcast 2.0 has been pushed for now — that one's still TBD."

[Advance to Demo & Completed Items.]

---

## Demo & Completed Items — Live Demo (~10 min)

"This is the big one for this cycle. Incident Management is now live and integrated — and I mean the real thing, not just screens. The whole field-to-command flow runs on live data now, on both the app and the Command Center.

Two pieces to it. The Command Center is the web view for supervisors — all active events, the live incident feed, athlete counts, all in one place, and now driven by real data coming straight from the field. And the Incident View covers the full lifecycle — from a report out in the field all the way to resolution in the command center — with a live course map and the athlete's medical context. For V1 that's Medical, Weather, Transportation, and Others.

But rather than me describing it, let's just see it. Leo, Hyago — over to you."

[Demo — Leo & Hyago. Suggested end-to-end flow: staff reports an incident on the app and picks a type → it shows up live in the Command Center feed on web → a coordinator opens the Incident View with the course map, medical context, and resource tracking → the incident is moved through to resolution, closing the loop.]

"Thanks Leo, thanks Hyago. So that's the full loop, live and on real data — a report goes out in the field, lands in the command center, and gets resolved, all in one flow."

[Advance to Next Developments.]

---

## Next Developments (~4 min)

"Now that incidents are shipped, here's what's coming next. First up, next sprint, is Roles & Permissions — we're adapting the whole app to the permissions matrix, so every screen, every action, every data view respects each person's role. And it's the same matrix we'll use to set up the test-event permissions.

Right behind that is PCR. The design is approved by TK Miller, validation is done, and development kicks off next week — that's the post-incident report and medical documentation for event day. Then, in Q3, we've got Staff Onboarding with QR — fast credential and role assignment plus asset tracking at check-in — and in September, Live Activities: the real-time feed of who's in the water, on the bike, on the run, plus aid stations and course clearance. And a bit further out we've still got Kiosk, Event Page Improvements, and Broadcast 2.0."

[Advance to Discussion.]

---

## Discussion — Testing & Adoption Planning (~9 min)

"Last part — let's talk about how we actually roll this out. I sat down with John Bertsch and James Hines yesterday and validated the plan with them, so this is where we landed.

The rollout goes in four phases, and between each one there's a feedback round and a go/no-go call before we move on. Phase 1 is a hybrid tabletop plus guided tasks — no real race scenarios yet. Phase 2 is the same format, but opened up to a wider team beyond our core group. Phase 3 is a field test in shadow mode, running alongside a real race. And Phase 4 is the pilot — a real event with the app running live.

Let me zoom into Phase 1, since that's what's next. It's a one-hour remote session: about ten minutes to get set up, thirty-five minutes of guided tasks, and fifteen for live feedback. We'll run it on Teams, use a FigJam board to capture feedback in the moment, and record everything with LogRocket to review afterward. What's in scope for Phase 1 is the core experience — login, profile, home dashboard, race page, chat, and live communications. Incident management, PCR, and kiosk we're holding for later phases, with the ops teams who actually own those. Web and app run side by side — leadership mostly on web, field staff on the app. And to move on to Phase 2, we need three things: no critical bugs blocking features, a solid confidence score from the participants, and every improvement need mapped and confirmed as non-blocking.

For Phase 1 we're keeping the group tight — just the core: Drew Wolff, Ken High, Keats McGonigal, Beth Atnip, Courtney Smith, Robert Cerniglia, and Pat Riley. Next step from here is getting that first session on the calendar.

And that brings me to what I need from you. The big one is for Pat: we need the test event set by Friday. Pat owns the race data — CRM, timing, databases — and the test data really has to reflect a realistic race scenario. Once that event is set, we can assign roles and permissions to the group. And for everyone else: please download the app — the instructions are already in your email and in chat."

[Advance to Close.]

---

## Close (~1 min)

"So, to wrap up: Incident Management is live and integrated — you saw it end-to-end today. PCR is approved and starting. And the testing plan is set, with the one thing on the critical path being that test event by Friday. That's it from me — happy to take any questions."

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
