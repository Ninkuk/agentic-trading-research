# SAP — SAP SE — 2026-11-22 (reopen of 2026-10-22, trigger: sap-fy26-fcf-at-or-above-10b-and-2027-accel-quantified-or-price-at-or-below-182)

> [!IMPORTANT]
> **In one sentence:** SAP remains a sticky business-software franchise with widening margins, but even after a 17% fall the price still discounts more growth than analysts expect and returns below its hurdle, so pass until nearer $173.

Price $198.93 (official close 2026-11-20, Robinhood; last extended-hours trade
$199.98) · market cap $231.91B (1,165.78M shares × $198.93) · next earnings
2027-01-28 (company-verified date; session unconfirmed — the Q4 2025 print
was BMO)

**Reopen.** Prior file `research/SAP-2026-10-22.md` — **PASS at $241.03**,
kill-thesis FLAWED (conditions=5, refuted=1: the price cleared the hurdle on
no path). Reopen question: has the price reached ~$182, where the consensus
path cleared, or has anything disclosed since the Q3 print changed the
business? The dated leg (the 2027-01-28 FY26 statement) is not yet due.
Unattended scheduled run, dispatched ahead of the dated trigger; this file
supersedes the 2026-10-22 thesis.

## 0. The reopen question, answered first

**The price leg came closer without firing, and the clearing price fell
toward it.** SAP fell $241.03 → $198.93 (−17.5%), $35 of it in the four
sessions 11-17 → 11-20 (−14.9% from the $233.83 close on 11-16). The cause
was sector-wide: CRM −15.7%, ORCL −13.0%, TEAM −12.7% and NOW −11.7% in the
same week (`data/stocks.db`, 1-week change to 2026-11-19). The whole market
fell too: SPY went 763.96 → 689.81 (−9.7%) over the same 10-22 → 11-20
window, as recorded by the same-day `research/ORI-2026-11-22.md` run. SAP
underperformed it by ~8 points. Nothing in SAP's
own disclosures moved. The one company-specific event is Thomas Saueressig's
exit from the Executive Board, announced 11-17.

The consensus clearing price did not hold still: it fell from ~$182 to
**~$173**. Three inputs moved: the 10-year breakeven (the terminal rate) fell
20bp, the USD translation of the same EUR TTM FCF fell 2.5%, and this run
uses stockanalysis's higher share count (+1.6%). A 5bp lower risk-free rate
offsets part of that. Net, the base-path spread narrowed from −194bp to
**−124bp**, and the most generous construction from −101bp to **−32bp**. The
PASS stands, by a much thinner margin.

| prior falsifier | actual | status |
|---|---|---|
| Shift — price ≤ ~$182 (flip toward buy) | $198.93 close 11-20; clearing price itself now ~$173 | GRAZED |
| Shift — FY26 FCF ≥ €10B, receivables normalized, 2027 accel quantified | not yet disclosed; due 2027-01-28 | NOT TRIGGERED |
| Shift — DGS10 back to ~4.6% at unchanged price | DGS10 5.04% (2026-11-19) | NOT TRIGGERED |
| Break — CCB cc < 20% two quarters ex-M&A | no print since Q3 (26% cc) | NOT TRIGGERED |
| Break — 2027 acceleration guide withdrawn | not withdrawn; CFO at Morgan Stanley TMT 11-19 previewed a new AI revenue KPI for January, gave no 2027 figure | NOT TRIGGERED |
| Shift — FY26 FCF below ~€9.5B | not yet disclosed | NOT TRIGGERED |
| Shift — cloud gross margin −2pp y/y cc, sustained | no print since Q3 (−0.7pp) | NOT TRIGGERED |
| Shift — support decline outrunning cloud capture | no print since Q3 | NOT TRIGGERED |

## 1. Verdict and thesis

**PASS at $198.93.** kill-thesis: **FLAWED** — conditions=5 (2 probable,
3 plausible), refuted=1, unknown=1, pending=1, not_obtained=0.

