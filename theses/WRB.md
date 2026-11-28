# WRB — W. R. Berkley Corporation — 2026-11-23

> [!IMPORTANT]
> **In one sentence:** W. R. Berkley is a disciplined specialty insurer, but at $77.90 the price needs about a 22% return on equity forever against 18.8% just delivered, so I pass.

Price $77.90 (official close, 2026-11-23; last trade $77.91) · market cap
$30,294,888,249 · next earnings 2027-01-25 AMC (broker tier, unverified;
`earnings.db` edgar-estimate 2027-01-18)

Scheduled re-run that supersedes `research/WRB-2026-10-22.md` (PASS at
$75.79, kill-thesis FLAWED). Not a reopen: that thesis's trigger dates
2027-01-26 (the Q4 print) and has not come due, so this run re-prices the
name, sweeps what was filed since (the Q3 10-Q), and re-derives the hurdle.
Held name (`composite.db` snapshot 146 `in_portfolio = 1`). Unattended
scheduled run.

## 1. Verdict and thesis

**PASS at $77.90.** kill-thesis: **FLAWED** — conditions=4 (2 probable,
2 plausible), refuted=1, unknown=0, pending=0, not_obtained=0.

> [!IMPORTANT]
> **p(beat SPY, 63 td): 0.42** · kill-thesis: 0.40 ·
> **Disputed expectation:** at 3.15x September book the price implies WRB
> earns ~22% on equity forever (~20.3–20.7% on a book with the bond marks
> reversed), against 18.8% printed in Q3 and ~17.7% at full new-money
> repricing. What revises it up is CR holding near 90% with rate ≥4% through
> the 1/1 reset; what revises it down is the Q4 year-end reserve review
> (commercial auto) and property/reinsurance softening earning in.

Nothing in the business changed in the month since the last run; the price
and the hurdle did. The stock rose 2.8% to within ~2% of its 52-week high
with no new company disclosure behind it, and the 10-year fell 23bp. A
lower rate does not rescue the valuation: it cuts the terminal-growth
ceiling (the breakeven fell to 2.13%) almost one-for-one with the risk-free,
so the gap between the cost of equity and growth is unchanged, while the
price-to-book multiplying that gap went up. This run also corrects the prior
run's ERP, which used Damodaran's cash-yield alternate rather than his
headline figure; the correction raises the hurdle ~40bp. A good insurer, a
full price. An owner holds; adding is not supported.

> [!WARNING]
> **Closest attack:** the beta floor, still. At the screened 0.22 beta the
> hurdle is 5.89%, the required perpetual ROE on reported book falls to
> ~14.0%, and every mid-cycle estimate clears it. The floor (0.8) is a stated
> convention doing load-bearing work (§4). Second: the Q4 bond-mark reversal.
> Rates fell 37bp since 9/30, so year-end book should recover a few hundred
> million, but that only moves the requirement from ~22.0% to ~20.7% — still
> above every delivered or modelled ROE.

Load-bearing conditions of the bull case (4):

