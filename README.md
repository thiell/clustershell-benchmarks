# ClusterShell benchmark results

Demo of the ClusterShell benchmark dashboard
([clustershell#709](https://github.com/clustershell/clustershell/pull/709) and follow-ups).

Browse the charts: https://thiell.github.io/clustershell-benchmarks/ (dashboard,
with the standard ASV site under `asv/`).

These pages are the output of a dry run of the benchmarks workflow on a
GitHub-hosted runner (2026-10-15): every release since v1.8 and every master
commit since v1.10.1, up to 4eff431, measured in one job.

- `results/` holds the raw asv results (JSON).
- The `gh-pages` branch holds the dashboard at its root and the ASV site
  under `asv/`.
