# BLZE — Infrastructure Cost Economics

**Prepared for internal investment discussion · Jul 2026**
**Company:** Backblaze, Inc. (NASDAQ: BLZE) — HDD-based cloud storage & backup

---

## TL;DR

Backblaze is a **capital-intensive, HDD-based** storage business whose single largest cost input is **depreciation of storage hardware**, not directly-expensed drive purchases. It finances "hundreds of thousands of hard drives" almost entirely through **finance leases (2–6 yr terms, ~12.3% discount rate)**, so rising drive prices flow through as higher lease liabilities, interest and depreciation over time — not as a one-time cash hit.

**Key reframe:** Backblaze's headline multi-year deals are as a **storage *provider*, not a customer**. The five-year, **$335M multi-exabyte CoreWeave agreement (Jun 2026)** and the eight-figure B2 "Neo Cloud" deal are *revenue* contracts where Backblaze *supplies* cheap HDD storage to AI neoclouds. Backblaze does **not** sign 5-year contracts that *lock in its own drive costs*. On the cost side it is **short/floating**: the ~30% equipment-cost inflation now hitting the industry passes through to Backblaze with only the buffer of its existing lease vintages.

**Net directional call:** Backblaze is **hurt on the cost side** by the AI-driven HDD price surge (equipment cost +~30% per-unit YoY; FY2026 capex revised up to a mid-thirties % of revenue), but is **simultaneously monetizing the same surge on the revenue side** as a low-cost supplier. Management's margin guidance *evolved*: the Q4'25 call flagged "−a few hundred bps," but by the Q1'26 call it was reframed to **net-flat** FY2026 gross margin, because a May 2026 price increase is expected to offset the cost/capex drag. The thesis hinges on whether high-margin provider revenue out-earns the cost inflation — the two effects are confirmed but **cannot yet be netted from public disclosure** (no CoreWeave revenue ramp or deal margin). First real read: the **Q2 2026 call (~early Aug 2026)**.

---

## 1. Cost inputs — what actually drives COGS

| FY | Revenue | GAAP COGS | Gross profit | GAAP GM | Adj. GM |
|----|--------:|----------:|-------------:|--------:|--------:|
| 2023 | $102.0M | $52.2M | $49.9M | 49% | — |
| 2024 | $127.6M | $58.3M | $69.3M | 54% | 78% |
| 2025 | $145.8M | $57.0M | $88.8M | 61% | 79% |

- **Depreciation & amortization inside COGS was $25.1M in FY2025 — ~44% of GAAP COGS, the single largest component.** The rest of COGS: colocation/data-center operating costs, network & bandwidth, customer support, credit-card fees, internal-use software amortization.
- **The ~18pt gap between GAAP (61%) and adjusted (79%) gross margin is almost entirely D&A.** Critically, **the entire HDD-cost exposure lives in the D&A that the adjusted metric excludes** — the headline 79% adjusted GM *masks* the drive-price risk.
- Balance sheet is hardware: gross PP&E of $139.3M (12/31/24) was ~86% data-center equipment ($54.6M owned + $65.0M leased/financed). FY2024 D&A ($28.3M) was ~2x that year's capex — a large embedded cost of prior storage investment.

## 2. HDD vs SSD — and why Backblaze is HDD-first

- Backblaze runs **hundreds of thousands of HDDs** (not SSDs) for B2 Cloud Storage, sourced from a **limited supplier base (Toshiba, Western Digital)** across leased colocation space (CA, AZ, VA, Amsterdam, Toronto). It owns no real property.
- **$/TB (best-sourced, 30TB nearline, Q1 2026, Vdura/Coughlin):** HDD ≈ **$22/TB** (+35% YoY) vs 30TB TLC SSD ≈ **$580/TB** → a **~22× spot multiple**. Blended bulk/hyperscaler HDD is lower (~$15/TB) but only blog-sourced — treat as directional.
- **Spot vs structural:** the 22× is a temporary NAND-shortage spike (SSD +470–520% vs HDD +35% over nine months, from ~4.9× in Q2'25). Analyst long-run view (Coughlin) is the gap **reverts to ~4–6× through 2030** — don't extrapolate 22× as permanent. CEO framing: "flash is now ~10× more expensive per TB than hard drives."
- Implication: HDD is structurally Backblaze's cost moat vs SSD-based rivals — but it is *also* where the AI-driven inflation is now landing, because AI data centers are buying the same nearline HDDs.

## 3. Sensitivity — how much do margins move?

- The exposed cost is **storage-hardware depreciation** (est. ~$18–22M of the $25.1M COGS D&A). Because drives are finance-leased over ~6 years, a sustained HDD price change phases in over the fleet's replacement cycle rather than hitting at once.
- **Rule of thumb:** a sustained **+30%** in drive cost, fully cycled through a ~$20M depreciation base, adds ~$6M to COGS ≈ **~4pts of GAAP gross margin**. Read this as the **cost-only downside**: management's *latest* (Q1'26) guide is net-flat FY2026 margin, because a May 2026 price increase is expected to offset the drag. The slider isolates the input-cost hit *before* the pricing offset — i.e. the risk if pricing power fails.
- **Amplifier:** the **April 1, 2025 useful-life extension (3–5 yr → uniform 6 yr)** cut FY2025 depreciation ~$5.2M (+$0.09 EPS) and **lifted FY2025 gross margin ~4pts (to 61% from 54%)**. This is an *accounting-estimate* tailwind, not a real cost reduction — it flatters reported margin and front-loads a benefit that reverses into a 2026 headwind. **Normalize for it when modeling underlying unit economics.**