1. **Mid-cycle ROE is sustained at ~22% (9/30 reported book) / ~20.3%
   (mark-reversed book) or better.** *Plausible*: Q3 operating ROE 18.8%,
   YTD 20.2% (Q3'26 8-K ex-99.1). 2010–2020 mean ~12%; full new-money
   repricing worth ~17.7% on today's book (§4). The FY2026 10-K
   (~2027-02-26) gives the full-year read.
2. **Underwriting discipline holds through the softening cycle.**
   *Probable*: Q3'26 CR 90.8%, AY ex-cat 88.1%, reinsurance NPW −11.6% by
   choice, renewal retention ~80% (Q3 8-K and call, 2026-10-19).
3. **Total reserves stay adequate: long-tail adverse keeps being absorbed
   without a material charge.** *Plausible*: Q3 net PYD ~0, insurance ~$15M
   adverse (commercial auto) offset by reinsurance releases (call); the 10-Q
   line split was not obtained (§6). The FY2026 10-K triangle (~2027-02-26)
   decides it.
4. **Capital-return and governance regime unchanged.** *Probable*: $435.1M
   of buybacks and $0.79/sh regular dividends through 9/30 (10-Q); "10
   figure" excess capital retained (call); no 8-K, 13D/A, Form 4 or 144
   since the call (EDGAR, §3).

> [!WARNING]
> **Dominant shared risk factor:** US commercial casualty pricing cycle and
> long-tail loss-cost inflation — shared by 2 of 30 other held names (HIG,
> ORI) · 0 unlabelled. Holdings read from `composite.db` snapshot 146
> `in_portfolio = 1` (the headless slot has no `portfolio.db` grant).

## 2. Business

Unchanged from `research/WRB-2026-10-22.md` §2; deltas only.

**Created:** specialty and E&S commercial coverage through ~60 decentralized
operating units, with other liability deliberately shifting toward smaller
accounts where competition is thinner (Q3 call).

**Captured:** (1) underwriting profit (Q3 record $296M on $3.21B NPE);
(2) float — net invested assets $33.95B, Q3 NII $383.5M (+9.2%), duration
3.3y against a ~4-year reserve life, domestic book yield ~4.7% with new money
80–100bp above *at the 10-19 call* (DGS10 then 5.15%; 4.92% now, so the
spread has narrowed); (3) small fee and non-insurance lines.

**Protected:** decentralized authority plus willingness to shrink
(reinsurance guided −10% to −20%). Diversification across lines absorbs a
single-line miss; it does not defend against an industry soft market.

**Control:** one class, one vote. Berkley family ~24.6%, Mitsui Sumitomo
15.1%, vote-aligned per the 2025 framework (13D/As carried). ~40% voting in
concert forecloses an unsolicited takeover and any activist path.

**Operating leverage (Phase 0): positive over the cycle, flat-to-stalling
on premium now.** FY2019–2025 revenue CAGR 10.9% vs pretax 17.8% (carried).
TTM revenue $14.867B through 9/30 (`stocks.db`), flat vs $14.87B at the
prior run; Q3 NPE +1.8% YoY while NII +9.2% and operating income +3.7%.
Earnings growth now comes from the bond portfolio, not premium.

## 3. Threads pulled

- **What moved since 10-22: price and rates, not the company.** Close
  $75.55 (10-22) → $77.90 (11-23), +3.1%; intraday high $79.70 on 11-20, a
  new 52-week high above the $78.96 the prior run carried. DGS10 5.15%
  (10-19) → 4.92% (11-20); 9/30 was 5.29%. T10YIE 2.35% → 2.13%. No new
  transcript: stockanalysis lists 95 events, newest Q3 2026 (2026-10-19),
  already read by the prior run.
- **Q3 10-Q and post-call docket** (EDGAR submissions JSON, CIK 11544).
  Since 2026-10-20: 10-Q 0000011544-26-000048 (filed 2026-11-02), S-3ASR
  0001193125-26-443869 (2026-11-02), 13F-HR (2026-11-16, WRB's own
  holdings), two 13G/As (10-27, 10-30) and a 53-filing 13G/13G/A batch on
  11-09 from one filing agent (bulk passive-holder filings; not read
  individually). **No 8-K, no Form 3/4/144, no 13D/A** — silence on the
  insider and control side. The S-3ASR is a universal shelf for a
  well-known seasoned issuer; read as routine renewal, not a raise (no
  prospectus supplement filed). 10-Q statements: Q3 pretax $574.3M (vs
  $648.1M, the gains comparison); NII $383.5M Q3 / $1,206.6M 9M; buybacks
  $21.1M Q3 / $435.1M 9M; dividends $0.10 Q3, $0.79 9M (regular only, no
  special); AOCI −$1,248.7M = unrealized investment −$928.2M + FX −$320.5M;
  shares 371,515,776 at 2026-10-26. Release: expense ratio 28.6% (28.5%),
  loss ratio 62.2%, Insurance CR 91.7%, Reinsurance & Monoline 83.4%,
  duration 3.3y, BVPS $25.87, TBVPS $25.27. The 10-Q's MD&A (line-level
  PYD, earned yield) and Part II (post-quarter buybacks, remaining
  authorization) were **not obtained** — the fetch truncated at Note 6 (§6).
