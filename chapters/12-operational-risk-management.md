
# Chapter 12 — Operational Risk Management


The trader on the phone is from one of Halverson's banking relationships. He is offering a swap that would convert Halverson's floating-rate borrowings into a fixed rate for the next three years. The pitch is sensible-sounding: with the Fed possibly raising rates again, locking in now protects Halverson from interest expense surprises. The cost of the swap, embedded in the rate Halverson would pay, is about 25 basis points above the current floating rate.

Tom, the treasurer, listens and says he'll think about it. He hangs up and looks at Maya, who has been sitting in for educational purposes: "That's the third call this month. Every time the Fed has a meeting, the swap traders come out of their offices. The question is not whether we *can* hedge. The question is whether we *should*."

This chapter is about the framework for the should question.

---

Before we work through Halverson's specific exposures, I want to establish a baseline that surprises most people when they first encounter it. In a frictionless world — no taxes, no distress costs, no information asymmetries — corporate hedging does not create value. It is irrelevant.

The reasoning is the same as Modigliani-Miller on capital structure, which we covered in Chapter 7. If a shareholder wants a hedged exposure to interest rates or foreign exchange or commodity prices, they can hedge it themselves in their own brokerage account. They do not need the firm to do it for them. The firm's hedging just moves the hedge from the corporate balance sheet to the individual portfolio without changing the total economic exposure. No value is created; the hedge is redundant.

This is the textbook irrelevance result. It sounds like an argument against hedging entirely, but it is not. It is an argument about what hedging cannot do — it cannot create value through mere risk-shifting in a perfect world — which sets up the more interesting question: in what ways is the real world imperfect, and do those imperfections make hedging valuable?

Three imperfections matter.

---

The first is distress costs. A firm with significant leverage faces a nonlinear cost function: above some threshold of financial strain, distress becomes likely, and distress is expensive — legal fees, management distraction, lost customers who don't want to be serviced by a troubled supplier, employees who leave, counterparties who demand more favorable terms. The cost of distress is not proportional to how deep into distress you go; it kicks in hard when the threshold is crossed.

Hedging reduces the probability of crossing that threshold by smoothing cash flows. If interest rates spike and Halverson has $700 million of floating-rate debt, the cash flow hit is large enough to force difficult decisions — cutting capex, drawing down the revolver, potentially triggering covenant conversations. A swap that converts that debt to fixed rates eliminates the rate spike as a source of cash flow surprise. The probability of financial distress goes down, and so does its expected cost.

For a firm with a fortress balance sheet and low leverage, this argument is weak. The probability of distress is low with or without the hedge, so the reduction from hedging is small. For a firm operating close to its leverage limit, the argument is strong. Halverson is in the middle — healthy balance sheet, but about to take on more debt for Plant 4 and the Cardinal acquisition. The distress argument supports hedging, on the margin.

The second imperfection is tax convexity. The corporate tax code is not linear. A firm that earns $200 million one year and nothing the next pays more in total taxes than a firm that earns $100 million each year, even though cumulative pre-tax income is the same. The reason is that the first firm pays full rate on the $200 million; the second firm averages across two years of $100 million, and various deductions and bracket effects make the average rate lower. Smoothing income through hedging reduces the tax burden.

The magnitude of this effect depends on the firm's income volatility and the specifics of the tax code. Smith and Stulz formalized this argument [verify]. For Halverson with relatively stable income, the tax convexity benefit is modest. For a highly cyclical firm, it can be material. This is not the primary reason Halverson should hedge, but it is a real effect.

The third imperfection is the most important for Halverson's current situation, and it is about investment. A firm that depends on internal cash flow to fund value-creating projects faces a painful dynamic when cash flow is volatile. In a bad year — commodity prices spike, a currency moves against you, rates rise — internal cash flow falls short of the capex budget. The firm cuts capital investment. The foregone projects represent real value destruction: not cash out the door, but positive-NPV investments that don't happen because the firm couldn't fund them.

External financing could fill the gap, but external financing is expensive. Chapter 10 established this: equity issuance runs 5 to 6% of proceeds in total cost, and even debt issuance requires favorable market conditions and consumes debt capacity. A firm that could have funded a $50 million expansion from internal cash may be unable or unwilling to fund it externally when cash flow disappoints.

Hedging stabilizes internal cash flow, ensuring the firm can fund its capex program consistently regardless of what happens to interest rates, exchange rates, or commodity prices in any given year. Froot, Scharfstein, and Stein formalized this argument [verify]. For Halverson, with an active capex program — Plant 4 construction, Cardinal integration, ongoing maintenance — this argument is the strongest of the three. Halverson's value comes from deploying capital into productive assets. Anything that interrupts that deployment destroys value. Hedging protects the pipeline.

