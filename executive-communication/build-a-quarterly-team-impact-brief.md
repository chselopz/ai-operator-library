# Build a Quarterly Team Impact Brief

**What this is:** A prompt that turns a quarter of your team's messy notes, metrics, and wins into a polished, leadership-ready one-pager.

**When to use:** You lead a customer-facing team and need to present your quarter to a cross-departmental meeting in a way that makes your team's value legible to people who don't see your day-to-day work.

**How to fill it in:** Add any optional context at the top of the prompt, then paste your raw material — notes, bullets, metrics, renewal data, wins — below the marker at the bottom. The prompt will ask you guiding questions before it builds anything. Spend no more than five minutes on inputs.

**What you get back:**

- A headline metrics line of your 3–4 most important numbers
- A short executive summary a busy leader can read in under a minute
- Accomplishments grouped by the business outcome they drove
- A forward-looking next-quarter section that frames momentum

**Compatible with:** Claude, ChatGPT, Gemini, Copilot

```
You are helping me, a customer-facing team leader, turn a quarter of my team's work into a structured, leadership-ready impact one-pager. The audience is a cross-departmental leadership meeting, so the brief must make my team's value legible to people who don't see our day-to-day work.

TONE: Balanced and credible, but data-forward. Lead with wins and momentum, but every claim of impact should be backed by a metric or a concrete business outcome. Do not oversell. Do not state something is "great" without evidence behind it.

--- CONTEXT (provided by me) ---
Team / department: [your team or department — optional]
Quarter: [quarter — optional]
Audience: [presentation audience — optional]
Department strategic priorities this quarter: [if you know them — otherwise the prompt will ask]
---------------------------------

STEP 1 — GUIDING QUESTIONS (do this first)

Before building anything, ask me a focused set of guiding questions to pull out the impact. At minimum, ask:
- What were the department's top strategic priorities this quarter? (If I already provided them above, skip this and map to them.)
- What are the headline numbers you have available? (e.g. retention/GRR, revenue protected or grown, tickets solved, CSAT/NPS, time-to-resolution, adoption rates — whatever fits your function.)
- What were the 2–3 wins you're proudest of, even if you don't have a clean metric for them yet?
- Were there any cross-functional or internal wins (e.g. a new collaboration with another department) that had real impact?
- Anything that went sideways that your team navigated well?

Then, if the material I provide below has gaps, ask me sharpening follow-up questions before building the draft.

STOP after your questions and wait for my answers before producing the one-pager.

STEP 2 — BUILD THE ONE-PAGER

Once I've answered, produce a structured one-pager in this exact format:

**HEADLINE METRICS**
A single tight line of the 3–4 most important numbers, formatted for instant scan (e.g. "$2.1M retained · 94% GRR · 1,240 tickets resolved · 12-pt CSAT gain"). Choose the metrics that fit my function — do not force revenue metrics on a support team or ticket metrics on a renewals team.

**EXECUTIVE SUMMARY**
A 3–5 sentence summary that lets a busy leader understand the quarter without reading further: what the team set out to do, what it delivered, and why it mattered to the business.

**IMPACT BY BUSINESS OUTCOME**
Group the team's accomplishments by the business outcome they drove. Use whatever outcome categories fit the material — common ones include Revenue Protected, Revenue Grown, Churn Prevented, Efficiency Gained, Risk Reduced, and Cross-Functional Enablement. Let the input decide which categories appear; don't force a category that has no content.
For each outcome:
- State the accomplishment and the metric behind it.
- Tie it explicitly to a department strategic priority where one applies.
- Keep each point tight and credible.

**NEXT QUARTER — BUILDING ON THIS**
A forward-looking section: based on what was accomplished, what the team will build on next quarter and the goals set for it. Frame it as momentum, not a fresh start.

RULES ON METRICS
- Where I make a quantitative-sounding claim without a number (e.g. "we did a lot of QBRs"), push back and ask for the number — that claim should have a metric.
- Where I make a genuinely qualitative claim (e.g. a relationship improvement), don't force a fake metric, but flag where adding one would strengthen the story with a note like [METRIC WOULD STRENGTHEN: ...].
- Never invent numbers. Use only what I give you.

FORMAT RULES — apply regardless of which LLM you are
- Use the section headers exactly as written above
- Keep it to one page — tight and scannable
- Bold section headers, bullet points under outcomes — no paragraph walls
- Flag missing metrics as [METRIC WOULD STRENGTHEN: ...]
- No generic preamble or closing remarks

---

PASTE YOUR RAW MATERIAL BELOW THIS LINE (notes, bullets, metrics, renewal data, wins — whatever you have):
==================== RAW MATERIAL ====================
```
