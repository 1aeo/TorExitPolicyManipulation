# TorExitPolicyManipulation

Analyses of the September–October 2026 exit-policy changes on Tor relays (the Quetzalcoatl family and
others), built from public data only. Each top-level folder holds the work for one data source.

| Folder | Data source | Contents |
|---|---|---|
| `collector-exit-policy-analysis/` | Tor Metrics CollecTor (consensuses, votes, server descriptors, 2025-01 .. 2026-10), with CAIDA and IPFire AS data; Onionoo as a cross-check | Reproduction of the Quetzalcoatl incident analysis, the network-wide analysis, and the tor-relays email draft |

Each folder has its own README with the steps to reproduce it. Downloaded data and large databases are
not committed; each folder's `.gitignore` lists them.

`collector-exit-policy-analysis/` was moved here, with its git history, from `quetzalcoatl-repro/` in
[1aeo/TorUtils](https://github.com/1aeo/TorUtils).