---

Now the cost side, because hedging is not free and the decision is always about whether the value exceeds the cost.

The direct cost is the bid-ask spread on the hedging instrument: 5 to 25 basis points depending on the instrument, counterparty, and transaction size. For the interest rate swaps Tom is considering, the swap trader quoted 25 basis points over the current floating rate. On $700 million of exposure, fully hedged, that is roughly $1.75 million per year. Real money but manageable.

The less visible cost is foregone upside. A hedge against rising commodity prices means giving up the gain if commodity prices fall. If Halverson hedges its steel input at current prices and steel falls 20% next year, Halverson's unhedged competitors gain a cost advantage that Halverson does not capture. The hedge bought protection from the bad scenario at the price of participation in the good one. This is not a criticism of the hedge — it is the nature of insurance — but it is a real cost that has to be weighed against the probability and magnitude of the adverse scenario.

There is also what I would call the hedger's regret problem, and it operates on the people making the decision rather than on the economics of the hedge itself. When a hedge works — rates rise and Halverson's fixed-rate swap pays off — the board and management praise the foresight. When a hedge loses money because rates fell and the unhedged exposure would have been cheaper — the board and management ask why Halverson was paying up for something that wasn't needed. This asymmetric accountability creates pressure to hedge less than is economically optimal, because the downside of a hedge that turns out to be unnecessary is more visible than the downside of a cash flow surprise that could have been avoided.

Tom knows about this problem. One of the reasons he listens politely to swap traders and says he'll think about it is that he is building the decision record before the fact — so that whatever happens to rates after the hedge is placed, he can point to the analysis that supported the decision. The hedge is not a bet on rates. It is risk management. The record matters.

---

With that framework in place, let me go through Halverson's actual exposures.

**Interest rate risk.** Halverson currently has $300 million of floating-rate debt tied to SOFR. A 1-percentage-point rise in rates increases annual interest expense by roughly $3 million [verify with current debt structure]. After the Plant 4 financing and the Cardinal acquisition close, total floating exposure could reach $700 million — $7 million of annual interest expense sensitivity per percentage point of rate movement.

This is material. Halverson's operating income is roughly $180 million [verify]. A 2-percentage-point rate rise on $700 million of floating debt is $14 million of additional interest expense, about 8% of operating income. That is enough to affect the firm's ability to fund its capex program in the year it hits.

The recommendation is to convert 50 to 70% of floating exposure to fixed rates via interest rate swaps, with a three-to-five-year horizon. Cost: approximately $1 to $1.25 million annually on the swapped portion. Benefit: elimination of the rate spike as a source of cash flow surprise, protecting the capex pipeline. The remaining 30 to 50% stays floating — both to retain some benefit if rates fall and to avoid the operational complexity of hedging the entire book.

Notice what the reasoning is not. The reason to do the swap is not "we think rates are going up." Timing interest rate moves is hard; the evidence that any firm can do it systematically is weak. The reason is to reduce cash flow volatility regardless of direction. The swap trader's pitch — "lock in before the Fed raises again" — frames the decision as a directional bet. It is not. It is a decision about how much cash flow volatility Halverson wants to absorb, at what cost.

**Foreign exchange risk.** Halverson's UK subsidiary does roughly £80 million of annual revenue, denominated in pounds, reported in dollars. A 10% move in GBP/USD changes reported revenue by roughly $10 million and reported earnings by roughly $2 million [verify].

But this number conflates two different exposures that require different responses.

*Transaction exposure* is the risk on specific contracted future cash flows in foreign currency. If Halverson has signed a contract to receive £5 million in three months, and the pound weakens, Halverson receives fewer dollars than expected. This is a concrete, hedgeable risk: enter a forward contract to sell £5 million in three months at today's rate, and the exchange rate movement in that period is neutralized.

*Translation exposure* is the risk that the quarterly P&L looks different when pounds are converted to dollars for financial reporting. This is largely accounting — the underlying economics of the UK business have not changed, but the dollar number in the income statement has. Hedging translation exposure costs real money to smooth a number that long-term shareholders should be able to look through.

The recommendation: hedge transaction exposure on contracted pound receipts using rolling forward contracts, sized to the actual payment schedule. Do not hedge translation exposure. The distinction matters both economically and in terms of hedge accounting treatment — improperly designed hedges create their own P&L volatility under ASC 815 [verify], which is the opposite of what the hedging program is supposed to achieve.

