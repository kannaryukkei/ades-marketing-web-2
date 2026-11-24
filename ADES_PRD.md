# ADES Marketing Website — Product Requirements Document

**PRD ID:** ADES-MW-PRD  
**Version:** 0.1  
**Status:** APPROVED BY OPERATOR — exact version v0.1 approved 2026-11-25  
**Prepared:** 2026-11-25  
**Project:** ADES Marketing Website  
**Entry path:** `new_build`  
**Business mode:** `studio_development`  
**ADES mode:** `single_agent_end_to_end`  
**Lead / Execution Agent / Governance Lead:** GPT-6 (OpenAI / ChatGPT), operator-appointed  
**Selected Product Profile:** `starter` v0.1.0 — single-page, static-first marketing/brochure website  
**Website repository:** https://github.com/kannaryukkei/ades-marketing-web-2

---

## 1. Product summary

Build a bilingual, single-page marketing website for ADES, a website design and development service operating from Surabaya, Indonesia and serving clients throughout Indonesia remotely.

The website must help prospective UMKM clients understand what ADES offers, distinguish the available service packages, understand the working process and boundaries, inspect clearly disclosed concept work, and start a free, no-obligation consultation through WhatsApp.

The website itself is also a demonstration of ADES's design and implementation quality. It must be distinctive, credible, accessible, responsive and conversion-oriented without unsupported business claims.

## 2. Business facts and public claim boundaries

### 2.1 Identity and audience
- Public brand name: **ADES** only. Do not display the founder's personal name or expand the public brand name into its acronym.
- Initial audience: UMKM across industries. Do not narrow the audience to one industry without further evidence.
- Operating base to display: **Surabaya, Indonesia** (city/country only; no street address).
- Service geography: nationwide Indonesia, delivered remotely. Do not imply local offices or in-person service coverage throughout Indonesia.
- Website language: Indonesian and English, with a header selector labelled **ID / EN**.
- Initial language follows the browser language; Indonesian is the fallback. Remember a visitor's manual language selection in their browser for subsequent visits.
- All content must be bilingual, including navigation, package information, portfolio/case study, workflow, FAQ, form/privacy notice and footer. Localize SEO titles, descriptions and relevant page metadata for both languages.

### 2.2 Offer and availability
- **Starter:** available. One simple landing page, responsive for mobile and desktop, WhatsApp button, and two revision rounds. Client supplies source text and images/photos; ADES helps refine and organize supplied materials. Full original copywriting and creation of all visual assets from zero are not included by this confirmation.
- **Business:** operator-confirmed as ready for sale and delivery. Positioned as Starter expanded to multiple pages, with the same quality standard. Page count is flexible and determined by client needs; do not publish a fixed page-count range. Two revision rounds. Content workflow matches Starter.
- **Custom:** show **Coming Soon** only. It is not developed/production-approved and must not accept orders or imply price, schedule, delivery or support readiness.
- Pricing: show prices as **estimates**, not fixed/guaranteed package prices. A prospective client must consult ADES for a tailored quotation. Earlier starting-price references (Starter Rp500.000; Business Rp1.500.000) are not to be shown as fixed prices. Whether indicative figures may appear with a clear estimate disclaimer is unresolved; safest v0.1 public treatment is **“Konsultasi untuk estimasi / Consult for an estimate”** without numeric prices until separately resolved.
- Free initial consultation is available to every prospective client, with no obligation to purchase. Consultation covers understanding website needs and selecting a suitable package; it does not include initial design recommendations or visual concepts.
- Inquiry response is handled personally by the founder when active/available. Do not promise 24/7 monitoring or a response-time SLA.
- No testimonials are currently approved. Do not display testimonials, invented reviews, customer counts, client logos or outcome metrics.
- Do not promise increased revenue/conversion, SEO rankings, absolute security, certifications, awards or other unverified outcomes.

