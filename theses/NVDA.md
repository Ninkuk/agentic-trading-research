# NVDA — NVIDIA Corporation — 2026-11-23

> [!IMPORTANT]
> **In one sentence:** NVIDIA sells the systems the AI build-out runs on at
> 66% operating margins, but even management's growth plan implies only about
> 10% a year at this price, short of the hurdle, with an SEC accounting probe
> unresolved — pass.

Price $165.05 (official close 2026-11-23; after-hours $163.43) · market cap
$3,985.46B · net cash $59.58B · next earnings 2027-02-24 AMC (broker,
unverified; `earnings.db` edgar-estimate 2027-02-16)

User-directed (no prior NVDA thesis). Unattended scheduled run. Composite
scores NVDA +4 (2 bullish, 0 bearish; `stocks_rsi` 15.0 on 11-20 and
`reddit_trending`, both microstructure) with `in_portfolio=0`.

## 1. Verdict and thesis

**PASS at $165.05** (official close 2026-11-23). kill-thesis: **FLAWED** —
conditions=6 (1 probable, 5 plausible), refuted=1, unknown=1, pending=4,
not_obtained=0.

> [!IMPORTANT]
> **p(beat SPY, 63 td): 0.45** · kill-thesis: 0.42
> **Disputed expectation:** at $165 the market prices roughly management's
> FY28 path (+75% revenue, FCF about doubling) followed by flat real cash flow,
> about 10%/yr. Three things revise it: the Q3 10-Q's legal note (due by
> 2026-12-04), the Dec 1–3 Huang testimony, and the 2027-02-24 FY28 outlook.

NVIDIA is the best business in semiconductors: it sells the whole AI
data-center system (GPU, CPU, networking, software), and on TTM revenue of
$361.8B it earns a 66% operating margin. The stock fell 47.5% from its
2026-10-06 high to the 2026-11-20 close. A CEO-resignation scandal tied to a
suspected Chinese intelligence contact and a reported SEC accounting probe
landed on top of an AI-capex scare. It then rose 31.5% in one session when
the board reinstated Huang. At $165, the cheap-on-earnings story does not
clear a cost of equity that respects the stock's own volatility. Management's
own FY28 path implies about 10% a year against a 14.83% hurdle, and the most
generous construction implies 14%. Meanwhile the accounting question, the
$118B guarantee book, and the export-control fallout are open, with no date
on which the first of them resolves. This is a fine business at a price that
already assumes the good year and asks the owner to carry the governance tail
for free.

> [!WARNING]
> **Closest attack:** the hurdle itself. At a band-clamped beta of 1.2 the
> hurdle falls to 10.21%. Management's path then sits 17bp short (net of
> cash), and a ten-year durable-AI path clears by +90bp, so the pass would
> rest on the governance tail rather than on price.

**Load-bearing conditions of the bull case (6):**

1. **The price clears the hurdle on the stated path.** *probable* (attackable
   today). Reverse DCF on SBC-adjusted levered FCF of $141.05B against market
   cap: management path ~10%, durable ten-year path ~11%, most generous ~14%,
   all against 14.83% (§4).
2. **Near-term demand delivers the guide.** Q4 FY27 revenue ≥ $126.1B (the
   $130B ±3% guide's low end) and the FY28 outlook (~75% growth, raised on
   the call from ~70%) reiterated. *probable*: $390B of supply commitments,
   a ~$20B first quarter of Vera Rubin shipments, and hyperscalers guiding
   2027 capex higher. Settled by the 2027-02-24 print.
3. **AI-infrastructure spend holds past FY28,** with no FY23-style digestion
   (FY23 operating income −58%). *plausible*: hyperscaler CY2027 capex guides
   (late Jan–early Feb 2027) and NVIDIA's FY28 outlook (2027-02-24) give the
   first decisive read, but only a partial one.
4. **The accounting is clean.** The SEC inquiry reported by Reuters on
   2026-11-20 does not end in a restatement or reclassification of revenue
   from financed or guaranteed customers. *plausible*: FY26 audit is
   unqualified; scope undisclosed. The Q3 10-Q legal note (due by 2026-12-04)
   shows whether the company discloses it, not how it ends.
5. **The export-control and national-security fallout stays contained.** No
   loss of licences into Singapore/Malaysia under the 2026-11-16 BIS rule, no
   company-level charge from the Megaspeed diversion probe, and no new
   damaging facts at the Dec 1–3 hearings. *plausible*: the board says
   reinstatement "poses no national security risk" after "input from senior
   levels of the United States government" (8-K, 2026-11-23). Hearings
   2026-12-01..03; BIS 90-day licence window ~Feb 2027.
