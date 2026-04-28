# Chapter 13 — International Corporate Finance

---

There is a temptation, when first encountering international finance, to treat it as a fundamentally different subject from what came before — a separate discipline with its own rules, its own logic, its own vocabulary of forwards and swaps and country risk premiums. The implication is that everything we built in the previous twelve chapters needs to be replaced.

It does not. International corporate finance is corporate finance with additional dimensions. The cash flows are still cash flows. The discount rate still reflects risk. NPV is still the right criterion for investment decisions. Capital structure still trades off tax benefits against distress costs. The framework holds. What changes is that some quantities you previously took as given — a single currency, a single tax regime, a stable regulatory environment — are now variables that require explicit treatment.

There are five new dimensions. Two of them are genuinely analytically different from anything in domestic finance. The other three are mostly administrative complexity layered on top of the same underlying logic. Knowing which is which is most of the practical value of this chapter.

---

## The Five Dimensions

Let me name them first, then work through each carefully.

**Currency.** Cash flows denominated in different currencies. Exchange rate movements change the dollar value of foreign earnings. This is analytically real — the mechanism is not obvious, and getting it wrong produces nonsense numbers.

**Country risk.** Political stability, regulatory regime, contract enforcement, capital controls, expropriation risk. Operating in the UK is low country-risk. Operating in some emerging markets is first-order risk that restructures the analysis.

**Tax.** Different jurisdictions have different rates, different rules, different definitions of taxable income. The interaction of the home country's rules with the host country's rules creates planning opportunities and compliance burdens.

**Transfer pricing.** When a US parent sells goods or services to a foreign subsidiary, the price set on that internal transaction determines how income gets allocated across jurisdictions for tax purposes. Tax authorities on both sides scrutinize it.

**Repatriation friction.** Cash earned abroad cannot always be moved back to the parent costlessly. Withholding taxes, capital controls, and home-country tax on repatriated dividends all create drag.

For Halverson Manufacturing, all five are live. The UK subsidiary, Halverson Flow Control Ltd., generates roughly £80 million of revenue annually from a facility outside Manchester. It was acquired in 2014 for £45 million and has paid for itself in cumulative repatriated cash flows. It currently holds £25 million of cash that has not been sent back to the parent, partly because UK-to-US tax planning became complicated after the 2017 US tax reform, and partly because nobody needed the money urgently enough to deal with it.

Diane now wants Maya to evaluate repatriating the £25 million to help fund the Cardinal acquisition, and to frame a broader recommendation on Halverson's international financial structure.

This chapter is the framework behind that analysis.

---

## Currency: Three Different Problems

FX exposure is not one thing. It is three distinct problems that require different analytical tools and different management responses. Conflating them is a persistent source of confusion.

**Transaction exposure** is the simplest. A specific future cash flow, denominated in a foreign currency, with a known amount and a known settlement date. Halverson UK signs a contract today for £10 million of revenue payable in 90 days. The dollar value of that £10 million will depend on the GBP/USD rate in 90 days. If the pound is at 1.28, Halverson receives $12.8 million. If the pound has fallen to 1.20, it receives $12.0 million. The $800,000 difference is pure FX risk on a transaction that has nothing to do with the underlying business quality.

Transaction exposure is manageable. The firm knows the amount and the date. It can sell pounds forward — agree today to exchange the £10 million for dollars at a fixed rate on the settlement date — and lock in the dollar value of the receivable. The forward contract eliminates the FX risk at a cost roughly equal to the interest rate differential between the two currencies, which is usually small. Halverson hedges its transaction exposure on a rolling 12-month horizon. This is standard treasury practice for a firm with meaningful foreign currency receivables and payables.

**Translation exposure** is different and, I will argue, less important than it sounds. When Halverson consolidates its UK subsidiary's financial statements into the parent's annual report, it has to convert pound figures into dollar figures. The earnings conversion uses average exchange rates for the period. The balance sheet conversion uses the rate at period-end. If the pound weakens during the year, the UK subsidiary's earnings translate into fewer dollars, and the reported consolidated earnings per share falls — even if the underlying UK business performed exactly as expected in local currency terms.

This is real for reported financials. It affects how analysts read the income statement. It can affect the stock price in the short run. But it is largely cosmetic for actual cash flows — the dollars Halverson can spend are not reduced by translation loss, because translation loss is an accounting artifact of currency conversion, not a cash event. Most CFOs do not hedge translation exposure because the hedge cost is real and the underlying economic exposure is not. Halverson does not hedge translation.

