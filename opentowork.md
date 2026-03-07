# opentowork.md

Planning document for the "Open to Work" sub-project on mikewaggoner.com and related resources.

See also: [AGENTS.md](AGENTS.md) for general agent conventions on this repo, including the editor preference (VS Code, not Cursor).

---

## Project Goal

Signal Mike's availability and fit to potential collaborators, clients, and employers — primarily through mikewaggoner.com but also via supporting materials and outreach resources.

Mike is open to:
- **Engineering / consulting / freelance** — Python, web architecture, cloud/SaaS, identity/IAM, geospatial
- **Staff / senior technical roles** — Solutions Architect, Staff Engineer, Principal Architect, or similar
- **Advisory or fractional work** — identity standards, digital civics, open source infrastructure

---

## Current State (as of 2026-03)

The site already includes:
- An explicit "open to new work" line in the intro
- A Calendly link for 30-minute discovery calls
- A summary of 10 years at Disney (Staff Solutions Architect)
- A specialties list (identity, web arch, Python, etc.)
- A conference/events list signaling active community engagement

Gaps identified:
- No dedicated page or section for project/portfolio work
- No downloadable or linked resume/CV
- No clear articulation of target role types or engagement models
- The "open to work" signal is buried mid-paragraph rather than prominently positioned
- No case studies or examples of past work

---

## Site Improvement Areas

### 1. Strengthen the Open-to-Work Signal

- [ ] Promote "open to new work" earlier in the page flow (above the fold or near the top)
- [ ] Add a brief positioning statement — what kind of work, what kind of team/org
- [ ] Consider a callout box or styled section for the availability signal + Calendly CTA

### 2. Resume / CV

- [ ] Create a linked resume (PDF or dedicated HTML page at `/resume`)
- [ ] Include: Disney highlights, key projects, skills, community involvement
- [ ] Keep in sync with `index.html` specialties list

### 3. Portfolio / Projects Section

- [ ] Add a section (or standalone page) listing select past and current projects
- [ ] Suggested projects to highlight:
  - Disney employee directory (~1M records, multi-HCM)
  - Knowledge management systems (theme park, legal, infosec)
  - IAM consulting (CA SiteMinder → Okta/SailPoint migration)
  - Open source / community work (fediverse, geosocial, DID/SharedSignals)
- [ ] Each entry: brief description, tech/domain, outcome or impact

### 4. Target Roles / Engagement Clarity

- [ ] Add a short section or sidebar-style note on what engagements fit best
- [ ] Examples: "I'm well-suited for orgs building internal platforms, identity infrastructure, or open-source-adjacent projects"
- [ ] Avoid generic "open to opportunities" language — be specific about domain fit

### 5. Contact / CTA Improvements

- [ ] The Calendly link is good — keep it prominent
- [ ] Consider adding a direct email CTA alongside Calendly
- [ ] Review LinkedIn profile alignment with site messaging

---

## Related Resources

These live outside the repo but are part of the open-to-work project:

| Resource | Status | Notes |
|---|---|---|
| LinkedIn | Active | `/in/mikehere/` — check alignment with site copy |
| GitHub | Active | `github.com/here` — pin relevant repos |
| Calendly | Active | `calendly.com/mike-here/30min` — keep current |
| Resume/CV | Missing | To be created; link from site |
| Mastodon | Active | `social.coop/@herebox` — professional presence |

---

## Agent Guidelines for Open-to-Work Tasks

When working on tasks related to this sub-project:

- Follow all conventions in [AGENTS.md](AGENTS.md)
- Do not alter the existing conference list or general site structure without explicit instruction
- Positioning and tone should match the existing voice: conversational, technically credible, community-oriented — not corporate or salesy
- Resume/CV content should be derived from `docs/index.html` and confirmed with Mike before finalizing
- Do not speculatively add new pages; create them only when explicitly requested

### File Naming Conventions for New Deliverables

```
docs/resume.html         # Dedicated resume page (if created)
docs/resume.pdf          # Downloadable PDF resume (if created)
docs/projects.html       # Portfolio/projects page (if created)
```

---

## Open Questions

- ~~What engagement model is preferred: full-time, contract, advisory, or all?~~ → **All / flexible** (confirmed 2026-03)
- Are there specific industries or mission areas to target (civic tech, open source, climate/water, transit)?
- Should the resume live on-site as HTML, as a downloadable PDF, or both?
- Is a separate `/projects` page desired, or should portfolio content be inline on the homepage?
- Any embargo on mentioning specific Disney/employer project details publicly?
- WebUrbanist Director of Technology role — dates TBD
- Pre-WebUrbanist experience — not yet captured
- Education — details TBD (placeholder in resume)

---

## Resume Boilerplate

Created: `hire/resume.md` — source-of-truth markdown resume for generating focused versions and PDF/DOCX exports.

### Assumptions logged (2026-03)

- Engagement model: **all / flexible** (FTE, contract, advisory, fractional)
- Location: **omitted** from resume
- Pre-Disney role: **WebUrbanist, Director of Technology** (dates TBD)
- Education: **placeholder** pending details
- Tone: conversational, technically credible — not corporate
- Resume scope: Disney (Staff SA) + WebUrbanist (Dir of Tech) + skills/community
