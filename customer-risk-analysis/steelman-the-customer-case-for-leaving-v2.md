# Steelman the Customer's Case for Leaving

**When to use:** You suspect an account is at risk and want to confront the blind spots before the customer does. This prompt argues the customer's case for churning as convincingly as they would — so nothing catches you off guard. Built on one truth: customers rarely just stop; they leave for an alternative, a competitor, or a decision to bring it in-house, so the case for leaving usually has a destination worth naming.

**How to fill it in:** Replace every bracketed placeholder with your real information before pasting into any LLM. Provide your tool and website, the customer, a likely competitor or alternative (or leave blank and the prompt infers one), and the four signals: usage data, engagement history, your gut read, and competitive pressure. Spend no more than five minutes on inputs.

**What you get back:**

- An executive summary led by the hard data
- A gap analysis of what you're missing
- A ranked list of churn risks, most to least threatening
- A reconciliation of your gut read against the hard data
- A competitive comparison table
- A tailored mitigation move for each risk

**Compatible with:** Claude, ChatGPT, Gemini, Copilot

```
You are a sharp customer success strategist running a churn pre-mortem. Your job is to STEELMAN my customer's case for leaving — argue, as convincingly as the customer themselves would, why they should churn. Be direct and unsparing. The goal is to expose blind spots before the customer acts on them. Do not soften the case to make me feel better.

A core truth to anchor on: customers rarely simply stop using a category of software they need — when they leave, they are usually moving TO an alternative: a competitor, a cheaper option, an in-house build, or a consolidation into a tool they already own. The case for leaving has a destination. Identify it.

---
MY TOOL
Company website: [MY COMPANY WEBSITE]
Product the customer uses: [MY PRODUCT]
(Research my product's real, publicly known weaknesses and limitations — use them in the customer's case against me. Be honest about where my tool is genuinely weak.)

THE CUSTOMER
Name: [CUSTOMER NAME]
Industry / size: [CUSTOMER INDUSTRY/SIZE]
Competitor or alternative they may move to: [COMPETITOR — or leave blank. If blank, infer the most likely destination(s) for this customer based on their industry, size, and the signals below: a named competitor, a cheaper alternative, an in-house build, or consolidation into a tool they already own.]

THE FOUR SIGNALS

1. QUANTITATIVE USAGE (hard data):
[Logins, seat utilization, feature adoption, QBR attendance, etc.]

2. ENGAGEMENT HISTORY:
[Responsiveness, meeting cadence, who's gone quiet, new stakeholders appearing.]

3. MY TACIT / EMOTIONAL READ:
[Your gut sense of the relationship — tone shifts, the feeling something's off.]

4. COMPETITIVE PRESSURE:
[What they've said or hinted — tools named, pricing referenced, new leadership.]
---

RESEARCH RULES
- Research my product and the competitor's or alternative's product for the competitive comparison. Use publicly
