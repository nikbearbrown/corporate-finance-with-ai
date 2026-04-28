# Chapter 5 — The Cost of Capital and the WACC


Maya, drafting her cover note for Diane on Friday morning, types: *"The project's NPV at the firm WACC of 8% is positive."* She stops. Where did 8% come from?

The footnote in the operations team's spreadsheet cites it as "the firm WACC, per the FP&A team's most recent update." She walks down to FP&A. The lead analyst there, Priya, opens a worksheet titled "WACC FY26 Q1." It uses a 5.2% pretax cost of debt, a 9.8% cost of equity derived from CAPM with a beta of 1.1, a 4.2% risk-free rate, and a 5.0% market risk premium; a target debt-to-capital weight of 30%; and a marginal tax rate of 24%. The blended number rounds to 8.0%.

Each of those inputs is a choice. None of them is obviously wrong. Several could plausibly be defended as different numbers. If the cost of equity were 11% instead of 9.8%, the WACC would round to 8.6% instead of 8.0%, and Plant 4's NPV would drop by something like 15%. The decision Maya is about to recommend turns on numbers Priya updated last quarter and nobody has questioned since.

This chapter is about what those numbers mean, where the judgment lives, and why the formula is both essential and surprisingly easy to get wrong.

---

Before we work through the inputs, I want to say something about what "cost of capital" actually means, because the phrase does three different jobs and the three are easy to blur.

The first meaning is a rate of return that capital providers expect. When equity holders give Halverson their money, they expect to earn some return — through dividends, share appreciation, or both — that compensates them for the risk of holding Halverson's stock. That expected return is, from Halverson's perspective, the cost of using their money. The same logic applies to bondholders: they lend at 5.2% because that is the rate they require for Halverson's credit risk. The cost of capital is what the providers require.

The second meaning is a hurdle rate the firm uses for investment decisions. When evaluating Plant 4, the firm needs a discount rate. That discount rate has to be at least as high as the cost of capital, or the project does not generate enough return to satisfy the providers. So the cost of capital is the threshold a project must clear.

The third meaning is the weighted average of debt and equity costs. Most firms use both, in proportions reflecting their capital structure. The weighted average of these two costs, adjusted for the tax deductibility of interest, is the WACC.

In the textbook treatment, all three meanings collapse into one: the WACC is the hurdle rate, and the hurdle rate equals what providers require. In practice they can drift apart. A firm whose stated WACC is 8% but whose investors actually require 11% is systematically mispricing its investments — taking on projects that destroy value while believing it is creating it. The CFO's job is to keep the three aligned. You cannot do that if you treat the WACC as a number someone else computes and puts in a footnote.

---

The formula is:

$$\text{WACC} = \frac{E}{V} \cdot R_e + \frac{D}{V} \cdot R_d \cdot (1 - T)$$

where $E$ is the market value of equity, $D$ is the market value of debt, $V = E + D$ is total firm value, $R_e$ is the cost of equity, $R_d$ is the pretax cost of debt, and $T$ is the marginal corporate tax rate. Six inputs. Let me take them in order of how much judgment each one requires.

**Market values, not book values.** The formula calls for the market values of $E$ and $D$, not the book values from the balance sheet. For equity this is unambiguous: shares outstanding times current price. The book value of equity reflects accumulated retained earnings and historical accounting choices; it is almost never the right denominator for a WACC calculation.

For debt, the market value differs from the book value when interest rates have moved since the bonds were issued. Halverson issued $300M of bonds at 5% in 2021. If current market rates for similarly rated debt are 5.2%, those bonds trade at a slight discount — their market value is below $300M. The difference is small for investment-grade debt with modest rate moves and large for distressed debt or significant rate shifts. The discipline is simple: use market values when available, and document clearly when you substitute book values.

**The cost of debt.** This is the easiest input. Halverson's existing bonds trade at some yield-to-maturity in the market. That yield is the market's current required return on Halverson's credit risk. Look it up. Two refinements: use the yield on *new* debt at Halverson's risk profile, not the coupon on old debt issued under different conditions. And multiply by $(1 - T)$ to capture the tax shield — every dollar of interest reduces taxable income by one dollar, saving the firm $T$ cents in taxes. At a 24% marginal rate, a pretax cost of debt of 5.2% becomes an after-tax cost of 4.0%.

The tax adjustment is one of the genuinely mechanical parts of the formula. Congress decided that interest payments are deductible and equity dividends are not. The WACC captures that asymmetry by measuring debt's cost on an after-tax basis. This is the correct treatment, but it means WACC depends on the tax code, and any change in the marginal corporate rate changes WACC even if the underlying business does not change at all.

