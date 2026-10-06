# Presentation Script — Bi-Weekly Update · Oct 6, 2026

**Deck:** `10-06-2026.html` · v0.11.0
**Presenter:** Isa
**Demos today:** Hyago (PCR on web, live) · Slot Allocation payment flow (video recorded by Leo)
**Not attending:** Leo (closing the last PCR adjustments on the app to submit to Apple) and Shay
**Closing:** promotional video
**Runtime:** ~25 min

Framing: Kona is Saturday — Isa, TK and John run the first PCR field tests. Everything today points at that. Say what the app can do now, not how many tickets moved. Send the deck and the promo video to the group after the session.

Regular text is read out loud. Lines in `[ ]` are stage cues; `[pause]` is a real beat.

---

## Cover + Agenda (~1 min)

"Good afternoon, everyone. We can get started. Leo and Shay won't join today — Leo is focused on the last PCR adjustments in the app so we can submit it to Apple, ahead of the Kona event on Saturday. TK, John and I will be doing field tests there, and I'll say more about that later.

[pause]

Today: the roadmap and what's coming next, then Hyago will demo the PCR flow on web. I'll show a video Leo recorded of the new Slot Allocation payment flow in the app. At the end we'll talk about the latest tests, and I want to share a promotional launch video we made for the app."

[Advance to Roadmap.]

---

## Roadmap (~2 min)

"On the roadmap: we're wrapping up PCR. The last integrations are being made, and the first field tests happen this week — that's going to be very important and useful as feedback.

[pause]

We've completed the Slot Allocation pilot phase. While we wait for Tap to Pay approval, we're moving ahead on the next evolution of authentication and permissions in our backend, and on the kiosk design. After that we come back to Global Dashboard improvements, thinking about IRONMAN's executive leadership.

The other items haven't changed."

[Advance to What Shipped.]

---

## What Shipped (~3 min)

"**Slot Allocation.** We built a fallback solution: the user can pay by entering their card details in the app, until Apple's Tap to Pay approval is available.

[pause]

**PCR.** We're finishing the integration. This week's adjustments were all focused on the test we'll have at Kona on Saturday. We're closing every mobile need today. Some further adjustments — more than one type of permission, additional flows — will come over the next few days.

**Fixes from testing.** We also shipped fixes and improvement suggestions that came out of our last test sessions."

[Advance to Demos.]

---

## PCR Demo — Web (~6 min)

"I'll hand it over to Hyago to present the PCR demo. Feel free to ask questions."

[Hyago — live on web. Suggested order: records list and filters → create a record (with/without athlete, T1/T2) → vitals and discharge diagnosis → share.]

[After Hyago, say:]

"Some adjustments are already mapped and in progress in the app — they came from conversations with John and TK. The flow in the app is very similar to web; we're only showing web today because Leo is focused on closing the last mobile adjustments for Kona. Apple's approval can take up to two days, which is why we're trying to get the app ready as early as possible. Everything you saw here also exists in the app, with a very similar flow. Thank you, Hyago."

---

## Slot Allocation Demo — Video (~4 min)

"Now the Slot Allocation video that Leo made, from the app.

Slot Allocation is the feature for offering qualifying spots to athletes after a race ends. The athlete can express interest and make the payment. We planned it with Tap to Pay, but that needs an Apple approval that's a bit more bureaucratic. So as a workaround, we're offering payment through the payment sheet — the athlete, right there at the qualification ceremony on the podium, can type in their card details if they want to pay."

[Play the video.]

---

## Now Building & Next (~2 min)

"What we're developing next: finishing the last PCR integrations, advancing on additional medical permission types, and moving all endpoints to the new authentication model on the backend. Then we come back to Global Dashboard improvements, and we finalize the design and start development of the kiosk."

[Advance to Next Steps.]

---

## Next Steps — Testing (~3 min)

"PCR will be tested at Kona. We've had several alignment meetings with TK from the medical board and with John, walking through the flow. We have a step-by-step manual to share with the medical team — about ten medical board members will have access and test. [Show the guide.]

[pause]

At first, care will always happen in the Medical Teams and run in parallel with paper. Afterwards we'll run a satisfaction and feedback survey with those users. Next week, with that feedback in hand, we'll come back and understand what needs to change in PCR.

As next steps, together with James we'll work out which events, and how, we can start introducing the app. Jordan also tested at the Worlds in Nice, and we already made some adjustments from there on Incident Management. The idea is to start testing some of the app's features in the field."

[Advance to the video.]

---

## Promotional Video (~2 min)

"Last, I want to show you a video we created about the app. It's a promotional video, with the main features of the app, for promotion."

[Play the video.]

"Thank you, everyone. Any questions? I'll send the presentation and the video to you after this."

---

### If you're running long

Cut in this order: Roadmap → Now Building → Fixes from testing. Never cut: the PCR demo, the Slot Allocation video, Kona, the promo video.