**Economic exposure** is the hardest to measure and can be the largest of the three. It is the long-run effect of persistent exchange rate movements on the firm's competitive position and underlying cash flow-generating capacity.

Here is the mechanism. Suppose the pound weakens persistently — by 15% over three years, not a quarterly fluctuation but a structural shift. In the short run, Halverson UK's translated earnings fall. But something else happens: the UK subsidiary's cost base, which is largely in pounds, becomes cheaper relative to its US-based competitors' cost bases, which are in dollars. Halverson UK becomes more competitive. It can price more aggressively against US firms selling into the UK market, or it can export to the US at attractive prices, or it can maintain margins and grow market share. The underlying business becomes more valuable even as the translated earnings look worse.

Economic exposure runs in the opposite direction when the pound strengthens. Halverson UK's costs rise relative to US competitors. Competitive pressure intensifies.

Managing economic exposure requires operational decisions, not financial hedging. Where the firm sources its inputs, where it manufactures, where it denominates its invoices — these choices determine how sensitive the underlying cash flows are to exchange rate movements. A firm that manufactures in the UK, sources inputs in the UK, and sells in the UK has low economic exposure to GBP/USD movements. A firm that manufactures in the US, sources inputs in the US, and sells in the UK has high economic exposure. The financial hedge can only address transaction flows; the operational structure determines the underlying exposure.

---

## Valuing Foreign Projects: The Mechanism

The NPV framework from Chapter 4 applies to cross-border projects. What changes is the discount rate and the currency in which cash flows are expressed. Getting these right matters more than it might seem, because the most common error in international project valuation produces numbers that are systematically wrong in a specific direction.

There are two equivalent approaches.

**Approach one**: project all cash flows in the foreign currency, discount at the foreign-currency cost of capital, convert the resulting NPV to home currency at today's spot exchange rate.

For the Mexico plant option from Chapter 6, this means projecting the peso cash flows, applying a peso discount rate, and converting the peso NPV to dollars. The peso discount rate is the firm's dollar WACC adjusted for the Mexico-US inflation differential and a country risk premium. Interest rate parity links the two: the expected peso depreciation is embedded in the interest rate differential, so a consistent peso discount rate and peso cash flow projection will give the same dollar NPV as the second approach.

**Approach two**: convert each year's foreign-currency cash flow to home currency using expected forward exchange rates, then discount the resulting dollar cash flow stream at the dollar cost of capital.

Project the peso cash flows. Convert each year to dollars using the forward rate for that year — observable in currency forward markets, or derivable from interest rate parity. Discount the dollar stream at Halverson's dollar WACC.

Both approaches give the same answer when executed consistently. The second is more common in practice because the forward rates are directly observable and the discount rate is the firm's familiar WACC.

The error that produces nonsense: **applying the dollar discount rate to unconverted foreign-currency cash flows**. This is wrong because the dollar WACC implicitly contains US inflation and US interest rate expectations. Applying it to peso cash flows — which embed Mexican inflation — is mixing incompatible units. The resulting NPV will be too low if Mexican inflation is high (the peso cash flows are nominally large but you are discounting them at a rate that does not account for their inflation content) or too high if you have failed to account for peso depreciation in the cash flow projection. I emphasize this because it is the most common analytical mistake in cross-border valuation, and it is easy to make without noticing.

[FIGURE: Side-by-side comparison of the two approaches for a Mexico plant. Approach 1: Peso cash flows → Peso discount rate (WACC + CRP) → Peso NPV → Convert at spot rate → Dollar NPV. Approach 2: Peso cash flows → Convert each year at forward rates → Dollar cash flows → Dollar WACC → Dollar NPV. Both paths converge to the same dollar NPV. A red arrow and label marks the error path: "Do not apply dollar WACC to unconverted peso cash flows." The figure should make visually clear that the two correct paths are parallel routes to the same destination, and the error path is a shortcut that mixes units.]

---

## Country Risk: Adding the Premium

When Halverson evaluates the Mexico plant, it faces business risk that its US operations do not face: the possibility of regulatory changes, FX controls, political instability, contract enforcement difficulties. These risks reduce the expected value of the project's cash flows and increase their variability. The discount rate needs to reflect them.

The standard approach is to add a **country risk premium** to the discount rate. Damodaran maintains a widely used time series of these premiums, derived from sovereign CDS spreads adjusted for the relative volatility of equity markets versus bond markets [verify — Damodaran country risk premium database]. Indicative current figures:

