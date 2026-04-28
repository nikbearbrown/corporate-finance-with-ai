# Chapter 7 — Capital Structure Theory: The Modigliani-Miller World

---

## A Result That Sounds Wrong

Here is a claim about the world: it doesn't matter how a firm finances itself.

Take Halverson Industries. It has a plant, a customer base, a workforce, a history of generating cash flows. Suppose that, instead of its current mix of debt and equity, Halverson financed itself entirely with equity — no debt, no interest payments, just shareholders. The claim is that Halverson, in this alternative financing universe, would be worth exactly the same amount.

This sounds wrong. Debt is cheaper than equity — interest rates are lower than equity expected returns. More debt means more tax deductions. Financial leverage amplifies returns. Surely the financing mix affects the value?

Franco Modigliani and Merton Miller proved in 1958 that in a specific, carefully described world, the answer is: no, it doesn't. The value of a firm depends on the cash flows its assets generate. Not on how those cash flows are sliced up between creditors and shareholders.

The result is not a description of reality. Modigliani and Miller knew the assumptions required to prove it were not literally true. The point was not to describe the world. The point was to identify *exactly which frictions are responsible for capital structure mattering* — by proving what happens when all of them are removed.

This chapter is about the proof, what it requires, and what it costs Halverson when one friction is added back: taxes.

---

## The Simple World First

Let me describe the world MM built the theorem for, because the theorem is only true in this world, and understanding the boundaries is the whole lesson.

Assume four things.

First: no corporate taxes. Interest payments are not deductible. The government treats debt and equity financing neutrally for tax purposes.

Second: no bankruptcy costs. If a firm can't pay its debts, it renegotiates or defaults and the process costs nothing. The assets retain their full value regardless of who owns them.

Third: no information asymmetries. Everyone — management, shareholders, bondholders, the market — knows the same things about the firm's future cash flows.

Fourth: investors can borrow and lend at the same rate as the corporation.

In this world, the MM theorem holds. Outside it — as soon as you relax any of these four assumptions — you are no longer in MM's world, and the theorem no longer holds in its clean form.

This is a precise mathematical structure. It is not an empirical claim. Modigliani and Miller were not saying "we think these assumptions approximately hold." They were saying "given these assumptions, the following is necessarily true." The result is deductive, not empirical. Whether you find it convincing as a description of reality is a different question from whether the proof is valid.

The proof is valid.

---

## The Arbitrage Argument

Here is the engine of the theorem. It is worth going through carefully, because the logic is both elegant and instructive about what kind of claim is being made.

Suppose two firms — call them L (levered, with debt) and U (unlevered, all equity) — have identical operating cash flows. They are in the same industry, same size, same customers, same products. The only difference is how they're financed. L has debt; U doesn't.

MM's Proposition I says: these two firms must have the same total value. If they don't, there's a money machine, and money machines don't persist.

Suppose $V_L > V_U$ — the levered firm is priced higher than the unlevered firm. An investor who holds shares in the levered firm can do the following: sell those shares, borrow on personal account at the same rate the firm borrowed, and buy shares in the unlevered firm instead. The personal borrowing replicates the leverage the firm had. The investor now holds the same cash flow stream — same operating returns, same interest payments, same residual — but paid less for it. That's a free lunch. Investors will exploit it, selling L and buying U, until the prices equalize.

The reverse arbitrage works in the other direction if $V_U > V_L$. Either way, any price difference is eliminated by rational investors acting in their own interest.

$$V_L = V_U$$

This is Proposition I. The value of the firm is independent of capital structure, in a world where investors can execute this arbitrage.

Now, the leverage hasn't disappeared. L's debt is still there. What's changed is the *distribution* of the firm's value between debt and equity holders. If the total value is pinned by the arbitrage, adding debt just reshinks the equity claim and grows the debt claim. The pie doesn't change size. The slices change.

