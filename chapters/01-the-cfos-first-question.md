# Chapter 1 — The CFO's First Question

---

## The Gap Nobody Tells You About

Here is the thing finance education doesn't tell you, and I want to get it on the table before anything else.

When you learn finance — in an MBA program, from a textbook, from a CFA curriculum — you learn how to analyze a firm from the outside. You learn to read a 10-K, build a discounted cash flow, calculate a weighted-average cost of capital, evaluate whether a company's capital structure makes sense. You are, implicitly, sitting in the position of an analyst at Morgan Stanley, looking at the company across the street, armed with public data and your models.

That is one kind of finance. It is a real kind. It is useful. The problem is that there is a second kind — the kind practiced by the people inside the firm, sitting in the CFO's office, with the actual cash position and the actual covenant language and the actual board dynamics — and the two kinds are not the same problem dressed in different clothes. They are genuinely different problems. The confusing part is that the textbook treats them as one thing.

This chapter is about the gap between them. More specifically, it's about what happens when you fall into it on your third Tuesday on the job.

---

## What Maya Was Asked

Maya Chen, senior analyst at Halverson Industries, gets a capital structure assignment at 9:14 AM: evaluate whether the firm should fund a $50M plant expansion with debt or equity. The CFO needs a memo by Friday. The board meets on the 15th.

Maya has a strong finance education. She can recite the Modigliani-Miller propositions. She can build a DCF. She knows what debt and equity are. None of that tells her what to write in the memo.

I want to understand *why* none of that tells her what to write, because this is the important question. The gap is not in Maya's technical knowledge. The gap is between the question she learned to answer and the question she's been asked.

Let me make that precise.

The question "should we fund Plant 4 with debt or equity?" sounds like a single question. It isn't. It's doing five different jobs at once, and the job that sounds most obvious — the literal question about which financing instrument to use — is actually the least interesting of the five.

**The cost job.** Debt costs interest. Equity costs dilution and expected future returns. All else equal, you prefer the cheaper one. But all else is never equal. The cost depends on Halverson's existing capital structure, the current tax rate, what the credit market is pricing right now, how the equity market feels about Halverson specifically, and how the board feels about issuing shares this quarter. "Which costs less" is not a number you look up. It is a calculation that requires a specific firm, a specific moment, and specific market conditions.

**The risk job.** Debt must be repaid on a fixed schedule whether Plant 4 succeeds or not. Equity has no such obligation. If Plant 4 underperforms, equity holders are disappointed; debt holders are in line to be paid regardless. The financing choice changes the risk profile of the entire firm, not just the project. The CFO isn't just asking "what's the cheaper capital?" She's asking "how much additional financial fragility does Halverson want to introduce?"

**The signaling job.** When a public company issues equity, the market tends to interpret it as the insiders saying "we think our stock is overvalued, so we're selling some." When a company issues debt, the market tends to interpret it as the insiders saying "we think our future cash flows are strong enough to support fixed payments." Diane's choice will be read and interpreted by equity analysts whether she intends a signal or not. The signal can move the stock price in ways that outlast the news about Plant 4 itself.

**The flexibility job.** A new debt issuance typically comes with covenants: restrictions on additional debt, on dividend payments, on acquisitions. Equity has no covenants, but it permanently changes the ownership structure. The choice today constrains the option space available tomorrow. A CFO who optimizes only for the cost of today's financing and ignores what that financing forecloses later is solving the wrong problem.

**The literal job.** Finally, yes: which instrument? Bank loan, bond offering, equity offering, retained earnings, convertibles? Each has a specific execution timeline, specific transaction costs, specific investor appetite.

Five jobs, one sentence. This is the first thing the inside view teaches Maya: the literal question is the smallest part of the question. A textbook would call this "specifying the decision context." I'd say it more directly: before you can compute anything useful, you have to understand what you're actually being asked. The computation is the easy part. The specification is the hard part, and almost nobody teaches it.

---

## Why the Outside View Doesn't Get You There

Let me explain the inside/outside gap more carefully, because it matters for everything that follows.

