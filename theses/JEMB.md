# JEMB — Janus Henderson Emerging Markets Debt Hard Currency ETF — 2026-10-30

> [!IMPORTANT]
> **In one sentence:** An actively run basket of dollar-denominated emerging-market bonds paying about 7% before losses, whose best case still trails the stock market's expected return and clears its own risk hurdle only if almost nothing defaults — pass.

Price $51.17 (official close, 2026-10-30) · net assets $483.86M · next earnings none scheduled (a fund; monthly distributions, last ex-date 2026-09-30)

User-directed (`/research-ticker JEMB`). Unattended scheduled run.

## 1. Verdict and thesis

> **PASS at $51.17.** kill-thesis: **FLAWED** — conditions=2 (1 probable,
> 1 plausible), refuted=1, unknown=1, pending=0, not_obtained=0.

> [!IMPORTANT]
> **p(beat SPY, 63 td): 0.44** · kill-thesis: 0.42
> **Disputed expectation:** the bond market prices a 7.59% yield to worst
> (261bp over the 10-year); after the 0.52% fee that is 7.07% before any
> default — below SPY's 9.18% expected return under the same inputs, and only
> 62bp over JEMB's own beta-adjusted hurdle. A spread compression large
> enough to deliver price gains, or a US equity drawdown, is what would
> revise it.

JEMB is not an operating company; it is an actively managed portfolio of
~300 US-dollar emerging-market bonds (sovereigns, quasi-sovereigns,
corporates), with a heavy high-yield and post-restructuring tilt (top
holdings: Pemex, Sri Lanka, Angola, Ukraine, Sonangol, Eskom, Ecuador). The
equity framework this skill runs — moat, operating leverage, reverse DCF —
does not apply, so the question collapses to one arithmetic test: does the
yield, net of fees and expected credit losses, beat what the benchmark is
expected to return? It does not, even at zero defaults, and the margin over
its own low-beta hurdle is thinner than any honest loss allowance for this
portfolio. The managers have a short, real record of beating their index,
but 26 months is one episode, not evidence of persistence. This is a sensible
income holding for a bond allocation; it is not a vehicle for beating SPY.

> [!WARNING]
> **Closest attack:** condition 1 — the zero-default net yield (7.07%) clears
> the 6.45% beta-adjusted hurdle by only 62bp; any expected credit-loss rate
> above 0.62%/yr erases it, and the portfolio's top ten is mostly
> high-yield issuers and countries that have already defaulted or restructured.

**Load-bearing conditions (bull case: owning JEMB beats SPY over 63 trading days):**

1. The portfolio's yield to worst, net of the 0.52% fee and expected credit
   losses, clears the hurdle on the stated path. *probable* (tier of the
   evidence, not of the claim) — YTW 7.59% and duration 6.41 are on the fund's
   own page as of 2026-10-29; the arithmetic is done in §4. Kill pass:
   **REFUTED**.
2. The active managers keep adding return over the JPM EMBI Global Core
   Index. *plausible* — since-inception NAV 7.18%/yr vs index 5.88% and 2025
   14.28% vs 13.90% (fund page, to 2026-09-30); no future filing settles
   whether it persists. Kill pass: **UNKNOWN**.

The US 10-year and EM spread path are exogenous §4 scenario inputs, not
conditions.

> [!WARNING]
> **Dominant shared risk factor:** global risk-off / US-dollar funding stress
> (EM credit spreads widen together with US equities falling), compounded by
> US Treasury duration — holdings unavailable in this session

## 2. Business

**Created:** a retail-sized, exchange-traded wrapper around a hard-to-reach
asset class — dollar-denominated EM debt, no local-currency risk — with
monthly income (distribution yield at NAV 6.64% as of 2026-10-01) and
professional credit selection across ~300 issues the investor could not
access directly at lot sizes this small.

**Captured:** one mechanism — a 0.52% annual expense ratio on net assets
(~$2.5M/yr on $483.86M), charged daily against NAV. Gross and net ratio
are equal; the contractual waiver runs through at least 2027-02-28. The
holder also pays the market spread: 30-day median bid/ask 0.86% (fund
page, 2026-10-29).

**Protected:** no moat in the equity sense, and none is needed — the holder
owns the bonds, not the manager's franchise. The only "protection" relevant
to the holder is the manager's credit selection, assessed as condition 2.
Competing wrappers exist (EMB, passive, larger and cheaper to trade —
EMB quote $91.85/$92.50 vs JEMB after-hours $44.35/$59.14, an after-hours
artefact of thin market-maker quoting).

