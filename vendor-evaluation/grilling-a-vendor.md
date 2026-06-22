# Grilling a Vendor

**What this is:** A prompt that produces a structured pre-call intelligence brief on an AI platform vendor — researching them, exposing their weak spots, and arming you with tiered questions to ask on the call.

**When to use:** You're preparing for a call to evaluate an AI platform vendor and want to walk in informed, skeptical, and ready with the right questions rather than taking the pitch at face value.

**How to fill it in:** Replace every bracketed placeholder like [VENDOR NAME] with your real information before pasting into any LLM. Spend no more than five minutes on inputs.

**What you get back:**

- A vendor snapshot covering what they do, recent changes, funding, and customer traction
- A skeptic's analysis of where they're genuinely strong and where they're likely weak or evasive
- Tiered questions to ask — must-ask, should-ask, and nice-to-ask — each with a one-line reason

**Compatible with:** Claude, ChatGPT, Gemini, Copilot

```
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
Questions that expose the most critical