> [!IMPORTANT]
> **p(beat SPY, 63 td): 0.47** · kill-thesis: 0.45
>
> **Disputed expectation:** at $231.91B the market pays ~22.8× forward
> earnings and a 3.86% SBC-adjusted FCF yield for SAP to compound FCF ~10%/yr
> to 2031 and then 2.15% forever. That path returns 7.70–8.13%/yr against an
> 8.94% cost of equity. What revises it: the 2027-01-28 FY26 statement (FCF
> ≥ €10B, a quantified 2027 acceleration, the first AI revenue KPI), or a
> price near $173, where the consensus path clears.

The business case from the July–October theses is untouched: nothing SAP
disclosed after the Q3 call bears on it. What changed is the price. The
market sold enterprise software as a block on fear that AI agents will
shrink per-user software spend, and SAP fell with it. At $198.93 SAP is
closer to fair than at any run since July. It is still not cheap enough: the
consensus path misses the hurdle by 81bp, and SAP still trades at roughly
twice the forward multiple of the peers it fell with.

> [!WARNING]
> **Closest attack:** the generous-construction attack: Damodaran's US
> headline ERP (4.41%, Nov 1 2026) instead of the operations-weighted 4.87%,
> the lower `sharesout` count (1,147.45M) and stockanalysis's `adjustedFCF`
> base ($8.998B) on the consensus path return 8.24% against 8.57%, a
> **−32bp** miss. That gap is about one more bad week; the closest it has
> been in four runs.

Load-bearing conditions of the bull case (owning SAP at $198.93 beats SPY):

1. **The moat holds.** *probable* — CCB €24.1B +26% cc in Q3; Cloud ERP
   Suite +28% cc (Q3 call, 2026-10-21). Nothing since contradicts it.
2. **The margin envelope keeps expanding.** *probable* — Q3 operating profit
   +18% on revenue +12% cc; TTM operating margin 29.1% (`data/stocks.db`)
   vs FY25 26.1%.
3. **~10%/yr FCF growth for five years.** *plausible* — FY26 ~€10B FCF
   reaffirmed at Q3, with ~€2B needed in Q4 against high receivables. The
   FY26 statement and the 2027 outlook settle this on 2027-01-28.
4. **Terminal growth of 2.15% survives AI build-vs-buy.** *plausible* — the
   ledger-survives argument. No dated disclosure settles it. The new AI
   revenue KPI due in January is the first datum that bears on it.
5. **The price clears the hurdle on the stated path.** *plausible* —
   attacked in §4: it fails on every row (consensus −81bp, most generous
   −32bp).

> [!WARNING]
> **Dominant shared risk factor:** generative-AI substitution of enterprise
> application seat-and-workflow spend, compounded by long-duration repricing
> at a 5%+ 10-year — shared by 5 of 30 other held names (INTU, MORN, G, RDDT,
> BKNG) · 0 unlabelled. (Holdings read from `data/composite.db`
> `ticker_scores.in_portfolio`, snapshot 2026-11-20 — `portfolio.db` is not
> granted to this slot. SAP is itself held at a 5.6% weight.)

## 2. Business

Unchanged from `research/SAP-2026-10-22.md` §2 (itself carried from the
2026-10-10 and 2026-09-07 files). Deltas since the Q3 call, from the CFO's
Morgan Stanley TMT fireside (Barcelona, 2026-11-19; partial read, §6.3):

**Created — delta:** "400 agents on the roadmap to go in general
availability by the end of this year" (300 at the Q3 call).

