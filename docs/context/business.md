# business.md

> Owns identity, value prop, customer segments, and pricing — everything about
> what the company is and how it makes money, in one place.
> Source: Prompt 1, Questions 1 + 2.
> Related: [team.md](./team.md) · [goals-and-targets.md](./goals-and-targets.md) · [vision-and-strategy.md](./vision-and-strategy.md)

## Identity (Q1)

- **Name:** Spanisch lernen (working title; prototype brand). Productized goal: a
  personalized language-learning app — see [Open questions](#open-questions) re: final brand.
- **Product:** A mobile-first PWA that helps German speakers learn Spanish for
  travel. Vocabulary training (multiple-choice, typing, speaking, flashcards),
  mini-dialogues, German-language grammar lessons, TTS audio, Web Speech API
  pronunciation checking, SM-2 spaced repetition, Firestore sync with Google
  login, offline-installable.
- **Industry:** Consumer edtech — language learning.
- **Stage:** Working prototype, pre-launch, pre-revenue. Built with Claude Code,
  deployed to Google Cloud (Firebase Hosting).
- **Website:** https://language-learning-app-22bea.web.app (live prototype)
- **Repo:** https://github.com/klausludemann/language-learning-app

> The product vision is *personalized* language learning. The prototype's
> personalization today is limited to SM-2 spaced repetition + topic choice;
> deeper personalization (level, interests, pace, adaptive path) is roadmap, not
> shipped. Tracked in [vision-and-strategy.md](./vision-and-strategy.md).

## Business model (Q2)

- **What we sell:** A subscription consumer app, published natively on the
  **Apple App Store** and **Google Play** (converted from the current free web
  PWA prototype). Login-based personalization and additional languages are
  in-scope product work for the sellable version.
- **Customer segments (primary first):**
  1. **Primary:** German-speaking adults learning *any* language (B2C / private
     users, not business). Spanish-for-travel is the proven prototype wedge into
     this segment.
  2. **Later expansion:** other source languages / learner types.
- **How we make money:** Recurring auto-renewing subscription billed through
  the App Store and Google Play (platform IAP, ~15–30% store fee applies).
- **Current pricing:** **€0.99 / month** subscription. _Hypothesis — to be
  validated; very low for the category, low LTV after store fees. Flagged in
  [Open questions](#open-questions)._

## Value proposition

> A personalized, travel-ready language app for German speakers — speak and
> remember faster with pronunciation feedback and spaced repetition, in any
> language you need — for under €1 a month.

_Note: "any language" is a launch requirement, not a prototype capability — the
prototype is Spanish-only. This makes multi-language a gating dependency for the
sellable product (see [bottlenecks.md](./bottlenecks.md))._

## Open questions

- Final product/brand name (prototype is internally "Spanisch lernen").
- How far "personalized" goes at launch vs. the SM-2-only prototype today.
- **Pricing risk:** €0.99/mo minus ~15–30% store fees ≈ €0.70–0.84 net/user/mo.
  Validate against CAC; consider annual plan / higher tier / intro pricing.
- Segment is "any language" but prototype is Spanish-only — multi-language is a
  launch gate, not a nice-to-have.
