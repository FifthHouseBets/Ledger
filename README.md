# FifthHouseBets — Public Ledger

Every pick we actually posted on X ([@FifthHouseBets](https://x.com/FifthHouseBets))
-- the daily **Cheat Sheet** (moneylines) and **Dinger Dandies** (home run
props) -- with its settled result.  `ledger.csv` is regenerated and
committed daily; nothing is edited or removed after the fact, so the git
commit history itself is the timestamp proof.

Tracking begins **2026-07-08**, the day this exact posting format
(Cheat Sheet + Dinger Dandies + morning Scorecard) launched. Earlier
days are not backfilled or reconstructed.

## Season so far (as of 2026-08-04 14:20 UTC)

- **Moneylines (Cheat Sheet):** 56-58 · -5.25u
- **HR props (Dinger Dandies):** 5-36 · -21.97u — its own ledger,
  never blended with the moneyline record
- **H+R+RBI unders (Quiet Nights):** 41-40 · +2.24u — posted since 2026-07-11, its own ledger

## Columns in `ledger.csv`

| column | meaning |
|---|---|
| date | game date (America/Chicago) |
| market | `ML` (moneyline), `HR` (home run prop), or `UNDER` (hits+runs+RBI under) |
| selection | who/what we picked |
| entry_odds | American odds at the moment we posted, pre-game |
| result | `WIN` / `LOSS` / `VOID` / `PUSH` |
| units | profit/loss at a flat 1-unit stake |
| clv_pp | closing-line value vs the market close (percentage points) |
| clv_fair_pp | CLV vs the de-vig ("no-vig") fair close — the stricter, honest-scale version |

21+. Not financial advice. Every pick timestamped pre-game.
