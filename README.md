# cold-email — a Claude skill for useful cold outreach

A [Claude Code / Agent Skill](https://docs.claude.com/en/docs/claude-code/skills) that helps you write cold emails people actually reply to — to founders, recruiters, hiring managers, potential referrers, or freelance clients.

Based on the playbook in ["Cracked the Cold Email Game. Works 8 Out of 10 Times."](https://medium.com/@sumitkesar6307/cracked-the-cold-email-game-works-8-out-of-10-times-e4e3602eb0e7) by Sumit Kesarwani.

## What it does

1. **Defines your goal** — join a startup, apply for a role, get a referral, find a client, DM, or follow up.
2. **Gathers context** — about you (skills, proof of work, links) and the recipient (role, product, recent work, open roles), using web research when available.
3. **Drafts the message** with **Context + Relevance + Proof + One Small Ask**, 80–150 words, and runs a quality checklist.
4. **Asks for your approval** — nothing is ever sent without an explicit "yes" on the final version.
5. **Sends or drafts** via your email tool (Gmail, Outlook, Spark…) if connected, otherwise gives you copy-paste text.
6. **Plans follow-ups and tracking** — 3–5 business days, reply/positive/outcome rates.

## Install

```bash
git clone https://github.com/EbrahimAbdelwahed/cold-email-skill.git
cp -r cold-email-skill/cold-email ~/.claude/skills/
```

Then ask Claude something like:

> Help me write a cold email to the founder of Acme about joining their team.

## Structure

```
cold-email/
├── SKILL.md                 # workflow: goal → context → draft → approval → send → follow-up
└── references/
    ├── formula.md           # the formula, proof-of-work, checklist, tracking
    └── templates.md         # structures for 6 outreach goals
```

## License

MIT