**The weights.** The formula calls for $E/V$ and $D/V$, but there is a question underneath that: which capital structure? Today's, or the one the firm is moving toward?

The conventional answer is target weights — the proportions the firm intends to maintain over the long run — on the theory that capital budgeting is a long-horizon exercise and the current structure is just a snapshot along the way. If Halverson is currently running at 25% debt but targets 30%, using target weights produces a lower WACC (more weight on cheaper after-tax debt). Whether this is right depends on how credible the target is, and credibility requires judgment.

The subtler point is that the weights should match the project, not just the firm. If Plant 4 will be financed differently from Halverson's average project — say, with project finance debt secured against the plant itself — then the appropriate WACC for Plant 4 uses the plant's own financing mix, not the firm average. Using the firm-average WACC for a project with above-average debt capacity understates the benefit of the tax shield; using it for a project with below-average debt capacity overstates it. The formula is right. The question is which capital structure to plug in.

---

Now to the input that carries the most uncertainty, and where the most judgment is concentrated: the cost of equity.

There is no yield-to-maturity for equity. Equity has no contractual cash flows, no maturity date, no promised return. The cost of equity is not observed; it is inferred. The standard tool for the inference is the Capital Asset Pricing Model:

$$R_e = R_f + \beta \cdot (R_m - R_f)$$

where $R_f$ is the risk-free rate, $\beta$ is the firm's systematic risk — its sensitivity to market-wide movements — and $(R_m - R_f)$ is the equity risk premium, the extra return the market as a whole is expected to earn above the risk-free rate. Three inputs, each with its own source of uncertainty.

**The risk-free rate.** The standard proxy is the yield on US Treasury securities — there is no credit risk and, in normal conditions, no liquidity risk, so the yield represents pure time value of money. The question is which maturity. Short-term Treasury bills yield one thing; 10-year Treasury notes yield something higher; 30-year bonds yield something higher still. The term spread between short and long rates has historically been 50 to 100 basis points, and that flows directly into the WACC.

The right answer is to match the project's horizon. For a three-month working capital decision, use the three-month rate. For Plant 4, with a 25-year asset life, the 10-year or 30-year rate is appropriate. Priya used 4.2% — presumably a current 10-year Treasury yield — which is reasonable for a long-horizon capital project.

**Beta.** Halverson's beta of 1.1 came from a regression of weekly stock returns against the S&P 500, probably over the past two years. That regression produces a number with a standard error. The true beta — the parameter that governs the relationship between Halverson's returns and market returns going forward — is unobservable. Different lookback windows produce different estimates. Different benchmark indices produce different estimates. Bloomberg and Yahoo Finance often report different betas for the same firm because they use different regression specifications.

A beta of 1.1 for Halverson means that historically, when the market moved 1%, Halverson moved about 1.1% in the same direction. A beta of 1.0 is average market risk. A beta below 1.0 is below-average risk. A beta above 1.0 means the stock amplifies market movements.

The standard error on a two-year weekly regression is roughly 0.15 to 0.25. So Halverson's beta of 1.1 is better described as a point estimate within a range of approximately 0.9 to 1.3 — and each point in that range produces a different cost of equity. The precision of "beta = 1.1" is illusory.

**The equity risk premium.** This is the most contested input in corporate finance. The equity risk premium — how much extra return equity investors require above the risk-free rate, as compensation for the additional risk of owning stocks — has been debated for decades, and there is no settled answer.

Historical estimates, computed from realized stock and bond returns over different time periods, range from roughly 4% to 7% depending on how far back you go, whether you use arithmetic or geometric averaging, and which markets you include. The academic literature has a name for the observation that historical equity returns have been surprisingly high relative to bond returns: the equity premium puzzle. The puzzle is that the historical premium implies a degree of risk aversion among investors that is hard to reconcile with observed behavior.

