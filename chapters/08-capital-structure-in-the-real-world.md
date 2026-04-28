
# Chapter 8 — Capital Structure in the Real World
---

At the end of Chapter 7 we arrived at a clean result. Every dollar of debt adds value through the tax shield. Add them up and the formula says the optimal capital structure is 100% debt — borrow as much as the bond market will give you, pay no taxes, maximize firm value.

No firm does this.

Not one. You can look at every publicly traded company in the United States and you will not find a firm that has leveraged itself to the hilt because a formula told it to. The largest, most financially sophisticated companies in the world — firms with teams of CFOs, investment bankers, tax lawyers, and capital markets specialists — all carry meaningful equity alongside their debt. Apple carries equity. ExxonMobil carries equity. Halverson Manufacturing carries equity.

Either every CFO in America is making the same elementary mistake, or the formula is missing something.

The formula is missing something. This chapter is about what.

---

## The Gap Between Theory and Reality

The MM-with-taxes result — $V_L = V_U + T \times D$ — follows from a set of assumptions that were stated at the beginning of Chapter 7 and then quietly set aside. No taxes on income except corporate taxes. No costs to bankruptcy or financial distress. No informational differences between managers and outside investors. No conflicts of interest between shareholders and debtholders.

Strip away those assumptions one at a time and you introduce a set of forces that push back against debt. Each force is a real economic phenomenon with real quantitative consequences. Together they explain why the actual optimal capital structure for most firms is not 100% debt but something considerably more moderate.

There are four forces. I want to explain each one carefully, because each one illuminates a different aspect of how firms actually work — not just how they are financed.

---

## Force One: Distress Is Not Free

The MM framework assumes that if a firm cannot pay its debts, something happens, and then the world continues as before. The firm's assets get redistributed to the debtholders. No value is destroyed in the process. Bankruptcy is costless.

This is false in a way that has large dollar consequences.

When a firm enters financial distress, two categories of costs appear.

**Direct costs** are the professionals. Bankruptcy attorneys, financial restructuring advisors, accountants doing the forensic work, court costs. For a mid-sized firm that enters Chapter 11, these costs commonly run 3–7% of the firm's pre-distress enterprise value [verify — Andrade & Kaplan 1998]. For Halverson at $2 billion of enterprise value, that is $60 million to $140 million of pure deadweight loss — value that disappears into legal fees and is not received by anyone who had a claim on the firm.

**Indirect costs** are larger and harder to see, but the empirical estimates suggest they matter more. When a firm is visibly in financial trouble, customers stop signing long-term contracts. Why would you commit to a five-year supply agreement with a company you're not sure will exist in three years? Suppliers start demanding faster payment or cash on delivery — which makes the cash flow problem worse. Key employees, the ones with options, start taking calls from recruiters. Competitors advertise against the firm's instability. The indirect costs in academic studies are estimated at 10–25% of pre-distress firm value [verify — Andrade & Kaplan estimates], and they typically dwarf the direct costs.

There is also a third category that appears before any formal distress filing: **operational distortions**. A firm that is approaching financial difficulty may pass on positive-NPV projects because it needs to conserve cash. It may sell assets at fire-sale prices. It may take on excessive risk — gambling for resurrection, trying to hit a jackpot that will make the debt problem go away. Myers (1977) [verify] called this the underinvestment problem; Jensen and Meckling (1976) [verify] called the risk-taking version asset substitution. Both are real, both are costly, and both operate well before the formal bankruptcy filing that would make them visible.

Now connect this to leverage. A firm with no debt essentially cannot enter financial distress — it has no fixed obligations it might fail to meet. A firm with 80% debt-to-capital enters distress in any meaningful recession. The probability of distress rises with leverage, slowly at first and then very steeply.

This creates an explicit trade-off. The tax shield benefit grows linearly with debt — every additional dollar of debt adds $T$ of present value through the interest deduction. But the expected distress cost — the probability of distress times the cost if it occurs — grows nonlinearly. At low leverage levels, distress probability is near zero and the tax shield dominates. At high leverage levels, distress probability is significant and the distress cost dominates.

The optimal capital structure is the leverage level where the marginal tax shield benefit exactly equals the marginal increase in expected distress cost. Below that point, take on more debt. Above it, pay debt down or don't issue more.

