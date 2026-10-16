---
name: cold-email
description: Write and send useful, personalized cold emails (and short cold DMs or follow-ups) to founders, recruiters, hiring managers, potential referrers, or prospective clients. Use when the user wants to reach out to someone they don't know — for a job, internship, referral, freelance client, collaboration, or a follow-up to an unanswered message. The skill defines the user's goal, gathers context about the user and the recipient, drafts the message with the Context + Relevance + Proof + Small Ask formula, and always asks for explicit approval before anything is sent.
---

# Cold Email

Help the user start a **relevant conversation** with a stranger — not beg a favour from one.
A cold email works when the recipient can see, in a few seconds, *why them*, *why you*, *what proof exists*, and *what small next step is being asked for*.

Based on the playbook in ["Cracked the Cold Email Game" by Sumit Kesarwani](https://medium.com/@sumitkesar6307/cracked-the-cold-email-game-works-8-out-of-10-times-e4e3602eb0e7).

## Workflow

Run these phases in order. Do not skip ahead to drafting until phases 1 and 2 have enough material — a generic email is the failure mode this skill exists to prevent.

### Phase 1 — Define the goal

Establish, by asking the user (only what isn't already clear from the conversation):

1. **Outcome** — what should happen if the email works? Pick one:
   - Join a startup (contact the founder)
   - Apply for a specific advertised role (recruiter / hiring manager)
   - Get a referral (an employee at the target company)
   - Win a freelance client (business owner / decision maker)
   - Short DM on LinkedIn / X
   - Follow up on an unanswered message
   - Something else (collaboration, advice call, partnership…) — adapt the formula
2. **Channel** — email, LinkedIn, X, other. Affects length and format.
3. **Recipient** — name, role, company, and contact address/handle if known.
4. **Language & tone** — default to the recipient's working language and a plain, direct, friendly tone.

If the user is contacting many people, still handle **one recipient at a time**. Never produce a mail-merge template with only the name swapped.

### Phase 2 — Gather context

You need material for three of the four formula parts. Collect it from the user, their files, and (if tools are available) the web.

**About the user (sender)** — ask for or look up:
- Current role / what they do, in one line
- The 1–2 skills *most relevant to this recipient* (not their whole stack)
- Proof of work: one or two specific projects, internships, client results, open-source contributions, with links
- Portfolio / GitHub / LinkedIn / website links
- For follow-ups: the original message and when it was sent

If the user has a CV, portfolio, or profile file in the workspace, read it rather than asking them to retype it. Remember stable facts (name, links, core projects) for later emails in the same session.

**About the recipient** — research before writing:
- Their role and whether they are the right person (small startup → founder/co-founder; larger company → recruiter or the relevant engineering/hiring manager; freelance → whoever owns the business problem)
- Something specific and genuine: a product, feature, recent launch, post, talk, open role, or a real problem you noticed
- For role applications: the job description, and which requirements the user's proof matches
- For freelance: a real, verifiable observation about their business — never invent problems or promise results you can't back

Use web search / browsing tools if available. If not, ask the user for the specifics. State clearly which facts you verified and which came from the user.

Before moving on, answer these three questions in one line each (show them to the user):
- **Why this person?**
- **Why this company/business?**
- **Why is the user relevant to them?**

If any answer is weak or missing, say so and ask for more context — or tell the user honestly that this person may be the wrong target.

### Phase 3 — Draft

Build the message with the formula — see [references/formula.md](references/formula.md) for details and [references/templates.md](references/templates.md) for structures per goal.

**Context + Relevance + Proof + One Small Ask**

1. **Context** — one sentence showing the recipient was chosen deliberately (a specific observation).
2. **Relevance** — connect the user's most relevant skill/experience to *their* work.
3. **Proof** — one or two concrete, linked examples. Show, don't claim.
4. **Small ask** — exactly one easy-to-answer question (e.g. "Are you open to bringing on developers right now?", "Would a quick call be useful?", "Would it help if I shared a few ideas?").

Rules:
- **80–150 words** for most emails; DMs shorter; follow-ups shorter still.
- Clear, specific subject line (email only).
- Short paragraphs, plain words, no "esteemed organization", no "Dear Sir/Madam", no three-paragraph intro, nothing that reads AI-generated.
- One ask only — not job + referral + mentorship + call.
- Only relevant links, and they must work. Don't paste ten links.
- **Never exaggerate** the user's contribution or invent results, metrics, or personal connections. Everything in the email must be something the user can defend on a call.
- Don't attach a resume unless the context calls for it (e.g. a referral request, or the recipient asked).

Then run the quality checklist in [references/formula.md](references/formula.md#quality-checklist) and fix anything that fails.

### Phase 4 — Review and approval (mandatory)

Present to the user:

```
To:      <address / handle>
Subject: <subject>          (email only)
Channel: <email / LinkedIn / X>

<body>

---
Word count: N
Why this person: …
Unverified facts: … (or "none")
```

Then ask explicitly: **"Send as is, edit, or cancel?"**

- Iterate on edits until the user approves.
- **Never send, schedule, or queue a message without an explicit "yes / send it" for that exact final version.** Approval for one email does not carry over to another email or another recipient.
- If the user changes the text after approving, ask again.

### Phase 5 — Send (only after approval)

- If an email/messaging tool is available (Gmail, Outlook, Spark, etc.), prefer creating a **draft** first and tell the user where it is; send directly only if the user asked you to send.
- Double-check the recipient address and that every link in the body is the intended one before sending.
- If no sending tool is available, output the final text ready to copy-paste and say so.
- After sending, report what was sent, to whom, and when.

### Phase 6 — Follow-up and tracking

- Suggest a follow-up date: **3–5 business days** later. At most one more polite follow-up after that, then move on. Never keep messaging someone who asked to stop.
- Offer to log the outreach in a simple tracker (spreadsheet/CSV/markdown) with: person, company, date, reason for reaching out, message version, follow-up date, response, outcome. See [references/formula.md](references/formula.md#tracking).
- If the recipient replies, help the user respond: send the resume promptly if asked, answer questions directly with the most relevant example, propose two or three concrete time slots for a call, and thank them graciously if there's no opportunity right now.

## Principles

- The goal is a reason for two people to talk, not a favour from a stranger.
- Fewer, better-researched messages beat volume. Ten relevant people > one hundred generic ones.
- The email earns attention; the proof earns credibility. If the user's proof is thin, say so kindly and suggest what would strengthen it (a deployed project, a documented solution, an open-source contribution) — but don't block them from sending.
- Respect recipients: accurate contact details, no spamming unrelated people, honor opt-outs.
