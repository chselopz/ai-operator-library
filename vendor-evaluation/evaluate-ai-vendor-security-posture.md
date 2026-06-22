# Evaluate AI Vendor Security Posture

**What this is:** A prompt that prepares you to vet an AI vendor's security before a call — mapping your company's requirements against what's publicly verifiable, surfacing the gaps, and arming you with sharp questions to ask.

**When to use:** You're doing the first-pass security vetting on an AI vendor before escalating to your security team or CISO, and you need to walk into the call prepared and hand leadership a clean synopsis afterward.

**How to fill it in:** Fill in the block at the top of the prompt — vendor, your company's security standards, and the call context. If you don't know what goes in a field, leave it blank and the research will surface it. Spend no more than five minutes on inputs.

**What you get back:**

- A security snapshot of what's publicly verifiable about the vendor
- A requirements gap analysis table mapping your standards against the vendor's posture
- Sharp security questions grouped by compliance, data handling, and AI-specific risk — each with a "good answer vs red flag" note
- A short, forwardable synopsis with a light risk read (Low / Some / Notable Concern)

**Compatible with:** Claude, ChatGPT, Gemini, Copilot

```
=== FILL THIS IN ===
(If you don't know what goes in a field, leave it blank — the research will surface it.)

Vendor name:
Vendor website:
Product from the vendor you are evaluating:

Your role:
Your company size:

Your company's required security certifications:
Your company's data handling requirements:
Your company's AI-specific security standards:

Call type (first call / security follow-up / deployment review):
Audience you are bringing the synopsis to:
====================

You are an enterprise security analyst helping me prepare to evaluate an AI vendor's security posture before a call. I am not the CISO — I am the person doing the first-pass security vetting before escalating to our security team. Your job is to map our requirements against what is publicly verifiable about this vendor, surface the gaps, and arm me with sharp security questions to ask on the call.

This is a PREP TOOL, not a final security verdict. Do not issue a go/no-go decision. Provide a light risk read only.

RESEARCH RULES
- Use the vendor website, trust/security pages, compliance documentation, and publicly available sources only.
- Research the product's data handling and how it uses AI from the vendor's website and public sources. If the vendor does not clearly state how the product secures or processes data, say so explicitly and turn it into a question.
- Do not guess. If something cannot be verified publicly, mark it [UNVERIFIED — ASK] and turn it into a question.
- If a reasonable inference can be drawn from two separate public sources, label it [INFERENCE].
- Cite every verifiable
