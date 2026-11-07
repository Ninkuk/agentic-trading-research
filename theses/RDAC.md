# RDAC — Rising Dragon Acquisition Corp. — 2026-11-04

> [!IMPORTANT]
> **In one sentence:** Rising Dragon is an empty shell company whose
> HZJL merger just collapsed, so each share is now simply a claim on
> about $11.17 of trust cash, and at $11.20 that claim earns less than
> the stock market should, so I pass.

Price $11.20 (official close, 2026-11-04; after-hours bid $10.45 / ask $11.20)
· market cap $38.79M (3,435,357 shares, of which only 1,685,982 public shares
hold a trust claim) · next earnings none scheduled (Q3 10-Q due 2026-11-16)

Entry path: user-directed ticker; composite carried it at score −3
(stocks_rsi −2, si_spike −1). Unattended scheduled run.

## 1. Verdict and thesis

> **PASS at $11.20.** kill-thesis: **FLAWED** — conditions=3 (2 probable,
> 1 plausible), refuted=1, unknown=0, pending=1, not_obtained=0.

> [!IMPORTANT]
> **p(beat SPY, 63 td): 0.40** · kill-thesis: 0.38
> **Disputed expectation:** the price has re-anchored on the trust
> (~$11.17/share) now that the deal is dead. The most a holder can collect
> on top of that is ~$0.069/share/month (sponsor deposits plus interest),
> about 7.4% a year. The price is revised only if the sponsor stops paying
> deposits and liquidates (≈$11.15, below price), or signs a new target
> (squeeze).

RDAC is a blank-check company with no operating business. Its 2025-approved
merger with HZJL Cayman was mutually terminated effective 2026-10-30. That
returned the public shares from "future HZJL stock" (priced near $5 for most
of 2026) to their contractual floor: a pro-rata claim on the trust, collectible
at liquidation or at the next business-combination vote. At $11.20 the market
has already priced that floor in full, slightly above my ~$11.17 estimate. What
is left is a cash-like carry of ~7% a year, available only if a cash-poor,
PRC-based sponsor keeps funding monthly extensions. That carry does not clear
SPY's implied return, and the immediate-liquidation path loses ~0.4%. The
discount trade, buying at $5 before termination, is already over.

> [!WARNING]
> **Closest attack:** on the bull side, the shell has squeezed three times
> this year on a ~1.7M float: $23.99 on 04-29, $22.28 on 08-19 and $8.58 on
> 09-01, each intraday on 16–24M shares. A new-target headline inside 63 trading
> days could repeat that. It is possible-tier option value, not a condition,
> and every prior squeeze round-tripped within days.

**Load-bearing conditions of the bull case (owning at $11.20 beats SPY):**

1. Trust intact at ≈$11.17 per public share and accreting — *probable*:
   6/30 trust $18,370,925 over 1,685,982 shares = $10.896 (10-Q filed
   2026-08-07), plus four $55,637.41 deposits (8-Ks 07-29, 10-13, 10-29) and
   trust interest (FY25 $2,389,246). The 9/30 balance prints in the Q3 10-Q,
   due 2026-11-16.
2. The sponsor funds monthly extensions past 2026-11-15 rather than
   liquidating at ≈$11.15, which is below the price — *plausible*: settled by
   the extension 8-K, expected ~2026-11-20.
3. The extension path's carry clears the hurdle — *probable-tier claim*:
   ~$0.069/month on $11.20 ≈ 7.4% a year, against an 8.48% CAPM hurdle and
   SPY's implied ~9.4%. The arithmetic is in §4 and is attacked in the record.

> [!WARNING]
> **Dominant shared risk factor:** idiosyncratic

Holdings were read from `composite.db` `in_portfolio` (30 names: ACT, BKNG,
BR, CAH, CI, CVSA, EEFT, G, GMED, GNTX, HIG, HMC, INTU, KTB, LOPE, MGY, MMS,
MORN, NTES, ORI, PAGS, PRDO, PRI, PYPL, RDDT, SAP, TIMB, WRB, YOU, ZTO), the
same route the same-day CYAB run used because `portfolio.db` has no headless
grant. RDAC is not held. The claim's only risks are the sponsor's
extend-or-liquidate decision and trust integrity, and neither co-moves with
any holding.

## 2. Business

