# CatchUp — Business Model Research & Launch Plan
**Prepared:** 28 October 2026 · **Scope:** Nigerian campus errand service; public desk research plus recommended validation steps.

## Executive recommendation
Launch CatchUp as a **hyperlocal, WhatsApp-first managed errand service** before building a marketplace app. The product at the beginning is reliability: clear request, agreed fee, confirmation, updates, completion evidence and a sensible complaints process. The landing page should create qualified WhatsApp conversations; it must not promise instant dispatch, live tracking, insurance, verified runners or university payment integrations until these capabilities exist.

## Comparable models and public evidence
- **Errandly at UCH, Ibadan:** a published case study describes using a WhatsApp group to test demand before building more technology. This supports a low-cost manual pilot, but reported figures are an operator case study, not an audited benchmark. [UIMSA Press — Errandly case study](https://uimsapress.org/how-olalekan-is-tackling-uchs-errand-problem-with-errandly/?amp=1)
- **NITDA Campus Runner:** the challenge brief identifies student verification, cost estimates, status tracking, communication, ratings and dispute handling as relevant capabilities. This is a problem/design brief, not proof of profitability. [NITDA — Campus Runner](https://innovation.nitda.gov.ng/challenge/d70602cc-b7bd-4c44-8bfd-7a55302a967c)
- **Campusshelf:** a Nigerian student venture profile describes a campus-oriented learning-material marketplace with verification and delivery. This is adjacent evidence for campus-specific convenience, not a direct competitor comparison. [Student Venture Capital Grant — Campusshelf](https://svcg.education.gov.ng/projects/28474)
- Public guides discuss campus delivery pricing, but rates are not verified for CatchUp's particular campus. Use them as hypotheses only, not as an official price list. [CampusPlug — business guide](https://campusplug.ng/blog/campus-delivery-business-nigeria) · [Pricing guide](https://campusplug.ng/blog/campus-errand-service-pricing-nigeria)

## Recommended services and boundaries
Start with low-risk, repeatable tasks in a defined campus zone: approved document drop-off, printing/photocopy pickup, small-item collection, general campus pickups and queue-related errands where permitted. Add purchase runs only with a clear budget, consent and receipts where available.

Assignment support must not facilitate cheating: only delivery of the student's own completed work where institutional rules allow it. Never impersonate students or complete assessed work for them. For school-fee assistance, direct customers to official institution channels and never ask for passwords, PINs or OTPs. Do not imply CatchUp is an authorised payment intermediary unless an authorised, tested arrangement exists.

## Revenue options to test
1. Per-errand service fee — simple to explain and measure.
2. Zone/distance bands — once common routes and costs are known.
3. Transparent waiting-time or urgency add-ons — only disclosed before acceptance.
4. Bulk orders for classes or student groups — after reliable delivery operations exist.
5. Vendor partnerships — later, with written terms and proven demand.

Keep item-purchase money separate from the service fee. Quote the complete total before work starts. Do not copy another provider's rates without local testing.

## Order workflow
1. Customer describes task, pickup/drop-off, deadline and item budget if relevant.
2. CatchUp checks feasibility and confirms estimated timing, service fee and exclusions.
3. Customer explicitly accepts the quote.
4. Payment arrangements are written down; item budget and fee are distinct.
5. Provide reasonable progress updates and completion proof appropriate to the task.
6. Customer confirms completion; cancellation and complaints follow a written policy.

A WhatsApp message alone should not imply that an order is accepted. Verify runners proportionately before assigning work; do not claim "verified" without a real process. Decline unsafe, unlawful, prohibited or academically dishonest tasks. Minimise collection of personal data, provide a privacy notice if data is collected, restrict access and set retention limits. Review Nigeria's Data Protection Act and consumer-rights guidance: [NDPC FAQs](https://ndpc.gov.ng/faqs/) · [NDPC Act resources](https://www.ndpc.gov.ng/ndp-act-2023/) · [FCCPC consumer rights](https://fccpc.gov.ng/consumers/consumer-rights-responsibilities/rights-responsibilities/) · [FCCPC Act resources](https://fccpc.gov.ng/resources-library/fccpa/).

## Landing-page conversion strategy
- Keep the supplied CatchUp identity recognisable; use blue futuristic hexagons and glass cards as the digital environment.
- One dominant WhatsApp group CTA, repeated near the bottom.
- Service cards explain the value without overpromising availability.
- Direct WhatsApp links for both supplied contact numbers.
- Trust section: upfront quote, written confirmation, responsible boundaries.
- FAQs answer pricing, order requests, item money and eligibility.
- Mobile-first static page with no backend dependency, keyboard-accessible controls, alt text and reduced-motion support.

## Four-week validation plan
**Week 1 — discovery:** interview 15–25 students across faculties, levels and living areas. Ask about real errands in the past month, current alternatives, pain points, actual amounts paid, urgency and trust barriers. Avoid leading questions.

**Weeks 2–3 — manual pilot:** use WhatsApp and a simple internal log. Track request category, zone, quoted price, acceptance, assignment time, completion time, direct cost, revenue, cancellation, issue, satisfaction and repeat use. Get permission before publishing customer stories or images.

**Week 4 — decision:** review request-to-quote rate, quote acceptance, completion rate, on-time rate against promised windows, contribution per errand (revenue minus direct runner/transport/transaction costs), 30-day repeat use, complaint/refund rate and founder time per order. Set targets after a baseline exists; never invent marketing statistics.

## Roadmap
- **Phase 1:** landing page + WhatsApp operations + manual order log.
- **Phase 2:** structured request form and internal job board if repeated friction justifies it.
- **Phase 3:** runner profiles, task acceptance, status updates, ratings and dispute workflow.
- **Phase 4:** payment integration, vendor partnerships and multiple campuses only after unit economics and compliance are understood.

## Deployment and QA
- Dedicated GitHub repository: `Emris-x/CatchUp-_landing-`.
- Dedicated Vercel project linked to that repository; no reuse of existing projects.
- Static deploy, no Supabase required.
- Test mobile dimensions, WhatsApp group URL, both contact links, keyboard focus, reduced-motion behavior, text contrast and image loading.
- Confirm service zone, actual pricing, operating hours, runner capacity and policies before launch. Public sources do not establish CatchUp's local demand, margins or campus approval; these must be validated directly.
