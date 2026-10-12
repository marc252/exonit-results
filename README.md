# ExoNit — public results

> **Experimental — personal research project (Confidence Level L0).** Results are not validated by an
> astrophysicist. These are raw pipeline outputs. **Do NOT submit anything here to ExoFOP** and do not make
> scientific claims based on it. See [CONFIDENCE_LEDGER.md](CONFIDENCE_LEDGER.md).

Generated 2026-10-12T17:17:22Z from internal commit `fbdd17169bf54049582222fb7e9aab9a97d7fc03` by `scripts/release/build_public_results.py`
of [exonit-public](https://github.com/marc252/exonit-public). Everything here is generated; do not edit by hand.

## What is here
- `sectors/s<NNNN>/summary.md` — one row per processed lot (TICs completed, failed, strong candidates, finalists).
- `sectors/s<NNNN>/lots/<run_id>.json` — the lot scorecard (recall vs the TOI catalog by depth/period/sectors,
  period/depth/duration precision, false-positive rates per stage). `<run_id>_dossier.md` — the vetting dossier
  (strong candidates after the systematic-family veto, finalists, shared-signal cross-check, cross-sector queue).
- `candidates/strong_candidates.csv` — every strong-candidate row from every dossier, with its verdict.
- `benchmarks/` — the latest blind TOI benchmark (recall of KP/CP/PC hosts processed with TGLC light curves).
- `INDEX.json` — machine-readable totals.

## How to read a verdict
`planet_candidate` means the gradient-boosted verdict classifier scored above its threshold on the pipeline's
own features; it is **not** a disposition. Compare with ExoFOP before believing anything.

## Totals
| sector | lots | strong | finalists |
|---|---|---|---|
| s0001 | 52 | 392 | 12 |
| s0002 | 20 | 0 | 0 |
| s0003 | 3 | 0 | 0 |
| s0005 | 5 | 0 | 0 |
| s0006 | 15 | 0 | 0 |
| s0007 | 8 | 0 | 0 |
| s0014 | 47 | 20 | 11 |
| s0015 | 16 | 2 | 0 |
| s0017 | 18 | 8 | 0 |
| s0018 | 12 | 0 | 0 |
| s0023 | 17 | 502 | 224 |
| s0026 | 8 | 0 | 0 |
