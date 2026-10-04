# Who Owns the Night — Agent Mode

*Draft v2 — companion working session for the Field Guide in Who Owns the Night, for review by Jeff Barbakow.*

*Who Owns the Night* closes by handing the reader a Field Guide: fourteen chapters' worth of audit-cost-swap-check questions, gathered under six headings, meant to be handed to "any capable assistant." The book already wrote the interview. This repo runs it live — with an agent, in one sitting, instead of alone on paper afterward.

Use this companion GitHub repo as your source of truth:
https://github.com/bshaekos/you-own-the-night-field-guide-agent

## Connect your agent

Paste this into Claude, Codex, or the agent of your choosing:

```text
You are helping me build my Night Plan — the six-heading document Who Owns the
Night asks its readers to assemble from the Field Guide at the back of the
book.

Use this repo as your source of truth, not memory or general self-help advice:
- README.md
- AGENTS.md
- night-plan/interviewing-the-reader.md
- night-plan/assembling-field-guide.md

Only open night-plan/three-move-restart.md if I mention falling off the plan,
or ask for the restart directly.

Do not summarize the Field Guide or the book back to me. Interview me through
it, one chapter at a time, in the order AGENTS.md sets out, and write back
each section as a short draft before moving to the next.

Start by asking me whether I'm starting a new Night Plan or picking up one I already have — from an earlier session, a notes doc, anything. If I already have one, ask me to paste it into the chat before we go any further, and pick up from wherever it leaves off rather than restarting the interview.

If I'm starting fresh, begin with Chapter 1 and move through the rest in the order AGENTS.md sets out.

If you can't reach this repository, tell me and I'll paste
night-plan/interviewing-the-reader.md directly.
```

## Start here

| I want to... | Use this |
| :--- | :--- |
| Give my agent its operating instructions | [`AGENTS.md`](AGENTS.md) |
| Work through one chapter at a time | [`prompts/starter-prompts.md`](prompts/starter-prompts.md) |
| Get back on the plan after falling off it | [`prompts/restart-prompt.md`](prompts/restart-prompt.md) |
| See the interview the agent runs, chapter by chapter | [`night-plan/interviewing-the-reader.md`](night-plan/interviewing-the-reader.md) |
| Get a quick summary of what each chapter is about | [`assets/chapter-summaries.md`](assets/chapter-summaries.md) |
| See how the answers get assembled into six headings | [`night-plan/assembling-field-guide.md`](night-plan/assembling-field-guide.md) |
| Read the book's main claims | [`assets/claims.md`](assets/claims.md) |
| Find further reading | [`REFERENCES.md`](REFERENCES.md) |

## What this repo is for

This repo answers three practical questions:

- **What is the method?** Sixteen chapters' worth of audit-cost-swap-check questions, already written, answered in order, then gathered under six headings — Current State, Underlying Needs, What Has Worked, The Target, Rules of Engagement, The Long Game.
- **What do I actually answer?** The same questions the book already asks. Nothing new is invented here — only how you arrive at the document changes.
- **What do I walk away with?** One document: your own Night Plan, in your own words, ready to hand to any assistant you trust to help hold the line.
## What to copy

Sixteen chapters, answered in order — each one builds toward the six headings the finished Night Plan gets assembled into at the end:

- **Current State** — covers what your nights look like right now, hour by hour.
- **Underlying Needs** — covers what you're actually after when you default to a screen.
- **What Has Worked** — covers what's already worked, even briefly.
- **The Target** — covers what your nights should be serving.
- **Rules of Engagement** — covers your non-negotiables and your restart moves, written before you need them.
- **The Long Game** — covers what sustained looks like a year out, and closes with assembling the finished document.
If you've already built a Night Plan and fell off it, skip straight to **Restart** — see [`prompts/restart-prompt.md`](prompts/restart-prompt.md). That's the one exception to running the interview in order: the restart isn't a chapter, it's how you get back to the one you left off on.

## Scope

This is the portable-prompt path: no memory, no proactive check-in. You bring yourself back for the restart, the same way the book asks you to. A version that remembers you and messages you a week later is a different build — a platform-specific skill, not this repo — and trades that portability for a single tool it lives inside.

One sitting, one document. When all sixteen chapters are answered, the agent hands you the finished Night Plan and stops. It isn't meant to become an ongoing coaching relationship, and following `AGENTS.md`, it won't try to.