**Captured — delta:** AI is sold as credits on a commit-to-consume basis:
customers "like skin in the game, so there has to be a value creation and
not just pay tokens, but pay for outcomes," and SAP will "reprice that at a
certain point in time." A new AI-related revenue KPI arrives with the
January print. The CFO called the Cloud ERP Suite share metric ("around
about 90%") "not so meaningful anymore." He described 2027 planning for the
AI revenue mix as "closer to a third, a third, a third." The three
components were not named in the portion read.

**Protected — delta:** none disclosed. The CFO called AI-driven productivity
"a deflationary environment almost." That is the bear's mechanism, stated by
the seller, and the reason the per-user pricing question (§3) matters.

**Control:** one share class, one vote per share, no controlling holder;
institutions 41.7% and insiders 5.4% of the register (`data/stocks.db`).
German SE with co-determination. Nothing structural forecloses an approach;
size does. The Executive Board loses Saueressig at end-March 2027 (§3).

**Operating leverage (Phase 0): positive — since 2024 only.** FY2019–FY2025
audited table in `research/SAP-2026-10-10.md` §2 (2019→2024 revenue +24.0%,
operating income +4.3%; FY25 margin 26.1%). TTM through Q3 2026: revenue
$44.73B, operating income $13.03B, margin 29.1% (`data/stocks.db`,
EUR-reported, USD-converted; operating income growth +14.5% on revenue
+7.9% in USD terms). Positive and continuing.

## 3. Threads pulled

- **The fall was sector-wide, and SAP still trades at a premium.** One-week
  changes to 2026-11-19 (`data/stocks.db`): CRM −15.7%, SAP −13.2%, ORCL
  −13.0%, TEAM −12.7%, NOW −11.7%, PLTR −10.4%, SNOW −10.1%, DDOG −9.8%,
  WDAY −9.1%, INTU −8.9%, ADBE −7.1%, ADSK −6.2%, MSFT −4.7%. Forward P/Es:
  SAP 23.3×, MSFT 24.0×, NOW 19.6×, ADSK 18.7×, WDAY 14.4×, INTU 13.2×,
  ORCL 13.0×, CRM 12.5×, ADBE 8.3×. SAP fell with the group, but only part
  of the way toward its multiples. Its year-to-date fall (−16.3%) is a third
  of NOW's (−42.0%) or ADBE's (−36.7%).

- **The stated driver is the bear case for condition 4.** Coverage of
  11-17 (low-confidence web): CRM −9.4% with no company news, NOW −6.5%,
  INTU −6.7%, attributed to fear that AI agents reduce demand for per-user
  licenses, a day before Anthropic's IPO priced (trading 11-19), plus a run
  of tech outages. SAP's own S/4HANA cloud contracts are priced largely on
  user equivalents. The agent credits the CFO described are the hedge, and
  they are not yet a disclosed revenue line. The market is pricing this
  question; nothing has answered it.

- **Saueressig's departure is a governance signal, not yet an operating
  one.** Announced 2026-11-17 (SAP release via Constellation Research,
  SAPinsider, newsquawk): the Chief Customer Officer and former head of
  Product & Engineering (board since 2019, term to 2028) leaves "to pursue a
  new opportunity outside the company." He hands his duties to Emmanuel
  Raptopoulos on an interim basis from January and leaves the board
  end-March 2027; succession is open. SAP fell 4.8% that day, alongside CRM
  −9.4%. He owned the customer side of the migration, which is the
  receivables and migration-credit question in condition 3. No evidence ties
  the exit to an operating problem. It follows a March 2026 board
  reorganization (Bloomberg, 2026-03-02).

- **The CFO's 11-19 fireside did not address the selloff.** In the portion
  read: 400 agents, commit-to-consume credits, the new AI KPI, the
  "deflationary" remark. There was nothing on the FY26 FCF guide,
  receivables, the buyback or Saueressig. The summary of the unread tail
  says none of those came up either; that summary is unverified (§6.3).
  Silence on the FCF guide eight weeks before the print is neither a warning
  nor a reassurance.

- **The buyback is running.** Low-confidence secondary of SAP's weekly
  disclosures: ~465K shares for ~€95.4M on XETRA, 11-02 to 11-06; ~9.6M
  shares acquired under the €10B two-year program through 11-06. €5B/yr is
  ~2.3% of the €213B market cap (ADR $231.91B ÷ the 11-19 ADR/Xetra ratio
  1.087). It is funded from FCF; the reverse DCF already counts that FCF, so
  the buyback adds nothing on top.

- **What the machine thinks.** `data/composite.db` (snapshot 2026-11-20):
  SAP score +1 from one voting signal, `stocks_rsi` 28.5 (oversold).
  `sa_fcf_yield` 4.25% and `sa_fscore` 6 are informational. Not flagged.
  `in_portfolio` = 1, weight 5.6%.

- **Rates moved toward SAP, the breakeven against it.** DGS10 5.15% → 5.04%
  (2026-11-19); T10YIE 2.35% → 2.15% (2026-11-20) (`data/fred.db`). The
  hurdle fell 11bp. The terminal rate fell 20bp, which lowers every implied
  return by roughly 15–20bp.

- **Earnings pattern unchanged.** Robinhood: seven beats of 4–9% in eight
  quarters, one currency-driven miss (Q2 2026). Q4 2026 estimate $2.25. The
  2027-01-28 print falls inside this run's 63-trading-day window, which
  ends ~2027-02-24.

- **Options read (mandatory):** path 2 only (Robinhood stopgap; SAP is not
  in the 24-symbol CBOE catalog). Mar 19 2027, 117 DTE, brackets the
  2027-01-28 Q4/FY print. The liquidity gate FAILED on the put spread. Table
  in §4.

- **Dead ends:** `data/sec_fundamentals.db` and `data/earnings.db` have no
  SAP row (20-F filer; US-universe monitor). `data/stocks.db` still carries
  `lastReportDate` 2026-09-30: no new fundamentals since the prior run, only
  FX translation (`fcf` $10.324B → $10.070B). The statistics probe CLI in
  this envelope prints the schema, not row values. Live statistics therefore
  come from the `stocks.db` snapshot (price date 2026-11-19), repriced at
  the Robinhood 11-20 close (a judgment call, stated). A search for an
  SAP-specific negative catalyst in 11-17 → 11-20 found only Saueressig. No
  6-K was fetched. None of this ruled anything out.

## 4. Valuation

**Inputs.** Levered TTM FCF paired with **market cap**; net debt 0 by the
pairing rule. Market cap **$231,910,000,000** = 1,165.78M shares × $198.93.
The share count is implied by stockanalysis `marketCap` $236,920,737,643 at
$203.23 (`data/stocks.db`). That is higher than the 1,147.45M `sharesout`
the prior run used: conservative against a BUY, worth ~+10bp to every
implied return if reversed (shown in the most-generous row). Base FCF
**$8,960,057,402** = `fcf` $10,069,528,217 less SBC $1,109,470,815 (2.48%
of revenue, unchanged). Base earnings $9,130,138,543 (TTM net income). Net
cash $0.46B, 0.2% of cap, ignored. No NCI haircut (NCI ~1.8% of net income,
carried). All USD figures are stockanalysis conversions of EUR financials.

**Hurdle.** `rf 5.04% + beta 0.8 × ERP 4.87% = 8.94%`. Risk-free: DGS10
2026-11-19 (`data/fred.db`). Beta clamped up from 0.702 to the 0.8 floor,
which works against a BUY (stated). ERP: operations-weighted country ERP
(EMEA 46% / Americas 39% / APJ 15%) from Damodaran's country table (Last
updated Jan 5 2026, single vintage, carried). Generous alternative: US
headline implied ERP **4.41% (Nov 1, 2026**, as fetched by the same-week
`INTU-2026-11-21` and `G-2026-11-21` runs, not re-fetched here) → hurdle
**8.57%**.

