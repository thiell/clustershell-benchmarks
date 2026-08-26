# ClusterShell benchmark results

Benchmark results for [ClusterShell](https://github.com/clustershell/clustershell),
produced by the asv suite in the main repository (`benchmarks/`).

Browse the charts: https://thiell.github.io/clustershell-benchmarks/

- `results/` holds the raw asv results (JSON, per machine).
- The `gh-pages` branch holds the generated HTML site (`asv publish`).

To add results: run `asv run` from `benchmarks/` in the main repository, copy
the new files from `benchmarks/.asv/results/` here, regenerate the site with
`asv publish`, and update the `gh-pages` branch.