$$V_L = V_U + \underbrace{PV(\text{tax shield})}_{\text{grows with } D} - \underbrace{PV(\text{expected distress costs})}_{\text{grows faster at high } D}$$

[FIGURE: Two curves and their sum. Horizontal axis: debt-to-capital ratio (0% to 100%). Vertical axis: value added (positive above, negative below). Curve 1: PV of tax shield — straight line rising from zero. Curve 2: PV of expected distress costs — flat near zero until roughly 40% D/C, then rising sharply. Curve 3: Net value added (tax shield minus distress cost) — rises to a maximum around 30–40% D/C, then falls. The peak of Curve 3 is labeled "trade-off optimum." The point at 100% debt is labeled to show that net value added there is negative despite the tax shield, because distress costs overwhelm it.]

For stable, profitable firms with tangible assets — Halverson fits this description — the empirical evidence suggests the trade-off optimum falls around 25–40% debt-to-capital [verify — Frank & Goyal 2009 on capital structure determinants]. Halverson's existing debt weight is 30%. This is not coincidence. CFOs calibrate to industry norms, and the industry norms encode the trade-off.

---

## Force Two: Shareholders and Debtholders Want Different Things

A second force is entirely distinct from distress costs and shows up even when the firm is nowhere near financial difficulty.

Once debt is in place, the firm has two classes of claimants with different payoff structures. Shareholders receive whatever is left after the debt is paid — they have unlimited upside and limited downside (the downside is capped at zero when the firm defaults and they receive nothing). Debtholders receive a fixed promised payment — no upside if the firm does exceptionally well, full downside if the firm defaults.

This asymmetry creates a systematic conflict. Shareholders benefit from riskier investments — the upside accrues to them, and some of the downside is absorbed by debtholders in default. Debtholders want the firm to be cautious and to protect the cash flows backing their claim.

This conflict takes two concrete forms.

**Asset substitution.** After issuing debt, the firm has an incentive to take on riskier projects than it promised debtholders when pricing the debt. The riskier projects' upside goes to equity; the riskier projects' downside (in default) is partly borne by debtholders. Debtholders, anticipating this incentive, price debt higher to compensate — which raises the cost of debt for the firm. The higher cost reflects a real value destruction: the conflict itself is costly, because the firm must spend on covenants, monitoring, and renegotiation to manage it.

**Debt overhang and underinvestment.** A highly levered firm may decline to fund positive-NPV projects because the gains flow primarily to debtholders — who get paid first — rather than to shareholders. This is Myers's (1977) underinvestment problem [verify]. The firm rejects projects it would accept if it were unlevered, and value is destroyed. The debt overhang is most severe when the firm is already in or near distress, which is one of the mechanisms by which financial distress destroys value before any formal default.

These agency costs are hard to measure precisely but they are empirically significant at high leverage levels [verify]. For Halverson at 30% debt-to-capital, the agency costs are modest — the conflict between shareholders and debtholders is real but contained by covenants and by the firm's operating health. Push leverage to 60% and the agency costs grow substantially.

---

## Force Three: Managers Know Things the Market Does Not

The third force comes from an informational asymmetry that MM assumed away entirely.

Managers know more about the firm's prospects than outside investors do. The quality of the next product launch, the status of a major contract negotiation, the CFO's private assessment of whether this year's earnings are sustainable — these are known inside the firm and not outside it. Investors know that managers know more, and they try to infer the firm's true value from observable actions, including financing decisions.

When a firm issues new equity, the market asks: why would management dilute existing shareholders right now? The most natural inference is that management believes the stock is overvalued — that the current price is higher than what the firm is actually worth — and is taking advantage of that overvaluation to issue shares cheaply. The market adjusts its estimate of the firm's value downward.

This is not irrational. It is Bayesian updating on the information content of the financing choice. And it has a large empirical signature: equity issuance announcements are associated with negative abnormal returns averaging 2–3% in the days around the announcement [verify — Asquith & Mullins 1986 and subsequent literature]. The market, on average, reads new equity issuance as bad news about firm value.

The implication, formalized by Myers and Majluf (1984) [verify], is the **pecking order theory**. Firms should prefer financing sources in order of their information-sensitivity:

Internal funds first. Retained earnings carry no signal at all — the firm is simply using its own accumulated cash. No adverse price reaction. No information cost.

Debt second. Debt prices are less sensitive to firm-specific information than equity prices. Issuing debt signals that the firm needs external capital, but it does not carry the same "we think the stock is overvalued" inference as equity issuance. The adverse price reaction is smaller.

Equity last. New equity carries the largest information cost. Issue it only when the first two sources are genuinely exhausted.

The pecking order is a different theory from the trade-off theory, and it is important to understand how. The trade-off theory says firms target a specific leverage ratio — the ratio at which marginal tax benefits equal marginal distress costs. The pecking order says firms do not target a ratio at all; they simply use the cheapest financing source available each time they need capital, and the resulting leverage ratio is whatever it turns out to be.

Both effects are real. Empirical evidence supports both [verify — Frank & Goyal survey]. Firms do seem to respond to deviations from an industry-norm leverage target (trade-off behavior), and firms do seem to prefer internal funds and debt over equity (pecking order behavior). A working CFO uses both lenses simultaneously.

For Halverson and Plant 4, the pecking order verdict is clear: fund the project from operating cash flow and debt first; issue equity only if those sources are insufficient. For a $50 million investment, equity issuance would be unusual and would send a signal the firm probably does not want to send.

---

## Force Four: The Tax Shield Is Smaller Than It Looks

Chapter 7 used Halverson's 24% corporate tax rate to compute the tax shield at $0.24 per dollar of debt. This understates one complication and overstates another.

The overstatement: the tax shield only has value if the firm has taxable income to shield. A firm with accumulated tax loss carryforwards from prior losses pays no taxes on its current income and therefore gets no benefit from additional interest deductions until the carryforwards are consumed. The marginal value of another dollar of debt for a firm in this position is zero, not $T$.

The additional complication: investors pay personal taxes on the income they receive. Interest income is taxed at ordinary income rates. Equity income — capital gains and qualified dividends — is typically taxed at lower rates. The corporate tax shield saves taxes at the corporate level, but the income that flows through to debt investors is taxed harder at the personal level than the income that flows to equity investors. Miller (1977) [verify] worked through this formally and showed that the personal tax disadvantage of debt partially offsets the corporate tax advantage.

After accounting for personal taxes and the probability of losing carryforward value, empirical estimates of the effective marginal value of debt for typical US firms are in the range of 10–15% of debt outstanding, not the headline corporate tax rate of 21–24% [verify — Graham 2000 estimates].

This does not reverse the conclusion that debt has tax value. It reduces the magnitude of that value, which shifts the trade-off optimum toward somewhat less debt than the Chapter 7 formula would suggest.

---

## The Complete Picture

Put the four forces together.

$$V_L = V_U + \underbrace{PV(\text{effective tax shield})}_{\approx 10\text{–}15\% \times D} - PV(\text{distress costs}) - PV(\text{agency costs}) - PV(\text{info costs of equity})$$

The first term pushes toward debt. The remaining terms create forces that grow with leverage and push back. The optimal capital structure is wherever the net of these forces is maximized — which is firm-specific, industry-specific, and depends on the firm's cash flow stability, asset tangibility, and growth opportunities.

For a firm like Halverson — stable cash flows, tangible manufacturing assets, moderate growth, investment-grade credit — the trade-off optimum falls in the 25–40% debt-to-capital range. This is what the empirical cross-sectional literature finds for firms with this operating profile [verify — Frank & Goyal 2009].

For a high-growth software firm with mostly intangible assets, the optimum is much lower — perhaps 5–15% — because the distress costs are enormous (customers and employees flee, intangible assets evaporate), the agency costs are large (lots of discretion for managers to destroy value), and the tax shield is less valuable if taxable income is low.

For a regulated utility with contractually guaranteed cash flows and hard assets that can be liquidated at predictable prices, the optimum is much higher — perhaps 50–60% — because distress is unlikely (the regulator ensures the firm earns its cost of capital) and the tax shield is fully capturable.

The formula is the same. The answer differs because the inputs differ.

---

## What This Means for Maya's Recommendation

Maya's actual recommendation to Diane runs as follows.