**Terminal growth ceiling.** T10YIE = **2.15% at 2026-11-20**, the terminal
rate except where stressed lower.

| scenario | base FCF | growth ×5y | terminal | implied return | vs hurdle |
|---|---|---|---|---|---|
| Consensus-tracking (3y EPS +17.7%, 3y rev +11.4%) | $8.960B | 15/14/12/10/8% | 2.15% | 8.13% | −81bp |
| Guided year-1 (~€10B FY26 FCF) | $8.960B | 15/11/10/9/8% | 2.15% | 7.84% | −109bp |
| **Base** | $8.960B | 12/11/10/9/8% | 2.15% | **7.70%** | **−124bp** |
| Conservative | $8.960B | 8/8/6/6/5% | 2.00% | 6.84% | −210bp |
| AI-stress | $8.960B | 6/4/2/0/0% | 0.00% | 4.33% | −461bp |
| Most generous (adjustedFCF base, 1,147.45M shares → cap $228.26B, consensus path, headline ERP) | $8.998B | 15/14/12/10/8% | 2.15% | 8.24% | −32bp vs 8.57% |
| *Clearing — consensus path at $172.85 (−13.1%)* | $8.960B | 15/14/12/10/8% | 2.15% | 9.00% | +6bp |
| *Clearing — base path at $159.55 (−19.8%)* | $8.960B | 12/11/10/9/8% | 2.15% | 9.02% | +9bp |