| Country | Country risk premium (approximate) |
|---|---:|
| United States | 0% (baseline) |
| United Kingdom | ~0.5% |
| Mexico | ~2.5% |
| Brazil | ~4.0% |
| Argentina | ~15% |

For the Mexico plant with a firm WACC of 8%, the CRP-adjusted discount rate is approximately 10.5%. This is broadly consistent with the 11.2% that emerged from the pure-play comparables analysis in Chapter 6 — the two approaches triangulate to the same range, which is reassuring.

The CRP approach is a shortcut. It bundles political risk, FX risk, and macroeconomic instability into one number. For a more rigorous analysis in a high-risk jurisdiction, decomposing the premium into components and pricing each one separately is better — but requires estimates that are themselves uncertain. The Damodaran shortcut is appropriate for project screening; the decomposed approach is appropriate for a final investment decision in a difficult jurisdiction.

For Halverson UK, the country risk premium is roughly 50 basis points — less than one rounding error in the firm's WACC. The UK analysis needs no meaningful adjustment for country risk. The Mexico analysis does.

---

## Tax: The Framework That Outlasts the Rules

I want to be direct about the limits of any specific tax discussion in a book. US international tax has been fundamentally restructured multiple times in the past decade. The 2017 Tax Cuts and Jobs Act introduced three new regimes governing foreign income — GILTI, BEAT, and FDII — that represent the largest change to international tax rules in a generation [verify current status of these provisions]. Treasury regulations and case law continue to evolve. Any specific tax rate or rule cited here may be outdated within months of publication.

What I can give you is the framework, which is more durable than the rules.

International tax planning for a US multinational addresses three questions.

**Where is income earned?** Transfer pricing — the price set on transactions between the US parent and its foreign subsidiaries — determines how taxable income is allocated across jurisdictions. Sell goods from the US parent to the UK subsidiary at a high price, and the income is recognized in the US. Sell at a low price, and the income is recognized in the UK. Each country's tax authority wants the price set such that more income lands in its jurisdiction. The arm's-length standard — set the transfer price as if the transaction were between unrelated parties — is the legal requirement, but applying it to unique intrafirm transactions is genuinely indeterminate. There is no single correct arm's-length price for most intrafirm services or IP licenses, just a defensible range.

**Where is income retained versus repatriated?** Income retained at the UK subsidiary is not immediately subject to US tax (subject to GILTI and other minimum tax rules [verify current rules]). Income repatriated to the US parent as a dividend triggers US tax on the dividend, with a credit for UK taxes already paid. The planning question is whether the marginal US tax on repatriation exceeds the investment return difference between keeping the cash in the UK and deploying it at the parent level.

For Halverson's £25 million: the UK subsidiary has already paid UK corporate tax on this income. Repatriation to the US triggers incremental US tax after applying foreign tax credits, which could be approximately 0–5% of the repatriated amount depending on Halverson's overall foreign tax credit position [verify with actual tax position — this is highly fact-dependent]. At a spot rate of roughly 1.27, £25 million is approximately $31 million. After estimated incremental US tax, the parent receives approximately $29–31 million.

**What entity structure minimizes the combined tax burden?** Holding companies in low-tax jurisdictions, hybrid entities, intercompany financing arrangements — these are the tools of tax structuring. They must satisfy substance-over-form requirements in each jurisdiction (operations must be genuinely located where the income is claimed to be earned) and must withstand scrutiny from both countries' tax authorities. This is the domain of international tax specialists. The corporate finance function's job is to understand the cash flow implications of the tax structure, not to design it.

---

## The Repatriation Decision

For Halverson, the repatriation question reduces to a comparison between two uses of £25 million.

**If it stays in the UK**: the cash earns returns appropriate for UK cash management — roughly UK short-term interest rates, currently modest [verify current UK rates]. The capital remains available for potential UK reinvestment, but there are no identified UK opportunities of comparable attractiveness to Cardinal.

**If it is repatriated to fund Cardinal**: the cash earns whatever return Cardinal generates on invested capital, less the incremental US tax on the dividend. Cardinal's projected IRR [cross-reference Cardinal analysis chapter] exceeds the UK cash return by a substantial margin. The net economic case for repatriation is positive if Cardinal's return exceeds the UK cash return by more than the incremental tax cost — which, at the 0–5% tax estimate, is a low bar.

The recommendation: **repatriate the £25 million now**. The funding need is real. The incremental US tax cost is modest. The opportunity cost of keeping the cash in UK cash management is significant. Document the tax position carefully to support any future audit challenge on the foreign tax credits.