*(The dashboard has an interactive slider to flex drive-price change × exposed depreciation base × pass-through timing.)*

## 4. Contracts & inflation exposure

- **As a customer (cost side):** colocation space is on non-cancelable **operating leases**; drives/equipment on **finance leases, 2–6 yr**. No evidence of long-dated fixed-price drive supply contracts that hedge inflation. Exposure is largely **floating** — the June 2026 credit-agreement amendment (Citizens Bank) *expanded* permitted capital-lease debt to fund more equipment, i.e. they are leaning further into lease financing as costs rise.
- **As a provider (revenue side):** **CoreWeave — ~$335M, multi-exabyte** (Jun 2026). Note: the $335M is a **consumption-based estimate, not a fixed minimum**, and the initial order forms run **5 *and* 7 years** (the "five-year" headline is the primary order form). Warrants: **4.19M @ $7.60** — 3.05M time-based (5%/qtr over 5yr, exp. 2032) + 1.14M capacity-based; ~**8–9% fully-diluted** if all vest, resale registration within 60 days. Revenue ramp **not disclosed**. Plus **B2 "Neo Cloud" — >$15M TCV, 2-year, ~no revenue until 2027** (+~300bps to '27 B2 growth).
- **Sizing vs the whole:** FY2026 revenue guide **$161.5–163.5M** (raised at Q1'26); Q1'26 total rev $38.7M (+12%), B2 $22.4M (+24%), AI customers +76% YoY, >1/3 of new bookings AI. CoreWeave ≈ **~$67M/yr at maturity** if evenly spread (≈40%+ of *current* annual revenue) — potentially transformational, but back-end loaded with little in 2026.
- So the "do the 5-year Neocloud deals account for cost inflation?" question inverts: the multi-year deal is a **revenue** contract. The relevant risk is the opposite — Backblaze commits to *supply* storage at contracted economics for 5–7 years while *its own* input (HDDs) inflates ~30%. Margin durability of the CoreWeave deal under HDD inflation is the real question to diligence.

## 5. Verdict — benefit or hurt when chip/drive costs move?

- **Costs UP (today's regime):** **net negative on unit cost** — higher lease liabilities, interest, depreciation; GM guided down; capex to mid-thirties % of revenue. Partially buffered by existing lease vintages and the 6-yr depreciation smoothing.
- **Costs DOWN (chip deflation):** **benefit** — cheaper drive vintages lower future depreciation and lift GM ("works both ways").
- **The offset:** the same tightness that raises Backblaze's costs also drives customers to its cheap HDD tier (CoreWeave, Neo Cloud). Management *asserts* qualitatively that AI revenue offsets the ~30% inflation and now guides FY2026 margin to net-flat. **But the netting cannot be quantified from public data yet** — the CoreWeave revenue ramp and any deal-level gross margin are undisclosed, and the Q1'26 margin lift to 61% leaned partly on the useful-life *accounting* change, not demonstrated neocloud profitability. **Next catalyst: the Q2 2026 call (~early Aug 2026)** — first with CoreWeave color. Underwrite then.

---

### Open items — what disclosure still won't tell us
1. **CoreWeave economics (the crux)** — deal-level gross margin and the revenue ramp/timing are **undisclosed**. Without them the revenue-vs-cost bridge can't be built. Watch the **Q2 2026 call (~early Aug 2026)**, the first since the deal closed.
2. **Lease vintages** — management hasn't quantified how much of the ~30% HDD inflation hits immediately vs. is buffered by existing lease cohorts (running older, cheaper drives longer via the useful-life extension is a de facto buffer, but unquantified).
3. **Warrant dilution** — model the ~8–9% fully-diluted overhang from the 4.19M warrants at $7.60 against the realized deal revenue.
4. **Guidance verification** — the capex (mid-30s %), ~30% inflation, and net-flat-margin figures are from **earnings-call transcripts (Motley Fool)**, not primary filings (the 8-Ks carry only revenue/EBITDA outlook). Verify against the IR webcast replay if load-bearing.

---

*Sources: Backblaze FY2025 & FY2024 10-Ks, Q3 2025 10-Q, Q1 2026 & Q4 2025 8-Ks/earnings calls; CoreWeave 8-K exhibit + BusinessWire (Jun 2026); industry storage pricing (Forbes/Tom Coughlin–Vdura index, TrendForce, Tom's Hardware, 2026). Full citations in the dashboard. Financial-statement figures verified 3-0 against primary filings; guidance/pricing figures carry the source-quality caveats noted above.*