**No row clears; the most generous construction misses by 32bp.** On the
lower 1,147.45M share count the clearing prices are ~$175.6 (consensus) and
~$162.1 (base). Against the prior run, the price fell 17.5%, but the
consensus clearing price also fell ~5% ($182 → $173), so the gap closed by
~12 points, not 17.5.

**Integrity checks.**

- *Reinvestment / terminal-ROE warning fired* (`terminal_reinvestment_rate:
  0.0186`, `implied_terminal_roe: 1.1541`; FCF ≈ earnings). Answered as
  before: terminal growth equals the 10-year breakeven, so the perpetuity
  claims zero real growth. The explicit-period ~10% is growth without
  visible reinvestment. It is defensible only because SAP expenses its
  reinvestment through R&D (18.0% of revenue, `data/stocks.db`).
- *Market-share sentence.* The base path takes $44.7B TTM revenue to roughly
  $65–68B by 2031, under ~10% of enterprise application software spend (TAM
  low-confidence). No "bigger than the market" failure.
- *Terminal risk from Item 1A.* The Innovation factor: the 20-F concedes
  customers "may leverage AI to produce their own solutions." The CFO's own
  "deflationary environment almost" is the same risk stated on stage. 2.15%
  survives only if the ledger persists while the seat layer commoditizes.
  The AI-stress row (4.33%) bounds the other case.
- *Excess-return base rate.* ~29% of firms out-earn their cost of capital.
  SAP does today (ROIC 18.5%, stockanalysis WACC 7.9%). The terminal fades
  it.
- *SBC.* Deducted ($1.109B, 2.48% of revenue; unchanged since the TTM did
  not roll).
- *Cash tax rate* 27.9% TTM — no NOL flattery.
- *Serial-acquirer check.* SmartRecruiters is rolling off; Reltio, Dremio
  and TechWolf are small. The paths are organic.
- *Cash-heavy / pension / litigation haircuts.* Net cash 0.2% of cap: none
  applied.
- *Distribution clamp.* 7.70% sits just under Damodaran's US median cost of
  capital (7.79%), inside the 5.26–9.88% band (Data Update 5, 2026). The
  hurdle sits in the band's upper half because the risk-free rate does.

**Options-implied move** (path 2 — Robinhood stopgap; path 1 unavailable).
Mar 19 2027 monthly, **117 DTE** from the Phoenix date 2026-11-22. It
brackets the 2027-01-28 Q4/FY print. ATM strike $200 against $198.93 spot
(0.5% OTM call). The next ex-dividend date is ~May 2027, outside the
window. Marks are Friday-close quotes (updated 2026-11-20 20:59Z): call
18.35 / put 17.15. IV is the mean of 39.23% and 40.05%. Dated claim tested:
this document's consensus clearing price, $172.85, a 13.1% decline by
expiry (passed as 0.130). Closes: 95 daily bars 2026-07-10 → 2026-11-20.

| metric | value |
|---|---|
| spot | 198.93 |
| dte (calendar days) | 117 |
| ATM IV | 39.64% |
| expected absolute move (MEAN, not a ceiling) | 17.85% |
| 1-sigma move | 22.44% |
| RV60 | 31.23% |
| IV > RV60? | YES |
| RV20 | 37.15% |
| IV > RV20? | YES |
| thesis requires | 13.00% |
| that is | 0.54 sigma |
| P(\|move\| ≥ required) | 58.602187% |
| refutes timing claim (> 2 sigma)? | NO |

The CLI treats the move as positive (`log1p(0.130)`). The downside log move
to $172.85 is `ln(0.869)` = −14.0%, ≈0.63σ. **Liquidity gate: FAILED →
UNRELIABLE.** The call spread $17.50/$19.20 ($1.70, 9.3% of mark) passes the
10% gate. The put spread $16.00/$18.30 ($2.30, 13.4% of mark) fails it. OI
249/210 clears the floor (25% of the median OI 206.5 across six quoted
contracts at $190/$200/$210, so ~52); volume was 3/1.

