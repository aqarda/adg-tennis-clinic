# Requirements — Tennis Clinic Website

*Note: client's name kept generic in this document pending confirmation she's comfortable being named in a public repo. Use her actual name in live site content once confirmed — see Section 7.*

## 1. Business goals

- Primary goal: a professional website that serves as a **coaching portfolio** for the coach — showcasing her background and experience as a competitive tennis player and coach, alongside her clinic's programs, availability, pricing, and contact info.
- Secondary goal: promote **Alberta-area tennis events/competitions** related to the clinic (informational only, links out to external registration — no in-site registration).
- Success looks like: a credible, professional web presence where none currently exists — this is the clinic's first real website.

## 2. Target users

- Parents booking lessons for children (programs are open to all ages)
- Adult recreational players
- Players of any skill level (beginner through competitive) — programs are open to all levels
- Visitors researching the coach's credentials/background before booking

## 3. Functional requirements

| ID | Requirement | Priority (MoSCoW) |
|----|-------------|--------------------|
| F1 | A visitor can view the coach's coaching background, certifications, and public tennis achievements | Must |
| F2 | A visitor can view the two program types offered: private 1:1 lessons and group lessons (open to all ages/genders/levels) | Must |
| F3 | A visitor can view pricing, structured by session length and multi-session packages | Must |
| F4 | A visitor can submit a booking request specifying general preferred days/times (not an exact slot) | Must |
| F5 | The coach manually reviews and approves/declines each booking request against her own schedule (no auto-confirmation) | Must |
| F6 | A visitor can submit a general contact form | Must |
| F7 | A visitor can view promoted Alberta-area tennis events/competitions, with an external link to the official registration page | Should |
| F8 | The clinic receives a notification when a booking request or contact form is submitted | Must |

## 4. Non-functional requirements

| ID | Requirement |
|----|-------------|
| N1 | Pages load in under ~2s on mobile connections |
| N2 | Meets WCAG 2.2 AA accessibility |
| N3 | Works on the last 2 versions of major mobile/desktop browsers |
| N4 | No private/personal identifying information about the coach (home address, personal phone/email, date of birth, family info) appears anywhere on the site or in the public repo — public-facing contact info only |

## 5. Scope boundaries

- **Confirmed IN scope for v1:** informational pages (home, about/coach, programs, pricing, events, contact), booking *request* system (manual approval, no payments), general (not exact-slot) time preference booking
- **Confirmed OUT of scope for v1 (deferred):** online payments, self-serve instant-confirm booking, in-site event registration (external link only)
- Client sign-off on above: [ ] Pending — confirm with the coach once first draft is shown

## 6. Content inventory

| Page | Real content available? | Notes |
|------|--------------------------|-------|
| Home | Partial | Needs a short intro + highlights pulled from About/Programs |
| About / Coach | ✅ Yes | Achievements, national ranking, tournament history available (personal/private info excluded — see N4) |
| Programs | ✅ Yes | Private 1:1 and group lessons, all ages/genders/levels |
| Pricing | ✅ Yes | Varies by session length + package bundles — exact numbers TBD |
| Events | Partial | Concept confirmed (link out to official registration); specific upcoming events TBD |
| Contact | Partial | Booking + general contact form; public-facing phone/email TBD |

## 7. Open questions (unresolved — follow up needed)

- **Whether the coach is comfortable being named by her real name in this public repo/requirements doc** — currently kept generic pending her confirmation
- Exact pricing numbers for private lessons, group lessons, and package bundles
- What public-facing phone number/email should be listed (not her personal ones)
- Specific upcoming Alberta tennis events she wants promoted, and their official registration links
- Any certifications/coaching credentials beyond what's in the achievements document
- Does she want her competitive playing history condensed to highlights, or does she want a fuller tournament history list on the site?

## 8. Assumptions (not confirmed — stated explicitly)

- Assuming "all ages and genders and all levels" applies to both private and group lessons equally (not split by program type)
- Assuming the site should NOT display the full ~20-item tournament list verbatim from her résumé — a condensed highlights version is more appropriate for a public website; full list available as source material if she wants more detail
- Assuming no existing brand colors/logo, since there's no prior web presence — visual identity will be defined from scratch in Phase 3
- Assuming her real name and clinic name CAN be used in live site content (that's the whole point of the site) — the generic naming in this document applies only to what's committed to the public repo/requirements doc, not the eventual live website