Fund Plant 4 with $50 million of new long-term debt. At Halverson's current 30% debt-to-capital ratio, the new debt keeps the firm comfortably within the 25–40% trade-off range. The tax shield on $50 million of debt at an effective marginal rate of, say, 15% [verify with Halverson's specific tax situation] adds approximately $7–8 million of present value. Equity issuance for a $50 million project carries an asymmetric information cost that is not worth bearing when debt is available.

The integrated value from Plant 4:

- Risk-adjusted operational NPV (from Chapter 6): $30 million
- Present value of incremental tax shield on new debt: ~$7–8 million
- Total value created: approximately $37–38 million

The risks are named explicitly. If Halverson's operating cash flows weaken in a recession, the new debt service adds pressure — but the increment is small relative to existing operating cash flow. If the bond market tightens and debt becomes expensive, the deferral option from Chapter 6 preserves the flexibility to wait. If Halverson's tax position changes materially, the tax shield value is revised downward.

None of these risks are reasons not to proceed. They are conditions on which the recommendation rests, and naming them is part of the recommendation. A board that approves the project should be approving the conditions as well as the conclusion.

---

## The Trade-Off and the Pecking Order Are Not Rivals

I want to say something about the relationship between these two theories before closing, because they are often presented as competing explanations for the same fact. They are not.

The trade-off theory describes where a firm's capital structure should be *over the long run* — the target leverage ratio that maximizes firm value given the firm's specific tax situation, distress costs, and agency costs. It is a theory about the destination.

The pecking order theory describes how firms *get there* — through a sequence of financing choices that prefer internal funds, then debt, then equity. In any given quarter, the firm uses whatever is cheapest. The destination accumulates from those choices.

The two theories are consistent. A firm that targets 30% debt-to-capital (trade-off) will fund its next project with operating cash flow and then debt rather than equity (pecking order). If the firm's leverage drifts well above 30% due to a run of debt-funded investments, it will eventually correct — by retaining earnings and paying down debt — back toward the target. Both effects show up in the data because both are real.

The CFO who only knows the trade-off theory knows where to point the ship but has no guidance for how to steer on any given day. The CFO who only knows the pecking order has a decision rule for today but no map for the long run. Halverson needs both.

---

## What Would Change My Mind

The trade-off theory predicts a specific relationship: firms that deviate from their optimal leverage ratio should correct toward it over time, and the correction should be associated with value gains. The empirical evidence for this correction is real but weaker than the theory predicts [verify — Welch 2004; stock returns largely drive leverage ratios passively through equity price changes rather than active capital structure management].

One interpretation is that CFOs are targeting capital structure in theory but not managing it actively in practice — they issue debt when they need to fund something and buy back equity when they have excess cash, but they do not fine-tune leverage for its own sake. If this is right, the trade-off optimum is less a target and more a guardrail: firms try to stay within a range rather than hitting a precise ratio.

I think the guardrail interpretation is more accurate than the targeting interpretation for most firms, including Halverson. The recommendation in this chapter — keep leverage within the 25–40% range — reflects this. It is not a recommendation to hit exactly 30.0%.

---

## Still Puzzling

The agency cost of debt is theoretically clean — the conflict between shareholders and debtholders is real, and debt covenants exist precisely to manage it. But empirically isolating the agency cost from the distress cost is difficult, because highly levered firms are also more likely to be in distress. The two forces operate together and are hard to price separately.

I also find myself uncertain about how much of observed capital structure patterns reflects the forces I've described versus simple industry anchoring. CFOs look at what comparable firms do and cluster around that. Whether they cluster because the comparable firms have worked out the trade-off correctly, or because clustering feels safe and deviation feels risky, is not obvious from the data. The industry norm may encode the optimum, or it may encode the conventional wisdom of a prior era that has not been challenged.

I think the former is more likely for stable industries with long histories. I am less sure for young industries where the capital structure conventions are still being established.

---

**Coming up.** Act Two ends here. Halverson has been analyzed, Plant 4 has been valued, and the financing structure has been recommended. Act Three begins with a different question: having made the decision, how does the firm execute? Chapter 9 takes up the mechanics of actually raising the debt — covenants, credit ratings, and what happens on the other side of Maya's memo when Halverson's investment bankers sit down with the bond market.
