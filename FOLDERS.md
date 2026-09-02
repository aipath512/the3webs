# FOLDERS.md

<!-- What lives where. Upload this once; it saves you six separate README files
     in the project knowledge base. -->

```
project/
├── CLAUDE.md      how to work, who the customer is, the quality bar
├── ROADMAP.md     what matters this week, what is out of scope
├── REVIEW.md      what to check before shipping
├── app/           the thing that ships
├── context/       what the product is and why
├── customers/     who buys, what they said
├── specs/         decided behaviour, written before it is built
├── demos/         proof you can show a stranger
└── routines/      work that repeats
```

## /app

The files that actually go live: pages, workers, configuration, data files.
If it is not in here, it is not the product.

## /context

Positioning, the one-paragraph explanation, the competitive picture, the
vocabulary. Answers "why does this exist" for anyone arriving cold, including
Claude in a new conversation.

## /customers

One file per real customer or prospect. What they asked for, in their words.
Objections you actually heard. Nothing invented — an imagined customer produces
imagined copy.

## /specs

Behaviour decided before it is built: pricing rules, what an endpoint returns,
what a page must contain. A spec is what makes review possible; without one,
"is this correct?" has no answer.

## /demos

The two-minute version you can put in front of someone: a screenshot, a live
URL, a recorded flow, a sample report. Proof, not promises.

## /routines

Work that repeats on a schedule: the weekly check, the monthly report, the
pre-launch pass. Written as instructions you could hand to someone else.
