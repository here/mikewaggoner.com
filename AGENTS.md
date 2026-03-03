# AGENTS.md

Guidelines for AI agents working on this repository.

## Repository Overview

Static personal portfolio site for Mike Waggoner, served from `docs/` via DigitalOcean App Platform. Deployment is triggered automatically by pushing to the main branch.

**No build step. No package manager. No JavaScript framework.**

## File Structure

```
docs/
  index.html   # All site content lives here
  style.css    # All styling lives here
  404.html     # Custom error page
  assets/img/  # Images only
README.md      # Deployment notes
```

Do not create new files unless explicitly requested. Do not add JavaScript, build tooling, or dependencies.

## Editing Style

### Conference List (`docs/index.html`)

The events list is grouped by year (descending) then sorted by date within each year (descending — latest month first).

**Entry format:**
```html
<li><a href="URL">Event Name Location</a> - Mon D-D</li>
```

- Name and location are concatenated in the link text, no separator
- Date format: abbreviated month + day range (e.g. `Aug 6-9`, `Jun 24-28`)
- For multi-month spans: `Jul 30-Aug 3`
- Wrap in `<i>...</i>` for planned or attended events (italics signal personal attendance)
- URL should be the most specific relevant page (e.g. community-tracks page, not just the homepage)

**Example of a correctly formatted entry:**
```html
<li><a href="https://sfconservancy.org/fossy/community-tracks/">FOSSY Vancouver BC</a> - Aug 6-9</li>
```

When adding a conference, always fetch the event URL to confirm dates and location before editing.

### General HTML Conventions

- Indentation: 2 spaces, matching surrounding context
- No trailing whitespace changes to unrelated lines
- Do not reformat or reorganize sections not being edited

## Branch and Commit Conventions

- Work on `claude/` branches as specified by the task
- Commit messages: short imperative summary, detail line if needed
- Only commit `docs/index.html` or `docs/style.css` for content edits; do not stage unrelated files

## What Agents Should Not Do

- Do not add comments, docstrings, or annotations to HTML/CSS
- Do not refactor or reformat code beyond the immediate change
- Do not add error handling, fallbacks, or new structural elements speculatively
- Do not push to `main` directly