**Created:** nothing operational. It is a Cayman blank-check vehicle formed
2024-03-08. Its IPO closed 2024-10-15: 5,750,000 units at $10.00, including
the full over-allotment, with $57,787,500 ($10.05/unit) placed in trust (10-K
filed 2026-03-30). It has two employees (Robinhood profile) and an office in
Taiyuan, Shanxi, PRC. For the public holder, the product is a cash claim with
an attached option on whatever target the sponsor brings next.

**Captured:** three mechanisms, all contractual.
- **Trust interest.** Cash at JPMorgan with Continental Stock Transfer as
  trustee (10-Q, Note 2: "substantially all … held in cash"). It earned
  $2,389,246 in FY25 and $685,588 in H1'26, ≈3.8–4.0% annualized.
- **Extension deposits.** $0.033 per public share per month (the lesser of
  that and $100K), funded by insiders as non-interest notes. 2026 deposits
  ran $100K Jan–May, then $55,637.41 monthly from June to October.
- **Redemption or liquidation.** Holders collect pro-rata trust only at a
  shareholder vote or at dissolution. Up to $50K of interest may be released
  for dissolution costs (10-K). Founder (1,437,500), private-placement
  (254,375) and representative (57,500) shares waive liquidation
  distributions. Rights (1/10 share each) expire worthless if no combination
  closes.

**Protected:** a mechanism, not a moat: the Investment Management Trust
Agreement. It segregates the cash, and the target has waived trust claims;
HZJL reaffirmed that waiver in the 2026-10-30 Termination Agreement. The
mechanism also cuts the other way. **A holder who does not tender at a
business-combination vote loses the redemption right for that deal.** That
is exactly why RDAC traded at ~$5 from February to October against a ~$11
trust.

**Control:** one class of ordinary shares. Insiders hold 1,749,375 of
3,435,357 shares (50.9%; 49.2% excluding the underwriter's 57,500
representative shares), up from ~28.43% at IPO (10-K) because public
redemptions shrank the denominator (my arithmetic). The sponsor, Aurora
Beacon LLC, can therefore approve ordinary resolutions, and plausibly the next
combination, on its own votes. Public holders cannot block a deal, only redeem
out of it. The CEO/Chair (Lulu Xing), the CFO and two independent directors
are PRC residents. The 10-K flags that the company "may be considered a
'foreign person'" for CFIUS, which constrains a US target.

**Operating leverage (Phase 0): negative.** A shell with no revenue and
rising costs.

| period | revenue | formation & operating costs | trust interest | net income |
|---|---|---|---|---|
| 2024-03-08 → 2024-12-31 | $0 | $285,533 | $543,046 | $257,513 |
| FY2025 | $0 | $815,284 | $2,389,246 | $1,573,962 |
| H1 2026 | $0 | $388,968 | $685,588 | $296,620 |

Operating cash used was $326,033 (2024 stub) and $660,474 (FY25). The only
"income" is interest on money that belongs to the redeeming public holders.

## 3. Threads pulled

- **Why ~$5 against an ~$11 trust? (the central thread).** The 2025-11-20 EGM
  approved the Reincorporation and Acquisition Mergers (4,775,965 for /
  273,331 against; 8-K filed 2025-11-24), and 5,715,609 shares were tendered.
  Later extension meetings paid out actual redemptions:
  - 2025-12-12: 1,548,345 at ≈$10.55
  - 2026-05-29: 1,903,823 at ≈$10.83
  - 2026-06-03: 611,850 at ≈$10.83

  (10-Q; 8-Ks 2025-12-18, 2026-06-01.) That left 1,685,982 public shares.
  The 2026-05-28 charter amendment allowed up to 15 one-month extensions to
  2027-10-15 with no further vote (8-K filed 2026-06-01). After it, a
  non-tendered holder's path ran only to HZJL stock ($350M consideration at
  $10/share), and the tape priced that at ~$5. Termination (8-K 2026-11-03,
  Item 1.02; effective 2026-10-30; no fee; mutual releases) restored the
  trust claim. The stock went from $5.10 (11-02) to $11.30 (11-03) on
  9,190,524 shares, 5.5× the public float. The jump is a contractual
  re-anchoring, not a sentiment pop.
- **Trust value now (estimate).** $18,370,925 (6/30) + 4 × $55,637.41
  (Jul–Oct deposits, all into trust) + ≈$249K interest (3.9% for ~126 days)
  ≈ $18.84M, or **≈$11.17 per public share**. Net of the $50K dissolution
  allowance ≈ $11.15. The public float at $11.20 is worth $18.88M, so the
  market pays ~0.2% over my estimate. Marked as an estimate; the Q3 10-Q
  settles it.