Forward-looking estimates — derived by working backward from current market prices to the implied expected return — tend to come in lower, around 4% to 5% in current conditions [verify against Damodaran's most recent implied ERP estimate]. CFO surveys have historically reported numbers in a similar range [verify Graham and Harvey]. Priya used 5.0%, which is a defensible choice — squarely in the middle of the reasonable range.

But notice what this means for the WACC. The equity risk premium has a defensible range of perhaps 4.5% to 6.0%. At the low end, Re = 4.2% + 1.1 × 4.5% = 9.15%. At the high end, Re = 4.2% + 1.1 × 6.0% = 10.8%. Combine this with the uncertainty in beta (say, 1.0 to 1.3) and the range widens further. The WACC formula looks precise — it produces a number like 8.0% — but the number is sitting atop inputs that could move it by 100 to 150 basis points in either direction without anyone making a clearly wrong choice.

---

Put it all together for Halverson. With Priya's inputs:

$$R_e = 4.2\% + 1.1 \times 5.0\% = 9.7\%$$

Round to 9.8%. Pretax cost of debt 5.2%, after-tax 4.0%. Target weights 70% equity, 30% debt:

$$\text{WACC} = 0.70 \times 9.8\% + 0.30 \times 4.0\% = 6.86\% + 1.20\% = 8.06\%$$

Rounds to 8.0%. The formula is not hard to compute once the inputs are specified. The work is in the inputs.

Now run a sensitivity. Suppose beta is 1.3 instead of 1.1 — within the standard error of most estimates. Then Re = 4.2% + 1.3 × 5.0% = 10.7%. Suppose the equity risk premium is 6.0% instead of 5.0% — equally defensible. Then Re = 4.2% + 1.3 × 6.0% = 12.0%. With those inputs and the same debt and weights:

$$\text{WACC} = 0.70 \times 12.0\% + 0.30 \times 4.0\% = 8.40\% + 1.20\% = 9.60\%$$

Plant 4's NPV at 9.6% is substantially lower than at 8.0%. Whether it is still positive depends on the project's cash flows, but the decision can flip. Maya is about to recommend approval of a major capital project on the basis of an NPV that is sensitive, in an unknown way, to inputs nobody has revisited since last quarter.

This is not a failure of analysis. It is the correct picture of the uncertainty. The failure would be to pretend the picture is sharper than it is.

---

There is one more thing to say about the WACC before closing, and it concerns when the firm WACC is the wrong discount rate even if it is computed correctly.

The WACC is the right discount rate for a project when the project has the same risk profile as the firm average. Halverson's WACC of 8% reflects the risk of Halverson's existing portfolio of assets — its mix of products, geographies, and operating characteristics. If Plant 4 looks like the average Halverson project, use 8%. If it does not, you need a different number.

The question of whether it does is an operational one, not a financial one. A new plant producing existing products in an existing market is probably close to the firm average. A new plant in an unfamiliar geography, or producing a product Halverson has never made, carries additional risk that should be reflected in the discount rate. How much additional? Estimate beta from comparable companies or comparable projects in that market, plug into CAPM with that beta, compute a project-specific Re, and build a project-specific WACC.

Operations teams almost never do this. The FP&A spreadsheet has one WACC for all projects. Maya's job, on this particular memo, is to check: does Plant 4 look like a typical Halverson investment? If so, 8% is the right number. If it represents a departure — new geography, new product line, different operating leverage — the right rate is probably higher, and the NPV that looks positive at 8% should be stress-tested at 10% or 12% before the recommendation goes to Diane.

The operations team's footnote does not specify which case applies. This is Maya's flag for the memo.

---

The WACC is mechanical to compute and conceptually fragile. Six inputs, three of them judgment calls, and the output drives every capital budgeting decision the firm makes. A CFO who treats it as a settled number has quietly handed capital allocation authority to the analyst who last updated the spreadsheet.

The defensible move is the one Maya is learning to make for every analytical claim in this book: state the assumption set explicitly, document the range of plausible inputs, run the sensitivities, and name what would change the decision. Not because the formula is hard — it is not — but because the inputs to the formula are softer than the formula's precision implies.

8.0% is a number. The question it answers — what rate of return does Halverson need to earn to keep its capital providers satisfied, on the margin, for this class of investment — is a question with a real answer that the formula approximates. The approximation is useful. Taking it for the answer is where the trouble starts.

---

*A note on what the chapter simplified.* The CAPM is the standard approach to cost of equity but not the only one. Multifactor models (Fama-French three-factor, Carhart four-factor) incorporate additional risk premia for size, value, and momentum, and produce systematically different Re estimates. The CAPM is also a single-period model being applied to a multi-period problem; strictly, the discount rate should vary by period if the risk-free rate or risk premium changes over time. And the WACC assumes the capital structure — and therefore the tax shield — remains constant over the project's life, which is an approximation for any project with scheduled debt repayment. These refinements matter less for most capital budgeting decisions than getting the right beta and ERP range. But they matter, and Chapter 9 will return to them.*
