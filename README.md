# ClusterShell benchmark results

Demo of the benchmark suite and dashboard proposed in
[clustershell#709](https://github.com/clustershell/clustershell/pull/709).

Browse the charts: https://thiell.github.io/clustershell-benchmarks/ (dashboard,
with the standard ASV site under `asv/`).

- `results/` holds the raw asv results (JSON). They were measured on a
  workstation in one evening: two passes over all revisions in opposite
  order, with their samples pooled.
- The `gh-pages` branch holds the dashboard at its root and the ASV site
  under `asv/`, built from a clean clone of the upstream repository.
