# BLZE — Infrastructure Cost Economics

**Prepared for:** Oleg K · **Analyst:** Stepan Logatskii · **Date:** Jul 2026
**Company:** Backblaze, Inc. (NASDAQ: BLZE) — HDD-based cloud storage & backup

---

## TL;DR

Backblaze is a **capital-intensive, HDD-based** storage business whose single largest cost input is **depreciation of storage hardware**, not directly-expensed drive purchases. It finances "hundreds of thousands of hard drives" almost entirely through **finance leases (2–6 yr terms, ~12.3% discount rate)**, so rising drive prices flow through as higher lease liabilities, interest and depreciation over time — not as a one-time cash hit.

**Key reframe on the PM's premise:** Backblaze's headline multi-year deals are as a **storage *provider*, not a customer**. The five-year, **$335M multi-exabyte CoreWeave agreement (Jun 2026)** and the eight-figure B2 "Neo Cloud" deal are *revenue* contracts where Backblaze *supplies* cheap HDD storage to AI neoclouds. Backblaze does **not** sign 5-year contracts that *lock in its own drive costs*. On the cost side it is **short/floating**: the ~30% equipment-cost inflation now hitting the industry passes through to Backblaze with only the buffer of its existing lease vintages.

**Net directional call:** Backblaze is **hurt on the cost side** by the AI-driven HDD price surge (management already guides FY2026 gross margin down a few hundred bps; capex jumping to mid-thirties % of revenue), but is **simultaneously monetizing the same surge on the revenue side** as a low-cost supplier. The thesis hinges on whether high-margin provider revenue out-earns the cost inflation — the two effects are confirmed but not yet netted in disclosure.

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
- Enterprise **HDD ≈ $10–20/TB** vs enterprise **SSD ≈ $79/TB** (2025–2026). The SSD-to-HDD cost multiple has **blown out from ~5–6x (Q2 2025) to ~16–23x (Q1 2026)** as AI demand starved NAND supply and SSD prices rose 250–470% while HDDs rose ~35%.
- Implication: HDD is structurally Backblaze's cost moat vs SSD-based rivals — but it is *also* where the AI-driven inflation is now landing, because AI data centers are buying the same nearline HDDs.

## 3. Sensitivity — how much do margins move?

- The exposed cost is **storage-hardware depreciation** (est. ~$18–22M of the $25.1M COGS D&A). Because drives are finance-leased over ~6 years, a sustained HDD price change phases in over the fleet's replacement cycle rather than hitting at once.
- **Rule of thumb:** a sustained **+30%** in drive cost, fully cycled through a ~$20M depreciation base, adds ~$6M to COGS ≈ **~4pts of GAAP gross margin** — consistent with management's "few hundred bps" FY2026 guide.
- **Amplifier:** the **April 1, 2025 useful-life extension (3–5 yr → uniform 6 yr)** cut FY2025 depreciation ~$5.2M (+$0.09 EPS) and **lifted FY2025 gross margin ~4pts (to 61% from 54%)**. This is an *accounting-estimate* tailwind, not a real cost reduction — it flatters reported margin and front-loads a benefit that reverses into a 2026 headwind. **Normalize for it when modeling underlying unit economics.**

*(The dashboard has an interactive slider to flex drive-price change × exposed depreciation base × pass-through timing.)*

## 4. Contracts & inflation exposure

- **As a customer (cost side):** colocation space is on non-cancelable **operating leases**; drives/equipment on **finance leases, 2–6 yr**. No evidence of long-dated fixed-price drive supply contracts that hedge inflation. Exposure is largely **floating** — the June 2026 credit-agreement amendment (Citizens Bank) *expanded* permitted capital-lease debt to fund more equipment, i.e. they are leaning further into lease financing as costs rise.
- **As a provider (revenue side):** **CoreWeave — 5-year, multi-exabyte, $335M** (plus 4.19M warrants at $7.60); **B2 "Neo Cloud" — >$15M TCV, 2-year, revenue starting 2027.** These are Backblaze *selling* storage into the AI wave.
- So the PM's "do the 5-year Neocloud deals account for cost inflation?" question inverts: the 5-year deal is a **revenue** contract. The relevant risk is the opposite — Backblaze commits to *supply* storage at contracted economics for 5 years while *its own* input (HDDs) inflates ~30%. Margin durability of the CoreWeave deal under HDD inflation is the real question to diligence.

## 5. Verdict — benefit or hurt when chip/drive costs move?

- **Costs UP (today's regime):** **net negative on unit cost** — higher lease liabilities, interest, depreciation; GM guided down; capex to mid-thirties % of revenue. Partially buffered by existing lease vintages and the 6-yr depreciation smoothing.
- **Costs DOWN (chip deflation):** **benefit** — cheaper drive vintages lower future depreciation and lift GM, exactly as the PM intuited ("works both ways").
- **The offset:** the same tightness that raises Backblaze's costs also drives customers to its cheap HDD tier (CoreWeave, Neo Cloud). **The bull case is that incremental high-margin provider revenue more than covers the cost inflation.** That netting is the open question — confirm drive-fill economics and contracted pricing of the CoreWeave deal before underwriting it.

---

### Open items to close before committing
1. **$/TB gap** — pin exact 2025–2026 nearline HDD $/TB from TrendForce/IDC to size the cost-moat precisely.
2. **Net P&L** — model whether CoreWeave + Neo Cloud revenue nets against ~30% equipment inflation and the FY2026 margin compression.
3. **Lease vintages** — how much of the ~30% HDD inflation flows through immediately vs. is buffered by existing lease cohorts.
4. **CoreWeave economics** — realized gross margin, pricing, drive-fill, and dilution from the 4.19M warrants at $7.60.

---

*Sources: Backblaze FY2025 10-K, FY2024 10-K, Q3 2025 10-Q, Q4 2025 & Q4 2024 earnings releases and calls, CoreWeave deal announcement (BusinessWire, Jun 2026), and industry storage-pricing reporting (Forbes/Coughlin, The Register, Club386, 2026). Full citations in the dashboard. All figures verified against primary filings.*
