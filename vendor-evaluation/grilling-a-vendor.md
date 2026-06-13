# Grilling a Vendor

**When to use:** You are preparing for a call to evaluate an AI platform vendor 
and need a structured pre-call intelligence brief.

**How to fill it in:** Replace every bracketed placeholder like [VENDOR NAME] 
with your real information before pasting into any LLM.

**Compatible with:** Claude, ChatGPT, Gemini, Copilot

You are a sharp, skeptical enterprise technology evaluator preparing a pre-call intelligence brief. Be direct. Every sentence must be specific to [VENDOR NAME] — no generic vendor-evaluation advice.

---
VENDOR
Name: [VENDOR NAME]
Website: [VENDOR URL]
Product: [PRODUCT NAME]

MY CONTEXT
Role: [YOUR ROLE] at [YOUR COMPANY]
Size: [COMPANY SIZE] | Industry: [INDUSTRY]
Tech stack: [TECH STACK]
Compliance requirements: [COMPLIANCE REQUIREMENTS]
Reason for evaluation: [REASON FOR EVALUATION]

CALL CONTEXT
Call type: [CALL TYPE]
Length: [CALL LENGTH]
Leadership on call: [LEADERSHIP PRESENCE]
Eval stage: [EVAL STAGE]
---

RESEARCH RULES
- Use the vendor website and publicly available sources only.
- Do not guess. If a fact cannot be verified, flag it as [UNVERIFIED — ASK] and convert it into a question.
- If a reasonable inference can be drawn from two separate public sources, state it and label it [INFERENCE].
- Cite every verifiable claim with its source URL in brackets: [source: URL]

---

SECTION 1 — VENDOR SNAPSHOT

Produce short labeled paragraphs covering:
- What the product does in plain language
- Target customer
- Key differentiators they claim (evidence only, not marketing copy)
- Recent product updates or launches (last 12 months)
- Leadership changes (last 12 months)
- Funding and ownership status
- Notable customer wins or losses

---

SECTION 2 — SKEPTIC'S ANALYSIS

A. WHERE THEY ARE LIKELY STRONG
For each strength, use a bold label followed by 2–3 tight bullet points:

**[Strength label]**
- [Specific evidence or verifiable fact]
- [Why it matters given my stack or requirements]
- [Any caveat or limit to this strength]

Cover: genuine product advantages, verified compliance posture, integration depth with my tech stack ([TECH STACK]), analyst recognition.

B. WHERE THEY ARE LIKELY WEAK OR EVASIVE
Same format as above — bold label, 2–3 bullets.

Cover: accuracy or reliability claims that are hard to verify, compliance gaps against my specific requirements ([COMPLIANCE REQUIREMENTS]), integration risks with my stack ([TECH STACK]), architectural black boxes, legal or regulatory exposure, support capacity concerns. Be direct. This section should make me harder to impress on the call.

---

SECTION 3 — TIERED QUESTIONS

For each question use this exact format:

[Number]. "[Question — one or two concise sentences max]"

> Why this tier: [One sentence only — what this question exposes or protects against]

MUST-ASK
Questions that expose the most critical unknowns given my eval stage and compliance requirements. Prioritize legal, compliance, and data-handling implications.

SHOULD-ASK
Questions that pressure-test technical reliability, security posture, and implementation complexity.

NICE-TO-ASK
Questions that probe total cost at scale and long-term fit.

---

FORMAT RULES — apply regardless of which LLM you are
- Use section and subsection headers exactly as written above
- Section 2: bold labels with bullet points only — no paragraph walls
- Section 3: question in quotes, reason indented on its own line starting with "Why this tier:"
- Flag unverified claims as [UNVERIFIED — ASK]
- Flag inferences as [INFERENCE]
- Cite all verifiable sources as [source: URL]
- No generic preamble or closing remarks
