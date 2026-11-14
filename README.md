# splinterlands-tools-data

Machine-published public data snapshots for [app.splinterlandstools.com](https://app.splinterlandstools.com)
(Verico Strategist / Glint Bombs). **Do not edit by hand — this branch is force-pushed hourly.**

- `verico/entries.json` — per-player eligible plot counts (entries) + the exposure-weighted
  per-plot daily win rate.
- `verico/claims.json` — archive of `claim_glint_bomb` transactions. The public
  `transactions/history` endpoint caps at 1000 rows and ignores pagination, so it silently
  drops older claims; this file preserves them.

All content is derived from public Splinterlands/Hive APIs.
