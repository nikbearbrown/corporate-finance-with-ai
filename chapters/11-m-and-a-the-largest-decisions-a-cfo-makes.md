> **Note:** Voice-unanchored draft. Rough first pass with `[verify]` flags.

# Chapter 11 — M&A: The Largest Decisions a CFO Makes

**Title options**
1. M&A: The Largest Decisions a CFO Makes
2. The Acquisition That Could Make or Break the Quarter
3. What the Empirical Record on Mergers Says (and Why CFOs Keep Doing Them Anyway)

**TL;DR.** Mergers and acquisitions integrate every analytical tool the book has covered so far — reading the firm, valuation, cost of capital, financing, payout. They also integrate the failure modes. The empirical record on M&A is sobering: most acquirers underperform after deals, and the underperformance is largest in the deals that looked most strategically compelling at the time. Halverson's potential acquisition is large enough to matter and risky enough to deserve the verification chain.

---

The target's name is Cardinal Flow Systems. It is a privately held competitor to Halverson, headquartered in Cincinnati, with $400M in revenue, $80M in EBITDA, and a market position in chemical-processing flow control where Halverson is weak. Halverson's CEO has been talking informally with Cardinal's founder-owner for six months. The conversations have reached the point where both sides are exchanging financial data under NDA. Diane has asked Maya to lead the financial diligence and produce the valuation memo.

The deal would be Halverson's largest acquisition in a decade. The total enterprise value being discussed is around $700M — equivalent to about a third of Halverson's enterprise value. If executed, it would consume a large chunk of Halverson's debt capacity, possibly require an equity issuance (Chapter 10), and meaningfully reshape the combined firm. If executed badly, it could be a major destroyer of shareholder value.

This chapter is about how to evaluate it.

## What "M&A" actually is

Specify. The umbrella term covers several distinct transaction types:

- **Strategic acquisition.** A larger firm acquires a smaller competitor, supplier, or customer to consolidate, expand, or integrate vertically. This is the Halverson-Cardinal case.
- **Financial acquisition.** A private equity buyer acquires a firm to operate it for a few years and then sell. The buyer's value creation comes from operational improvements, financial leverage, and exit timing.
- **Merger of equals.** Two similarly sized firms combine into one. Rare in practice; most "mergers of equals" turn out to be acquisitions of one by the other after a year.
- **Hostile takeover.** An acquirer bypasses the target board and offers directly to shareholders. Used when the board resists a deal the acquirer believes shareholders would accept.

Each type has different mechanics, different valuation approaches, and different empirical track records. The chapter focuses on strategic acquisitions because that's the Halverson case and the most common form for industrial firms.

## The empirical record

Before getting to the valuation mechanics, the empirical record matters because it should set the prior. The literature on M&A returns is unusually consistent on one point: **acquirers, on average, underperform.**

Studies of post-acquisition performance generally find that acquiring firms experience negative abnormal returns over 3–5 years following deals, in the range of -5% to -15% relative to peers [verify; Loughran & Vijh 1997, Andrade Mitchell Stafford 2001]. Targets, on the other hand, capture most of the synergy value through the deal premium they receive (typically 30–50% over the pre-announcement stock price).

The mechanism: acquirers tend to overpay. The deal premium plus the integration costs plus the strategic distraction cost frequently exceeds the synergy value. The acquirer is the residual claimant — they get whatever value is left after target shareholders capture their share. On average, that residual is negative.

This does not mean every acquisition destroys value. It means that the prior on any given acquisition should be skeptical, and that the burden is on the acquirer to demonstrate why this deal will be in the better tail of the distribution. Maya's diligence has to clear that bar.

## The valuation: three approaches, all needed

For Cardinal, three valuation approaches:

### Approach one: standalone DCF

Project Cardinal's free cash flows under current ownership. Discount at Cardinal's cost of capital (estimated from comparable public firms). The result is the *standalone value* — what Cardinal is worth as an independent firm.

For a $400M-revenue, $80M-EBITDA firm with stable margins and modest growth, a standalone DCF might produce an enterprise value of $500–600M [verify with actual projections]. This is the floor for what Halverson needs to pay.

### Approach two: precedent transactions

Look at recent acquisitions of comparable firms in the same industry. Compute the transaction multiples (EV/EBITDA, EV/Revenue) and apply them to Cardinal. Adjust for differences in size, growth, profitability.

For mid-cap industrial firms in flow-control or process-equipment sectors, recent transactions have closed at 8–12x EBITDA [verify recent comparable deals]. Applied to Cardinal's $80M of EBITDA: $640–960M of enterprise value. Halverson's offer of $700M is at the lower end of this range.

### Approach three: synergy valuation

Identify the specific synergies the deal creates — cost savings, revenue enhancements, tax benefits — and value them as a separate cash flow stream. The combined valuation is the standalone value plus the synergy value.

For Halverson-Cardinal, plausible synergies:

- **Cost synergies.** Combined procurement, eliminated duplicate corporate functions, plant rationalization. Estimate $20–30M annually after 24 months of integration. NPV at Halverson's cost of capital: $200–300M.
- **Revenue synergies.** Cross-selling Cardinal's chemical-processing product line through Halverson's existing distribution. Estimate $5–10M of incremental EBITDA over 3 years. NPV: $40–80M.
- **Tax synergies.** Cardinal's tax loss carryforwards, if any, applied against Halverson's taxable income. [verify whether Cardinal has NOLs]

Total synergy estimate: $250–400M of NPV, which would be added to Cardinal's standalone value.

