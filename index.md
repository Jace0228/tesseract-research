---
title: Tesseract Research
description: Public, machine-checkable research output from Jonathan Carroll's ResearchJobs project — Moon impact probabilities and impact-flash forecasts, with every number traceable to a fetched source.
---

# Tesseract Research

Public output from **ResearchJobs**, Jonathan Carroll's AI-assisted science project. Everything here is produced by
pipelines whose code, data sources and pre-registered gates live in the project repository; this site only publishes
what those pipelines write. The rules the project runs by:

- **Blind recovery first.** A pipeline must reproduce a known published result without being told where it is before it
  is allowed to publish anything new. Each section states its gate and whether it passed.
- **Machine-verifiable.** Every table carries its sample counts, intervals, source hashes and the generation time.
- **Predictions are frozen before the event.** A forecast is committed to this repository before the window it covers;
  the git commit hash and timestamp are the proof. Observed counts are entered afterwards, from third-party reports only,
  and every window is scored — misses included. A correction is a new row, never an edit.
- **Honest odds, honest banners.** A result that has not fully passed its gate says so in its own header.
- **AI use is disclosed.** The pipelines were built by AI build threads (Anthropic Claude models) directed and reviewed by
  Jonathan Carroll. Nothing here has been reviewed by a specialist in the field unless the page says so.

## Sections

| Section | What it is | Files |
|---|---|---|
| [Lunar Sentry](lunar-sentry/) | Which known asteroids could hit the **Moon** in the next 100 years, with our computed chance and the flash each would make. NASA's Sentry publishes this for Earth; nobody did for the Moon. | [`lunar-sentry.json`](lunar-sentry/lunar-sentry.json) |
| [Moon Watch](moon-watch/) | When to watch the Moon for meteoroid impact flashes and how many to expect per hour, per city and telescope size, with a public forecast-vs-observed scoreboard. | [`moon-watch.json`](moon-watch/moon-watch.json) · [calendar `.ics`](moon-watch/moon-watch.ics) · [RSS](moon-watch/moon-watch.xml) · [`scoreboard.json`](moon-watch/scoreboard.json) |

More sections will be added as other jobs in the project produce public, gated results.

## How to use the feeds

- The JSON files are the canonical output; the pages are rendered from the same data.
- Subscribe to the Moon Watch calendar (`.ics`) to get the observing windows in your own calendar, or the RSS feed for new windows.
- Dates and times in the files are UTC. The Moon Watch page also lists local observing hours for ten cities.

## Status

<!-- LAST-UPDATED -->
**Last updated:** 2026-10-12 21:08:40 UTC (automatic daily run; the files below are regenerated from the research repository).
Site created 10/12/2026. Lunar Sentry: v0 table, gate PASS (2024 YR4 reproduced; see the page header). Moon Watch: v1.1 forecast,
gate A PASS / gate B INCOMPLETE — **forecast not fully validated**; v1.2 (per-program detection efficiency) is being built and the
November 2026 Taurids windows will be the first pre-published, scored forecasts.
<!-- /LAST-UPDATED -->

Contact: Jonathan Carroll, via the GitHub repository's issues page.