6. **Unit economics hold.** Gross margin troughs at 71–72% in Q4 and recovers
   to 72–73% in FY28, operating cash flow converts towards earnings as the
   receivables and inventory build slows, and none of the $118B guarantee
   book crystallises. *plausible*: settled by the 2027-02-24 print and
   10-K.

> [!WARNING]
> **Dominant shared risk factor:** AI data-center capex pace and the
> financing behind it — shared by 0 of 31 held names · 0 unlabelled (held list
> per `composite.db` `in_portfolio=1`; portfolio.db unreadable in this slot).
> Six holdings (INTU, SAP, MORN, RDDT, G, BKNG) carry the inverse factor,
> generative-AI substitution, which fails when AI succeeds rather than when
> capex stalls.

## 2. Business

**Created:** a customer gets the shortest path from capital to a working AI
cluster. That means GPUs, Grace/Vera CPUs, NVLink and InfiniBand/Ethernet
networking, and the CUDA software stack, sold as one integrated, validated
system on an annual cadence (Blackwell → Vera Rubin, shipping since August →
Rubin Ultra 2027 → Feynman 2028, per the Q3 call). Customers pay a premium
because time-to-capacity is the binding constraint: rented B300 capacity is
up "more than 60%" since introduction, and Hopper contracts re-priced at "up
to twice their original price" (Kress, Q3 FY27 call). The surplus is real
while compute stays scarce.

**Captured:** four distinct mechanisms.

1. *System hardware margin*: Data Center was $107.6B of $115.8B Q3 revenue
   (Hyperscale $60.1B; AI Clouds, Industrial & Enterprise $47.5B), at a 74.9%
   non-GAAP gross margin. "All are getting the same pricing" (Kress), so
   capture is list-price power, not customer-by-customer discounting.
2. *Supply allocation*: $390B of supply/capacity commitments, mostly
   multi-year memory, lock up HBM, CoWoS and substrates that rivals then
   cannot get.
3. *Balance-sheet-enabled demand*: $32B of neocloud agreements, $102B of
   cloud-service and data-center-lease commitments, $20B of equity-investment
   commitments, and $118B of maximum guarantee exposure. That includes $105B
   of SB Energy credit support behind 20-year OpenAI leases (CFO commentary
   Q3 FY27). NVIDIA increasingly finances the capacity its chips go into; this
   is the mechanism the SEC thread (§3) and the short sellers question.
4. *Edge/Graphics*: $8.2B Edge Computing, $9.8B Graphics segment.

**Protected:** a mechanism, not a label. Each of the following raises the
cost of switching on an annual cycle:

- CUDA and its library ecosystem, which a customer's engineers and code
  already depend on.
- System-level integration (NVLink domains, networking, rack design) that a
  merchant or custom ASIC must match whole.
- Pre-bought supply that starves rivals of HBM and packaging.

