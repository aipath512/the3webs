# CLAUDE.md

<!-- The operating manual for this project. Claude reads this first, every session.
     Keep it under ~200 lines. Facts and rules only — no history, no narrative. -->

## 1. What this project is

- Product: <name> — <one sentence a stranger would understand>
- Live at: <domain>
- Repository: <owner/repo>
- Deployed by: <how a file gets from the repo to the live site>
- Primary language: <EN>. Secondary: <none>

## 2. Who the customer is

- Buyer: <role, company size, country>
- What they are trying to avoid: <the fear or cost>
- What they are buying: <the outcome, not the feature>
- What they already tried: <so we don't sell it again>

## 3. Words we use, words we never use

Use: <term>, <term>, <term>
Never use: <term>, <term>, <term>

<!-- Put the hallucinated vocabulary here the day it appears. This section is
     the cheapest fix in the whole file. -->

## 4. Sources of truth

One fact, one file. If two files disagree, the one named here wins.

| Fact | Owner |
| --- | --- |
| Prices | `pricing.json` |
| <count / metric> | `<file>` |
| Legal identity | `<file>` |
| Copy for the homepage | `index.html` |

Never hardcode a fact that a file already owns.

## 5. How to work with me

- One file at a time. Finish it, then ask before starting the next.
- Before opening any file, show: file number, exact upload path, resulting live
  URL, one-line description of what changed.
- When a change is more than a small edit, propose the plan first. I approve,
  then you write.
- If a request conflicts with this file, say so instead of guessing.
- Ask when a decision is mine to make. Don't invent a number, a price, a date,
  a partner name, or a legal detail.

## 6. Definition of done

A file is finished when:

- [ ] It passes every line in `REVIEW.md`
- [ ] Every fact in it comes from a source of truth listed in section 4
- [ ] It works on mobile at 380px
- [ ] Nothing on the page claims something we cannot show evidence for

## 7. Out of scope

Do not work on these unless I say the scope changed:

- <thing that keeps pulling attention>
- <the redesign that is not this week>
- <the feature that needs a decision I have not made>
