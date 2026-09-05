# Open: profile README redesign

**Status: v1 shipped and live, but founder isn't happy with it. Revisit before calling this done.**

## What's live now (v1)

- Hero concept: a boathouse rack of finished racing shells, drawn as a pen-plotter blueprint,
  in the portfolio's real brand palette (cream/peach/electric-blue), ink/cream variants that
  swap with GitHub's light/dark theme.
- A "manifest" table (`## The Rack`) of real projects with honest status instead of a badge wall.
- Live contribution-stats widgets (github-readme-stats / streak-stats / activity-graph).

## Why it's flagged, not finished

Founder feedback after seeing it live: doesn't like it, no specifics given yet. Don't assume
what's wrong — get concrete direction before redesigning (what's off: the rowing/boathouse
concept itself, the tone/copy, the layout, the color execution, something else entirely).

## Known secondary issue (separate from the above)

The contribution-stats widgets are unreliable on their free public instances — at last check,
`github-readme-stats.vercel.app` returned 503 and `github-readme-activity-graph.vercel.app`
returned 402 (payment required); only `github-readme-streak-stats` was up. Durable fix is
self-hosting a personal instance on Vercel (free, fork-and-deploy) rather than depending on the
shared public ones. Not done yet — do this regardless of what happens with the redesign above.

## Next step

Get the founder's actual reaction in detail (what to keep, what to kill, any new reference/
direction) before touching the design again.