This illustrates the broader principle: repatriation decisions are not tax decisions. They are capital allocation decisions with a tax overlay. The question is always whether the internal return on the capital is higher inside the foreign subsidiary or at the parent level. When the parent has an identified high-return use, the answer is almost always to repatriate.

---

## When International Is Just Domestic With Extra Steps

There is a useful diagnostic question worth asking about any cross-border analysis: is the international layer adding genuinely new financial considerations, or is it adding compliance and administrative burden on top of the same underlying logic?

For Halverson UK — a UK firm doing the same kind of business as the US parent, in a stable legal jurisdiction, with transparent accounting standards and efficient capital markets — the honest answer is: mostly the latter. The capital budgeting decisions follow domestic logic with currency and tax overlays. The capital structure question is the same trade-off analysis from Chapter 8, with a higher effective tax rate. The payout decision is the same cash deployment question, with repatriation friction added.

For a hypothetical Halverson operation in an emerging market with an unstable regulatory regime, a weakly enforced contract law system, and a history of capital controls — the honest answer is the former. The international complexity becomes first-order. The capital budgeting model needs fundamentally different inputs. The capital structure may require host-country financing to reduce expropriation exposure. The repatriation strategy may need to be built into the project design from day one, because getting money out may be the hardest part of the whole investment.

The diagnostic matters because treating first-category problems as if they are second-category wastes time and adds false precision. Treating second-category problems as if they are first-category is how firms lose money they did not expect to lose.

Halverson UK is first-category. A Mexico plant would be closer to the boundary — not the full complexity of an unstable emerging market, but enough genuine first-category risk (currency, political, regulatory) that the analysis cannot be domestic-plus-tax-overlay.

---

## What Would Change My Mind

The chapter's CRP shortcut — adding Damodaran's country risk premium to the discount rate — is widely used and academically contested. The concern is that the CRP bundles together risks that have different pricing implications. Political risk, for instance, is largely diversifiable for an investor with a globally diversified portfolio; if so, it should not enter the discount rate (systematic risk only should be priced). The Damodaran approach includes political risk regardless of whether it is diversifiable, which may overstate the cost of capital for cross-border projects in politically unstable jurisdictions [verify — Bekaert and Harvey on emerging market cost of capital; the diversifiability question is empirically contested].

If the Bekaert-Harvey critique is correct and the CRP approach overstates the cost of capital for emerging-market projects, the chapter's conclusion that Mexico requires roughly 250 basis points of additional discount rate would be too pessimistic — the true CRP might be closer to 100–150 basis points. This would shift the NPV of the Mexico plant option upward, potentially materially.

I find this debate genuinely open. The practitioner consensus uses CRP adjustments because they produce defensible numbers and because clients and boards understand "Mexico is riskier, add 250 basis points" more readily than "Mexico's political risk is diversifiable, so the theoretical adjustment is smaller." Defensibility and theoretical correctness are not always the same.

---

## Still Puzzling

The transfer pricing problem has no clean theoretical resolution, and I want to be honest about this rather than presenting the arm's-length standard as if it solves the problem it claims to solve.

When a US parent licenses proprietary technology to a UK subsidiary — technology that was developed jointly, that has no external market price, and that the subsidiary needs to compete — there is no natural arm's-length transaction to reference. The "correct" royalty rate is whatever produces the desired income allocation between jurisdictions, dressed up in a comparables analysis. Both tax authorities know this. Both challenge the analysis when the allocation is not in their favor. The resulting compliance burden is real, the audit risk is real, and the outcome is largely a function of the negotiating leverage between the multinational and the respective tax authorities.

This is not a solvable technical problem. It is a political economy problem inside the firm's financial structure. The chapter's presentation of transfer pricing as a compliance issue with a technical answer — the arm's-length standard — understates the genuine indeterminacy at the core of it. A CFO who expects to find the right transfer price through financial analysis will be disappointed. The right transfer price is the one that survives audit challenge, which depends on documentation quality, the tax authorities' current enforcement priorities, and, sometimes, the firm's overall relationship with the revenue authorities in each jurisdiction.

---

**Coming up.** Chapter 14 takes up the integration of the financial strategy across all of Halverson's decisions — domestic and international — into a coherent CFO agenda for the next planning cycle. The chapter-by-chapter analysis is done. What remains is asking how the pieces fit together into a strategy that the board can hold in one frame.