- **Who pays the extensions now?** SZG Limited, HZJL's designee, was the sole
  payee on the 07-15, 08-15 and 09-15 notes. The 10-15 deposit split
  $44,448.73 sponsor / $11,188.68 SZG (8-K filed 2026-10-29). SZG's notes,
  $455,919.41 in total, are cancelled by the termination. The sponsor already
  carries $655,637 in related-party notes and $650,241 of advances (6/30).
  Company cash outside the trust was $8,695, with a $1,326,710 working-capital
  deficit and going-concern language (10-Q). Its incentive points the other
  way: the founder shares are worth $0 in liquidation, so ~$55.6K a month buys
  a cheap option. The next deposit is due by 2026-11-15, and an
  October-dated sponsor payment the day before termination looks like
  planning for life after HZJL (an inference).
- **Nasdaq listing.** An MVLS deficiency notice under Rule 5550(b)(2) came
  on 2026-08-19, with a 2027-02-16 deadline (8-K filed 2026-08-20). Robinhood
  shows the status "Noncompliant." MVLS today is 3,435,357 × $11.20 =
  $38.5M ≥ $35M, so 10 consecutive closes ≥ ~$10.19 (through ~2026-11-16)
  should cure it. Delisting would not touch the trust claim, only liquidity.
  The Nasdaq 36-month limit (2027-10-15) caps the life of the shell in any
  case.
- **Holders.** UBS Group AG holds 225,438 shares (6.56%) as of 9/30 (13G/A
  filed 2026-11-04). Nine other 13G/13G-A filings in 2026 were not read (see
  §6). Typical SPAC-arb holders would keep the price pinned near trust while
  a redemption path exists.
- **Composite flags.** `stocks_rsi` −2 (RSI 87.5 on 11-03) is a mechanical
  echo of a re-anchoring, not overbought mean-reversion: the anchor itself
  moved. `si_spike` −1 (raw 5.15) is dated 2026-08-31, 65 days stale, and
  predates the termination. Neither bears on the trust claim.
- **Options read (mandatory):** no listed options. Robinhood
  `get_option_chains` returned an empty chain list, and `data/options.db`
  `underlyings` has no RDAC row. Paths 1 and 2 are both unavailable; see §4.
- **Dead ends:**
  - stockanalysis.com carries no financials for RDAC (income-statement
    `__data.json` shows `features.financials=false`), so statements came
    from EDGAR.
  - The XBRL `companyconcept` API returned 404 via WebFetch.
  - Robinhood `get_earnings_results` is empty, which is normal for a shell.
  - A web search for a new target found only spam-farm pages (unrelated
    .edu/.gov-style domains) claiming "renewable energy/EV supply chain"
    targets. They are discarded as unverifiable and carry no weight.
  - `data/earnings.db` has no RDAC row.
  - `sec_fundamentals.db` `v_screener` shows equity −$3,195,460 and assets
    $18,426,287. That is the SPAC temporary-equity artifact (redeemable
    shares sit outside equity), not leverage.

## 4. Valuation

**Inputs and pairing.** `reverse_dcf` does not fit this claim. With FY25
operating cash flow of −$660,474 as the base it **refused**: `refused:
base_fcf must be positive, got -778000.0` (run on the H1'26 cost run-rate,
exit 2). The honest arithmetic is a finite-lived cash claim. The denominator
is the 1,685,982 public shares at $11.20 ($18.88M), **not** the $38.79M market
cap: the 1,749,375 insider shares waive liquidation and are priced into the
cap mechanically. The flow is trust accretion of $0.033/month deposit (if the
sponsor pays) plus ≈3.9% interest on ≈$11.17 (≈$0.036/month), ≈$0.069/month
in total. No minority interest, SBC, pension or litigation haircut applies;
the $50K dissolution allowance is deducted in the liquidation rows.

**Hurdle:** rf 4.95% (DGS10, 2026-11-03) + beta 0.8 × ERP 4.41% = **8.48%**.
Beta is not measured (stockanalysis "n/a", `stocks.db` null) and is set at
the 0.8 floor of the house band. The ERP is Damodaran's implied ERP as of
2026-11-01, as fetched by the same-day CYAB run and not re-fetched here. The
economic beta of a trust claim is ~0, so the spread against rf is shown too.
SPY's implied expected return is rf + ERP ≈ 9.4%. Ten-year breakeven
(T10YIE, 2026-11-04): 2.26%. It is not used, because a shell with a hard
2027-10-15 end date has no terminal value.

