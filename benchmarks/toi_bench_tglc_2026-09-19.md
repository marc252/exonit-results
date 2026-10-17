# TOI bench report — blind recall (Fase 3, bloc 1)

- Sample TICs: **4490**
- Processed TICs (status=completed): **4489**
- TOIs evaluated (period > 0): **4578**

Percentages below are over ALL TOIs in each group (processed and not) — this is an in-progress run, so `processed` says how much of the denominator has even had a chance yet.

## Per disposition

| Disposition | n | processed | L1 % | L2 % | L3 % | miss reasons |
|---|---|---|---|---|---|---|
| KP | 290 | 290 | 74.5% | 12.4% | 11.4% | no_cand=19, unresolvable=8, wrong_period=47 |
| CP | 307 | 307 | 56.0% | 27.4% | 26.4% | no_cand=14, unresolvable=38, wrong_period=83 |
| PC | 2884 | 2883 | 64.9% | 11.7% | 7.8% | no_cand=200, no_star=1, unresolvable=192, wrong_period=620 |
| APC | 292 | 292 | 73.6% | 18.2% | 11.6% | no_cand=12, unresolvable=20, wrong_period=45 |
| FP | 764 | 764 | 63.2% | 12.6% | 7.2% | no_cand=48, unresolvable=28, wrong_period=205 |
| FA | 32 | 32 | 6.2% | 0.0% | 0.0% | no_cand=6, unresolvable=8, wrong_period=16 |
| none | 9 | 9 | 55.6% | 0.0% | 0.0% | no_cand=1, unresolvable=2, wrong_period=1 |
| **KP+CP** | 597 | 597 | 65.0% | 20.1% | 19.1% | no_cand=33, unresolvable=46, wrong_period=130 |

## KP+CP by period bin

| Bin | n | L1 % | L2 % |
|---|---|---|---|
| <3d | 155 | 78.1% | 17.4% |
| 3-10d | 330 | 70.6% | 23.3% |
| 10-30d | 95 | 34.7% | 16.8% |
| >30d | 17 | 5.9% | 0.0% |

## KP+CP by Tmag bin

| Bin | n | L1 % | L2 % |
|---|---|---|---|
| <10 | 154 | 46.8% | 25.3% |
| 10-12 | 265 | 70.9% | 23.8% |
| 12-13.5 | 119 | 77.3% | 15.1% |
| >13.5 | 59 | 61.0% | 0.0% |

## FP specificity (false promotions)

- FP TOIs evaluated: **764**
- Reach L2 (`planet_candidate`): 96 (12.6%)
- Reach L3 (strong tier): 55 (7.2%)