### 2.3 Delivery and commercial boundaries
- Starter and Business estimated delivery: **1 working day**, beginning only after the project-specific agreed deposit has been received and all required client materials are complete. This is an estimate, not an SLA.
- Each package includes two revision rounds. Revision turnaround depends on the level and complexity of the requested changes; no fixed revision response time is promised.
- Scope is agreed through WhatsApp conversation; a separate formal scope document is not a standard prerequisite.
- Out-of-scope requests are assessed flexibly according to type and extent. Do not promise automatic acceptance or rejection; discuss the request and quote additional work when applicable.
- Deposit percentage is agreed per project; do not publish a universal percentage. Remaining balance is due after completion and before handover.
- Accepted payment methods: bank transfer and e-wallet. Specific account/provider details are shared privately per transaction and must not appear on the public website.
- Client purchases, pays for and independently configures their own domain and hosting. ADES does not provide setup assistance.
- Source code is handed over to the client; ADES retains a copy for maintenance.
- First three months of maintenance are free. Coverage: fixes for bugs/errors originating from ADES-delivered work plus reasonable minor text/image changes without a fixed request-count cap. It excludes unlimited redesign, new sections/features and major scope expansion.
- After the free period, paid maintenance may be requested as needed; no mandatory monthly subscription. Paid maintenance fees and detailed scope are not confirmed; do not publish a price or detailed promise.
- ADES only maintains websites originally built and delivered by ADES; it does not accept maintenance for third-party-built sites.
- Major post-completion additions (pages/features/redesign) are evaluated and quoted individually.
- Optional simple logo add-on: separately charged, not included in Starter/Business. Scope is a simple wordmark and/or symbol, not a full brand identity. Deliverables confirmed as PNG and SVG; editable source files are not included in the confirmed offer. Exact price and additional terms are unresolved; do not publish an amount.

## 3. Visitor problem, goals and tasks

### Primary visitor problem
A prospective UMKM client needs a clear, credible explanation of ADES's website services, package fit, process, delivery expectations and ongoing responsibilities before deciding whether to start a conversation.

### Primary visitor task
Understand the offer and its boundaries, then start a relevant free consultation through WhatsApp.

### Secondary visitor tasks
1. Compare Starter, Business and Custom availability.
2. Understand the consultation-to-handover workflow.
3. Inspect concept work without mistaking it for real client work.
4. Find answers about estimates, delivery, revisions, domain/hosting, maintenance and ownership.
5. Submit an inquiry form and hand the details to WhatsApp intentionally.

### Business outcomes
- Make the service and its boundaries understandable.
- Generate relevant WhatsApp inquiries.
- Reduce uncertainty about package selection and project responsibilities.
- Demonstrate quality through the rendered website, not unsupported proof claims.

No conversion-lift or revenue-impact claim is part of acceptance; no baseline analytics data has been supplied.

## 4. Scope

### In scope
- One public-facing page / one primary route.
- Fully bilingual Indonesian and English content.
- Responsive navigation and section anchors.
- Clear explanation of ADES, service packages and package availability.
- A process section from initial consultation through handover.
- Selected concept/demo portfolio work with prominent disclosure.
- General FAQ.
- Inquiry form with required fields: name, WhatsApp number, service type, message.
- Direct WhatsApp CTA using the approved destination: https://wa.me/6281246027946
- Form validation and client-side WhatsApp handoff using a prefilled message.
- Visible privacy notice adjacent to the form.
- Localized SEO title, meta description and page metadata for ID/EN.
- Responsive, accessible implementation and evidence-based QA.
- Concise handover instructions and source-code delivery readiness.

### Out of scope
- Backend, database, CMS, user accounts or persistent inquiry storage.
- Sending or storing form submissions on an ADES server.
- Email inquiry, CRM, analytics or third-party marketing integrations unless separately approved.
- Booking, checkout, online payment, customer dashboards or custom application workflows.
- Full brand strategy or complete brand identity.
- Full original client copywriting or commissioned photography/large-scale visual production as a package promise.
- Paid maintenance price list, formal invoice-system claims, payment-account details.
- Publishing unverified NARA material as client work.
- Testimonials, client logos, quantified results, awards or certifications without evidence and permission.
- Domain purchase/setup, hosting purchase/setup, DNS changes, deployment or public release.
- Numeric public package prices until the estimate/starting-price presentation is resolved.

## 5. Information architecture and content requirements

The final page may arrange sections creatively; this list defines content responsibilities, not a prescribed visual layout.

1. **Hero / value proposition**
   - Explain in plain language that ADES designs and builds websites for businesses.
   - Communicate the remote nationwide service and Surabaya operating base accurately.
   - Primary CTA: free consultation via WhatsApp.
   - Secondary path: explore services/process or concept work.
2. **Problem / outcome**
   - Explain the practical role of a clear, credible business website.
   - Avoid implying guaranteed business results.
3. **Packages**
   - Starter: one landing page; responsive; WhatsApp button; two revision rounds; client-provided source text and imagery refined/organized by ADES.
   - Business: multi-page website; page count scoped to client needs; two revision rounds; same content-supply boundary.
   - Custom: Coming Soon, unavailable for orders.
   - Explain estimate-based pricing and consultation for tailored quotation. Do not show numeric amounts in v0.1 absent further resolution.