- **Q4 book from the rate move (my estimate).** A 37bp fall at ~3.3y
  duration on a fixed-income book in the high-$20Bs is roughly $250–300M
  after tax of mark reversal. Add ~$0.45B Q4 operating income, less the
  regular dividend, and year-end book lands near ~$10.3B before any special
  dividend: ~2.94x at today's price. The estimate is mine, not a filing
  (§6).
- **The same rate move cuts the bull's best new argument.** The 80–100bp
  new-money spread was quoted against a 5.15% 10-year. At 4.92% the spread
  over the ~4.7% domestic book yield is ~23bp narrower, so Run F's
  full-repricing uplift is now a ceiling, not a midpoint.
- **Earnings-estimate pattern** (broker tier): $1.01/0.99, $1.05/1.04,
  $1.10/1.09, $1.13/1.13, $1.30/1.14, $1.27/1.09, $1.17/1.16; Q4 consensus
  $1.21 (was $1.20). Beat-by-a-hair resumed in Q3. The actuals are operating
  EPS; SEC `v_screener` carries Q3 GAAP diluted $1.14 on $446.0M net income,
  consistent with the 8-K's GAAP/operating bridge.
- **Sell-side.** `stocks.db` mean target $69.82 (18 analysts, Hold), 10.4%
  below the price — the gap widened from $6.73 to $8.08.
- **Options read (mandatory):** path 2 only (Robinhood stopgap); path 1 not
  applicable — WRB is outside the 24-symbol CBOE catalog and `options.db`
  holds zero WRB rows. Expiry Apr-16-2027, the first that brackets the
  thesis's catalyst (the Q4 print 2027-01-25 AMC, repricing 01-26; Jan-15
  expires before it). Liquidity gate FAILS badly. §4 has the table.
- **Dead ends:** `composite.db` snapshot 146 scores WRB coverage 0.0, no
  flags. `stocks.db` short-interest fields read implausibly (shortFloat
  0.012; the statistics page states 30,255 shares short vs ~5.4% of float a
  month ago) — a feed artifact, not a covering event; not load-bearing and
  not pursued. Web search for November company news found nothing beyond the
  Q3 release.

## 4. Valuation

**Inputs.** Market cap $30,294,888,249 (388,894,586 shares incl. grantor
trust × $77.90). TTM net income $1,862,994,000 (`stocks.db`, through 9/30;
SEC Q3 net income $446,005,000 matches). TTM OCF $3,194,369,000 and capex
−$116,257,000 now roll through 9/30; levered FCF less SBC ($62,443,000, 0.42%
of revenue) $3,015,669,000 — float-inflated, a bound only. Equity
$9,610,213,000 (9/30, 8-K and 10-Q). All flows levered and paired with
**market cap**, net debt 0 by the pairing rule; investment cash is float
backing and not netted; NCI negligible. P/B 3.152.

**Hurdle:** rf 4.92% (DGS10, 2026-11-20) + beta 0.80 × ERP 4.41% (Damodaran
implied ERP, headline "trailing 12 month, with adjusted payout", as-of
2026-11-01; his T-bond 4.94%) = **8.45%**. Beta floored from the screened
0.221 (`stocks.db`), same reasons as the prior run: float 63.9% of shares,
two vote-aligned anchors, and a regression beta on an underwriting cycle
measures liquidity rather than risk. Raw-beta hurdle 5.89%. **ERP
correction:** the 2026-10-22 run used 3.70%, Damodaran's October
*cash-yield alternate*; his October headline was 4.20%. On the prior run's
basis (Nov alternate 3.79%) this run's hurdle would be 7.95%. **Terminal
growth 2.13%**, the 10-year breakeven (T10YIE, 2026-11-23).

| scenario | base FCF | growth ×5y | terminal | implied return | vs hurdle |
|---|---|---|---|---|---|
| A — all TTM net income distributable (bound) | $1,863.0M | 5% | 2.13% | 9.23% | +78bp |
| B — TTM ROE 19.26%, retention charged | $1,379.3M | 5% | 2.13% | 7.40% | **−104bp** |
| C — 9/30 levered FCF less SBC (float-inflated bound) | $3,015.7M | 4% | 2.13% | 13.09% | +464bp |
| D — mid-cycle 16.3% ROE (5.0% yield), retention charged | $1,086.0M | 5% | 2.13% | 6.29% | **−215bp** |
| E — mid-cycle 14.9% ROE (trailing like-for-like yield) | $951.4M | 5% | 2.13% | 5.78% | **−267bp** |
| F — full new-money repricing, ~17.7% on 9/30 book | $1,221.9M | 5% | 2.13% | 6.81% | **−164bp** |
| G — Q3's 18.8% operating ROE held forever, retention charged | $1,326.2M | 5% | 2.13% | 7.20% | **−124bp** |