What does *not* protect it is shown by the 10-K's own words: cloud customers
have "internal teams designing hardware," and NVIDIA "expect[s] an
increasingly competitive environment." The two largest direct customers were
22% and 14% of FY26 revenue. Management did not engage the ASIC/TPU question
on the call (Arcuri's question got a roadmap answer). The moat is strong per
cycle but must be re-won each cycle by customers who are also building
substitutes.

**Control:** one class of common stock, 2M preferred authorized and none
issued, no controlling holder (FY26 10-K). Insiders hold 3.90% and
institutions 70.43% (`stocks.db`). Huang's personal stake was NOT OBTAINED
(proxy, incorporated by reference). Nothing structural forecloses a takeover
or an activist; at $4T neither is practical. The board's practical
independence is in question: it reinstated Huang 11 days after accepting his
resignation, citing "input from senior levels of the United States
government" (8-K, 2026-11-23).

**Operating leverage (Phase 0): positive.** Revenue grew ~33× while operating
income grew ~84× (SEC XBRL, 10-K values; TTM = four quarters to 2026-10-25):

| FY | revenue | op income | op margin |
|---|---|---|---|
| FY2020 | $10.92B | $2.85B | 26% |
| FY2021 | $16.68B | $4.53B | 27% |
| FY2022 | $26.91B | $10.04B | 37% |
| FY2023 | $26.97B | $4.22B | 16% |
| FY2024 | $60.92B | $32.97B | 54% |
| FY2025 | $130.50B | $81.45B | 62% |
| FY2026 | $215.94B | $130.39B | 60% |
| TTM Q3 FY27 | $361.81B | $239.09B | 66% |

FY2023 is the reminder: flat revenue cut operating income 58%. The same
leverage runs both ways.

## 3. Threads pulled

- **Anatomy of the drawdown** (broker daily bars, split-adjusted). Record
  close $239.24 on 2026-10-06, then seven straight weekly declines (longest
  since 2008, CNBC):
  - Nov 5: −9.3% ($200.13 → $181.60) in an AI-chip selloff Reuters tied to
    midterm results.
  - Nov 12: opened $151.01 after the resignation and closed $166.19.
  - Nov 20: −14.0% ($145.98 → $125.53) on the SEC report, with SPY −3.7%
    open-to-close ($717.19 → $690.91).
  - Nov 23: +31.5% to $165.05 on the reinstatement (SPY $722.29).
  The stock is still −31% from the high. The Q3 beat on Nov 17 did not stop
  the slide: it fell 19% over the next three sessions ($155.46 → $125.53).
- **CEO episode** (primary: 8-Ks, accessions 0001045810-26-000082 and -000090).
  - 2026-11-11: the board accepted Huang's resignation as President, CEO and
    director; CFO Colette Kress became interim CEO. No investigation language
    and no severance terms.
  - 2026-11-22: the board unanimously reinstated him. Press release: "input
    from senior levels of the United States government," "no national
    security risk." It also announced an independent-director committee with
    counsel investigating reports that Huang was "the target of a foreign
    intelligence effort," a new National Security and Export Control
    Committee, a Chief Compliance Officer search, and continued cooperation
    "with ongoing government investigations and inquiries."
  - News (low-confidence): the matter is a relationship with Alice Huang, a
    former Megaspeed executive whom US officials reportedly suspect of spying
    for China (CBS, CNBC). Huang faces closed-door House interviews on Dec 1
    (GC Teter Dec 2) and a public Senate Banking hearing on Dec 3 (CNBC).
  - Rosen Law filed a proposed securities class action (CNBC live blog).
  - Read: the key-person risk resolved in the owner's favour, but under
    political sponsorship, which is itself a dependency.
- **SEC accounting inquiry** (low-confidence: Reuters via Yahoo/Business
  Recorder/Motley Fool, 2026-11-20). Enforcement staff are reportedly looking
  at "possible accounting issues"; scope undisclosed, and neither the SEC nor
  NVIDIA has confirmed. Outlets connect it to the 2025 change that stopped
  reporting Singapore as a separate revenue geography, and to the AI financing
  deals. Reuters said it could not tie it to the geographic change. NVIDIA
  settled an SEC accounting matter once before, in 2003 (cease-and-desist
  without admitting or denying). The Q3 10-Q is not yet on EDGAR (due by
  2026-12-04). This is condition 4, and it is UNKNOWN.
- **California AG** (low-confidence: Reuters/Politico via search, 2026-11-19).
  Investigative subpoena on whether chips or confidential information reached
  China and whether investors were misled. Investigative subpoenas sit at the
  early end of enforcement; most close without action.
- **Export controls and Megaspeed.**
  - A BIS interim final rule (2026-11-16, Skadden summary) licenses remote
    compute for China-headquartered firms above 12M TPP. It adds licence
    requirements for Indonesia, Malaysia, Singapore, Thailand and Brazil and
    rescinds the AI Diffusion Rule. Existing facilities get 90 days to
    license.
  - DOJ/Commerce disclosed a criminal probe into Megaspeed (Singapore; more
    than $4B of NVIDIA purchases per trade records; reportedly on NVIDIA's
    internal block list since June 2025). Commerce blacklisted it on 11-23
    (CNBC).
  - Q4 guidance already assumes zero China data-center compute; Q3 had $2.4B
    of licensed Hopper sales to China, now stopped (CFO commentary).
  - The Southeast Asian licence requirement is new exposure I could not size:
    billing-location revenue for Singapore is no longer reported. Condition 5.
- **Cash conversion and the balance sheet** (CFO commentary Q3 FY27; SEC XBRL).
  - TTM OCF $158.86B against TTM net income $226.26B. Net income includes
    $25.47B of nine-month equity-investment gains.
  - Q2 FY27: OCF $24.08B on net income $59.69B. Q3 FY27: OCF $48.25B on
    $65.29B, so conversion is improving.
  - Receivables $81.03B (DSO 64). Inventory $39.72B, up from $21.40B at FY-end.
  - Non-marketable equity stakes $65.53B, up from $22.25B at FY-end.
  - Q2 commentary attributed slow conversion to extended terms on large
    multi-quarter contracts (KB Securities via Asia Business Daily,
    low-confidence).
  - Kress, asked by Rasgon whether the "neocloud commitments only take effect
    if financing is secured" language was new: "Is it new? No. Did we change
    anything? No."
  - This is the thread on which the bull and short cases actually disagree:
    revenue is real cash only if the customers' financing is real.
- **Gross margin trough.** Q4 guide 71–72% from 74.9%; Kress: "We expect Q4 to
  mark the bottom," then 72–73% in FY2028. The cause is a "significant change
  in terms of the cost of supply," i.e. memory (Q3 call). Condition 6.
- **Customer concentration and the capex backdrop.**
  - Direct customers 22% and 14% of FY26 revenue (10-K). Frontier labs are
    ~15% of data center revenue (call).
  - Big-four 2026 capex ~$700–725B, all guiding 2027 higher (Amazon "spend
    meaningfully more"), though Microsoft trimmed its CY26 figure $175B →
    $170B (web roundups, low-confidence).
  - Kress cited a $2.5T "cloud industry backlog." That is the industry's
    backlog, not NVIDIA bookings.
- **EPS pattern** (broker, 8 quarters). Beats every quarter, growing in size:
  Q1 FY26 $0.96 vs $0.75 est; Q3 FY27 $2.68 vs $2.47 (+8.5%). Not
  beats-by-a-hair. The actuals are non-GAAP; SEC GAAP diluted EPS differs by
  investment gains (Q2 FY27 GAAP $2.46 vs non-GAAP $2.22, Q1 GAAP $2.39 vs
  $1.87). That is a basis difference, consistent with the release's
  reconciliation, not a conflict.
- **Capital return.** Q3 buybacks $22.12B and dividends $6.03B (about 65% of
  YTD FCF). $227.3B of authorization left, to be used "through fiscal 2028."
  Share count fell from 24.30B at FY-end to 24.15B.
- **Options read (mandatory):** path 1 and path 2 both ran.
  - Path 1 (`options.db`, 2026-11-19, before the −14% and +31% days): iv30
    53.39%, iv_rank 67, iv_percentile 90 on n_days=98 (readable but
    low-confidence below 252). skew25 +0.0836 at its own 93rd percentile, so
    the downside was bid. term_spread +0.0508, front 12-18 vs back 02-19;
    neither brackets the 02-24 print, so the front premium is the scandal and
    hearing window, not earnings. Put/call volume ratio 0.69.
  - Path 2: 2027-03-19 $165 straddle; table in §4.
  - The skew reading contradicts any claim that the market is complacent about
    downside. This thesis makes none.
- **Insiders** (low-confidence). Director Mark Stevens sold ~$1.5B over the 12
  months to 2026-10-26, part of it not under a 10b5-1 plan (Stocktwits,
  Massive). A Tench Coxe Form 4 dated 2026-11-06 was seen in an index; its
  details were NOT OBTAINED. Not load-bearing.
- **Dead ends:**
  - The probe CLI prints schema only in this slot. The `screener/table` API
    returned HTTP 400 on two column sets. Exact figures came from the
    statistics `__data.json` hover strings and SEC XBRL `companyconcept`.
  - The FY26 10-K fetch truncated at ~280k characters, before Note 12 and the
    cash-taxes line, and Item 1A was read as headings via summary. The
    commitments came from the Q3 CFO commentary, which supersedes the 10-K's
    $95.2B (now $390B).
  - The Reuters original on the SEC probe was not reached; only secondary
    restatements were. CNN's live blog returned HTTP 451.
  - The call did not address TPU/ASIC share directly; nothing in the record
    rules competition in or out.
  - `sec_fundamentals.db` holds only FY27 Q1–Q2 and has no Q3 10-Q yet.

## 4. Valuation

**Inputs** (statistics `__data.json` hover values, priced at the 2026-11-23
close):
- Market cap $3,985,462,350,000. TTM `fcf` $148,723,000,000 = OCF
  $158,863,000,000 + capex −$10,140,000,000. This is levered, so it pairs with
  market cap; net debt is 0 by the pairing rule.
- SBC: TTM $7,675,000,000 (`stocks.db`; equals the SEC four-quarter sum,
  2.12% of revenue) is deducted, giving a base of **$141,048,000,000**.
- Base earnings: $198.4B, i.e. TTM operating income $239.09B × (1 − 17%
  Q3/FY guide tax). GAAP net income of $226.26B carries ~$25B of equity
  marks, so it is not used.
- Cash and securities $97.73B, debt $38.15B, net cash $59.58B (1.5% of cap);
  non-marketable stakes $65.53B. No minority-interest line in the statements
  read; no pension.
- Litigation (class action, SEC, CA AG) is unquantifiable: §6.

**Hurdle:** rf 4.92% (DGS10 2026-11-20) + beta 2.248 × ERP 4.41% (Damodaran,
Nov 1 2026; his T-bond 4.94%) = **14.83%**, unclamped.
- The regression beta sits far above the 0.8–1.2 band, but it is not a
  thin-float artefact (insiders 3.90%, float 23.18B of 24.15B shares). It is
  what the stock does: −47.5% in seven weeks, +31.5% in a day.
- At beta 1.2 the hurdle is 10.21%. Both are shown; the unclamped figure
  governs, consistent with this repo's prior high-beta runs (e.g. 14.23% at
  beta 2.116).
- 14.83% sits above the 5–10% distribution band, which needs an argument; the
  argument is the realised volatility.

**Terminal ceiling:** T10YIE 2.13% (2026-11-23), used as `--terminal-growth`.

ATM IV 52% > 50%, so implied returns are quoted to whole percents and the range
is wide.

| scenario | base FCF | growth ×5y | terminal | implied return | vs hurdle |
|---|---|---|---|---|---|
| A management path (FY28 +75%, then mature) | $141.0B | +90/+15/+5/+3/+3 | 2.13% | ~10% | −490bp |
| A′ same, net of net cash and stakes ($3,860B) | $141.0B | +90/+15/+5/+3/+3 | 2.13% | ~10% | −470bp |
| A″ same, net of net cash, beta 1.2 | $141.0B | +90/+15/+5/+3/+3 | 2.13% | ~10% | −20bp (vs 10.21%) |
| B peak-then-fade | $141.0B | +60/+5/−10/0/+2 | 2.13% | ~7% | −760bp |
| C digestion (FY23-style) | $141.0B | +40/−30/−30/0/+2 | 2.13% | ~4% | −1030bp |
| D flat TTM | $141.0B | 0×5 | 2.13% | ~5% | −940bp |
| E bust | $141.0B | +20/−40/−30/0/0 | 2.13% | ~4% | −1100bp |
| F durable AI, 10y | $141.0B | +90/+15/+10/+8/+6/+5/+4/+3/+3/+3 | 2.13% | ~11% | −370bp (+90bp at beta 1.2) |
| G normalized conversion, path B | $190.0B | +60/+5/−10/0/+2 | 2.13% | ~9% | −580bp |
| H most generous (G base, F path) | $190.0B | F path | 2.13% | ~14% | −80bp |

**Break-even prices at the 14.83% hurdle:**
- Path A clears near a $2.43T cap, ~$100/share.
- Path F clears near $2.74T, ~$114/share. The Nov 20 close of $125.53 was
  within reach of that line; today's price is not.
- At beta 1.2, path A clears near ~$162 and path F clears at today's price.

**Integrity checks:**
- *Reinvestment and terminal ROE.* The base runs print reinvestment 28.9% and
  implied terminal ROE 7.36%, below the hurdle: the terminal assumes value
  destruction. That is an artefact of a hypergrowth year's working-capital
  build ($18.3B of inventory and a receivables surge), not steady state.
  Repricing existing assets at the breakeven needs ~no reinvestment.
  - The normalized runs (G/H, base $190B ≈ earnings less capex) swing to 4.3%
    reinvestment and a 50% terminal ROE. That is more than 5 points above the
    hurdle, which is "tough to do" in perpetuity; it is defended only by the
    per-cycle system moat of §2, against a 29% base rate of firms earning
    above their cost of capital.
  - The truth sits between the two constructions. Neither clears.
- *Market-share sentence.* Path A's year-1 FCF of ~$268B implies revenue of
  roughly $650–700B in the twelve months to Oct 2027. That is near the
  big-four's entire 2026 capex (~$700–725B, all categories), so it needs
  neoclouds, sovereigns and labs on top. Path F's year-10 FCF of ~$463B at
  today's ~39% FCF margin implies ~$1.2T of revenue in 2036. That is roughly
  half of a ~$2T+ annual AI-infrastructure market that does not yet exist.
- *Terminal growth vs Item 1A.* The dominant structural risk is custom
  silicon at the largest customers ("internal teams designing hardware";
  22%/14% concentration). A 2.13% terminal, i.e. inflation only with no real
  growth, survives it. It does not survive a scenario where the hyperscalers
  in-source, which is what paths C/E bound.
- *Cash taxes.* ETR 15.1% FY26 and 17.4% Q3, below the ~21% marginal rate.
  $4.0B of unrecognized tax benefits; IRS examining FY23–FY24. The base is
  mildly flattered and the haircut is small; the conclusion does not turn on
  it.
- *SBC.* Deducted ($7.675B, 2.12% of revenue vs 5.04% for semiconductors per
  Damodaran Jan 2026). There is no large overhang hidden in the count:
  buybacks are shrinking shares.
- *Contingent claims.* The $118B maximum guarantee exposure (no payments to
  date) is not deducted. A 25% crystallisation would be ~$30B, under 1% of the
  cap, which is not decisive by itself; the risk is correlation with a capex
  downturn.
- *Distribution clamp.* Paths A–G are at or below the 5–10% band's top. Only H
  exceeds it, on a terminal ROE that needs defending.

**Options-implied move:** path 2, 2027-03-19 expiry, $165 strike, 116 DTE.
This brackets the 2027-02-24 print and the 63-trading-day horizon. Broker
marks as of 2026-11-23 16:00 ET.

| metric | value |
|---|---|
| spot | 165.05 |
| expected absolute move | 23.21% |
| 1-σ move | 29.36% |
| ATM IV | 52.09% |
| RV60 | 76.11% |
| RV20 | 126.24% |
| IV > RV60? | NO |
| IV > RV20? | NO |

- Liquidity gate: call spread $0.50 on a $20.15 mark (2.5%), put $0.40 on
  $18.15 (2.2%), volume 6,786/2,048, OI 14,461/14,317. **Passed**
  (thresholds uncalibrated; a pass is unverified).
- IV sits below both realized windows. Those windows contain the scandal days
  (−14.0%, +31.5%), so this is not "cheap vol." Both windows agree; neither
  reads elevated.
- Timing check: NOT APPLICABLE. The thesis states no required move and no
  dated price claim; the reopen price ($114) is a level, not a forecast.

## 5. Falsifiers

**For the pass (flip toward buy):**

- **Shift —** price at or below ~$114, where the durable path clears 14.83%
  unchanged.
- **Shift —** the Q3 10-Q's legal note (by 2026-12-04) describes the SEC
  matter as narrow (e.g. a disclosure-geography question), or the SEC closes
  it. Condition 4 then moves from UNKNOWN to SURVIVED, and the pass rests on
  price alone.
- **Shift —** the 2027-02-24 print shows Q4 revenue ≥ $130B, gross margin at
  or above the 71% floor, OCF/net income above 85%, and an FY28 outlook of
  ≥ +75%. That moves path A's base and re-runs the table.

**For an owner (sell):**

- **Break —** a restatement, a Wells notice, or revenue reclassification tied
  to financed or guaranteed customers.
- **Break —** a company-level export-control charge or licence revocation
  into Southeast Asia after the BIS 90-day window.
- **Shift —** Q4 gross margin below 71%, or FY28 gross margin guided below the
  72–73% Kress set.
- **Shift —** a hyperscaler guiding CY2027 capex flat or down. Any one of the
  22%/14% customers in-sourcing a generation.
- **Shift —** OCF/net income staying below 75% for two more quarters while
  receivables grow faster than revenue.

> [!NOTE]
> **Reopen trigger:** 2026-12-04: nvda-q3-10q-sec-inquiry-scope-and-dec-1-3-huang-testimony-or-price-at-or-below-114

## 6. UNKNOWNs

1. **UNKNOWN — the SEC inquiry's scope and outcome.** No filing will print the
   outcome on a schedule. The 10-Q (by 2026-12-04) may disclose existence and
   scope only. Load-bearing (condition 4); its absence does not kill the
   business but does block owning it at a price that ignores it.
2. **UNKNOWN — revenue by billing country after the Singapore line was
   dropped.** This is the size of exposure to the new SEA licence regime and
   to Megaspeed-type intermediaries. A retired disclosure has no route; it
   bounds condition 5, which is otherwise PENDING.
3. **PENDING 2026-12-04 — the Q3 FY27 10-Q:** customer concentration (A/B/C
   percentages), receivables by customer, the guarantee and commitment
   timing, and Item 1 legal proceedings.
4. **PENDING 2027-02-24 — Q4 FY27 print and FY28 outlook:** gross margin
   trough, OCF conversion, the FY28 growth figure.
5. **NOT OBTAINED — FY26 10-K Note 12 and full Item 1A text** (fetch truncated
   at ~280k characters; Item 1A read as headings via summary). Superseded for
   commitments by the Q3 CFO commentary. Not load-bearing.
6. **NOT OBTAINED — Huang's ownership percentage** (2026 proxy) **and the
   2026-11-06 Coxe Form 4 details.** Not load-bearing.
7. **Possible (option value, not a condition):** Rubin Ultra / Feynman
   extending the moat beyond 2028; a China re-opening; the $2.5T industry
   backlog converting at NVIDIA's current share.

## 7. Sources

**Primary:**
- SEC 8-Ks: 0001045810-26-000082 (2026-11-11 resignation, Ex. 99.1) and
  0001045810-26-000090 (2026-11-22 reinstatement, Ex. 99.1).
- 8-K 0001045810-26-000088 (2026-11-17): Ex. 99.1 Q3 FY27 release; Ex. 99.2
  CFO commentary (`q3fy27cfocommentary.htm`).
- FY26 Form 10-K (`nvda-20260125.htm`, filed 2026-02-25; customer
  concentration, share classes, debt, ETR) and the Q2 FY27 10-Q
  (`nvda-20260726.htm`).
- SEC XBRL `companyconcept` (Revenues, OperatingIncomeLoss,
  NetCashProvidedByUsedInOperatingActivities, ShareBasedCompensation).
- Q3 FY27 earnings call 2026-11-17, transcript via stockanalysis (Quartr),
  primary-transcribed; read in full by a fetch agent, with quotes as relayed.

**stockanalysis.com (vetted exception):**
- `/stocks/NVDA/statistics/__data.json` hover values: market cap, EV, OCF,
  capex, FCF, net income, cash, debt, beta, shares.
- `custom/financialsWidget?period=quarterly`.
- `/stocks/nvda/transcripts/` index (cadence: calls 02-25, 05-20, 08-26,
  11-17; GTC Berlin 10-21; Communacopia 09-10).

**Broker/market microstructure:** Robinhood MCP. Admissible because no
integrated official source covers real-time quotes, option chains or the
consensus-estimate side:
- NVDA/SPY quotes and official closes (2026-11-23).
- Daily and hourly bars (2026-07-16..11-23).
- `get_earnings_results` (8 quarters).
- NVDA chain; 2027-03-19 $165 call/put quotes.

**Reference data:**
- Damodaran implied ERP 4.41% (Nov 1, 2026; T-bond 4.94%).
- Damodaran semiconductor margin/capex rows (Jan 2026): pre-tax operating
  margin 35.33%, SBC/sales 5.04%, sales/capital 1.21.
- EVA excess-return base rate ~29% (per the anchors reference).

**Point-in-time repo DBs (read-only):**
- `stocks.db` v_latest: beta 2.248, insiders 3.90%, institutions 70.43%,
  float 23.18B, shares 24.147B, SBC $7.675B, sbcByRevenue 2.12, 63 analysts.
- `fred.db`: DGS10 4.92 (11-20), T10YIE 2.13 (11-23).
- `earnings.db`: calendar_now 2026-11-23; 2026-11-17 AMC confirmed; next
  2027-02-16 edgar-estimate.
- `sec_fundamentals.db`: FY27 Q1–Q2 only.
- `options.db` (2026-11-19): v_iv_rank, v_latest_sentiment, v_skew_term.
- `composite.db`: score +4; rsi 15.0, reddit +2; fcf_yield 4.91 and fscore 4
  informational; in_portfolio=0; 31 held names via in_portfolio=1.

**Low-confidence:**
- CBS, CNBC (11-12 live blog; 11-23 articles), Yahoo/Motley Fool/24-7 Wall
  St/Business Recorder (Reuters SEC-probe restatements, 11-20/21).
- Politico/Reuters via search (CA AG subpoena), Skadden/Nextgov (BIS rule),
  SCMP/Tom's Hardware (Megaspeed).
- Yahoo/Motley Fool roundups (hyperscaler capex), Asia Business Daily/KB
  Securities (conversion), Stocktwits/Massive (insider sales).
- AP/Trefis (the November selloff narrative).

## Kill-thesis record

**Ledger:** FLAWED call=PASS conditions=6 (1 probable, 5 plausible)
refuted=1 unknown=1 pending=4 not_obtained=0 · reopen 2026-12-04.

**Self-consistency first.** The bull case claims high growth (FY28 +75%), low
reinvestment (FCF converting towards earnings, capex 2.8% of revenue) and low
risk (a moat strong enough that excess returns persist) all at once. g =
reinvestment × return on capital lets a 66%-margin business do the first two
only while the moat holds. And the 66% margin is exactly what pays for the
customers' internal ASIC teams the 10-K names. That pair is strained, though
not refuted.

**Per condition:**

1. *Price clears the hurdle* — **REFUTED.** Every construction falls short of
   14.83%: management path ~10% (−490bp), durable ten-year ~11% (−370bp),
   most generous ~14% (−80bp, and only on a 50% terminal ROE). Repairable:
   at ≤ ~$114, or by accepting a 1.2 beta (where F clears by +90bp but A
   still misses by 20bp).
2. *Near-term demand* — **PENDING 2027-02-24.** Attacked with the BIS rule
   (new SEA licensing), the China zero, and the 53-week flattering of Q4. It
   stands today: the $130B guide already excludes China, supply commitments
   rose $279B → $390B, and Rubin shipped ~$20B in its first quarter.
3. *Durability past FY28* — **PENDING 2027-02-24.**
   - Attacked with the base rate: semiconductor cycles digest, and NVIDIA's
     own FY23 cut operating income 58% on flat revenue.
   - Token prices are down ~60% since May (call), so returns on the capacity
     being built are compressing.
   - Microsoft trimmed CY26 capex, and part of demand is financed by NVIDIA's
     own guarantees.
   - Not refuted: every big-four hyperscaler guided 2027 higher.
4. *Clean accounting* — **UNKNOWN.**
   - The probe's scope is undisclosed and its outcome has no scheduled
     disclosure.
   - The short case is specific. OCF/net income was 40% in Q2 and 74% in Q3.
     Receivables are $81B. Non-marketable stakes in customers and partners
     tripled to $65.5B in nine months. $118B of guarantees back customers'
     capacity. Singapore stopped being reported the year before a Singapore
     intermediary became the centre of a diversion probe.
   - Nothing here proves misstatement. It is exactly the pattern an
     enforcement inquiry would examine.
5. *Export/national-security containment* — **PENDING 2026-12-04** (hearings
   12-01..03, 10-Q by 12-04). Attacked with Megaspeed (more than $4B
   purchased; criminal probe; blacklisted 11-23), the CA AG subpoena, and the
   new BIS licence regime. It stands on the board's and the administration's
   stated clearance of Huang. That support is political, which is not the
   same as legal.
6. *Unit economics* — **PENDING 2027-02-24.** Attacked with the Q4 margin cut
   (to 71–72%, memory) and with Q2's 40% conversion. It stands on Q3's
   improvement to 74% and on management's "bottom" call.

**Standing checks.**
- *Base rate:* ~29% of firms sustain returns above their cost of capital
  (Damodaran EVA). NVIDIA is in that 29% today. The question is the terminal,
  and the base rate says fade.
- *Short case (strongest version):* the AI build-out is increasingly financed
  by NVIDIA's own balance sheet. That covers $32B of neocloud agreements, the
  $105B SB Energy guarantee for OpenAI, and $65.5B of stakes. Cash conversion
  lags earnings by $67B over the TTM (about $25B of it is investment gains). A diversion scandal now touches the
  intermediary channel that dropped out of the geography disclosure. On this
  view, reported revenue overstates arm's-length demand, and FY28 is a
  cyclical peak financed by the vendor.
- *Management incentives:* buybacks of $227B "through fiscal 2028" spend at
  peak-cycle prices. The board reinstated a founder-CEO under outside
  political pressure. The new compliance officer reports to a committee, not
  the CEO, which is a check, but the board has just shown it can be leaned on.
- *Disconfirming search (against the bull):* found the SEC probe, the CA AG
  subpoena, the Megaspeed blacklisting, the BIS rule, Burry/Chanos on revenue
  recognition, and Morgan Stanley's ~$170B off-balance-sheet estimate.
- *Disconfirming search (against the pass):* found hyperscaler 2027 capex up
  across the board, a Q3 beat ($115.8B vs ~$109B est.) and raise, an RSI of 15 before the
  bounce, and ~12× forward earnings at the low (Reuters via search, at ~$125).
  That last one is the real case for the other side.
- *Moat:* a mechanism (CUDA lock-in, system integration, pre-bought supply),
  re-won each cycle against customers who fund substitutes.

**Statistical checks:** composite's +4 rests on RSI 15.0 and Reddit
trending. Both are microstructure, and the scanner's own record says it flags
dislocations, not businesses. Nothing here leans on a backtest.

**Options timing check:** not applicable. The bull case states no required
move by a date. Path 2 ran (2027-03-19, 116 DTE, gate passed); path 1 ran at
n_days=98 (low-confidence).

> [!WARNING]
> **Closest attack:** on the pass, the beta choice. At a band-clamped 1.2 the
> durable path clears by +90bp, and the pass would then rest entirely on the
> UNKNOWN accounting inquiry rather than on price.

> [!NOTE]
> **Flip evidence:** toward SOUND, a 10-Q/SEC disclosure that bounds the
> inquiry plus a price at or below ~$114, or a 2027-02-24 print that lifts
> path A's base enough to clear 14.83%. Toward a deeper FLAWED (dead), any
> restatement, Wells notice, or revenue reclassification tied to financed
> customers.

**p(beat SPY, 63 td): 0.42.** The stock is 31% off its high on a
best-in-class business and has just been de-risked on its key person. The
next 63 trading days carry the hearings, the 10-Q, an open SEC inquiry and
the print, against a hurdle the price does not clear.