4. **Selected work**
   - Nusa Forma Studio may appear as a concept case study with scenario/problem framing, design approach and concept outcome.
   - Every demo/concept item must display a prominent **“Concept Project / Proyek Konsep”** label, not only inside its detail.
   - Clearly disclose synthetic imagery and assumptions. Never imply real client engagement, delivery, measured outcomes or verified client results.
   - NARA Objects must be omitted unless provenance, status and publication permission are verified.
5. **Workflow**
   - Show the end-to-end process from initial free consultation to handover.
   - Scope is agreed through WhatsApp conversation; do not imply a mandatory separate formal scope document.
   - Reflect project-specific deposit and the requirement for complete client materials before the estimated delivery clock starts.
   - Include completion, revisions, balance payment before handover, source handover and maintenance boundary accurately.
6. **Why ADES**
   - Explain the working approach: discovery, research, design exploration, synthesis, implementation and QA.
   - Describe the process, not unsupported superiority or guaranteed outcomes.
7. **General FAQ**
   - Cover estimates/quotation, free consultation, delivery estimate, revisions, client-supplied materials, domain/hosting, source-code handover, free maintenance and paid maintenance boundaries, logo add-on, and Custom availability.
8. **Inquiry form and final CTA**
   - Direct WhatsApp CTA always available.
   - Form fields: name, WhatsApp number, service type, message.
   - Email and budget are not required.
   - After validation, open WhatsApp with a prefilled message addressed to the approved ADES number. The visitor must still press Send.
   - Do not show a success modal/message claiming the inquiry was sent or received.
9. **Footer**
   - ADES name only; Surabaya, Indonesia; remote nationwide service; ID/EN availability; WhatsApp contact.
   - Do not invent business email or social accounts.

## 6. Workflow content and public expectations

The process section should explain these stages without implying unconfirmed operational services:

1. **Free consultation:** discuss website needs and select a suitable package; no purchase obligation and no initial design concept.
2. **Scope agreement:** agree project scope and quote through WhatsApp conversation.
3. **Project start:** agree the project-specific deposit and payment arrangement. Work/timeline start after the agreed deposit is received and required client materials are complete.
4. **Design and build:** organize supplied content, explore/design and implement the agreed website scope.
5. **Review and revisions:** two revision rounds; timing depends on request complexity.
6. **Completion and balance:** remaining balance is due after completion and before handover.
7. **Handover and maintenance:** client receives source code; ADES retains a copy. First three months include the defined free maintenance coverage.

Do not imply a formal contract, invoice system, client domain/hosting setup service, guaranteed response time, fixed revision turnaround or a fixed universal deposit percentage.

## 7. Functional requirements

### Navigation and language
- Navigation links move to the correct page sections.
- Mobile navigation is operable by keyboard and touch, exposes its expanded/collapsed state to assistive technology and closes appropriately after navigation.
- ID/EN selector changes all visible page content and localized metadata.
- Initial locale uses browser language with Indonesian fallback.
- Manually selected locale persists in the browser for subsequent visits.
- No third-party translation service is required.

### WhatsApp
- Direct CTA opens the exact approved URL: https://wa.me/6281246027946
- Inquiry form validates required fields and safely encodes the prefilled message.
- Form handoff opens WhatsApp; it does not claim delivery, storage or receipt.
- No inquiry data is sent to any other third party or server before the user deliberately opens WhatsApp.
- Avoid putting form contents into analytics, logs, URLs other than the intended WhatsApp handoff, or persistent browser storage.

### Privacy notice
- Display a concise privacy notice beside the form explaining that details are used to prepare a WhatsApp message and are not submitted to an ADES server by this website; the visitor must review and send the message in WhatsApp.
- No mandatory consent checkbox is required by the operator's selection.
- Exact privacy wording and legal review remain unresolved; do not claim full legal compliance solely because a notice is present. Before publication, ensure the wording matches the implemented data flow and applicable obligations.

### Other interactions
- FAQ disclosures/accordions, if used, must be keyboard accessible and expose expanded state.
- All visible buttons, links, selectors and controls must work.
- Do not use placeholder forms, dead buttons or fake success states.

## 8. Content, brand and asset constraints

- Brand character preference: modern, professional, neat, trustworthy and convincing. This is a strategic preference, not a frozen visual identity.
- No approved ADES logo, colour palette or tagline currently exists. Explore from zero after the R1 process; do not reuse Zacks Detailing identity.
- Tagline options may be explored in ID and EN, but none is approved at PRD stage.
- No official social accounts or dedicated business email are available to display.
- Use only assets with documented provenance and rights. Generated/synthetic visuals must be labelled when they represent concept work.
- Do not use stock images as fake client proof.
- Do not invent testimonials, names, logos, metrics, client outcomes, awards, certifications or service locations.

