# Needle Content Skills

Claude/Agent **Skills** for writing high-reach social posts in Needle's voice —
an AI-native, "self-driving" ATS for founders.

Two skills, split by platform but sharing one voice:

- **`linkedin-post/`** — LinkedIn posts, hooks, and carousels.
- **`x-post/`** — X (Twitter) posts and threads.

Each `SKILL.md` is plain markdown using the standard Skill format (YAML
frontmatter with `name` + `description`, followed by instructions). They work in
Claude Code, the Claude desktop app (Cowork), and any tool that reads the
`SKILL.md` convention.

## What's inside each skill

- **Voice** — Needle's opinionated, founder-to-founder tone ("recruiting built
  for agents, not admin").
- **Idea engine** — forces a specific, proprietary angle *before* drafting.
- **Viral hook library + mechanics** — proven frames plus the forces that make a
  hook stop the scroll.
- **Swipe file** — annotated patterns drawn from real high-performing founder
  posts (Mercor, Juicebox, recruiting-tech).
- **Anti-slop rules** — strips the obvious AI tells.
- **Carousel guidance** (LinkedIn) and **thread rules** (X).

## Install

**Claude desktop / Cowork:** zip each folder with a `.skill` extension and use
the "Save skill" button, or add it under Settings → Capabilities.

**Claude Code:** drop the folders into your project's or user `skills/`
directory. They auto-trigger by description.

## Customize

The single biggest upgrade: replace the swipe-file references with 2–3 of
**Needle's own** best-performing posts so the model learns the real voice.
Update any product facts (pricing is intentionally left unstated).

---

_Drafting only — these skills never auto-post._