| scenario | base FCF | growth ×5y | terminal | implied return | vs hurdle |
|---|---|---|---|---|---|
| A. No deposit by 11-15 → liquidate ~Dec 2026 at ≈$11.15 | n/a (trust claim) | none | none | ≈ −0.4% over ~1 mo (≈ −5%/yr) | ≈ −1,350bp (≈ −1,000bp vs rf) |
| B. Extensions funded ~8 mo → redeem at a new-deal vote, trust ≈$11.72 | n/a | $0.069/mo accretion | none | ≈ +4.7% over 8 mo (≈ 7%/yr) | ≈ −140bp (+200bp vs rf) |
| C. Extensions to 2027-10-15 → liquidate at ≈$11.90 | n/a | $0.069/mo accretion | none | ≈ +6.3% over 11.4 mo (≈ 6.6%/yr) | ≈ −190bp (+165bp vs rf) |
| D. New target signed → low-float squeeze | n/a | n/a | n/a | unbounded, unforecastable | possible-tier; not underwritten |

Precision is kept to tenths of a percent. There is no IV to apply the >50%
rule to, but realized volatility has been extreme (52-week range $4.13–$23.99),
so the mark-to-market path is far noisier than the trust arithmetic.

**Integrity checks.**
- **Reinvestment / terminal ROE:** not applicable; there is no terminal
  value. The 10-K's Item 1A endgame is mandatory dissolution if no
  combination closes by the deadline, so the claim has a hard maturity.
- **Market-share sentence:** not applicable; there is no top-line growth
  path.
- **Distribution clamp:** scenarios B and C (≈6.6–7%) sit inside the 5–10%
  cost-of-capital band, but below both the 8.48% hurdle and SPY's implied
  ≈9.4%. Scenario A is below the band.
- **Break-even price:** the 12-month extension path clears SPY's implied
  9.4% only at ≤ ≈$10.97 (≈$12.00 trust in 12 months ÷ 1.094), and clears
  the 8.48% hurdle only at ≤ ≈$11.06. Yield-to-worst turns positive only
  below ≈$11.15.
- **Commitments:** the related-party notes ($655,637 at 6/30, plus later
  sponsor notes) are payable only at a closing and convert to $10.00 private
  units. The SZG notes cancel on termination. None has a claim on the trust.

**Options-implied move:** no listed options. The Robinhood chain list is
empty and there is no `options.db` underlying (paths 1 and 2 both
unavailable), so there is no table. The liquidity gate and the timing check
are N/A.

**Equity as option:** the leverage gate fires mechanically (negative book
equity −$3.20M; going-concern language), but the lens is not run. The public
share is a senior claim on a segregated trust, not a residual claim on a
levered firm. The $1.3M of related-party obligations has no recourse to the
trust, and the negative book equity is the temporary-equity classification of
redeemable shares. The trust-claim frame (the table above) governed §1's
ownership call.

## 5. Falsifiers

**For the pass (flip toward buy):**
- **Shift —** the price trades at or below ≈$10.95 while the sponsor is still
  funding extensions. The extension carry then clears SPY's implied return,
  and the trust floor bounds the loss at ≈−2%. Revalue as a trust-discount
  trade.
- **Shift —** a new definitive agreement is announced. The redemption right
  at the vote keeps the floor, the squeeze option comes back, and the target
  itself needs its own research.

**For an owner (sell):**
- **Break —** no extension deposit by 2026-11-15, or a liquidation notice.
  Payout ≈$11.15 is below the price.
- **Break —** the Q3 10-Q shows a 9/30 trust below ≈$18.6M, or any trust
  withdrawal beyond taxes or the $50K dissolution allowance. That is a
  trust-integrity failure.
- **Shift —** a new deal is signed with a vote date. A holder must tender
  before the vote deadline or be locked in again. The 2025–26 path, where
  holders who missed the window got ~$5 HZJL-equivalent paper, is the
  precedent.
- **Shift —** a Nasdaq delisting determination after 2027-02-16. The trust
  claim survives, but liquidity does not.