The discipline: **synergies must be quantified, time-phased, and signed off by the operations team that will deliver them.** A "synergy" that no operating manager has signed up to deliver is a placeholder, not a value driver. The empirical record on synergies is that the cost synergies usually arrive (because they're under direct management control) and the revenue synergies usually do not (because they require customer behavior changes that the acquirer cannot control).

A common acquirer mistake is to credit revenue synergies fully in the valuation. The discipline is to credit cost synergies at 70–80% of stated value (haircut for execution risk) and revenue synergies at 30–50% (haircut for the empirical track record).

## The mechanism: how the deal price gets set

The acquirer's maximum walk-away price is:

```
Max price = Standalone value + Synergy value (haircut applied)
```

The target's minimum acceptable price is:

```
Min price = Standalone value (or higher, if there are competing bidders)
```

The deal price lands somewhere in the bargaining range between these two, with the split determined by the relative leverage of the parties. In friendly deals with a single bidder, the split is typically 50/50 of the synergy value. In auctions with multiple bidders, the target captures most of the synergy value because competition pushes the price up. In hostile situations or where the target has weak alternatives, the acquirer can capture more.

For Halverson-Cardinal, with one acquirer (Halverson) and one motivated seller (Cardinal's founder considering retirement), the deal price will reflect a roughly even split of the synergy value plus the standalone value. Maya's modeling:

- Cardinal standalone value: $550M (midpoint)
- Synergy value with appropriate haircuts: $300M
- 50/50 split of synergies: $150M to each party
- Halverson's max walk-away: $850M
- Halverson's offer of $700M: implies $150M of synergy value to Halverson, $150M to Cardinal's seller

This is a defensible deal *if* the synergy estimates hold up. The verification chain is everything.

## Three diligence flags Maya raises

Beyond valuation, Maya's diligence flags three concerns for the board memo:

**Concentration in Cardinal's customer base.** Two customers account for 35% of Cardinal's revenue. If either consolidates with a competitor or builds in-house capability post-acquisition, the synergy case erodes. Maya recommends a deal structure that includes earnouts or escrow tied to customer retention.

**Integration risk.** Halverson has not done an acquisition this size in a decade. The integration team will be assembled from existing functions, several of which are already stretched (the controller's group during audit season; the IT team during the ERP migration). The synergy timeline assumes 18-month integration; based on industry patterns, 24–36 months is more realistic.

**The seller's information advantage.** Cardinal's founder has run the firm for 28 years. He knows the customer relationships, the operational quirks, and the soft spots better than any due diligence process can uncover. A deal that depends on him remaining as a transition advisor for 24 months is one risk profile. A deal where he exits at close is another. The terms matter.

These flags do not kill the deal. They shape its structure and the expected post-deal performance. Maya's memo will recommend specific deal-structure provisions to address each.

## Maya's draft recommendation

For the board, Maya's draft framing:

**Recommend proceeding with the Cardinal acquisition at the proposed $700M price, structured as $500M cash and $200M Halverson stock,** subject to four diligence-driven provisions:

1. Customer retention earnout: 10% of consideration deferred for 24 months, contingent on top-customer retention.
2. Founder's transition agreement: 24-month retention with key milestones.
3. Synergy tracking: quarterly reporting to the board against the integration plan, with named accountability for each synergy bucket.
4. Financing: $500M new debt (Halverson's existing capacity supports this) plus $200M stock issuance (avoids the underpricing cost discussed in Chapter 10 and gives the seller equity participation in upside).

**Risks named:**

- The synergy realization may run behind plan. The deal economics survive 12 months of slippage but become marginal at 24+ months.
- The acquisition consumes management bandwidth that will not be available for Plant 4 ramp or other strategic initiatives. Sequencing matters.
- The empirical M&A record argues for skepticism even when the strategic case is strong. The verification chain has to be tighter than usual.

**What would change the recommendation.** If diligence reveals customer concentration risk worse than current information suggests, or if the founder's involvement post-close cannot be secured, or if the financing markets shift such that the cash portion becomes prohibitive, the deal should be paused or repriced.

## Closing the loop

M&A is the chapter where every prior tool gets used. Reading the firm (Chapter 2) — applied to Cardinal. Cash flow projection (Chapter 4) — applied to combined entity. Cost of capital (Chapter 5) — applied to deal IRR. Capital structure (Chapter 8) — applied to financing the deal. Payout policy (Chapter 9) — affected by the cash deployment. The integration is the work.

It is also the chapter where the empirical record is most sobering. The CFO who skips the prior — who treats this deal as the exception rather than the rule — is the CFO most likely to produce the next case study in M&A value destruction. Maya's diligence is not paranoia. It is the discipline that gives the deal the chance to be in the better tail.

---

**What would change my mind.** If the empirical M&A literature shifted to show that strategic acquirers (as opposed to financial acquirers) systematically created value, the chapter's prior would lighten. The current evidence is mixed but tilts negative for acquirer returns [verify; Moeller Schlingemann Stulz 2005 on the "mass destruction of shareholder wealth"].

**Still puzzling.** The persistence of M&A activity in the face of the empirical record on acquirer returns is unexplained by purely rational models. Some combination of CEO hubris, agency problems, and selection effects (the unannounced deals are the ones that didn't happen for good reason) is doing the work. I do not know how to clearly partition the causes.

---

**Tags:** M&A, synergies, acquirer-returns, integration-risk, Cardinal-Flow-Systems