Timing check: applied, did not refute, and the gate failure would bar it
from moving the verdict anyway. Both windows read IV > RV ("elevated"), but
the expiry spans the January print and RV20 now holds the selloff week
itself. The stopgap caveat applies. ATM IV 39.6% < 50%, so implied returns
keep their decimals; ±1pp is the honest width.

## 5. Falsifiers

**For the pass (flip toward buy):**

- **Shift —** price at or below **~$173** with the thesis otherwise intact:
  the consensus path clears the 8.94% hurdle there. The base path needs
  ~$160.
- **Shift —** the 2027-01-28 FY26 statement prints FCF at or above €10B with
  receivables normalized, and the 2027 outlook quantifies total-revenue
  acceleration. That makes the consensus path the base.
- **Shift —** the new AI revenue KPI (January) shows agent/credit revenue
  growing fast enough to offset user-based pricing pressure. That turns
  condition 4 from argument to evidence.
- **Shift —** DGS10 at ~4.7% at an unchanged price: the hurdle falls to
  ~8.6% and the consensus path misses by ~47bp. The rate alone still does
  not clear.

**For an owner (sell):**

- **Break —** CCB cc growth below 20% for two consecutive quarters, ex-M&A.
- **Break —** the 2027 total-revenue acceleration guide is withdrawn on
  2027-01-28.
- **Shift —** FY26 FCF lands below ~€9.5B: Q4 collections failed and
  migration credits are a structural drag, not a timing one.
- **Shift —** the Saueressig succession leaves the customer/migration
  portfolio unfilled past the March exit, or more Executive Board exits
  follow.
- **Shift —** cloud gross margin down ≥2pp y/y cc, sustained.
- **Shift —** support revenue decline accelerating without matching cloud
  capture.

> [!NOTE]
> **Reopen trigger:** 2027-01-28:
> `sap-fy26-fcf-at-or-above-10b-and-2027-accel-quantified-or-price-at-or-below-173`

## 6. UNKNOWNs

1. **PENDING 2027-01-28 — FY26 FCF, the 2027 outlook and the first AI
   revenue KPI.** Whether ~€10B lands, whether the 2027 acceleration is
   quantified or trimmed, and what the new KPI shows. Together they set the
   five-year path. Its absence does not kill the PASS: consensus fails by
   81bp.
2. **UNKNOWN — AI-agent displacement of user-priced application revenue.**
   No filing can carry a decade-out customer-behaviour claim. It is bounded
   by the AI-stress row and is load-bearing for condition 4. The January
   KPI is evidence toward it, not resolution.
3. **NOT OBTAINED — full transcript of the CFO's Morgan Stanley TMT
   fireside, 2026-11-19** (stockanalysis
   `/quote/etr/SAP/transcripts/801082-…/`). Read ~three-quarters verbatim;
   the tail came only as an unverified summary, and the probe CLI here
   prints the schema, not the text. Not load-bearing: the read portion
   carries the AI-pricing remarks; FCF and buyback were not discussed, per
   the summary.
4. **NOT OBTAINED — Q3 2026 quarterly statement** (6-K exhibit on EDGAR;
   sap.com PDF returned 403 last run): software support revenue, nine-month
   OCF, the 2026-09-30 share count, which would settle the 1,147M vs 1,166M
   question (~10bp). Not load-bearing.
5. **UNKNOWN — the reason for Saueressig's exit.** The release says "a new
   opportunity outside the company." No filing will say more unless the
   destination is announced.
6. **UNKNOWN — deadline-pulled vs value-pulled migration share.** Still
   undisclosed.

## 7. Sources

**Primary:** SAP Q3 2026 earnings call, 2026-10-21, and SAP's Q3 news
release (carried from `research/SAP-2026-10-22.md`). Morgan Stanley European
TMT Conference fireside with Dominik Asam (CFO), 2026-11-19, transcript via
stockanalysis `/quote/etr/SAP/transcripts/801082-morgan-stanley-european-technology-media-telecom-conference/`
(primary-transcribed; ~three-quarters read verbatim through a fetch agent).
SAP release "Thomas Saueressig to leave SAP Executive Board," 2026-11-17, as
quoted by Constellation Research, SAPinsider and newsquawk (release not
fetched directly). FY2025 20-F Item 1A and FY2019–FY2025 audited figures
carried from `research/SAP-2026-10-10.md`.

