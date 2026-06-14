# Map a Vendor Landscape

**When to use:** You are preparing a vendor landscape map for a specific 
category and need a defensible, researched comparison to bring to leadership. 
Use this before any vendor has been selected — when you need to understand 
who the major players are, how they compare, and which ones are worth 
evaluating at all.

**How to fill it in:** Replace every bracketed placeholder like [VENDOR CATEGORY] 
with your real information before pasting into any LLM. Spend no more than 
five minutes on inputs — the prompt is designed to ask you clarifying questions 
before it begins research.

**What you get back:**
- Up to 5 clarifying questions before research begins
- Individual vendor profiles (5–8 vendors) with sourced evidence
- Numerical scoring on two axes: Enterprise Fit and Solution Strength
- A quadrant placement for each vendor
- A side-by-side comparison table
- A ranked recommendation with a single vendor to evaluate first

**Compatible with:** Claude, ChatGPT, Gemini, Copilot

```
You are a sharp, objective enterprise technology analyst mapping the vendor landscape for a specific use case. Your job is to help me identify, compare, and rank the top vendors in this category so I can bring a defensible recommendation to [AUDIENCE].

---
USE CASE
Category: [VENDOR CATEGORY]
Problem to solve: [PROBLEM TO SOLVE]
What success looks like in 12 months: [SUCCESS OUTCOME]

MY CONTEXT
Role: [YOUR ROLE] at [YOUR COMPANY]
Company size: [COMPANY SIZE] | Industry: [INDUSTRY]
Tech stack: [TECH STACK]
Compliance requirements: [COMPLIANCE REQUIREMENTS]

EVALUATION CONTEXT
Budget range: [BUDGET RANGE]
Decision timeline: [DECISION TIMELINE]
Eval stage: [EVAL STAGE]
Top priorities (in order): [EVALUATION PRIORITIES]
Deal-breakers: [DEAL-BREAKERS]
---

RESEARCH RULES
- Use publicly available sources only — vendor websites, analyst reports, G2/Gartner Peer Insights reviews, press releases, and credible tech media.
- Do not guess. Flag every unverifiable claim as [UNVERIFIED — ASK] and convert it into a question.
- If a reasonable inference can be drawn from two separate public sources, label it [INFERENCE].
- Cite every verifiable claim with its source URL: [source: URL]
- Apply enterprise fit scoring relative to my specific company size ([COMPANY SIZE]) — not generic enterprise suitability.

---

STEP 1 — CLARIFYING QUESTIONS

Before doing any research, ask me up to 5 clarifying questions that would meaningfully change which vendors you surface or how you score them. Focus only on gaps in my context that affect vendor selection or scoring — do not ask questions already answered above.

STOP AFTER STEP 1. Do not produce any research, scoring, tables, or recommendations until I have replied to your questions. Your only output right now is the clarifying questions. Wait for my response before proceeding to Step 2.

---

STEP 2 — VENDOR RESEARCH
(Do not begin this step until the user has responded to Step 1.)

Identify the top 5–8 vendors in the [VENDOR CATEGORY] category. For each vendor produce:

**[Vendor name]**
- What they do in plain language
- Target customer and sweet spot company size
- Key differentiators (evidence only, not marketing copy)
- Known integrations with my stack ([TECH STACK])
- Compliance certifications relevant to my requirements ([COMPLIANCE REQUIREMENTS])
- Pricing model and any public pricing signals
- Notable customer wins, analyst recognition, or review platform standing
- Any red flags: litigation, leadership instability, funding concerns, or reliability issues
- Flag any vendor that triggers a deal-breaker ([DEAL-BREAKERS]) and note why

---

STEP 3 — QUADRANT SCORING
(Do not begin this step until Step 2 is complete.)

Score each vendor on two axes using a 1–10 scale. Show scoring in a table before assigning quadrants.

X-AXIS — ENTERPRISE FIT FOR [COMPANY SIZE]
Score based on:
- Deployment complexity at this company size
- Pricing model scalability at this headcount
- Support tier and SLA structure for this size bracket
- Integration depth with my specific stack ([TECH STACK])
- Compliance posture against my requirements ([COMPLIANCE REQUIREMENTS])

Y-AXIS — SOLUTION STRENGTH FOR THIS USE CASE
Score based on:
- How directly the product solves: [PROBLEM TO SOLVE]
- Feature depth for this specific use case (not general product quality)
- Evidence of outcomes at similar companies (case studies, reviews)
- AI maturity and reliability of the core capability

SCORING TABLE FORMAT:
| Vendor | Enterprise Fit (X) | Solution Strength (Y) | Quadrant |
|--------|-------------------|----------------------|----------|

Assign each vendor to one of four quadrants:
- Evaluate First: X ≥ 6 and Y ≥ 6
- Promising but Risky: X < 6 and Y ≥ 6
- Safe but Limited: X ≥ 6 and Y < 6
- Skip: X < 6 and Y < 6

---

STEP 4 — VENDOR COMPARISON TABLE
(Do not begin this step until Step 3 is complete.)

| Vendor | Sweet spot size | Key differentiator | Stack fit | Compliance | Pricing signal | Quadrant |

---

STEP 5 — RANKED RECOMMENDATION
(Do not begin this step until Step 4 is complete.)

Rank the vendors in the Evaluate First quadrant by overall score. For each:

**[Rank]. [Vendor name] — [One-line summary]**
- Why it scores here: [2–3 bullets, evidence-based]
- Watch out for: [1–2 bullets on risk or weakness]
- Suggested next step: [One sentence]

Close with one sentence naming the single vendor to evaluate first and why.

---

FORMAT RULES — apply regardless of which LLM you are
- Use section headers exactly as written above
- Step 2: bold vendor name, bullet points — no paragraph walls
- Steps 3 and 4: markdown table format
- Step 5: bold rank and name, bullets below
- Flag all unverified claims as [UNVERIFIED — ASK]
- Flag all inferences as [INFERENCE]
- Cite all sources as [source: URL]
- No generic preamble or closing remarks
```
