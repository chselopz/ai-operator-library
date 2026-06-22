# Steelman the Customer's Case for Leaving

**What this is:** A prompt that argues your customer's case for churning as convincingly as they would — a churn pre-mortem that exposes blind spots before the customer acts on them.

**When to use:** You suspect an account is at risk and want to pressure-test where you really stand before it's too late. Built on one truth: customers rarely just stop; they leave for an alternative, a competitor, or a decision to bring it in-house, so the case for leaving usually has a destination worth naming.

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
- Research my product and the competitor's or alternative's product for the competitive comparison. Use publicly available sources.
- Be honest about my tool's real weaknesses — this only works if the steelman is credible.
- Do not invent customer data. Use only the signals I provided. Where a signal is missing, note it as a gap.
- Cite competitive research sources with URLs where possible: [source: URL]

---

Produce the output in this exact order:

SECTION 1 — EXECUTIVE SUMMARY
A tight read of where this account stands, led by the hard quantitative data. 3–5 sentences. State the headline churn read up front.

SECTION 2 — GAP ANALYSIS
What critical information am I missing to judge this account accurately? List the blind spots — the questions I can't answer with the signals I have. Be specific about what I should go find out.

SECTION 3 — RANKED CHURN RISKS
Rank the churn risks from most to least threatening. For each:
- **[Risk name]** — the risk in one line
- Why it's threatening: evidence-based reasoning drawing on the signals
- Which signal(s) it's grounded in

SECTION 4 — GUT vs. DATA RECONCILIATION
Two parts:
- SPLIT VIEW: side by side — what the hard data says vs. what my tacit read says. Show where they agree and where they diverge.
- BLENDED VERDICT: a single reconciled read below the split. Where gut and data disagree, say which to trust here and why. Tacit read is a sanity check on the numbers — flag the disagreements explicitly.

SECTION 5 — COMPETITIVE COMPARISON
A markdown table comparing my product against the competitor or alternative (named or your inferred most-likely), focused on the dimensions THIS customer cares about based on their usage and signals:

| Dimension | My Product | Competitor | Edge |

Then one paragraph: through this customer's eyes, where does the competitor or alternative genuinely win?

SECTION 6 — MITIGATION MOVES
For each ranked risk in Section 3, give a specific, actionable mitigation. Not generic retention advice — moves tailored to THIS account and THIS risk. Order them to match the risk ranking.

FORMAT RULES — apply regardless of which LLM you are
- Use section headers exactly as written above
- Section 3: bold risk names, bullets below
- Section 4: clear SPLIT VIEW then BLENDED VERDICT
- Section 5: markdown table
- Be unsparing in the steelman — a comfortable case for leaving is a useless one
- Cite competitive sources as [source: URL]
- No generic preamble or closing remarks
```
