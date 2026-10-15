# EO Melbourne email system

The system contains **four recognisable email families**. Each must have a consistent, distinctive look and content hierarchy, while sharing the official EO Melbourne logo, approved colours and typography.

**Confident hybrid is the default for Learning Events only**, not a universal chapter email layout. Follow `voice.html`, `tokens.css`, `PHOTOGRAPHY.md` and official logo guidance. The voice guide remains a draft pending chapter approval.

## Email families

| Family | Recognisable design | Story hierarchy | Typical action |
|---|---|---|---|
| **Learning Events** | Bold photographic hero, premium editorial invitation, EO Blue anchor, Hero Blue CTA | Why attend → compact details → one value section → register | Register |
| **Chapter News** | Recurring **CHAPTER NEWS** masthead with month/issue, white editorial canvas, compact story dividers | Lead news → 2–4 distinct chapter updates → upcoming dates | Read / explore |
| **Member Updates** | **MEMBER UPDATE** label, restrained note-like layout, minimal imagery, strong notice/action emphasis | What changed → why it matters → what members need to do | Understand / respond |
| **Strategic Alliance Partners** | Recurring **PARTNER INSIGHTS** / **STRATEGIC ALLIANCE PARTNERS** masthead, EO-led design with approved partner attribution | Member-relevant insight/benefit → partner context → terms → next step | Explore / enquire |

**Recognition:** Reuse each family's masthead wording, placement, rhythm and information density every month. Differentiate through structure and presentation, **not** through unapproved colours, invented EO logos or unrelated visual brands.

## Core principles

- Design for a **600–650px email canvas** (maximum 650px).
- Use **one strong hero image** for flagship events; avoid stacking competing visuals.
- Lead with a short **member-first proposition**, not a speaker biography.
- Keep copy concise, focused and easy to scan.
- Anchor in **EO Blue `#0C0C31`**, use **Hero Blue `#5258E2`** for CTA and emphasis, and **white `#FFFFFF`** for breathing room.
- Use only the approved EO Melbourne palette: `#0C0C31`, `#5258E2`, `#33388F`, `#99A1FF`, `#FFFFFF`.
- Set display/headlines in **Century Gothic** and body copy in **Roboto**, with email-safe fallbacks.
- Use **one primary CTA** where possible; avoid competing actions.
- Group event date, time, venue and other essentials into **compact, scannable details**.
- Use cards and callouts sparingly. Avoid making emails feel like webpages or newsletters packed with modules.
- When a framework is familiar to EO members, sell its **new application, access or relevance**, rather than reteaching curriculum they already know.

## Recommended Learning Event email structure

1. **Hero image:** One distinctive approved photograph or event creative.
2. **Proposition:** Eyebrow, short headline and no more than two short member-first paragraphs.
3. **Compact event details:** Date, time, location and essential eligibility/logistics.
4. **One structured value section:** Specific outcomes, numbered questions or clear reasons to attend.
5. **One short resolution/value block:** What becomes clearer or actionable afterwards; do not repeat earlier benefits.
6. **Optional guest note:** Only when relevant to guest access or eligibility.
7. **One primary CTA:** Direct, action-oriented link to the verified registration destination.
8. **Minimal footer:** Approved identity, relevant contact and required compliance/unsubscribe information.

Omit unnecessary sections. Maintain one clear narrative from hero to CTA. **A modern EO Melbourne event email is a designed invitation, not an email containing information.**

## Chapter News — monthly editorial digest

- Start with the same **CHAPTER NEWS** masthead and visible month/issue each send.
- Feature one lead story followed by 2–4 genuinely distinct updates, milestones or upcoming dates.
- Use white space, simple rules and small contextual images; unlike Learning Events, several short stories are appropriate.
- Use clear links per item rather than several competing full-size CTA buttons.
- Keep the tone useful and celebratory, not a collection of event advertisements.

## Member Updates — direct chapter note