Outside the firm, finance analysis has a clean structure. There is public data — 10-Ks, earnings releases, market prices — and there is your analysis of that data. The data is in EDGAR. You download it. You build your model. You verify that your model produces numbers consistent with what other analysts are reporting. If your WACC is wildly different from the consensus, you check your inputs. The verification process is fundamentally about cross-referencing public information.

Inside the firm, this breaks down immediately. Halverson's actual cash position isn't in EDGAR — it's in the controller's month-end report, which may not have been distributed yet, and which contains estimates that are themselves subject to revision when the accounts receivable team finishes the collections run. The actual covenant language on the existing revolver isn't in the bond indenture summary on the investor relations page — it's in the full credit agreement on Tom the treasurer's hard drive, and the critical restrictive covenant is in Section 7.4 of an amendment filed in 2021 that nobody has summarized into a readable form.

The numbers Maya needs don't exist as numbers yet. They exist as processes, spreadsheets, people, and institutional memory, and getting them requires going to talk to those people in a way that public-market analysis never requires. This is not a minor inconvenience. It changes the nature of the verification problem entirely.

Outside the firm, "verify" means cross-reference public information against other public information. Inside the firm, "verify" means go find the person who owns the number and understand how they built it.

This is why Maya is stuck. Her verification instincts are trained on public data. The data she needs is not public. The analysis she knows how to do assumes the data is clean and given. The data she has is messy and owned by specific people who may not answer their email.

---

## The Method, Moved Inside

There is a discipline that handles this, and Maya already has the outline of it. I'll call it the three-beat method, though the label matters less than the substance.

The first beat is **verify the inputs**. Where is each number coming from? Who built it? What assumptions does it rest on? What's its update cadence? This is not a quick checkbox. When the controller's draft memo says "approximately $12M in interest expense next year," the word "approximately" is doing a lot of work. What is it approximately of? What scenario does it assume? What would change it? At Halverson, getting clean inputs for a Friday memo means making several calls by Wednesday and being explicit about which numbers are confirmed and which are planning-level estimates.

The second beat is **calculate transparently**. No black-box outputs. Every number in the memo is one Maya can derive on a page in front of the CFO, in real time, if asked. This is not about distrust of tools — Claude can run the WACC calculation, Excel can run the sensitivity tables — it's about ensuring that Maya understands every step well enough to defend it and fix it when (not if) a number turns out to be wrong. The catastrophic memo is the one where the analyst can't explain how they got from input to conclusion. That memo gets killed.

The third beat is **sanity-check against something you know.** If the WACC comes out at 4%, Maya knows that is wrong before she checks the math, because Halverson's bonds currently trade at a yield above that, and equity holders expect more than the cost of debt. The sanity check is cheap insurance against a catastrophic error. It's the first thing to do when a model produces a number that feels surprising.

This method is not about any particular tool. It's the discipline of someone whose recommendation will be taken to the board. The board will ask questions. The questions will be pointed. The answers need to be true.

---

## Why Financing Affects Value (And When It Doesn't)

Maya needs the outline of the underlying theory today, even if the full machinery comes later.

In 1958, Franco Modigliani and Merton Miller proved something that still feels surprising: in a world without taxes, bankruptcy costs, or information asymmetries, the way a firm finances its assets doesn't affect the firm's total value. If Halverson is worth $500M as an unleveraged firm, it's worth $500M as a 50% leveraged firm. The source of the $50M for Plant 4 doesn't change what Plant 4 is worth. The pie — the value created by the firm's assets — is the same size regardless of how you slice it into debt and equity claims.

This is a clean, important result. It is also obviously not a description of the world Halverson operates in.

Halverson's world has taxes. And the tax treatment of debt versus equity is not symmetric: interest payments on debt are tax-deductible, while dividend payments and equity returns are not. What this means in practice is that every dollar of interest Halverson pays saves the firm some fraction of a dollar in taxes — roughly the dollar times the effective corporate tax rate. At current federal rates plus state taxes, this is a meaningful annual benefit. The debt option has a tax shield that the equity option doesn't, and the present value of that tax shield is real money.

But Halverson's world also has financial distress. If Halverson takes on more debt than its cash flows can reliably support, and those cash flows turn out weaker than expected, the firm faces distress — missed payments, covenant violations, creditor negotiations, potential default. Distress is expensive independently of the resolution. Lawyers are expensive. Distracted management is expensive. Customers who hear the company is struggling take their business elsewhere. Suppliers tighten credit terms. The firm can survive the distress and still have destroyed substantial value in the process.

