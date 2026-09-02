# REVIEW.md

<!-- The checklist a file must pass before it leaves the desk.
     Every line here should come from a mistake that already happened once. -->

## Blockers — a file with any of these does not ship

- [ ] A number that contradicts the source of truth in `CLAUDE.md` section 4
- [ ] A price written into the page instead of read from `pricing.json`
- [ ] Vocabulary from the "never use" list
- [ ] A claim we cannot show evidence for ("certified", "guaranteed", "compliant")
- [ ] A link, file, or endpoint that returns 404
- [ ] A name, logo, or partner reference I did not approve

## Check before shipping

- [ ] Renders at 380px wide without horizontal scroll
- [ ] Every internal link resolves
- [ ] Every external claim has a source
- [ ] Metadata matches the visible page (title, description, language)
- [ ] Nothing changed outside the file we agreed to touch

## How to report

When a file is ready, tell me in this order:

1. File number and name
2. Exact upload path in the repo
3. Resulting live URL
4. One line: what changed
5. Which blockers were relevant and how each was cleared

If something in this list could not be cleared, say so before I open the file.

## Mistakes log

Add a line the second time something goes wrong. The second time is the signal.

- <YYYY-MM-DD> — <what broke> → new rule: <the line added above>