**Commodity risk.** Halverson's steel, copper, and aluminum inputs represent roughly 30% of cost of goods sold [verify]. Not all of that is fully exposed: Halverson's customer contracts include partial price-passthrough provisions, so some commodity price moves are automatically absorbed by customers rather than Halverson's margin. The net exposed portion — the part Halverson genuinely bears — is perhaps $150 million of annual purchases [verify with procurement team].

A 20% spike in steel prices, fully absorbed without passthrough, would compress margin by roughly $20 million. That is larger than the interest rate exposure in the current rate environment, and it is the exposure most directly linked to the capex pipeline argument: a bad year for commodity costs is precisely when capital investment budgets get cut.

The recommendation is to hedge 40 to 60% of net commodity exposure on a rolling 12-month horizon using futures contracts, refreshed quarterly. The partial hedge — rather than 100% — serves two purposes. It retains participation in the upside if commodity prices fall, preserving cost competitiveness relative to unhedged peers. And it limits the hedge accounting complexity: a full hedging program requires designation, effectiveness testing, and ongoing documentation that is operationally expensive for a firm of Halverson's size.

**Counterparty risk.** The $40 million of receivables concentrated in three large customers sits outside what futures and swaps can address. The exposure here is not to a market price; it is to the credit health of specific counterparties. A large customer bankruptcy would be a cash flow event that no rate swap or commodity future mitigates.

The right tool is credit insurance — a policy that pays out if a covered customer fails to pay within a defined period after the due date. Premiums run roughly 0.3 to 0.5% of insured amount annually [verify with carriers]. On $25 million of coverage across the two largest concentrations, annual cost is roughly $100,000. The benefit is protection against a tail event that, while unlikely, would be operationally disruptive if it occurred during the Cardinal integration period when Halverson's financial attention is already strained.

---

Total cost of the recommended hedging program: roughly $1.5 to $2 million annually [verify against current market rates for each instrument]. This is less than 1% of operating income. Against it sits a material reduction in the probability that rate moves, currency moves, or commodity moves force Halverson to cut its capex program in any given year.

That is the trade Halverson is making. Not a bet on rates, not a view on the dollar, not a prediction about steel prices. A decision about how much financial volatility is acceptable given the firm's investment program and leverage level.

---

I want to close with something about the limits of the framework, because they are real.

The three deviations from irrelevance — distress costs, tax convexity, investment financing — tell you *why* hedging can add value. They do not tell you *how much* to hedge. The recommendation to convert 50 to 70% of floating rate exposure to fixed rates is a reasonable range, not a calculated optimum. I do not know how to derive the precise optimal hedge ratio for a firm with Halverson's profile from first principles. Neither does anyone else in a way that produces a single defensible number.

What the framework gives you is the structure of the decision: which exposures are large enough to matter, which hedging tools are clean enough to be worth their operational cost, and whether the distress-protection and investment-pipeline arguments are strong enough to overcome the direct cost of the hedge and the foregone upside. For Halverson in its current situation — significant leverage, active capex program, uncertain rate and commodity environment — the arguments favor selective hedging. For a different firm with a different balance sheet and a different investment program, the same framework might produce different conclusions.

"We hedge our exposures" is not a policy. A policy specifies which exposures, with which instruments, at what cost, against what threshold of materiality, reviewed on what schedule. Tom has that policy. The trader on the phone is selling an instrument that is consistent with the policy. But the trader's framing — lock in before rates rise — is not the reason to do the trade. The reason is more basic: Halverson has an investment program that creates value, it cannot afford to interrupt that program because of a rate move, and a swap costs $1 million a year to eliminate that risk. Whether or not rates rise, the swap was worth buying.

---

*A note on what the chapter simplified.* The hedge accounting treatment under ASC 815 is a significant operational consideration that this chapter treated in a single sentence. Qualifying for hedge accounting — which allows the gains and losses on the hedge to be matched in the income statement against the hedged item, rather than running through earnings each period — requires specific documentation, designation, and effectiveness testing. Firms that run derivatives programs without qualifying for hedge accounting can see P&L volatility from the derivatives themselves that partially offsets the economic benefit of the hedge. The practical implication is that hedging programs require accounting expertise alongside financial economics expertise, and the two do not always give consistent advice about what to hedge and how. This interaction between hedge accounting rules and hedge economics is the largest gap between what the framework recommends and what firms actually do in practice.*