G is new this run: the bull's best *delivered* number (Q3 operating ROE,
a benign-cat quarter with a property benefit the CFO called not run-rate)
held in perpetuity. It still prints −124bp. F was −103bp on 10-22; the move
to −164bp is the ERP correction (~−40bp), the price (+2.8%) and the lower
breakeven.

**Integrity checks.**

- *Reinvestment / terminal ROE.* A and C trip the tool's growth-without-
  reinvestment warning and are bounds only. B charges retention g/ROE
  (implied terminal ROE 8.20% vs 8.45% hurdle — terminal value assumes
  roughly cost-of-capital returns, the default fade read). D–G's printed
  terminal ROEs (5.1%/4.4%/6.2%/7.4%) are computed against TTM earnings, not
  their own mid-cycle earnings; on their own earnings terminal ROE equals
  the scenario ROE, with no fade below it — generous.
- *The excess-return cross-check (the finding).* Required perpetual ROE =
  g + P/B × (r − g). Reported 9/30 book: 2.13% + 3.152 × 6.32% = **22.0%**.
  Book with the full $928.2M after-tax unrealized investment loss added back
  ($10.54B, 10-Q AOCI): 2.13% + 2.875 × 6.32% = **20.3%**. Estimated
  year-end book ~$10.3B (§3): ~20.7%. Against Q3
  operating 18.8%, full-repricing ~17.7%, mid-cycle 14.9–16.3%. r − g is
  6.32% vs 5.76% last run: the ERP correction (+0.57pt at the floor beta)
  more than offsets the rate move, which lowered r and g almost equally.
- *The double count, carried.* Adding the mark back to book *and* crediting
  full new-money yield counts one rate move twice; admissible pairs are
  reported book with F (22.0% vs ~17.7%) or ex-mark book with D/E (20.3% vs
  14.9–16.3%). Each CR point is ~1.0pt of ROE; closing the gap needs ~3–5
  *permanent* CR points beyond the ~94.7% 2013–2020 mean already embedded.
- *Like-for-like drift.* On the prior run's ERP basis (7.95% hurdle), B is
  −55bp, vs −37bp on 10-22: price +2.8% and breakeven −22bp moved it, not
  the business.
- *Base-year integrity.* Cash tax ~20% vs ~23% normalized (carried). Growth
  organic. Cat load 9M'26 $224M vs $289M 9M'25 — a benign year flattering B.
- *Market share.* 5% for five years takes revenue $14.87B → ~$19.0B, ~3% →
  4% of US commercial P&C premium (carried, order-of-magnitude). The case
  fails on margin, not size.
- *Terminal risk (FY2025 10-K Item 1A).* Pricing cycle, long-tail reserving
  under social inflation, cat severity; AI-liability latency named on the
  Q3 call. Annual repricing lets premium track nominal loss cost, so a
  2.13% nominal terminal (the breakeven, no real growth claimed) survives.
- *Distribution clamp.* D 6.29%, E 5.78%, F 6.81%, G 7.20%, B 7.40%:
  inside Damodaran's US 5–10% band, below its ~7.8% median.
- *Prices at which the 8.45% hurdle clears* (two-stage arithmetic at fixed
  base, same model as the tool): B ~$65, G ~$62, F ~$57, D ~$51.

**Options-implied move** — path 2 (Robinhood stopgap) only; path 1
unavailable (not in the CBOE catalog, no `options.db` rows). Apr-16-2027
expiry, strike 77.5 (nearest to spot 77.90), DTE 144 — brackets the Q4
print (2027-01-25 AMC) and the 1/1 renewal season; it also spans ~5 months
of ordinary tape and two ex-dividend dates, so it is not an earnings-only
measure. Closes: 67 regular-session closes 2026-08-20 → 2026-11-23 (the
interpolated 11-23 bar replaced by the official close).

