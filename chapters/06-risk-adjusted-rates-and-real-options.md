
# Chapter 6 — Risk-Adjusted Rates and Real Options

Maya's revised NPV for Plant 4 came in at $42 million. She is reasonably proud of it. She spent two chapters getting there. The number is wrong.

Not wrong in the arithmetic sense. Wrong in a deeper sense: the calculation correctly answers a question that is not quite the question Halverson should be asking. It uses the wrong discount rate for this particular project. And it assumes a kind of irrevocability — commit today, no looking back — that no rational manager actually faces.

This chapter fixes both problems. The fixes point in opposite directions: the correct discount rate makes the NPV smaller, and acknowledging flexibility makes it larger. They do not cancel out. Understanding why they don't is most of what I want to teach you here.

---

## The First Problem: One Rate for Everything

Go back to Chapter 5 for a moment. The cost of capital depends on risk. We arrived at Halverson's WACC of 8% by blending the required returns on its debt and equity, where the equity return was derived from a beta estimated against the firm's existing operations.

That 8% is the average risk of Halverson as it currently exists. It is the right discount rate for a project that is exactly as risky as Halverson's average project — a capacity expansion in an existing product line in an existing geography, using a proven manufacturing process.

Plant 4 is not that.

Suppose Plant 4 is in Mexico. Halverson operates in the US Midwest. The plant introduces country risk, currency risk, and operational risk that Halverson's existing business does not carry. The 8% WACC was estimated from a firm that has none of those risk exposures. Discounting the Mexican plant's cash flows at 8% treats those additional risks as free. They are not free.

Here is the precise error. The NPV formula says: discount future cash flows at a rate that reflects their risk. When the risk of the project differs from the risk of the firm, the firm's WACC is the wrong rate to use. Using it anyway produces an NPV that is too high — the denominator is too small — and systematically overstates the case for projects that are riskier than the firm average.

Most firms use the firm WACC for all projects because it is convenient. The convenience has a real cost. A firm that systematically applies a low discount rate to high-risk projects will accept too many of them. Over years, this introduces a quiet drift toward riskier projects and away from the core competence that the firm actually understands. The evidence on this drift in diversified conglomerates is suggestive [verify — capital allocation literature on conglomerate discount].

The discipline is simple to state: **the discount rate should match the risk of the project, not the risk of the firm.**

---

## Finding the Right Rate: Pure-Play Comparables

How do you find the right rate for a project with a different risk profile than the firm?

The cleanest method is called the **pure-play comparable approach**. The idea: find publicly traded companies whose primary business is the same as the project's business. Not firms that happen to have a division like the project — firms whose entire operation looks like what the project will be. Compute their betas. Use those betas to back out a project-appropriate required return.

The mechanics follow directly from Chapter 5's beta framework, with one important adjustment. The pure-play firms have their own capital structures, and capital structure affects measured equity beta — a firm with more debt has a higher equity beta than the same firm with no debt, because the fixed debt obligations amplify the variability of returns to equity. Before we can use these firms' betas to estimate the project's risk, we need to remove the effect of their capital structures.

This is called **unlevering the beta**. The formula for the unlevered (asset) beta is:

$$\beta_{\text{asset}} = \frac{\beta_{\text{equity}}}{1 + (1 - t) \cdot D/E}$$

where $t$ is the corporate tax rate and $D/E$ is the firm's debt-to-equity ratio. The asset beta removes the capital structure effect and gives you a pure measure of the business risk.

Once you have asset betas from several comparable firms, you average them, then **re-lever** using Halverson's capital structure for the project. This gives you an equity beta appropriate for the project under Halverson's financing conditions. Plug into CAPM:

$$R_e^{\text{project}} = R_f + \beta_{\text{project}} \times \text{ERP}$$

For Halverson's Mexican plant, suppose the pure-play comparables — publicly traded Mexican industrial manufacturers or US firms with majority Mexican operations — have average asset betas around 1.4 after unlevering [verify]. Relevered at Halverson's capital structure:

$$R_e^{\text{project}} = 4.2\% + 1.4 \times 5.0\% = 11.2\%$$

Halverson's firm-level $R_e$ is 9.8%. The project's required equity return is 1.4 percentage points higher. Combined with the same debt costs and weights, the project WACC comes out around 9.0% instead of 8.0%.