**stockanalysis.com (vetted exception):** transcript list
`/quote/etr/SAP/transcripts/` (latest five events: 11-19 MS TMT, 10-21 Q3,
09-08 Goldman, 07-23 Q2, 06-10 BofA). Statistics via the `data/stocks.db`
snapshot (below), because the probe CLI prints the schema only.

**Broker/market microstructure:** Robinhood MCP — admissible because no
integrated official source covers these fields for SAP. Official close
$198.93 (2026-11-20) and extended-hours $199.98; daily bars 2026-07-10 →
2026-11-20; trailing-8-quarter EPS estimate vs actual (Q4 2026 estimate
$2.25, date 2027-01-28 verified); Mar 19 2027 chain, $190/$200/$210 quotes,
IV, OI, volume.

**Reference data:** Damodaran implied ERP 4.41% (Nov 1, 2026, carried from
same-week runs); country ERP table, Last updated Jan 5, 2026
(operations-weighted 4.87%, carried); US median cost of capital 7.79%, 80%
band 5.26–9.88% (Data Update 5, 2026); EVA excess-return base rate ~29%.

**Point-in-time repo DBs:** (read-only) `data/stocks.db` snapshot 102
(price date 2026-11-19): marketCap $236.92B, fcf $10.070B, SBC $1.109B
(2.48%), adjustedFCF $8.998B, net income $9.130B, revenue $44.73B, operating
income $13.03B, beta 0.702, forward P/E 23.3, RSI 28.5, insiders 5.38%,
institutions 41.72%, `lastReportDate` 2026-09-30; peer 1-week changes and
forward P/Es. `data/fred.db` — DGS10 5.04% (2026-11-19), T10YIE 2.15%
(2026-11-20). `data/composite.db` snapshot 145 — SAP score +1, signals,
`in_portfolio` holdings list (31 names). `research/*.md` factor lines for
the 30 other holdings. `data/sec_fundamentals.db` and `data/earnings.db`:
no SAP row.

**Low-confidence:** web coverage of the 11-17 → 11-20 software selloff
(Benzinga, mlq.ai, invezz, TradingKey, GuruFocus, globalbankingandfinance:
CRM −9.4%, NOW −6.5%, INTU −6.7% on 11-17; the Anthropic IPO and outage
framing); buyback figures via secondary summary of SAP's weekly
disclosures; Bloomberg headline on the March 2026 board reorganization;
analyst average target $284.5 (16 analysts, stockanalysis aggregate in
`stocks.db`); TAM statistics.

## Kill-thesis record

**Kill-thesis verdict: FLAWED** — 5 load-bearing conditions, 1 refuted, 1
unknown, 1 pending, 0 not obtained.

The object attacked is the bull case: owning SAP at $198.93 beats SPY over
63 trading days.

**Per-condition adjudication:**

1. *The moat holds.* **SURVIVED** (probable). Attacked via the selloff's
   own thesis: SAP's cloud ERP is priced on user equivalents, and agents
   that do users' work shrink the billable base. That attack lands on the
   terminal (condition 4), not on today's switching cost. CCB +26% cc and
   Cloud ERP Suite +28% cc stand, and nothing since the Q3 call contradicts
   them.
2. *Margin envelope keeps expanding.* **SURVIVED** (probable). Attacked via
   the CFO's "deflationary environment almost," the cloud GM −0.7pp, and
   the cost of 400 agents. Q3 operating profit +18% against revenue +12% cc
   answers it for now.
3. *~10%/yr FCF growth for five years.* **PENDING 2027-01-28.** Attacked
   with today's evidence. The guide was held, not raised, at Q3; receivables
   are high. The executive who owns the customer/migration side announced
   his exit seven weeks after the Q3 call. The CFO said nothing on FCF at
   the 11-19 fireside. None of it refutes ~10%: the €10B guide still implies
   ~15% in year one. The FY26 statement decides.