**Control:** an open-end ETF series of Janus Henderson; shareholders vote
only on fund-level matters (adviser contract, fundamental policies). The
adviser controls portfolio decisions; nothing to take over, no activist path.
Null answer for controlling holders.

**Operating leverage (Phase 0): flat.** By construction — the only cost is a
fixed percentage of assets, so "revenue" (portfolio income) and "costs" scale
1:1. No revenue/operating-income history exists to print; the fund has no
SEC income-statement line in `sec_fundamentals.db`, and its performance
figures are in §4.

## 3. Threads pulled

- **Phase 0 classification:** symbol lookup returns type `ETF`
  (`/symbol-lookup/?q=JEMB` → `!JEMB`, "Janus Henderson Emerging Markets Debt
  Ha…", $483.86M). Inception 2024-08-13; 365 holdings per stockanalysis,
  302 debt issues per the fund (2026-10-29) — the gap is presumably cash,
  derivatives and pending trades; immaterial to the call.
- **What drove the Q3 drawdown:** NAV −4.21% over the 3 months to 2026-09-30
  vs index −4.38%; price $53.93 a year ago → $51.17 today (−5.1% price,
  +1.03% total return). Third-party commentary (VanEck, 2026-10-08) attributes
  September's EM bond loss to a Treasury sell-off rather than EM-specific
  stress ("EM debt held its ground"). So the recent loss is mostly duration,
  and with duration 6.41, a 28bp rise in yields erases one quarter's net
  carry (1.77%).
- **Credit quality of the top ten:** Pemex 2.19%, Sri Lanka 1.47%, Angola
  1.33%, Bapco 1.13%, Ukraine 1.11%, Sonangol 1.08%, Eskom 1.07%, Ecuador
  1.00% (fund page, 2026-10-30). Sri Lanka and Ukraine bonds are
  post-restructuring paper; Angola, Ecuador and Sonangol are single-B
  credits. The 7.59% YTW is a promised yield on a portfolio with genuine
  default risk; the loss rate that should be netted against it is not
  disclosed (§6).
- **Premium/discount behaviour:** at a premium on 227 of 246 trading days in
  2025, 51 of 63 in Q3 2026 (fund page). Buyers have routinely paid above
  NAV, a small structural cost to an entrant.
- **Benchmark inconsistency:** the fund page measures performance against JPM
  EMBI Global Core but lists the Bloomberg Global Aggregate in its ETF
  details. Condition 2 uses the EMBI, the comparison the manager reports.
- **Market-data anomaly:** Robinhood's `close` block reports 2026-10-29 at
  $51.49 while the same payload's `previous_close` is $51.1318; stockanalysis
  and the fund both give $51.17 for 2026-10-30. Used $51.17; the $51.49 row is
  unexplained and not relied on.
- **Options read (mandatory):** no listed options — `get_option_chains`
  returned an empty chain list for JEMB. See §4.
- **Dead ends:** no earnings, no transcript, no 8-K cadence (a fund files
  N-CSR/N-PORT, not 10-K/10-Q); stockanalysis `news` feed empty. Single search
  for an October 2026 EM-specific sell-off found none. `data/etfs.db` read
  was not permitted in this unattended slot (no `sqlite3 -readonly
  data/etfs.db` grant), so the point-in-time ETF record was not cross-checked;
  it would carry the same AUM/price, nothing load-bearing.

## 4. Valuation

**Inputs:** the bond market already computes the reverse DCF this section
normally runs — yield to worst is the internal rate of return equating the
portfolio's price to its contractual cash flows. `reverse_dcf` was not run:
a bond portfolio's flows amortise to par rather than growing in perpetuity,
so any `--growth`/`--terminal-growth` path would be a category error.
Substituted arithmetic: YTW 7.59%, effective duration 6.41y, WAM 8.44y (fund
page, 2026-10-29); expense ratio 0.52%; 30-day SEC yield 6.29% (2026-09-30);
trailing distributions $3.35 (6.54% on price).

**Hurdle:** rf 4.98% (DGS10, 2026-10-29) + beta 0.35 (stockanalysis) × ERP
4.20% (Damodaran US implied ERP, 2026-10-01, as read by the same-day sweep runs) =
**6.45%**. Beta left at 0.35, not clamped to the 0.8–1.2 band: the clamp
guards an equity's estimated beta; 0.35 is the honest co-movement of a bond
fund, and clamping it up would only make the pass more decisive. SPY's
expected return under the same inputs: 4.98 + 4.20 = **9.18%**.
10-year breakeven (T10YIE) 2.34% (2026-10-30) — no terminal-growth input
exists here, so it bounds nothing; recorded for the template.

| scenario | base yield | annual credit loss | fee | net expected | vs hurdle 6.45% | vs SPY 9.18% |
|---|---|---|---|---|---|---|
| zero default (ceiling) | 7.59% | 0.00% | 0.52% | 7.07% | +62bp | −211bp |
| break-even loss | 7.59% | 0.62% | 0.52% | 6.45% | 0bp | −273bp |
| 1% loss (illustrative) | 7.59% | 1.00% | 0.52% | 6.07% | −38bp | −311bp |
| 2% loss (illustrative) | 7.59% | 2.00% | 0.52% | 5.07% | −138bp | −411bp |

The loss rates are illustrative inputs, not sourced estimates (§6 item 1).

- **Integrity — no reinvestment question:** a bond portfolio has no
  retained-earnings growth claim; the only "terminal" risk is that coupons
  are cut by default, which the loss column carries.
- **Market-share sentence:** N/A — no growth path is assumed.
- **Item 1A analogue:** the prospectus risks that bear on the long run are
  sovereign default/restructuring and USD funding stress; both sit in the
  loss column and the factor line, and neither is diversified away at 300
  issues because EM credit spreads move together in risk-off.
- **Distribution clamp:** a 6.45% hurdle sits inside the 5–10% cost-of-capital
  band; the ceiling scenario beats it narrowly, every positive-loss scenario
  above 0.62% does not.
- **63-day path:** quarterly net carry ≈ 1.77%; SPY's quarterly expectation
  ≈ 2.3%. Duration 6.41 means ±28bp in yield moves price by about one
  quarter's carry, so over this horizon the result is set by rates and
  spreads, not the yield. JEMB beats SPY mainly in states where equities fall
  and EM spreads hold.
- **Trading cost:** the 0.86% median spread equals ~1.5 months of net carry
  for a round trip.

**Options-implied move:** no listed options — `get_option_chains` returned
no chains for JEMB. Neither path 1 (CBOE `iv30`) nor path 2 applies; the
precision rule falls back to the fund's realised behaviour (beta 0.35, Q3 NAV
−4.21%), which is narrow enough that the bp figures above are meaningful.