## 9. Non-functional and quality requirements

- Responsive and intentionally art-directed at mobile, tablet and desktop.
- Semantic HTML, logical heading structure, skip navigation, visible keyboard focus and keyboard-operable interactions.
- Sufficient colour contrast; do not communicate state by colour alone.
- Respect reduced-motion preferences; motion must be purposeful and non-blocking.
- Images must load, use appropriate formats/sizing and have suitable alternative text where meaningful.
- No material horizontal overflow, blocking runtime errors or known critical accessibility issue at acceptance.
- Static-first architecture; no backend/database/CMS by default.
- Use the simplest maintainable stack that satisfies the approved PRD. Stack selection is a Lead decision after research and is not prescribed here.
- Localized metadata for both languages. Do not claim SEO ranking guarantees.
- Apply the ADES Security & Deployment Standard proportionately. Source/build checks may be performed before deployment; live TLS, DNS, redirect and response-header verification remain NOT_VERIFIED until an authorized deployment exists.

## 10. Acceptance criteria

The website is acceptable when:
1. It implements the approved PRD and makes the primary visitor task clear.
2. All public business facts, package terms, timelines and policies match the confirmed boundaries above.
3. Indonesian and English are complete and consistent across all page content, form/privacy notice, FAQ, footer and metadata.
4. Browser-language selection, Indonesian fallback and persisted manual language choice work.
5. The package comparison makes Starter, Business and Custom readiness/boundaries unambiguous without unsupported numeric prices.
6. The process section accurately represents consultation through handover and all payment/timing caveats.
7. All concept/demo portfolio work has a prominent bilingual concept disclosure; no unverified NARA work or testimonials appear.
8. The direct WhatsApp CTA reaches the approved destination.
9. The inquiry form validates all four required fields and opens WhatsApp with a correctly encoded prefilled message; it does not claim that the inquiry has been sent or stored.
10. The privacy notice accurately describes the actual form-to-WhatsApp data flow and has no misleading legal-compliance claim.
11. Every visible in-scope link, button, menu, CTA and interaction works.
12. Mobile, tablet and desktop layouts have no material overflow and are reviewed in rendered form where a browser path is available.
13. Keyboard navigation, focus visibility, semantic structure, contrast and reduced-motion behaviour receive proportionate checks.
14. Images and other third-party assets have documented rights/provenance.
15. No unsupported testimonial, customer metric, business outcome, certification, award, SLA or security guarantee appears.
16. Source/build-output checks and applicable security review are recorded. Live deployment checks are explicitly NOT_VERIFIED unless separately authorized and performed.
17. Handover identifies repository/commit, run/build instructions, limitations, source ownership, domain/hosting responsibilities and maintenance boundaries.

## 11. Assumptions, unresolved items and conservative treatment

The following do not block a responsible PRD draft but must not be silently invented:
- Numeric public starting-price display: unresolved; omit figures in v0.1 and use consultation-based estimates.
- Detailed eligibility/content limits for Starter and Business: unresolved; explain only confirmed inclusions and quote case-by-case.
- Paid maintenance fees and detailed paid scope: unresolved; state that a separate quote is required, without publishing an amount.
- Logo add-on price and exact additional deliverables: unresolved; mention availability only if needed and state that it is quoted separately.
- Exact privacy-notice wording/legal review: unresolved; draft against actual data flow and review before public release.
- Portfolio media/provenance for Nusa Forma: verify source assets and rights before use; if not verified, use newly generated concept imagery with explicit synthetic disclosure or omit.
- NARA Objects: omit unless provenance and publication permission are verified.
- Public contact title/name: omit; use ADES only.
- Email/social links: omit; none approved.
- Tagline and visual identity: explore during design work; do not treat any option as approved.
- Analytics: none approved/configured; no tracking claim or conversion measurement promise.
- Deployment provider, domain, hosting, cost and release date: not supplied; no purchase, DNS, deployment or public release is authorized.

## 12. Change control and approvals

- This PRD governs the website assignment through R1, R2 and R3. It defines outcomes, scope and acceptance criteria, not a prescribed visual design.
- Any material change to audience, visitor goal, page architecture, data handling, integrations, commercial claims or acceptance criteria requires a revised PRD and fresh version-bound approval before affected work proceeds.
- Approval required: operator must explicitly approve **PRD v0.1** and its scope in the conversation. A continuation message such as “gas” or “lanjut” is not PRD approval.
- R1 is not authorized by this draft. R1 may begin only after exact PRD approval and completion/freeze of the common evidence-backed Research Pack, including the targeted OSI findings and recorded limitations.
- No spending, third-party contact, DNS changes, deployment or public release is authorized by this PRD.
