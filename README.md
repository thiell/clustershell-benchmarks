# ClusterShell benchmark results

Demo of the benchmark suite and dashboard proposed in
[clustershell#709](https://github.com/clustershell/clustershell/pull/709).

Browse the charts: https://thiell.github.io/clustershell-benchmarks/ (dashboard,
with the standard ASV site under `asv/`).

These pages are the output of a dry run of the #709 workflow on a
GitHub-hosted runner (2026-10-08): every release since v1.8 and ten master
commits up to 3324b25, measured in one job.

- `results/` holds the raw asv results (JSON).
- The `gh-pages` branch holds the dashboard at its root and the ASV site
  under `asv/`.