The trade-off is this: more debt means more tax shield (good) and more financial distress risk (bad). The optimal capital structure balances those two forces. Where exactly the balance is depends on the specific firm — its cash flow stability, its existing leverage, its business cyclicality, the current credit market environment.

For Halverson specifically — an industrial company with relatively stable cash flows and conservative existing leverage — the preliminary case favors debt at this scale. The tax shield is real and the distress risk, at $50M additional leverage on top of a healthy balance sheet, is modest. But "preliminary case" is not a memo. The numbers need to be run.

There is a third force that M&M's world excludes: information. Inside the firm, management knows things about Halverson's prospects that the equity market doesn't know yet. When Diane chooses debt, the market reads it as confidence in future cash flows. When she chooses equity, the market reads it as a signal that management thinks the stock is overvalued. These interpretations are not always accurate, but they affect the stock price, and the CFO has to factor them in.

The signaling problem is genuinely hard, in a way that I find honest to admit doesn't resolve cleanly. The theory says equity issuance signals overvaluation. The empirics show that equity issuances are often followed by stock price declines. But the clean empirical test — separating the signal from the actual news that prompted it — is difficult to run on the data Halverson generates internally. For now, Maya should be aware that the market will read her recommendation as a signal even if the recommendation is entirely driven by cost and tax considerations.

---

## What Maya's Plan Looks Like

Here is what Maya writes on a sticky note, which becomes the rough architecture of the memo.

She needs Halverson's current capital structure. Total debt, weighted average interest rate, covenant restrictions, debt maturity schedule. She needs this from Tom by Wednesday morning, which means asking Tom on Monday, not Wednesday.

She needs the project's cash flow assumptions verified. Plant 4 is supposed to produce some amount of incremental EBITDA per year for some number of years. Whose number is that? Has operations pressure-tested it? Is the $50M construction cost itself a confirmed estimate or a planning placeholder? A planning placeholder should be disclosed as such in the memo — Diane will know the difference, and finding out later that the number was soft will damage Maya's credibility.

She needs to compute the cost of each financing option. The cost of debt comes from Halverson's existing bond yield curve, adjusted for the current credit market. The cost of equity comes from CAPM — Halverson's beta, the risk-free rate, the equity risk premium. Both need to be adjusted for taxes appropriately.

She needs to compute the value impact of each option. The tax shield from debt financing has a present value. The dilution from equity financing has a cost. She needs both calculated explicitly so the comparison is honest.

She needs a stress test. What if EBITDA comes in 30% below projection — does Halverson still cover debt service with margin? What if the equity market closes for several months — can Halverson fund the plant through other means or delay the project?

Then she writes the memo. One page. Recommendation. Reasoning. Three honest risks named by name.

This is the rough shape of every recommendation in this book. The variables change. The discipline does not.

---

## The Real Thing the Chapter Is About

I want to end on the idea that opened it, because I think it matters more than the capital structure content.

The gap between inside-the-firm and outside-the-firm finance is not a gap in technical knowledge. Maya has the technical knowledge. The gap is in how you orient yourself when the analysis you need to do is not the analysis you were trained to do.

Outside the firm, you are a spectator with good tools. Inside the firm, you are a participant whose recommendation has consequences. The data is messier. The questions are less clean. The people who own the numbers have other things to do. And the memo goes to the board, where it will be read by people who will ask harder questions than any exam.

The textbook can give you the theory. This book tries to do one additional thing: describe the practices — verification, transparent calculation, honest risk-naming — that connect the theory to a memo you would actually sign your name to.

Maya's Friday memo will recommend debt financing, contingent on the covenant analysis from Tom and the EBITDA verification from operations. The chapter's prediction: the recommendation will be right for the right reasons, and Diane will know the difference between a memo that was reasoned and one that was produced.

Whether it goes to the board on the 15th is not Maya's decision. The analysis is.

---

*Tags: capital structure, inside-the-firm, Modigliani-Miller, trade-off theory, three-beat method, cost of capital, signaling, financial distress*