- Use a recurring **MEMBER UPDATE** label with a restrained, personal-note layout.
- Start with the actual change or message; explain why it matters to members.
- Show a clearly labelled action, owner and deadline only when needed.
- Prioritise readable HTML text over photography; avoid ornamental sections.
- Provide one primary next step or a clear reply/contact pathway.

## Strategic Alliance Partners — partner value, EO framing

- Start with a stable **STRATEGIC ALLIANCE PARTNERS** or **PARTNER INSIGHTS** masthead.
- Frame the message around a specific member problem, insight or benefit, **not** a sponsor biography or advertisement.
- Clearly attribute the partner; use approved EO and partner logos without merging or fabricating marks.
- State any relevant eligibility, offer conditions or partnership disclosures accurately.
- Keep partner promotions concise, claims verified and one main action unmistakable.

## Copy style

Follow `voice.html`: **direct, warm, ambitious, member-first**, written in **Australian English**. Speak peer-to-peer, not as a corporate broadcaster. Use short headings and specifics over broad claims.

- Avoid generic phrases such as “don’t miss this opportunity”, “world-leading expert”, “unlock”, “exceptional opportunity” and “trusted by thousands” unless there is a precise, substantiated reason.
- Do not repeat one benefit in the intro, bullets and another “Why attend?” section.
- If members already know the topic, acknowledge that familiarity and quickly explain why **it matters now**.
- **Diagnostic questions** are often stronger than curriculum descriptions.
- Prefer concrete access, outcomes and next-stage relevance over generic inspiration.
- Never invent dates, pricing, speakers, claims, urgency or testimonials.

**Instead of:** “Learn the Four Decisions every business needs to get right.”

**Prefer:** “Use the Four Decisions to identify what is constraining your next stage of growth.”

## Visual hierarchy

- Establish a **strong hero first**, then a short opening block.
- Use generous white space and deliberate typographic contrast.
- Use EO Blue sections for emphasis and the Hero Blue CTA as the primary action.
- Use **simple numbered rows** for steps, questions or outcomes when helpful.
- Use short cards only when they add real hierarchy.
- Tell one coherent story from hero to CTA.
- Avoid excessive borders, boxes, background switches and decorative modules.
- Follow `PHOTOGRAPHY.md`: use authentic, approved images; preserve faces in cropping and confirm usage rights.

## Email-safe implementation

- Use **table-based HTML layouts** for reliable rendering across email clients.
- Centre the email with **max-width 650px** and fluid sizing below that width.
- Keep body copy, headlines and CTA button labels as **HTML text**, not text baked into imagery; use an email-safe clickable button.
- Reserve images for hero creative and essential approved brand imagery, including the logo.
- Provide meaningful **alt text** for all informative images and empty alt text for purely decorative ones.
- Use approximately **22px mobile side padding** and **34–40px desktop side padding**.
- Fonts are not reliably supported in every inbox: use **`Century Gothic, Arial, sans-serif`** for display and **`Roboto, Arial, sans-serif`** for body, with legible fallback line-height and sizing.
- Inline critical styles, define image dimensions and do not depend on JavaScript or advanced browser CSS.
- **Test desktop and mobile** inbox rendering, image blocking, dark mode, CTA behaviour and accessibility before sending.
- Replace and verify **all placeholder links, dates, prices and event details** before production.
- **Never fabricate or redraw EO logos.** Use only official approved EO Melbourne assets, and use an approved raster version when email-client SVG support is unreliable.
- Include sender information and any required unsubscribe/compliance elements appropriate to the distribution.

## Reference templates

- **Learning Events:** `examples/event-email.html` — planned canonical flagship invitation template.
- **Chapter News:** `examples/chapter-news-email.html` — planned recurring editorial digest.
- **Member Updates:** `examples/member-update-email.html` — planned direct chapter note.
- **Strategic Alliance Partners:** `examples/sap-email.html` — planned partner-insight communication.

These are **planned email-safe templates, not existing files**. Build and verify them before referring to them as available. The existing webpage examples are not email-ready HTML. Until templates exist, this document governs design and copy decisions.
