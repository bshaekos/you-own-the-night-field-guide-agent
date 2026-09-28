# Who Owns the Night — Agent Mode

*Draft v1 — companion working session for the Field Guide in* Who Owns the Night*, by Barbakow.*

*Who Owns the Night* closes by handing the reader a Field Guide: fourteen chapters' worth of audit-cost-swap-check questions, gathered under six headings, meant to be handed to "any capable assistant." The book already wrote the interview. This repo runs it live — with an agent, in one sitting, instead of alone on paper afterward.

## Connect your agent

Paste this into Claude, Codex, or the agent of your choosing:

```text
You are helping me build my Night Plan — the six-heading document Who Owns the
Night asks its readers to assemble from the Field Guide at the back of the
book.

Use this repo as your source of truth, not memory or general self-help advice:
- README.md
- AGENTS.md
- night-plan/field-guide.md

Only open references/three-move-restart.md if I mention falling off the plan,
or ask for the restart directly.

Do not summarize the Field Guide or the book back to me. Interview me through
it, one heading at a time, in the order AGENTS.md sets out, and write back
each section as a short draft before moving to the next.

If I already have a partial Night Plan — from an earlier session, a notes
doc, anything — ask me to share it before we start from scratch.

Start by asking which heading I want to begin with, or recommend Current
State if I have no preference.

If you can't reach this repository, tell me and I'll paste
night-plan/field-guide.md directly.
```

## Start here

| I want to...                              | Use this                                                     |
| :----------------------------------------- | :------------------------------------------------------------ |
| Give my agent its operating instructions   | [`AGENTS.md`](AGENTS.md)                                       |
| Work through one heading at a time         | [`prompts/starter-prompts.md`](prompts/starter-prompts.md)     |
| Get back on the plan after falling off it  | [`prompts/restart-prompt.md`](prompts/restart-prompt.md)        |
| See the protocol the agent draws from      | [`night-plan/field-guide.md`](night-plan/field-guide.md)        |
| Read the book's main claims                | [`claims.md`](claims.md)                                        |
| Find further reading                       | [`references/three-move-restart.md`](references/three-move-restart.md) |

## What this repo is for

This repo answers three practical questions:

* **What is the method?** Fourteen chapters' worth of audit-cost-swap-check questions, already written, gathered under six headings — Current State, Underlying Needs, What Has Worked, The Target, Rules of Engagement, The Long Game.

* **What do I actually answer?** The same questions the book already asks. Nothing new is invented here — only how you arrive at the document changes.

* **What do I walk away with?** One document: your own Night Plan, in your own words, ready to hand to any assistant you trust to help hold the line.

## What to copy

Six headings, six entry points — run them in order, or start wherever tonight actually finds you:

* **Current State** — best for naming what your nights look like right now, hour by hour.
* **Underlying Needs** — best for naming what you're actually after when you default to a screen.
* **What Has Worked** — best for taking stock of what's already worked, even briefly.
* **The Target** — best for naming what your nights should be serving.
* **Rules of Engagement** — best for setting your non-negotiables and writing your restart moves before you need them.
* **The Long Game** — best for describing what sustained looks like a year out, and for assembling the finished document.

If you've already built a Night Plan and fell off it, skip straight to **Restart** — see [`prompts/restart-prompt.md`](prompts/restart-prompt.md).

## Scope

This is the portable-prompt path: no memory, no proactive check-in. You bring yourself back for the restart, the same way the book asks you to. A version that remembers you and messages you a week later is a different build — a platform-specific skill, not this repo — and trades that portability for a single tool it lives inside.

One sitting, one document. When the six headings are answered, the agent hands you the finished Night Plan and stops. It isn't meant to become an ongoing coaching relationship, and following `AGENTS.md`, it won't try to.