> [!NOTE]
> **Reopen trigger:** 2026-11-20: rdac-nov15-extension-funded-and-q3-10q-trust-or-price-at-or-below-10.95

## 6. UNKNOWNs

1. **PENDING 2026-11-16:** the 9/30 trust balance and interest rate. The Q3
   10-Q is due 2026-11-16, since the 2026-11-14 deadline falls on a Saturday.
   Not fatal: the 6/30 base and deposit 8-Ks bound it within a few cents.
2. **PENDING 2026-11-20:** whether the sponsor funds the 2026-11-15
   extension. The extension 8-K settles it. This is load-bearing (C2):
   without it, scenario A governs.
3. **UNKNOWN:** how many of the 1,685,982 public shares still carry an
   un-reversed November 2025 business-combination tender. That changes the
   tradable float and the squeeze mechanics, not the trust claim. No filing
   breaks it out.
4. **NOT OBTAINED (non-load-bearing):** the other nine 2026 Schedule 13G/13G-A
   filings (holder identities, arb vs. retail). Not fatal.
5. **UNKNOWN:** the sponsor's target pipeline, and the base rate at which a
   SPAC with a terminated deal and under 12 months of life signs and closes a
   second deal. No measured rate was obtained, so treat the squeeze/deal
   option as unpriced.
6. *Possible-tier option value:* a new-target announcement inside 63 trading
   days repeats the low-float squeezes of April, August and September 2026.

## 7. Sources

- **Primary:** SEC EDGAR, CIK 2018145.
  - 10-K filed 2026-03-30: IPO terms, $50K dissolution allowance, PRC/CFIUS
    disclosures, FY24/FY25 statements of operations.
  - 10-Q filed 2026-08-07: trust $18,370,925; 1,685,982 public shares at
    $10.90; redemptions; deposits; notes; going-concern language; cash held
    in trust at JPMorgan, Continental trustee.
  - 8-Ks: 2025-11-24 (business-combination vote results, 5,715,609
    tendered); 2025-12-18 (extension vote, 1,548,345 redeemed); 2026-06-01
    (15-extension charter amendment, 1,903,823 redeemed); 2026-08-20 (Nasdaq
    5550(b)(2) notice, deadline 2027-02-16); 2026-10-13 (Aug/Sep SZG notes
    $55,637.41 each); 2026-10-29 (Oct notes: sponsor $44,448.73, SZG
    $11,188.68; deadline 2026-11-15); 2026-11-03 (Item 1.02 termination,
    EX-10.1 Termination Agreement, EX-99.1 press release).
  - Schedule 13G/A filed 2026-11-04 (UBS Group AG, 225,438 sh, 6.56%).