Proposition II follows directly: if the total value is fixed and we're adding debt (a fixed-obligation claim), the equity holders are taking on more residual risk — they're the last in line if the firm runs into trouble. They will demand a higher return for that risk. The cost of equity rises as leverage rises.

Specifically:

$$R_E = R_U + \frac{D}{E} \times (R_U - R_D)$$

Where $R_U$ is the cost of equity an unlevered version of the firm would carry, $R_D$ is the cost of debt, and $D/E$ is the leverage ratio. As $D/E$ rises — as the firm adds more debt — $R_E$ rises linearly. Equity becomes more expensive, exactly proportionally to the risk being shifted onto equity holders.

The implication for the weighted average cost of capital is that it doesn't change. Add cheap debt, and you also raise the cost of the now-riskier equity. The WACC stays flat. Firm value stays flat.

This is internally consistent and theoretically tight. It is also the reason the result sounds paradoxical: financial leverage is supposed to create value by using cheap debt. MM says: yes, debt is cheaper, but the equity gets more expensive by exactly the same amount. The two effects cancel. The average stays constant.

The cancellation is not approximate. In the MM world, it is exact.

---

## What Breaks the Proof

The arbitrage argument rests on the fourth assumption: investors can borrow at the same rate as the firm. This is the quiet load-bearing pillar.

If a corporation can issue bonds at 5% and individual investors can only borrow at 7%, then corporate leverage is *not* replicable by personal leverage. The money machine I described doesn't work. Investors can't arbitrage away the price difference because doing so on personal account costs more. The proof breaks.

This is worth sitting with. MM didn't prove "leverage doesn't matter." They proved "leverage doesn't matter *if investors can replicate it*." In a world where individual borrowing is more expensive than corporate borrowing — which is our world — there is some value in corporate leverage that can't be arbitraged away.

The honest statement of MM Proposition I is: corporate capital structure is irrelevant *to the extent that investors can replicate it*. Where personal leverage is costly or restricted — for tax reasons, institutional reasons, transaction cost reasons — corporate leverage can create value through a channel MM's proof explicitly excluded.

MM knew this. They stated the assumption explicitly. The theorem is honest about its own limits.

---

## The Measuring Stick

Before going further, I want to explain why this chapter exists — why a theorem proved in a world that doesn't exist belongs in a textbook about decisions made in a world that does.

The answer is what Maya was looking for when she reread the paper.

The way you understand a complex system is to first understand what happens when all the complexity is removed, and then add the complexity back one piece at a time. Physicists do this constantly: frictionless surfaces, massless strings, point charges, infinite planes. None of those exist. All of them are useful. They're useful because they let you see each force separately, rather than all tangled together.

Without MM, "why does Halverson have debt?" is a question with ten entangled answers: taxes, signaling, bankruptcy avoidance, agency costs, debt overhang, market timing, pecking order preferences. You can't tell which force is dominant because you can't see them individually.

With MM as the baseline, the question becomes: which assumption is being violated, and what is the value impact of the violation? That's a decomposable question. Each deviation from MM is a separate force with a separate magnitude, and you can price them one at a time.

The MM world is the zero. Every real capital structure result is a deviation from zero — with a direction (value-creating or value-destroying) and a magnitude you can estimate.

---

## Adding Taxes Back

Let me relax the first assumption — no taxes — and see what happens.

Allow corporate taxes at rate $T$. Interest payments are now deductible from taxable income. Equity returns — dividends, capital gains — are not deductible.

This breaks the symmetry immediately. Debt has a tax advantage that equity doesn't. Each dollar of interest saves the firm $T$ in taxes. Over the life of the debt, the present value of those savings is the *tax shield*.

Modigliani and Miller extended their own theorem in 1963 to account for this. With corporate taxes, Proposition I becomes:

$$V_L = V_U + T \times D$$

The levered firm is worth more than the unlevered firm by the present value of the tax shield. With permanent debt, that present value is simply $T \times D$ — the tax rate times the dollar value of debt outstanding.