One percentage point sounds modest. Applied across a ten-year cash flow stream plus a terminal value, it is not modest. Maya's $42 million conservative NPV at 8% becomes approximately $25 million at 9%.

[FIGURE: Two NPV profiles plotted against discount rate. One labeled "Firm WACC = 8%" with NPV = $42M marked. One labeled "Project WACC = 9%" with NPV = $25M marked. The curve shows how steeply NPV falls as the discount rate rises from 8% to 9% for this project — steeper than a short-horizon project because of the terminal value. The crossover with the horizontal axis (NPV = 0) occurs around 11.5%, illustrating that even the risk-adjusted NPV has meaningful margin before turning negative.]

Still positive. The project still passes the basic hurdle. But the recommendation is now anchored to what Plant 4 actually is, not to what Halverson's average project is.

---

## The Second Problem: The Future Isn't Locked

Here is a scenario.

Halverson's board approves Plant 4 today. The firm commits $50 million and begins construction. Six months in, regional demand data comes back weaker than expected. The project's NPV, recomputed with the new information, is negative — Halverson would not start this project today knowing what it knows now. But the plant is half-built. The firm has spent $30 million in sunk costs. The rational thing to do is to complete the construction and operate at a loss rather than abandon a half-built plant.

Alternative scenario: Halverson defers the construction commitment by six months. During the deferral, regional demand data comes back weaker than expected. The firm cancels the project. It has spent only the planning costs — perhaps $500,000. It avoids the $50 million capital outlay and the subsequent operating losses entirely.

These two scenarios produce materially different financial outcomes. The standard NPV formula does not distinguish between them.

The NPV formula asks: given today's probability distribution over future cash flows, is the expected discounted value positive? It implicitly assumes that the decision is made today, irrevocably, and the firm then watches the future unfold without any ability to act on new information. No competent manager actually operates this way. Every manager retains the ability to accelerate, defer, scale up, or abandon as information arrives.

The value of that flexibility is real, and it belongs in the analysis. The framework for capturing it is called **real options**.

---

## What a Real Option Is

The word "option" is doing the same work here as in financial options. A call option on a stock gives you the right, but not the obligation, to buy the stock at a fixed price on a future date. You exercise if the stock price exceeds the strike; you walk away if it doesn't. The asymmetric payoff — you capture the upside, you limit the downside — is why the option is worth something even before you know whether you'll exercise it.

A real option is the same structure applied to a capital project. The right, but not the obligation, to make a capital investment at a future date based on information available at that date. Three forms appear most often:

The **option to defer**: the right to wait and invest later rather than now. Valuable when uncertainty is high and waiting will reveal information that matters for the decision. The firm gives up early cash flows in exchange for not committing capital before the uncertainty resolves.

The **option to expand**: the right to invest more if the initial results are good. Valuable when the initial project serves as a platform for follow-on investments. The initial plant is not just Plant 4 — it is the option to build Plants 5 and 6 if Plant 4 demonstrates regional demand.

The **option to abandon**: the right to terminate the project and recover salvage value if results are bad. Valuable when assets are redeployable. A plant built with general-purpose equipment can be sold; a plant built with single-purpose tooling cannot.

Plant 4 has all three. Halverson can defer the commitment. If demand is strong, it can build additional capacity. If demand collapses, it can sell a general-purpose manufacturing facility for a fraction of its construction cost.

---

## Why Options Have Value: The Asymmetric Payoff

The key insight is the same one that underlies financial option pricing.

When you exercise an option, you exercise selectively. You exercise when conditions are good. You decline when conditions are bad. This selective exercise breaks the symmetry of the underlying uncertainty: you get the full upside of good scenarios, and you limit your downside by refusing to participate in bad ones.

The NPV formula, by contrast, averages across all scenarios — good and bad — before discounting. It has no mechanism for the manager to say "I would not invest in the bad scenario." Every scenario, good and bad, contributes to the expected cash flow that gets discounted.

When a firm has real flexibility, the NPV formula systematically understates the project's value because it charges the firm for bad scenarios it could actually avoid.

Let me put numbers on it for Plant 4.

Suppose that demand over the next six months resolves into one of two roughly equally likely states: strong demand, where the NPV of committing to Plant 4 at that point is $80 million, or weak demand, where the NPV of committing is −$10 million [these are illustrative; verify against actual regional demand data and plant economics].

If Halverson commits today, it commits regardless of which scenario materializes. The expected NPV — accounting for the time value of waiting six months, which reduces both numbers slightly — is roughly:

$$0.5 \times \$80\text{M} + 0.5 \times (-\$10\text{M}) = \$35\text{M}$$

If Halverson waits six months and decides based on the information that arrives, it commits only in the strong-demand scenario:

$$0.5 \times \$80\text{M} + 0.5 \times \$0 = \$40\text{M}$$

The $0 in the second term reflects the firm declining to invest in the weak-demand scenario. It does not lose $10 million — it simply does not commit the capital.

The difference between $40 million and $35 million is the **option value**: $5 million. That is what the deferral flexibility is worth. The standard NPV calculation ignores it because the standard NPV formula has no mechanism for the manager to act on the six-month information.

This is not a small rounding issue. In decisions with high underlying uncertainty — new geographies, new technologies, new product lines — option value can be the largest single component of the project's total value.

---

## How to Compute Option Value in Practice

Two approaches are standard.

The first is the **decision tree**. Map out the scenarios, the probabilities, and the decisions available at each node. Starting from the far right — the final payoffs — work backwards, computing expected value at each decision node and probability-weighted expected value at each chance node.

For Plant 4, the decision tree has two stages: Commit now, or wait six months and decide. If you wait, two scenarios branch: strong demand or weak demand. At the strong-demand node, commit and receive the strong-demand NPV. At the weak-demand node, decline and receive zero. The present value of the tree, discounted back six months, gives you the NPV with optionality.

The decision tree is the right tool when the underlying uncertainty has a manageable number of discrete scenarios and the decision points are clear. Plant 4 fits this description. Regional demand data for the product arrives quarterly. The scenarios — strong, moderate, weak — are roughly identifiable. The decision to commit is a single trigger point, not a continuous process.

[FIGURE: Decision tree with two stages. Root node: "Today: Commit now or wait 6 months." Left branch: "Commit now, NPV = $25M (risk-adjusted)." Right branch: "Wait 6 months" — splits into two chance nodes. Upper: "Strong demand (p = 0.5), NPV if commit = $80M → Commit, NPV = $80M." Lower: "Weak demand (p = 0.5), NPV if commit = −$10M → Do not commit, NPV = $0." Expected value of "Wait" branch after discounting six months ≈ $40M. Option value = $40M − $35M = $5M. Note what the diagram should show: the "Do not commit" branch at the weak-demand node explicitly captures that managers choose not to participate in bad scenarios.]

The second approach adapts **financial option pricing models** — Black-Scholes or binomial trees — to real assets, treating the project value as the underlying asset and the investment cost as the strike price. This approach is mathematically elegant and is sometimes the right tool when the underlying uncertainty evolves continuously rather than in discrete jumps. It is harder to apply in practice because the lognormal-diffusion assumption underlying Black-Scholes fits financial asset prices better than it fits industrial demand cycles. For most capital project decisions, the decision tree is both more transparent and more honest about the actual nature of the uncertainty.

---

## How the Two Corrections Interact

Now I can address the observation that opens this chapter. The risk-adjustment makes the NPV smaller. The real options adjustment makes it larger. Do they cancel?

They do not cancel, and understanding why they don't requires seeing that they correct different kinds of errors.

The risk-adjustment corrects a *valuation error*. The expected future cash flows from Plant 4 are being discounted at a rate that does not reflect how risky those cash flows are. Making the discount rate higher does not change what the cash flows are — it changes what they are worth today. The project is being overpriced; the correction re-prices it correctly.

The real options adjustment corrects a *strategy error*. The standard NPV computes the expected value of a strategy — "commit today, irrevocably" — that is not the strategy Halverson will actually follow. The firm will follow a contingent strategy: commit if conditions look favorable, defer or abandon if they don't. That contingent strategy has higher expected value than the irrevocable commitment, because it excludes bad-scenario capital commitments. The correction replaces the wrong strategy with the right one.

These are genuinely different corrections. One fixes the price; the other fixes the plan.

For Plant 4, the combined picture:

| Analysis | NPV |
|---|---:|
| Firm WACC (8%), no optionality — Maya's original | $42M |
| Project WACC (9%), no optionality | $25M |
| Project WACC (9%), with deferral option | ~$30M |

The risk adjustment costs $17 million of apparent NPV. The real option recovers about $5 million. Net effect: the defensible NPV is roughly $30 million, not $42 million.