- **stockanalysis.com (vetted exception):** symbol lookup, and the overview
  route (`/stocks/RDAC/`: market cap 38.48M, shares 3.44M, industry "Shell
  Companies"). There are no financials on the route.
- **Broker/market microstructure:** Robinhood MCP.
  - Official close $11.20 (2026-11-04); after-hours bid $10.45 / ask $11.20.
  - Fundamentals: float 1,743,481; 52-week range $4.13 (10-22) – $23.99
    (04-29); status "Noncompliant."
  - Daily bars from 2026-03-01 to 11-04 (squeeze volumes; the 11-03
    re-anchoring on 9,190,524 shares).
  - Empty option-chain list; empty earnings results.

  Admissible because no integrated official source covers intraday or
  extended-hours quotes, bars or option listings for this ticker.
- **Reference data:** Damodaran implied ERP 4.41% (as of 2026-11-01, via the
  same-day CYAB run's fetch; not re-fetched); the 5–10% cost-of-capital band
  and the ~29% excess-return base rate (`references/damodaran-anchors.md`).
- **Point-in-time repo DBs:**
  - `fred.db`: DGS10 4.95 (2026-11-03), T10YIE 2.26 (2026-11-04).
  - `stocks.db` `v_latest`: price 11.30, insiders 49.25%, institutions
    26.20%, float 802,240; beta/SBC null.
  - `sec_fundamentals.db` `v_screener`: assets $18,426,287, equity
    −$3,195,460 (temporary-equity artifact).
  - `composite.db` snapshot 127 (2026-11-05T04:05Z): score −3; stocks_rsi
    87.49 → −2; si_spike 5.15 → −1, 65 days stale; `in_portfolio` list.
  - `earnings.db` and `options.db`: no RDAC rows.
- **Low-confidence:** web-search spam pages claiming a renewable/EV target
  shortlist. Discarded.

## Kill-thesis record

> **FLAWED** — conditions=3 (2 probable, 1 plausible), refuted=1, unknown=0,
> pending=1, not_obtained=0.

**Per-condition adjudication (bull case: owning at $11.20 beats SPY over 63
trading days):**

1. *Trust intact at ≈$11.17 and accreting* — **SURVIVED** (probable). The
   attack: is any third party ahead of the public holders?
   - HZJL reaffirmed its trust waiver in the Termination Agreement.
   - Deferred underwriting ($1,868,750) is payable only on a closing.
   - Interest may be withdrawn only for taxes (Cayman, so none withdrawn) and
     $50K of dissolution costs.
   - The cash sits at JPMorgan under a Continental trusteeship.

   The residual risk is that vendor claims could reach the trust despite
   waivers. The 9/30 figure is due 2026-11-16.
2. *Sponsor funds extensions past 2026-11-15* — **PENDING 2026-11-20.** The
   attack: the July–September deposits came from HZJL's designee alone, and
   company cash is $8,695 against a $1.33M working-capital deficit. Not
   refuted: the sponsor paid $44,448.73 of the October deposit, and its
   founder shares are worth $0 in liquidation, so the incentive is to keep
   buying the $55.6K/month option.
3. *Carry clears the hurdle on the extension path* — **REFUTED.** Even on the
   best funded path, $0.069/month on $11.20 is ≈7.4% a year. That is below
   the 8.48% clamped hurdle and below SPY's implied ≈9.4%. The zero-beta
   framing rescues it against rf (+~200bp) but not against the benchmark the
   bull case is graded on. Repairable only by price: ≤ ≈$10.97.

**Standing checks:**
- *Base rate:* no measured rate was obtained for second-deal completion after
  a late-life termination. Folklore says most such shells liquidate; that is
  not credited either way and is recorded as an UNKNOWN in §6.
- *Short case:* the price sits above liquidation value (~$11.15), backed by a
  cash-poor PRC sponsor that is CFIUS-constrained, with 11 months of life
  left and a failed deal behind it. The 11-03 volume was 5.5× float, and
  every 2026 squeeze round-tripped. The upside is capped at trust plus
  accretion absent a target.
- *Management incentives:* founders get $0 in liquidation and ~$14M of paper
  at $10 in any deal. They will extend and will sign almost anything.
  Insiders hold 50.9% of the vote, so the public's only protection is
  tendering at the vote. That is consistent with C2 and adverse to anyone who
  misses a tender window.
- *Disconfirming search:* searched for a new target, rescue financing and
  sponsor distress. Only spam pages turned up, and nothing primary since the
  2026-11-03 8-K.
- *Moat:* N/A. The protection is the trust agreement, a contract mechanism
  that has demonstrably held: redemptions were paid at $10.55–$10.83.

**Statistical checks:** the composite `stocks_rsi` (87.5) fired on a
contractual re-anchoring. RSI's mean-reversion inference assumes a stationary
anchor, which this is not, so it carries no evidential weight. `si_spike` is
65 days stale. Neither is a forward-return claim this thesis relies on.

**Options timing check:** N/A. There are no listed options (Robinhood chain
list empty, no `options.db` row), and the only dated claim (the 2026-11-15
deposit) is a binary filing event, not a priced move.

> [!WARNING]
> **Closest attack:** the bull case's own best path loses to the benchmark
> by ≈200bp a year at $11.20. The pass rests on arithmetic, not on any
> negative story about the sponsor. The only bull route that beats SPY is
> an unforecastable new-target squeeze.

> [!NOTE]
> **Flip evidence:** toward SOUND, the price trades at ≤ ≈$10.95 with the
> 11-15 deposit confirmed by 8-K, so C3 clears and C2 survives. Toward a
> harder FLAWED, no deposit and a liquidation notice, so the payout lands at
> ≈$11.15, below the price, or a Q3 10-Q trust below ≈$18.6M breaks C1.

**p(beat SPY, 63 td): 0.38.** Over a quarter, the claim returns ≈ +1.8% on
the funded path or ≈ −0.4% on liquidation. SPY's quarterly distribution
(mean ≈ +2.3%, σ ≈ 8%) beats +1.8% a bit more than half the time and beats
−0.4% about 63% of the time. A small squeeze tail adds back a few points.