4. *Terminal 2.15% survives AI build-vs-buy.* **UNKNOWN.** The market spent
   a week pricing the opposite, and SAP's CFO described the environment as
   deflationary. Neither is evidence about 2035. The January AI KPI is the
   first observable, and it will not settle a perpetuity.
5. *The price clears the hurdle on the stated path.* **REFUTED.** At 8.94%
   every row fails: consensus −81bp, guided −109bp, base −124bp, most
   generous −32bp. Internal-consistency attack: ~10% growth with FCF ≈
   earnings is growth without visible reinvestment, legitimate only through
   expensed R&D. Repairable by price (~$173 consensus, ~$160 base) or by a
   materially raised FCF path on 2027-01-28.

**Standing checks.** *Base rate:* ~29% of firms out-earn their cost of
capital; a single large cap beats a cap-weighted index over a quarter
roughly 45–47% of the time. A −15% four-session drawdown at RSI 28.5 leans
weakly toward short-horizon mean reversion. Sector de-ratings driven by a
narrative tend to run in legs: NOW is −37% in a month and still falling.
Neither was credited. *Short case (strongest form):* the software de-rating
is not finished, and SAP is its most expensive survivor. At ~22.8× forward
it trades near MSFT and at twice ORCL, CRM, INTU and WDAY. Its year-to-date
fall is a third of NOW's or ADBE's, so convergence alone is another 20–40%
of multiple. User-based pricing is the exact mechanism the market is
selling. The Chief Customer Officer leaves mid-term into the migration
peak. The FCF guide was held while receivables rose. And the cash yield
(3.9%) is still ~115bp under a 5.04% Treasury. *Management incentives:*
comp leans on cloud revenue, CCB and non-IFRS operating profit (carried).
The new AI KPI is a metric management chose to introduce in a quarter when
the old ones stopped impressing; read its definition before its growth
rate. *Disconfirming search:* ran. Searched for an SAP-specific negative
catalyst in 11-17 → 11-20 (found only Saueressig) and read the CFO's
fireside for guide changes (none in the portion read). Against the pass:
found the 17.5% price fall, the buyback running, the oversold RSI and an
analyst target of $284.5. *Moat as mechanism:* passes for the ledger
(re-implementation cost). Unproven for the agent layer, and now attacked
for the pricing unit that rides on it.

**Statistical checks.** No backtest or signal claim. The composite +1 is one
technical signal (RSI) with no efficacy credited. The eight-quarter beat
pattern is n=8 with overlapping estimate-setting. Effective n for the
selloff observation is 1 (one sector-wide shock).

**Options timing check.** Ran, path 2 only (path 1 structurally
unavailable). Dated claim: −13.1% to the $172.85 consensus clearing price
by the Mar 19 2027 expiry. `refutes timing claim (> 2 sigma)? NO` — 0.54σ
on the CLI's positive-move convention (≈0.63σ as a downside log move),
P = 58.60%. **Liquidity gate FAILED (put spread 13.4% of mark) →
UNRELIABLE**; it could not have moved the verdict. The non-refutation is not
evidence for the thesis.

> [!WARNING]
> **Closest attack:** the generous-construction attack: headline ERP 4.41%,
> the lower share count and the adjustedFCF base on the consensus path leave
> −32bp, the narrowest miss in four runs.

> [!NOTE]
> **Flip evidence — to SOUND (bull case holds):** a price near $173 or
> below, with the 2027-01-28 statement confirming ~€10B FCF and a quantified
> 2027 acceleration. That un-refutes condition 5 and leaves only the
> terminal unknown.
> **Flip evidence — deeper FLAWED (thesis dead, not repairable):** the
> 2027-01-28 outlook withdraws or trims the 2027 acceleration, or FY26 FCF
> lands below ~€9.5B, which refutes condition 3 as well.

> [!IMPORTANT]
> **p(beat SPY, 63 td): 0.45** — written before re-reading §1. Base rate
> ~45–47%. The −15% four-session drop at RSI 28.5 and a print inside the
> window, which has historically beaten, offset an unfinished sector
> de-rating in which SAP is still the premium multiple, and the CCO exit.
