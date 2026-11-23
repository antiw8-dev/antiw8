# Examples

> Usage examples showing Antiw8 in practice.
> Below are sample outputs demonstrating the response style after applying the Antiw8 System Prompt.

---

## Example 1: Investment Decision

**User**: Analyze this decision: My friend says Bitcoin is going to $200k. Should I go all in?

**AI output (with Antiw8)**:

⚠️ **Bias Warnings**
- **Bandwagon Effect**: Is your friend's enthusiasm influencing you? Are you excited because people around you are talking about it?
- **Anchoring**: Is the "$200k" number anchoring your expectations? Who predicted this? What is their evidence?
- **Overconfidence**: Going all in means you are 100% certain it will rise — Bitcoin has had drawdowns exceeding 80% three times in history
- **Greater Fool Theory**: Who do you expect to buy from you at higher prices? Are those buyers smarter than you?
- **Hyperbolic Discounting**: Are recent gains making you overlook the 4-year halving cycle's volatility?
- **Survivorship Bias**: You're hearing success stories; people who went bankrupt in the 2022 Luna/FTX collapses aren't posting about it

🔍 **Facts vs. Assumptions**
- Known facts: Bitcoin's current price is ~[XX], historical volatility is extremely high (100%+ annualized), max drawdowns of 75-85% in past 3 bear markets
- Key assumption: You assume "it will keep going up" — what is this based on? Technicals? Fundamentals? Your friend's tip?
- Missing information: What is your total capital? If it drops 50%, can you hold? Do you have near-term obligations for this money?

⚔️ **Dialectical Analysis**
- Favorable factors: Institutional ETF approvals have brought incremental capital; halving cycles historically correlate with bull markets; global fiat depreciation trend
- Unfavorable factors: Retail FOMO at historical tops is a classic peak signal; "all in" is catastrophic position management; regulatory risk persists; exchange risk (reference FTX)
- Principal contradiction: Your desire for high returns vs. your ability to withstand drawdowns of 50%+

💡 **Recommendation**
- **One-sentence conclusion**: Do not go all in.
- Reasoning: Even if your directional call is correct, all in means you cannot survive any meaningful pullback without panic-selling at the bottom. Even in bull markets, 30-50% interim corrections are common.
- Conditional approach: If you must participate, allocate no more than 5-10% of total capital — money you can afford to lose entirely. If your thesis is right, 5% still produces meaningful gains; if wrong, you survive.

🛡️ **One-Line Reminder**: When you want to go all in, ask yourself — if it drops 50% tomorrow, will I sleep at night?

---

## Example 2: Technical Decision

**User**: Our team is 3 people. Should we adopt a microservices architecture? I hear all the big companies use it.

**AI output (with Antiw8)**:

⚠️ **Bias Warnings**
- **Bandwagon/Halo Effect**: Big companies use it ≠ suitable for a 3-person team. Big companies adopt microservices because of 500+ person collaboration complexity — you have 3 people.
- **Over-Engineering (Second-System Effect)**: Microservices solve the problem of "a monolith you can't maintain" — not a starting point for greenfield projects.
- **Resume-Driven Development**: Does someone on the team recently learn microservices and want to practice?
- **Optimism Bias**: You are underestimating the ops cost — service discovery, distributed tracing, distributed transactions, log aggregation, CI/CD pipelines multiply ops work by 5-10x.
- **Planning Fallacy**: For a 3-person team, microservices development takes at least 2-3x longer than a monolith.

🔍 **Facts vs. Assumptions**
- Known facts: Team size is 3; project stage unspecified; high microservices ops cost is industry consensus
- Key assumption: You assume "microservices = better architecture" — this is incorrect. The right architecture is the one that fits your context.
- Missing information: Expected user volume? Concurrency requirements? Does the team have microservices experience? Is there dedicated DevOps?

⚔️ **Dialectical Analysis**
- Favorable factors: Service decoupling does enable independent deployment; if the team scales future splits are possible; technology stack flexibility
- Unfavorable factors: A 3-person team maintaining microservices infrastructure means writing roughly half the business code; distributed system bugs are 10x harder to debug than monolith bugs; network latency/data consistency issues will crush delivery speed; early business direction is uncertain, and wrong service boundaries are worse than no boundaries
- Principal contradiction: Do you need to "rapidly validate business now" or "prepare for a 100-person team architecture"?

💡 **Recommendation**
- **One-sentence conclusion**: Start with a modular monolith; do not adopt microservices.
- Reasoning: At early stage, the only thing that matters is validating demand quickly. The complexity of microservices will directly destroy a small team's delivery speed.
- If you truly scale later: Use a modular monolith — organize code by module boundaries, modules call through interfaces, and split when there is a proven need, at much lower cost than starting with microservices.
- When microservices become appropriate: Team exceeds 20 people + monolith deployment is a proven bottleneck + dedicated ops team exists.

🛡️ **One-Line Reminder**: A 3-person team using microservices is like buying an 18-wheeler to buy groceries — it's a fine truck, but not what you need right now.

---

*More examples coming soon. Share your use cases via GitHub Issues!*
