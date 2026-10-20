# Presentation Script — Bi-Weekly Update · Oct 20, 2026

**Deck:** `10-20-2026.html` · v0.12.0
**Presenter:** Isa
**Demo today:** Kiosk prototypes (walkthrough by Isa)
**Closing:** open discussion on the next field test
**Runtime:** ~25 min

Framing: PCR is done and it worked in the field at Kona. Celebrate it, thank TK and John, then use the demo slot for a quick pass on the Kiosk prototypes (PCR was already demoed last time); they go to the responsible team afterwards to validate the flow. Close on picking the next feature to test at a real event.

Regular text is read out loud. Lines in `[ ]` are stage cues; `[pause]` is a real beat.

---

## Cover + Agenda (~1 min)

"Good afternoon, everyone. Let's get started.

Today: a quick look at the roadmap, then how PCR went at Kona. For the demo, I'll walk you through the Kiosk prototypes. Then a new topic, the roles and permissions architecture, and what we're building now. We close with next steps, and I want to leave some time open to discuss which feature we test next in the field."

[Advance to Roadmap.]

---

## Roadmap (~2 min)

"On the roadmap, the big news: **PCR is complete.** It went to the field at Kona and the tests went very well.

[pause]

We're now working on adapting the Global Dashboard, the improvements we designed for leadership, and we've started the Post-Race Report. Roles and permissions keep moving in the backend. The kiosk prototype is delivered and waiting on validation; that's today's demo. The other items haven't changed."

[Advance to PCR at Kona.]

---

## PCR at Kona (~4 min)

"We had very successful tests at Kona. It was great to see: the team actually used the app, and **37 PCRs were created** during the event, always alongside paper, so nothing depended on the app. Thirteen members of the medical team had access to the feature.

[Point to the photo.] This is the team gathered at Kona to test it during the event.

We made a step-by-step manual and shared it with the medical team before the race. That helped a lot with onboarding.

[pause]

I want to thank **TK** and **John** for all the support: preparing the test, running it, and championing it with the team. Thank you both.

[Point to the bottom cards.] This sprint we also closed out PCR: records close automatically at the end of the event, and PCR and incident actions are restricted by role on web and mobile. Some Kona feedback is already in testing, like letting the user pick lb or kg and Fahrenheit or Celsius, and limiting PCR to medical roles. The bigger items, like how discharge and closing a chart should work, we'll go through together: next week we'll sit down with the team to prioritize these adjustments and plan the next steps in how the tool is used."

[Advance to the Demo.]

---

## Demo — Kiosk (~8 min)

"For the demo today, a quick walkthrough of the kiosk prototypes. The goal is to share them afterwards with the team responsible for the process, so they can validate the flow.

[Open kiosk-self-check-in.html.]

**Kiosk, athlete self check-in.** The athlete checks in on their own at the iPad kiosk. They find their entry with the QR code or their email, confirm it's them with the camera and an ID, pick the entry, individual or joining a relay team, and if needed pay right there or on their phone. [Show the summary.] We also designed what happens when things go wrong: the help desk handoff, a kiosk that's out of order, and the idle timeout. It works in English, Portuguese and Spanish.

[Open kiosk-relay-roster.html.]

**Relay roster and ticket change.** This is the staff-assisted side, using Lake Placid as the example. Find the registration, switch the ticket between individual and relay or join an existing team, collect the waivers for every signer, and charge the price difference with tap to pay.

[pause]

The kiosk prototype is delivered. We're waiting for Jordan to validate it with the operations team, and development starts after that."

[Advance to Roles.]

---

## Roles & Permissions (~3 min)

"A new topic: we've made a lot of progress defining the roles and the permissions architecture.

[Point to the table.] Each role has a scope, event or global, the CRM positions it maps to, and the persona in the app. Event roles come from the person's position on that event. The three global roles, ELT, Incident Response and Medical Board, don't need a position and act on every event.

For medical, we're adding Medical Director, Medical 1 and Medical 2 as new positions in the CRM, and EMS becomes Medical 3.

[pause]

We're moving forward with the **9 roles defined**. The screens and the backend will decide by role, not by position. Now that the roles are defined, the next step, coming soon, is to map what each role sees on each screen."

[Advance to Now Building.]

---

## Now Building & Next (~2 min)

"What we're building now: the Global Dashboard improvements for leadership, with map pins by race status, filters, season KPIs and incident visibility; the Post-Race Report, which starts with an entry card on the event page, athlete KPIs and DNFs, and a medical summary straight from the PCR data; and roles and permissions in the backend.

Right after that: onboarding via QR code, so staff join an event by scanning a code and get the right role automatically; PCR adjustments from the Kona feedback; Live Activities; and kiosk development once the prototype is validated."

[Advance to Next Steps.]

---

## Next Steps & Discussion (~5 min)

"Two next steps.

**First**, next week we'll hold a session to go through the PCR improvement feedback from Kona: exit versus discharge, required fields before closing a chart, more findings and diagnoses, and labs. We'll schedule it with TK and John.

[pause]

**Second**, now that PCR went well, the idea is to choose the next feature to test in the field at a real event. I'd like to leave this open for ideas. Some starting points. Our recommendation is Incident Management: Jordan already saw it in Nice, and the first adjustments from Nice will be done before the next event. Other options are PCR again, with the adjustments, with a second medical team; or chat and broadcast for team communication on race day. Which feature should we take to the field next, and which upcoming event would be a good fit?"

[Open the floor. Note the ideas.]

"Thank you, everyone. I'll send the presentation after this."

---

### If you're running long

Cut in this order: Now Building → the relay roster flow (just mention it) → the bottom cards on the Kona slide. Never cut: Kona and the thank-you, the kiosk walkthrough, the open discussion.