## 5. Falsifiers

For the pass (flip toward buy):

- **Shift —** YTW minus fee rises to ≥ 9.2% (SPY's expected return on these
  inputs) with the top-ten credit mix unchanged — i.e. YTW ≳ 9.7%, a spread
  blowout that pays the default allowance. Checkable on the fund page any
  day.
- **Shift —** the hurdle falls: DGS10 down materially with the ERP rising
  (equity expected return up relative to bonds is the opposite; this one
  only helps if rf falls and the bond's spread holds).

For an owner (sell):

- **Break —** a top-ten sovereign (Sri Lanka, Ukraine, Angola, Ecuador)
  misses a coupon or announces a restructuring; the loss column moves from
  illustrative to realised.
- **Shift —** NAV underperforms the JPM EMBI Global Core over a rolling
  12 months, removing condition 2's only evidence.

> [!NOTE]
> **Reopen trigger:** 2027-01-31: jemb-ytw-net-of-fee-at-or-above-spy-expected-or-12m-alpha-negative

## 6. UNKNOWNs

1. `UNKNOWN` — the portfolio's expected annual credit-loss rate. No filing
   carries it; a rating-mix × historical default/recovery table (rating
   agencies' sovereign/EM default studies) could bound it, and the fund's
   credit-quality breakdown is on its page only as a chart. Does not kill the
   pass — the pass holds even at zero loss vs SPY; it decides only the
   hurdle-relative row.
2. `UNKNOWN` — whether the 130bp/yr since-inception outperformance persists
   (condition 2). No disclosure, now or future, settles it; it is graded
   only by future returns. Absence does not rescue the bull case.
3. `PENDING` (unscheduled) — the fund's next N-PORT/annual report would give
   exact country and rating weights; not needed for this call.
4. *Possible-tier, unnumbered:* a sharp EM spread compression (rating
   upgrades, a weaker dollar) would deliver price gains above carry — option
   value, not a condition.

## 7. Sources

- **Primary:** Janus Henderson JEMB product page (investor site, fetched
  2026-10-30): YTW 7.59%, effective duration 6.41y, WAM 8.44y, 302 issues
  (10/29); SEC yield 6.29% (9/30); distribution yield 6.64% (10/01); top-ten
  holdings (10/30); NAV/market/EMBI performance to 9/30; premium/discount
  day counts; 0.86% median spread; 0.52% expense ratio and waiver date; PMs.
- **stockanalysis.com (vetted exception):** `/symbol-lookup/?q=JEMB`,
  `/etf/JEMB/` (probe + page): AUM $483.86M, 9.45M shares, beta 0.35,
  dividends (Apr–Sep 2026 monthly, $3.35 trailing), price changes, 1y TR
  1.03%, inception, close $51.17.
- **Broker/market microstructure:** Robinhood MCP `get_equity_quotes`
  (JEMB/EMB/SPY, 2026-10-30) and `get_option_chains` (empty) — admissible
  because no integrated source covers ETF quotes/option listings for JEMB in
  this slot.
- **Reference data:** Damodaran US implied ERP 4.20% (2026-10-01), as read by
  the same-day sweep runs (VRSK/UTHR lines in `research/verdicts.log`); not
  re-fetched this run.
- **Point-in-time repo DBs:** `data/fred.db` DGS10 4.98 (2026-10-29), T10YIE
  2.34 (2026-10-30), BAMLH0A0HYM2 3.26 (2026-10-29, US HY OAS — context only).
  `data/etfs.db` not readable in this slot.
- **Low-confidence:** VanEck "Treasuries Led September's Sell Off. EM Debt
  Held Its Ground" (2026-10-08), via web search — used only for the
  attribution of the Q3 drawdown to rates.

## Kill-thesis record

`2026-10-30 JEMB FLAWED conditions=2 refuted=1 unknown=1 pending=0 not_obtained=0 reopen=2027-01-31:jemb-ytw-net-of-fee-at-or-above-spy-expected-or-12m-alpha-negative`

The draft listed a third condition ("the US 10-year does not sell off
further"); it is an exogenous rate and was moved to §4 as a scenario input,
leaving two.

- **Condition 1 — net carry clears the hurdle: REFUTED.** Against SPY (the
  stated benchmark) the ceiling scenario is −211bp before any default; that
  alone refutes "owning this beats SPY on carry". Against the 6.45%
  beta-adjusted hurdle it survives only below a 0.62%/yr loss rate, on a
  portfolio whose top ten has three sovereigns that have defaulted within
  the past five years (Sri Lanka, Ukraine, Ecuador) and several single-B
  issuers. Repairable only by price (a much higher YTW), not by argument.
- **Condition 2 — manager alpha persists: UNKNOWN.** Effective n ≈ 1: one
  26-month episode, monthly overlapping returns, +130bp/yr vs index before
  any significance test. A 2025 margin of +38bp is within noise. No disclosure
  can settle persistence; uncertainty is not credited.
- **Base rate:** active fixed-income funds' alpha is usually small and
  inconsistent net of fees; a 130bp record over two years is the normal
  luck band, not evidence (unquantified — SPIVA EM-debt figures not fetched).
- **Short case:** a holder is short volatility on the riskiest corner of EM
  credit for 7.07%, while the 10-year pays 4.98% with no default risk; the
  261bp gross spread compensates for losses that arrive all at once in
  risk-off, exactly when equities fall too, so the diversification is weakest
  when it is needed.
- **Management incentives:** the adviser is paid on AUM; reaching for yield
  (B-rated, distressed paper) raises the distribution and attracts flows.
  The top-ten mix is consistent with that incentive.
- **Disconfirming search:** sought evidence of EM-specific stress in
  October 2026 — found none; the Q3 loss is rate-driven. This weakens no
  attack on condition 1, which is arithmetic.
- **Statistical checks:** run on condition 2 (n, overlap) as above.
- **Options timing:** N/A — no dated claim and no listed options.

> [!WARNING]
> **Closest attack:** condition 1 against the beta-adjusted hurdle — 62bp of
> headroom at zero defaults, gone at a 0.62%/yr loss rate.

> [!NOTE]
> **Flip evidence:** toward SOUND — YTW ≳ 9.7% with the credit mix unchanged
> (net carry ≥ SPY's expected return), plus another year of index
> outperformance. Toward a harder FLAWED — a coupon miss or restructuring in a
> top-ten sovereign, or 12-month NAV alpha turning negative.

**p(beat SPY, 63 td): 0.42** — written before re-reading §1. Lower expected
return than SPY, but with a 0.35 beta the outcome over one quarter is close
to a coin flip skewed against it; JEMB wins mainly if equities draw down
while EM spreads hold.
