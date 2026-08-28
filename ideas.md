# ResQPlan Command Center — Design Direction

## Three stylistic approaches

### Theme Name: Calibrated Command Surface
Very Brief Intro: Preserve the existing editorial landing-page restraint, then extend it into a composed emergency operations surface with deep navy framing, mineral-white work areas, and disciplined safety accents. The result should feel like a civic decision-support instrument rather than a generic admin dashboard.
Probability: 0.067

### Theme Name: Field Ledger
Very Brief Intro: Translate preparedness into a tactile field-operations language with paper-like evidence panels, quiet map annotations, and a warm institutional palette. The direction would emphasize provenance, verification, and human accountability.
Probability: 0.031

### Theme Name: Signal Atlas
Very Brief Intro: Use a darker cartographic canvas with luminous route traces and sparse alert colors to make live prioritization feel immediate. This is the most cinematic option, but it stays grounded in operational clarity rather than cyberpunk spectacle.
Probability: 0.088

## Chosen Direction: Calibrated Command Surface

### Design Movement
Contemporary civic-institutional editorial design, informed by Swiss information graphics and emergency operations-room wayfinding. The existing ResQPlan page already uses a restrained split layout, lifecycle rail, thin rules, and human-governance language; the dashboard will extend those principles rather than replace them.

### Core Principles
1. Make the chain of action legible at a glance: prepare, assess, simulate, prioritize, allocate, approve, recover.
2. Use contrast as an operational signal: deep navy for authority and framing, mineral white for evidence, teal for verified/safe states, and red/orange only for escalating risk.
3. Preserve human approval as a visible product principle; AI is presented as transparent decision support, never autonomous dispatch.
4. Prefer composed asymmetry and editorial grouping over uniform card grids or generic admin-dashboard repetition.

### Color Philosophy
The palette uses near-black navy (#061B2D) as a calm, trustworthy command frame; paper white (#F4F7F4) as the evidence field; muted slate for secondary labels; sea-glass teal (#0B8F82) for verified, prepared, and resolved states; amber (#E39A38) for attention; and signal red (#D84A3A) for critical urgency. Emergency colors must be rare enough to remain meaningful. No purple gradients or decorative color fog.

### Layout Paradigm
A persistent lifecycle rail anchors the left edge on desktop and becomes a compact horizontal strip on mobile. Main work surfaces use a strong first column for narrative/status and a wider second column for maps, tables, and evidence. Operational pages should feel like a sequence of annotated instruments, not a dashboard wall. Use large, quiet section labels and right-aligned action clusters.

### Signature Elements
1. The lifecycle rail with numbered stages and a slim active marker.
2. Evidence strips that pair a small uppercase label with a bold value and a status dot.
3. Map panels framed as briefing instruments with a simulated-location watermark, risk legend, and concise popups.

### Interaction Philosophy
Every action should reveal a consequence in the shared demo state. Assigning a volunteer changes that volunteer’s workstream; saving a citizen record updates vulnerability counts; activating a disaster creates a prioritized incident; assigning a responder locks the resource; status changes propagate to authority views. Toasts should be concise, factual, and human-governed.

### Animation
Use short 180–260ms ease-out transitions for navigation, selection, button feedback, and panels. Stage progress can use a restrained fill/opacity transition. Toasts should slide from the top-right with a short fade and never block content. Map markers can pulse only for critical incidents. Respect prefers-reduced-motion and avoid perpetual animation except for the smallest critical marker pulse.

### Typography System
Use Fraunces for editorial display headlines and IBM Plex Sans for operational UI text. Headlines use a light/regular contrast with compact line-height; UI labels use IBM Plex Sans at 10–12px uppercase with letter spacing; body copy is 14–16px with generous line-height. Avoid Inter. Numbers in KPIs use IBM Plex Sans with tabular figures.

### Brand Essence
A human-governed disaster decision-support platform for authorities, organizations, volunteers, and responders that turns verified local evidence into a clearer chain of action.
Personality adjectives: composed, accountable, field-aware.

### Brand Voice
Headlines should be direct, calm, and outcome-oriented. CTAs should name the next action, not advertise the product. Microcopy should make simulation and human approval explicit.

Example lines:
- “One incident. A clearer chain of action.”
- “Prioritize the people and places that need help first.”

### Wordmark & Logo
Keep the existing RESQPLAN wordmark treatment and symbol language. For the upgraded workspace, use a compact symbol built from two offset brackets around a central route node: the brackets represent containment and coordination, while the node represents a verified signal. Use the symbol at a visible 28–32px size in the shell and as favicon source if available.

### Signature Brand Color
Sea-glass teal #0B8F82 — a grounded, ownable signal of verified readiness that sits between institutional blue and emergency green.

## Style Decisions
- Preserve the current public landing-page tone and lifecycle language; the new command center is an extension, not a replacement.
- Keep demo/simulated-data disclaimers visible wherever maps, people, or locations appear.
- Use a deep navy frame with mineral-white evidence panels and sparing emergency accents.
- Use Fraunces + IBM Plex Sans; never fall back to Inter as the primary typographic identity.
- Every major interaction must update shared client state and show a concise notification.

- Treat the topbar as a sober command readout rather than casual SaaS account chrome; favor sync posture, human-review state, and workstream context.
- Give the lifecycle rail a stronger vertical spine and clearer active-stage emphasis so the chain of action remains the primary narrative.
- Frame the live map as a simulated GIS briefing instrument with integrated evidence watermarking and risk annotations.
- Keep red and amber constrained to active escalation and decision points; use teal, navy, slate, and mineral white for the rest of the operating picture.

## Style Decisions
- The command shell is an instrument: sober, institutional, and status-forward rather than a generic productivity toolbar.
- The lifecycle rail is the product’s primary brand motif and should visually organize every operational page.
- Map panels must communicate simulated, verified civic evidence through their frame and annotations, not only through the basemap.