| metric | value |
|---|---|
| spot | 77.90 |
| expected absolute move (MEAN, not a ceiling) | 12.71% |
| 1-sigma move | 15.89% |
| ATM IV | 25.29% |
| RV60 | 19.88% |
| IV > RV60? | YES |
| RV20 | 20.05% |
| IV > RV20? | YES |

Both windows agree IV sits above realized; with a print and the reinsurance
reset inside the expiry that is the market pricing a known calendar item
(the stopgap's structural bias), not a discovery.

**Liquidity gate: FAILED → UNRELIABLE.** Call 4.00/7.50 around a 5.75 mark
is a 60.9% spread; put 3.00/5.30 around 4.15 is 55.4%. Volume 0 / 0
against OI 8 / 1. It may not move a verdict and does not.

**Timing check: NOT APPLICABLE.** The thesis makes no dated price claim.

## 5. Falsifiers

**For the pass (flip toward buy):**

- **Shift —** the beta convention: reject the 0.8 floor on argued grounds
  (hurdle 5.89%, required ROE ~14.0%; every mid-cycle estimate clears).
- **Shift —** price at or below ~$65 (Run B clears at fixed base); ~$57
  clears Run F.
- **Shift —** plateau proof: CR ≤ ~91% with rate ex-comp ≥ 4% through
  Q4'26 and Q1'27, after the 1/1 property/reinsurance reset.

**For an owner (sell):**

- **Break —** reserves: other-liability or auto strengthening of $100M+ in
  a quarter, or net PYD adverse beyond ~$150M a year — watch the Q4
  year-end review, now that the reinsurance releases covering auto shrink
  with the segment.
- **Break —** discipline: AY ex-cat CR sustained above 95% while NPW grows.
- **Shift —** pricing: rate ex-comp negative, or insurance growth bought
  with rate.
- **Shift —** control: family/estate or MSI selling.

> [!NOTE]
> **Reopen trigger:** 2027-01-26: `wrb-q4-print-1-1-renewal-ay-excat-and-auto-pyd-or-price-at-or-below-65`
> — the Q4'26 print (2027-01-25 AMC, broker tier, unverified) must show AY
> ex-cat CR, rate ex-comp after the 1/1 renewals, the year-end reserve
> review's line-level PYD (commercial auto, other liability), full-year
> operating ROE and year-end book; or price at or below ~$65. Classification:
> shift (revalue, not exit). An owner holds through it.

## 6. UNKNOWNs

1. **NOT OBTAINED — Q3 10-Q MD&A and Part II** (0000011544-26-000048):
   line-level prior-year development, total-portfolio earned yield,
   post-quarter buybacks and remaining authorization. The fetch truncated at
   Note 6. Not load-bearing for the ledger: condition 3 survives on the
   aggregate (net PYD ~0, derived from the release), and the FY2026 10-K
   triangle is its decisive document.
2. **UNKNOWN — Q4 book value.** The ~$10.3B year-end estimate is my
   arithmetic (rate move × assumed duration and fixed-income size), not a
   filing. PENDING the Q4 release 2027-01-25. Moves the requirement by
   ~1.3pt at most; does not close the gap.
3. **UNKNOWN — loss-cost trend by line.** Standing non-disclosure;
   management's "abating ex-auto" is the only read.
4. **UNKNOWN — AI-liability latency in recent casualty vintages.** Level
   risk to book, *possible* tier, not a condition. The Q3 release now lists
   "the increasing use of artificial intelligence technologies" among its
   forward-looking risks.
5. **UNKNOWN — founder's estate liquidity needs** (carried; no filing).
6. **UNKNOWN — short-interest feed.** `stocks.db`/stockanalysis read 30,255
   shares short, implausible against a month-ago ~5.4% of float; FINRA file
   not read. Not load-bearing.
7. **UNKNOWN (option value, not a condition) — California workers' comp
   firming** ("bottoming out and incremental firming", Q3 call). Upside
   only.

## 7. Sources

**Primary:** SEC EDGAR, CIK 11544 — submissions JSON (58 filings dated
2026-10-20 or later, listed in §3); 10-Q 0000011544-26-000048 (period
2026-09-30; statements through Note 6 read: income, equity, AOCI,
buybacks, dividends, cover-page shares); Q3'26 8-K
0000011544-26-000046 ex-99.1 (expense/loss ratios, segment CRs, duration,
BVPS, buybacks, risk language) re-read. Q3'26 8-K
0000011544-26-000046 ex-99.1 and the Q3'26 call (2026-10-19, Quartr via
stockanalysis, primary-transcribed), both carried from
`research/WRB-2026-10-22.md`. FY2025 10-K Item 1A and reserve note carried.

