# Funnel Teardown Workbench

Takes apart a digital health funnel, labelling every finding as observed, sourced or inferred.

**[Try the live demo](https://funnel-teardown-workbench.vercel.app)**. It works straight away with no setup, runs entirely in your browser, and stores nothing. All data is fictional or synthetic.

## Why I built it

I took apart several live telehealth funnels by hand, page by page and review by review. The hardest discipline was keeping track of what I'd actually seen versus what I was guessing, so I built that discipline into a reusable tool.

## The problem

Most funnel reviews blur what you saw yourself, what a customer review says and what you're guessing, so the list of top issues mixes facts with hunches.

## What I built

Two fictional funnels, one direct to consumer and one where clinicians control access, with a clear scope box, a stage by stage severity view, a way to log new findings and a prioritized summary that keeps guesses in a separate 'validate first' list. It exports to Markdown.

## Who it's for

Product managers, growth leads and analysts reviewing a digital health product from public information.

## What it does

- Switch between a direct to consumer funnel and a clinician controlled one
- Filter by stage, hide inferred findings and log your own
- Get a prioritized summary and copy the full review as Markdown

## Decisions that shaped it

1. **Every finding says how you know it:** observed, sourced or inferred.
2. **Scope is part of the result:** including what was deliberately left out.
3. **Find who really converts:** when clinicians control access, they are the real customer.

## Key takeaway

Confidence is part of every finding. Something you observed carries more weight than something you inferred.

## Built with

- HTML, CSS and JavaScript in a single file

## Run it locally

Open `index.html` in any browser. There's nothing to install.

## About this project

This is a working prototype I built to explore a real problem space. It uses illustrative, fictional data and isn't connected to any organisation's systems. You can find more of my work at [jane-natividad.github.io](https://jane-natividad.github.io).

Built by [Jane Natividad](https://github.com/jane-natividad).
