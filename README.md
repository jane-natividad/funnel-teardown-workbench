# Funnel Teardown Workbench

A structured workbench for tearing down a live digital-health funnel from the outside, where every finding is tagged by stage, severity, and how you actually know it — observed, sourced, or inferred.

**[Live demo](https://funnel-teardown-workbench.vercel.app)** — works immediately, no API key or setup required. Everything runs in your browser; nothing you enter is stored or sent anywhere. Please use fictional/sample data only.

## Who it's for

Product managers, growth leads, and analysts evaluating a digital-health product — their own or a competitor's — from public information.

## Why it matters

Most funnel teardowns blur what you saw yourself, what a customer review says, and what you're guessing — so the 'top issues' list mixes facts with hunches. This tool forces every finding to say how you know it, so the final priority list separates confirmed problems from hypotheses to validate.

## What it does

- Switch between a DTC subscription funnel and a clinician-gated (B2B2C) funnel
- Filter findings by stage, hide inferred findings, and log your own
- Get a prioritized summary ranked by severity × confidence, and copy the whole teardown as Markdown

## Product decisions that mattered more than the model

1. **Evidence type on every finding** — observed, sourced, or inferred
2. **Scope is part of the output** — including what was deliberately not done
3. **Find who actually converts** — in a clinician-gated product, it's the clinician

## Built with

- HTML, CSS, JavaScript (single-file prototype, no framework, no build step)

## Run locally

Open `index.html` in any browser — no install needed.

## Status

This is a prototype built to explore a problem space, using fictional/synthetic data — not a finished product and not connected to any organization's real systems. Built by [Jane Natividad](https://github.com/jane-natividad) — see more at [jane-natividad.github.io](https://jane-natividad.github.io).