**stockanalysis.com (vetted exception):** `/stocks/WRB/transcripts/` (95
events, newest Q3 2026, 2026-10-19); `/stocks/WRB/statistics/` schema and
summary text (ROE 19.26%, short-interest line). Exact hovers were not
readable in the headless envelope (the probe CLI prints schema only); the
same fields were taken from `stocks.db` below.

**Broker/market microstructure** (admissible: no integrated official source
covers these fields): Robinhood quote $77.91 last / $77.90 official close
(2026-11-23); eight-quarter EPS estimate vs actual plus Q4 estimate $1.21
(2027-01-25 pm, unverified); daily split-adjusted bars 2026-08-20 →
2026-11-20; option chain expiries and Apr-16-2027 77.5 call/put quotes
(marks, IV, OI, volume, bid/ask).

**Reference data:** Damodaran implied ERP 4.41% (headline, as-of
2026-11-01; alternates 3.79% cash yield, 5.81% 10-year average; his
treasury rate 4.94%); October headline 4.20%. EVA base rate ~29% and US
cost-of-capital band from the anchors reference.

**Point-in-time repo DBs:** `stocks.db` `v_latest` (priceDate 2026-11-20):
price $78.31, market cap $30.45B, beta 0.221, insiders 1.21%, institutions
54.1%, float 248.3M, shares 388.89M, SBC $62.4M (0.42% of revenue), TTM
revenue $14.867B, net income $1.863B, OCF $3.194B, capex $0.116B, equity
$9.62B, ROE 19.26%, P/B 3.17, target $69.82 (18, Hold). `fred.db`: DGS10
4.92% (2026-11-20), 5.29% (9/30), 5.15% (10-19); T10YIE 2.13% (2026-11-23).
`earnings.db` (calendar today 2026-11-23): next 2027-01-18 edgar-estimate.
`composite.db` snapshot 146: coverage 0.0, no flags, `in_portfolio = 1`;
its 31 `in_portfolio = 1` symbols are the holdings list for the factor
overlap, each graded by its newest thesis's factor line.
`sec_fundamentals.db` `v_screener`: Q3 revenue $3.739B, net income $446.0M,
equity $9.610B, diluted EPS $1.14. `options.db`: no WRB rows.
`portfolio.db`: not readable in this session (no headless grant).

**Low-confidence:** web search (Quartr summary, InsuranceNewsNet reprint,
Yahoo 11-09 close $75.92) — no November company news found.

## Kill-thesis record

Ledger line restated: **FLAWED** — conditions=4 (2 probable, 2 plausible),
refuted=1, unknown=0, pending=0, not_obtained=0; ownership PASS at $77.90.

The attack ran against the bull case: that owning WRB at $77.90 beats SPY.
Self-consistency first, at zero cost. The bull now needs a ~22% perpetual
ROE on reported book (~20.3% ex-mark), 5% growth and a sub-market risk
profile all at once. A business with a perpetual excess return of 12–14
points over a 8.45% cost of equity, unchallenged by competition, in an
industry whose own management says the soft market is arriving — the
low-risk and high-excess-return claims attack each other.