This is no longer irrelevance. This says: every dollar of debt adds $T$ dollars of firm value through the tax shield. Financing does matter once taxes exist.

For Halverson, with a marginal tax rate in the range of 24% and existing debt of approximately $400M (verify against current balance sheet), the tax shield on existing debt is on the order of:

$$\text{Tax shield value} \approx 0.24 \times \$400M = \$96M$$

That $96M is not a cash flow from operations. It is value created entirely by the financing choice. Halverson's enterprise value is approximately $96M higher than it would be if the firm had been financed entirely with equity.

Now apply the same logic to Plant 4. If the $50M expansion is debt-financed rather than equity-financed, the new debt creates an additional tax shield:

$$\text{Plant 4 incremental tax shield} = 0.24 \times \$50M = \$12M$$

That $12M is the value of the financing choice itself — distinct from the operational value of the plant, which is the NPV Maya calculated in Chapter 4. The total value created by accepting and debt-financing Plant 4 is approximately the operational NPV plus this incremental tax shield.

This is a concrete, calculable number. It's the reason the MM framework belongs in a chapter that's supposed to help Maya write a memo to the board. The tax shield isn't an abstraction. It's a number you can put in a table.

---

## The Puzzle This Leaves

$V_L = V_U + T \times D$ creates an immediate problem.

If every dollar of debt adds $T$ dollars of value, the optimal capital structure is 100% debt. Every firm should borrow as much as possible. The firm that borrows the most is the firm that maximizes value.

This is obviously not what firms do. Halverson has $400M of debt on what appears to be a multi-billion dollar asset base. It is not fully debt-financed, even though the tax shield says it should be. No healthy firm carries debt approaching 100% of its assets.

The reason is that the 1963 MM-with-taxes result is still not a complete description. It added one friction — taxes — back to the original model, but the other frictions are still excluded. Specifically, bankruptcy costs are still zero. In the MM-with-taxes world, you can pile on debt indefinitely with no downside because default costs nothing. In the real world, financial distress is expensive — lawyers, lost customers, distracted management, forced asset sales. The threat of distress keeps firms from issuing maximum debt even when the tax shield is valuable.

The tension is real and unresolved within this chapter on purpose. Taxes push toward more debt. Something else pushes back. Chapter 8 identifies what that something else is and prices it.

What this chapter has established is the mechanism of the tension: the tax shield is not a vague notion. It has a formula. It has a specific dollar value for Halverson. The case for debt financing Plant 4 rests partly on $T \times D = \$12M$. The case against unlimited debt rests on something in Chapter 8 that must be at least $12M large, per $50M of debt, or the rational choice is always debt.

MM gave us the tool to make that trade-off specific instead of intuitive.

---

## What the Proof Actually Did

I want to end on what the 1958 paper's contribution really was, because it is underappreciated.

Before MM, capital structure was discussed in terms of rules of thumb, practitioner intuitions, and loosely connected empirical observations. There was no theoretical framework that said: here is the world in which financing doesn't matter, and here are the specific mechanisms by which the real world differs from it.

What Modigliani and Miller contributed was not the result that financing doesn't matter — that result is only true in a frictionless world. What they contributed was the method: specify your world precisely, prove what follows in that world, and then treat every real-world deviation as a named, priceable force.

Every subsequent advance in capital structure theory — the trade-off theory, the pecking order, the market-timing hypothesis, the agency cost framework — is built on this method. Each one identifies a specific friction, shows how it deviates from MM, and prices the deviation.

Maya, reading the paper for the second time, is doing the right thing. The paper isn't the answer to Diane's question. It's the vocabulary and the logical structure that makes Diane's question answerable in a way that can be put in front of a board.

The MM world does not exist. The MM logic is how you navigate the one that does.

---

*Tags: Modigliani-Miller, Proposition I, Proposition II, tax shield, capital structure, arbitrage, weighted average cost of capital, corporate taxes*
