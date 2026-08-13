# Tennis Clinic Website — Project Blueprint

---

## Phase 0 — Project Foundation (before anything else)
- [x] Create a GitHub repo (`tennis-clinic-website` or similar)
- [x] Add a `README.md` with: project description, tech stack (fill in as decided), how to run locally (fill in later)
- [x] Set up a GitHub Project board with columns: Backlog / In Progress / Done — one card per phase

**Deliverable:** Empty repo with README and a project board.

---

## Phase 1 — Requirements

**Goal:** Know exactly what this business needs before designing anything.

- [x] Talk to the client — business goals, real programs offered, coach background, pricing structure, booking approval preference
- [x] Document functional requirements
- [x] Document non-functional requirements
- [x] Confirm final page list based on real content

**Deliverable:** `requirements.md`

---

## Phase 2 — UX / Information Architecture

**Goal:** Know how users move through the site before you know what it looks like.

- [ ] Sitemap — every page and how they connect
- [ ] User flows for key scenarios: booking a private lesson, booking a group lesson, browsing coach background/achievements, checking an event
- [ ] CTA strategy — decide the ONE primary action per page
- [ ] Content inventory — confirm what's real vs. still placeholder
- [ ] UML use case diagram (actors + actions)
- [ ] UML activity diagram (booking flow specifically — has real branching logic)

**Deliverable:** A sitemap diagram + 2–3 user flow diagrams + use case diagram + activity diagram for booking.

---

## Phase 3 — Visual Design (Figma)

**Goal:** Define the design system once, apply it everywhere.

- [ ] Color system (primary, secondary, neutrals, semantic colors) — check contrast ratios now
- [ ] Typography scale — pick 1–2 font families max
- [ ] Spacing scale (e.g. 4/8/16/24/32/48/64px)
- [ ] Core components: buttons, cards, form fields, nav
- [ ] Wireframes → high-fidelity mockups for: Home, About/Coach, Programs, Pricing, Events, Contact

**Deliverable:** A Figma file with a design system page + mockups for each screen 

---

## Phase 4 — Technical Architecture

**Goal:** Make the stack/data decisions deliberately, on paper, before writing code.

- [ ] Finalize stack (frontend, backend, database)
- [ ] Data model / ERD — Programs, Sessions, Bookings, Events, (maybe) Coach profile
- [ ] UML sequence diagram for the booking request (Frontend → API → Database)
- [ ] API design — endpoints and what each returns
- [ ] Decide what's static vs. dynamic
- [ ] Repo/folder structure decision

**Deliverable:** `architecture.md` + ERD diagram + sequence diagram + API endpoint list.

---

## Phase 5 — Implementation

**Goal:** Build in reviewable chunks, static-first.

- [ ] **5a — Static frontend first**: Home, About/Coach, Programs, Pricing, Events, Contact — real content, no backend yet
- [ ] **5b — Backend + database setup**: models, migrations, basic CRUD
- [ ] **5c — Booking flow**: request form → backend → stored → notification
- [ ] **5d — Contact form**: validation, clear success/error states
- [ ] **5e — Polish pass**: loading states, empty states, error states

**Deliverable:** Working site running locally, one feature/page per commit or PR.

---

## Phase 6 — Testing

**Goal:** Catch what you can't see by just "looking at it."

- [ ] Manual QA pass: desktop + tablet + mobile
- [ ] Keyboard-only navigation
- [ ] Screen reader spot check
- [ ] Accessibility audit against WCAG 2.2 AA
- [ ] Performance check (Lighthouse)
- [ ] Form validation edge cases

**Deliverable:** A short test checklist doc with results and fixes made.

---

## Phase 7 — Deployment

**Goal:** Get it live, properly.

- [ ] Choose hosting (frontend: Vercel/Netlify; backend+DB: Railway/Render/similar)
- [ ] Environment variables set up properly (no secrets in the repo)
- [ ] Domain connected, HTTPS confirmed
- [ ] Basic analytics
- [ ] Final production test on the live URL

**Deliverable:** Live website, real domain, working booking + contact forms in production.

---