1. **Mid-cycle ROE ≥ ~22% (reported) / ~20.3% (ex-mark) — REFUTED (at the
   0.8 beta floor).** The best delivered quarter (Q3 operating 18.8%) came
   with a benign cat load (9M'26 $224M vs $289M) and a property benefit the
   CFO called not run-rate. The best *modelled* case (F, full new-money
   repricing, ~17.7%) is now a ceiling, since the 10-year fell 37bp from
   9/30 and the 80–100bp new-money spread was quoted against 5.15%. Every
   admissible pair falls 1.6–7pts short (§4). Repairable only by price
   (~$65 for B) or by rejecting the floor (raw-beta requirement ~14.0%,
   cleared by all scenarios except E).
2. **Underwriting discipline — SURVIVED (at *probable*).** Attacked on the
   expense ratio (28.6% vs 28.5%, flat on +1.8% NPE, so no scale benefit) and
   Insurance CR 91.7% against a reinsurance segment (83.4%) being shrunk.
   Discipline means writing less when price is inadequate. The −11.6%
   reinsurance NPW is that behaviour, and nothing in the 10-Q statements
   contradicts it. The margin-*level* attack belongs to condition 1.
3. **Total reserve adequacy — SURVIVED (at *plausible*).** Net PYD is ~0 in
   Q3, derived from the release (CR 90.8 − AY ex-cat 88.1 − cat 2.7). The
   attack that nearly landed is carried: auto adverse is covered by
   releases from the segment being shrunk 10–20% a year. This run could not
   read the 10-Q's line split (§6, NOT OBTAINED, logged to `gaps.log`).
   The condition is adjudicated on the aggregate, and its decisive document
   is the FY2026 10-K triangle. No evidence of the net turning adverse.
4. **Capital-return and governance unchanged — SURVIVED (at *probable*).**
   Attacked on the S-3ASR filed 2026-11-02, since a shelf can precede
   issuance. No prospectus supplement followed, WKSI shelves auto-expire
   every three years, and management holds "10 figure" excess capital.
   Issuance would contradict its own capital narrative, so I read it as a
   renewal. No 8-K, Form 4/144 or 13D/A since the call. Q3 buybacks were
   light ($21.1M), and no special dividend appears through 9/30. That is
   price discipline, not a regime change.

Standing checks. **Base rate:** ~29% of firms earn above their cost of
capital (Damodaran EVA). The bull needs a ~12-14 point *perpetual* excess,
a small subset of that 29%. **Short case (strongest form):** a cyclical
priced at 3.15x a book that fell in Q3, rising to a new 52-week high with
no new disclosure. Premium is stalled (NPE +1.8%) and earnings growth comes
from the bond portfolio. The same rate decline that may lift book in Q4 is
already eroding that reinvestment spread. Property and reinsurance soften
first at 1/1. Long-tail auto develops adverse every quarter it is examined.
The sell-side mean ($69.82) sits 10% below the price. **Management
incentives:** family alignment is real. Light Q3 buybacks are consistent
with management not seeing the stock as cheap. ROE-linked pay points
toward reserve releases (DEF 14A not read, non-load-bearing). **Disconfirming
search:** run against the bull, it found the narrowed new-money spread, the
ERP vintage error that had flattered the prior hurdle, and the
price-without-news drift. For the bull it found the likely Q4 mark reversal
(~$250–300M, my estimate) and the clean docket. **Moat as mechanism:** unit
authority plus willingness to shrink, shown again in reinsurance. It does
not defend against an industry soft market, and §4 prices that.

Statistical checks: **not applicable**. No condition rests on a backtest,
screen or repo signal (composite coverage 0.0).

Options timing check: **NOT APPLICABLE**. The thesis makes no dated price
claim. Coverage disclosed: path 2 stopgap only, Apr-16-2027 ATM 77.5 at DTE
144 bracketing the Q4 print, liquidity gate FAILED (spreads 60.9% / 55.4%
of mark, zero volume, OI 8/1) → UNRELIABLE. Path 1 unavailable.

> [!WARNING]
> **Closest attack:** against the *pass*, the beta floor. At the screened
> 0.22 beta the hurdle is 5.89%, the required ROE ~14.0%, and Q3's 18.8%
> clears it by nearly five points. The pass is only as strong as the 0.8
> convention, which this run keeps for the reasons stated in §4.

> [!NOTE]
> **Flip evidence:** toward SOUND (and a buy), any one of: an argued rejection
> of the 0.8 floor; a price at or below ~$65; or CR ≤ ~91% with rate ≥ 4%
> holding through the 1/1 reset for two quarters. Toward more-flawed, a Q4
> year-end reserve review with $100M-scale auto/other-liability
> strengthening, or net PYD turning adverse once reinsurance releases thin.

> [!IMPORTANT]
> **p(beat SPY, 63 td): 0.40** — written before re-reading §1's number.
