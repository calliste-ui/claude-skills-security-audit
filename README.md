# Claude Skills — Calliste Domont

A curated collection of structured skills for Claude — built from real consulting and AI workflow practice.

Each skill is a `SKILL.md` file that extends Claude's behavior for a specific domain: security auditing, learning diagnostics, software problem-solving, and more.

---

## What is a Claude Skill?

A Claude Skill is a structured instruction file (Markdown) that you load into Claude's context to activate a specialized behavior. Think of it as a reusable prompt architecture — with a defined scope, methodology, and output format.

Skills in this repo are:
- **Opinionated** — built around proven frameworks (ISC2 CC, etc.)
- **Anti-hallucination** — explicit rules on what Claude must not invent
- **Actionable** — structured outputs, not just summaries

---

## Skills

| Skill | Description | Status |
|---|---|---|
| [security-audit](./skills/security-audit/SKILL.md) | ISC2-anchored security evaluation for software, MCPs, APIs, repos | ✅ Stable |

More skills coming.

---

## Usage

1. Open Claude (claude.ai or API)
2. Copy the content of the `SKILL.md` file into your system prompt or paste it at the start of a conversation
3. Claude will activate the skill's behavior for the session

---

## Philosophy

These skills are built for practitioners — consultants, developers, architects — who use Claude as a real work tool, not a toy. The goal is repeatable, auditable, high-signal outputs.

If a skill is useful to you, star the repo. If you adapt one, a mention is appreciated but not required (MIT).

---

## Author

**Calliste Domont** — AI consulting & process optimization  
[github.com/calliste-ui](https://github.com/calliste-ui)

---

## License

MIT — see [LICENSE](./LICENSE)