Still positive. The project is still worth doing. But notice something more important: the *recommendation* has changed in structure, not just in number.

A recommendation grounded in the $42 million NPV says: approve the $50 million commitment today.

A recommendation grounded in the $30 million NPV with deferral option says: approve up to $50 million, but preserve the right to defer the final commitment by up to six months pending Q2 regional demand indicators. The option has value precisely because committing before those indicators arrive throws away information that would be available cheaply.

The real options analysis does not just change a number. It changes what the board is being asked to decide.

---

## The Honest Limits

I want to flag two places where this framework requires more judgment than the mathematics suggests.

**The probabilities are judgment calls.** The 50/50 split between strong and weak demand in the decision tree is a placeholder. I chose it to make the arithmetic clean. In practice, eliciting these probabilities from operating managers is genuinely difficult. They anchor on whatever number sounds reasonable in a conference room. They do not come to meetings with calibrated probability distributions for regional industrial demand. The discipline of building a decision tree is valuable regardless — it forces explicit commitment to a structure of uncertainty that can be stress-tested. But the specific numbers going into the tree deserve as much scrutiny as the discount rate assumptions.

**The pure-play betas are an approximation.** The comparable firms I described earlier are not identical to Plant 4. They have different capital structures, different product mixes, different vintage points in the economic cycle. The asset betas I back out from them contain noise. The resulting project WACC of 9% should be thought of as "probably between 8.5% and 10%" rather than precisely 9%. The right response is to present a range — project NPV at 8.5%, 9%, 9.5% — so the board can see how sensitive the recommendation is to the rate assumption.

Both of these limits point toward the same meta-point: the value of the risk-adjustment and the real options analysis is not that they produce precise numbers. It is that they force the right questions. Is this project actually riskier than our average? How much of the project's value depends on our ability to learn before committing? These questions improve the decision even when the quantitative answers are approximate.

---

## What Would Change My Mind

The chapter's enthusiasm for real options rests on the claim that they genuinely improve capital allocation decisions when applied. The empirical evidence is suggestive but complicated [verify — Triantis & Borison surveys of real options practice]. Firms that explicitly value real options do not consistently outperform firms that use simpler NPV-based approaches, at least not in ways that survive controls for other capital allocation quality differences. The optimistic interpretation is that real options are good but rarely used correctly. The pessimistic interpretation is that the framework adds analytical complexity without adding decision quality.

I find the pessimistic interpretation plausible in the specific case where the probability estimates are arbitrary and the decision tree becomes a tool for rationalizing a conclusion already reached. If the decision tree's probabilities are chosen to make the option value whatever the sponsor wants it to be, the real options analysis is not discipline — it is decoration.

The framework is worth taking seriously precisely because it identifies real flexibility that standard NPV ignores. The discipline is to take the probability estimation as seriously as the discounting, not to treat it as a free parameter.

---

## Still Puzzling

The two problems corrected here — wrong discount rate and no flexibility — both make the NPV analysis more accurate. But there is a third problem with NPV analysis that this chapter does not solve: the cash flow forecasts themselves.

The $42 million NPV depends on a revenue forecast for Plant 4 that is built on assumptions about regional demand, market share, pricing, and competitive response — all of which are uncertain, all of which were estimated by the same operating managers who proposed the project. There is a well-documented pattern in capital budgeting research [verify — Kahneman on reference class forecasting; Lovallo & Kahneman on the planning fallacy] where project proponents systematically overestimate revenues and underestimate costs, producing NPVs that are optimistic relative to eventual outcomes.

The risk-adjusted discount rate partially addresses this: a higher rate penalizes cash flows that are far in the future, which is where the optimistic forecasts tend to be largest. But it does not address the optimism in the forecast itself.

I do not have a clean solution to this. The best practice I know — which involves comparing the project's assumptions to the base rate of actual outcomes from similar projects at this firm and at comparable firms — is not a formula. It is a discipline that requires the CFO to push back on operating managers who are emotionally committed to seeing their projects approved.

The discount rate can be corrected with math. The forecast bias requires a different kind of honesty.

---

**Coming up.** Chapters 4 through 6 have treated capital budgeting as a single-firm problem — Halverson deciding in isolation whether to build Plant 4. Chapter 7 zooms out: how does the firm choose between Plant 4 and the other capital requests competing for the same pool of funds? This is the capital rationing problem, and it requires a framework for ranking projects that have different sizes, different durations, and different risk profiles.
