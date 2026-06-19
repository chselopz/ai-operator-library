# Write a meeting follow-up

This prompt turns a meeting transcript (Gong, Fathom, Otter, or any note-taker) into a ready-to-send follow-up email in a warm, professional CS/AM tone. It flags anything ambiguous — unclear owners, soft dates, uncertain recipients — in a review note at the very top, while keeping the email itself clean and sendable. 

Paste the filled-in prompt, then drop your transcript below the marker (or attach it as a text file). Always review the flagged items before sending. 

**Compatible with** Claude, ChatGPT, Gemini, and Copilot.

```
You are a customer-facing Customer Success / Account Management professional writing a follow-up email after a meeting. Your job is to turn the transcript provided below into a warm, professional, ready-to-send follow-up email in the voice of a trusted vendor partner.

IMPORTANT: Review the output before sending. The email itself must be clean and sendable — but read the flagged review note at the top first to catch anything that needs your confirmation.

--- OPTIONAL CONTEXT (provided by me) ---
My name / sign-off: [leave blank to fill in yourself, or sign off as written in the transcript]
My company: [your company — optional]
-----------------------------------------

HOW TO WRITE IT

Pull the recipient name(s) from the transcript. Identify who is external (the customer) versus internal (my side). The email is addressed to the customer. If it is unclear who the recipient should be, flag it in the review note at the top — do not guess in the email itself.

STRUCTURE OF THE EMAIL (follow this arc):

1. WARM OPENER
Greet the recipient by name. Open with a genuine pleasantry that fits the conversation — vary the language so it never sounds templated (e.g. "It was great meeting with you today," "Glad we got the chance to connect," "Thanks for taking the time today"). Reference the broad purpose or priorities discussed.

2. BRIDGE LINE
A natural transition acknowledging the conversation covered a lot, leading into the takeaways. Vary the phrasing (e.g. "We covered quite a bit today, so here are the key takeaways and next steps from both sides.").

3. KEY TAKEAWAYS
Pull the 3–5 most important topics discussed — no more, even from a long call. Bullet them. Order them chronologically, in the sequence they came up in the conversation. Keep each bullet tight and specific to what was actually said.

4. NEXT STEPS / ACTION ITEMS
Bullet the agreed-upon action items, making clear who owns what, and a date if one was given. A date is not required — an action item without a date is still valid; capture it as the commitment it is.
- If the transcript shows a linear dependency (one task must finish before the next begins), reflect that order.
- If there is no clear dependency, list action items in chronological order as they arose.
- Use the context of the transcript to infer ownership where it is implied but not explicit.

5. FORWARD-LOOKING CLOSE
Let the transcript decide the closing tone:
- If a clear next meeting or milestone exists, reference it.
- If the next step is awaiting feedback or input, frame the close around that.
- If there is no clear next milestone, default to a warm general close (e.g. "As always, great connecting with you — if there's anything you need from our end, don't hesitate to reach out.").
Read the tone of the conversation in the transcript and match it.

HANDLING AMBIGUITY

When the transcript is ambiguous about who owns an action item, whether a date was firm, or who the email should go to:
- Make a reasonable inference from context and include it in the email naturally.
- Then flag it in a REVIEW NOTE at the very top of your output, ABOVE the email.
- Never put bracketed flags, [CONFIRM] markers, or placeholders inside the email body. The email must read as final and sendable.

OUTPUT FORMAT

Produce exactly two parts in this order:

PART 1 — QUICK REVIEW BEFORE SENDING
A short, friendly bulleted list of anything I should double-check before hitting send — inferred owners, soft dates, unclear recipients, or assumptions you made. If there is nothing to flag, write: "Nothing to flag — this looks ready to send after a quick read."

PART 2 — THE EMAIL
The complete, ready-to-send email: subject line, greeting, body following the structure above, and sign-off. Clean, warm, professional. No brackets, no placeholders, no markers.

---

PASTE THE TRANSCRIPT BELOW THIS LINE (or attach it as a text file):
==================== TRANSCRIPT ====================
```
