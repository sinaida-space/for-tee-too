<p align="center">
  <img src="images/brain_8bit_roses.png" alt="8‑bit pixel brain surrounded by red roses and purple wildflowers on black" width="100%" />
</p>

# for‑tee‑too

A Claude Code skill that argues with your idea until it becomes something real.

[sinaida.eu](https://sinaida.eu/) · [@sin.ai.da](https://www.instagram.com/sin.ai.da/)

---

## What this actually is

`for-tee-too` is a [Claude Code](https://claude.com/product/claude-code) skill: a
folder of instructions that turns a chat into a structured brainstorming session.
Invoke it with `/for-tee-too` and it runs a guided, one‑question‑at‑a‑time
conversation, mixing hard business scoping with the creative‑ideation toolkit from
Sinaida's own experience in corporate and artistic environments.

It is not a chatbot that writes your project brief for you. It plays a studio
partner who keeps asking “why” until the answer stops moving, then makes you
defend the direction you land on.

## Why it exists

Ideas rarely die from lack of talent. They die from three quieter&nbsp;failures:

- **The blank page never gets a shape**, because the freedom to do anything
  makes it impossible to do the first thing.
- **The first workable idea becomes the only idea**, because the brain rewards
  “found it” and stops looking.
- **The creative part gets built without ever meeting the business part**: no
  scope, no audience, no answer to “why does this matter, and to whom.”

Most AI brainstorming tools make this worse. Ask for ideas, get a wall of
options, none of them yours. `for-tee-too` inverts the relationship: the model
asks, offers, and pushes back. The user decides. The guide it's built on states
the principle directly: *the model generates, you decide. Without filtering an
answer through your own judgment, you get something statistically likely, not
something good.*

## How it works

A session moves through eight phases, each built from a question bank rather
than a fixed script:

1. **Frame**: what is this session for, and what kind of thing is it (art,
   client work, a venture, something else)?
2. **Blockers** (only if you're stuck): six recognizable failure patterns,
   from blank‑page paralysis to the inner critic showing up too early, each
   with one matching move to get unstuck.
3. **Diagnosis**: a real problem statement, run through *5&nbsp;Whys* until
   the wording stops changing.
4. **Expansion**: divergent thinking through reverse brainstorming, SCAMPER,
   analogical thinking, and constraint design, matched to whatever you're
   actually stuck on, and only after you've generated a few raw ideas
   yourself.
5. **Business grounding**: a condensed pass through problem, audience, goal,
   scope, competitors, resources, risk, market, and business model, weighted
   to fit an art piece, a client project, or a venture, never skipped
   entirely.
6. **Focus**: a Six Hats pass on the shortlist, narrowed to one direction.
7. **Prototype**: the roughest version that could exist by tomorrow, and how
   you'd test it.
8. **Ownership test**: can you defend the final call with three of your own
   reasons, none of them “the AI suggested it”? If not, the session loops
   back instead of calling it done.

At the end, it asks how you want the result: a Markdown file, a Word document,
or a PDF, and writes it in your own words, not its summary of&nbsp;them.

<p align="center">
  <img src="images/brain_8bit_flowers.png" alt="8‑bit pixel brain surrounded by red roses and purple wildflowers on black" width="100%" />
</p>

## Files in this repo

```
SKILL.md                  entry point: role, operating rules, session flow
references/methods.md     blockers, the 9 thinking tools, symptom → method matrix
references/frameworks.md  business‑case question bank, premortem, PR‑FAQ, lean canvas, etc.
images/                   the two banners above
```

## Install

Copy the skill into your Claude Code skills folder:

```bash
git clone https://github.com/sinaida-space/for-tee-too.git
mkdir -p ~/.claude/skills/for-tee-too
cp -r for-tee-too/SKILL.md for-tee-too/references ~/.claude/skills/for-tee-too/
```

Then invoke it in any Claude Code session with `/for-tee-too`, or just describe
what you're trying to scope, brainstorm, or decide, and it triggers on its own.

## Source

The creative‑ideation framework (blockers, the 9 tools, the 5‑phase process,
and the AI‑as‑coauthor protocols) is adapted from Sinaida's own guide,
published at [sinaida.eu](https://sinaida.eu/). The business‑case framework is
her own scoping checklist from years running projects at&nbsp;GE.

---

[sinaida.eu](https://sinaida.eu/) · [@sin.ai.da](https://www.instagram.com/sin.ai.da/)

This repo is a production mirror.

I develop in a private repo and publish releases here. Issues and ideas are welcome: I read them and carry them over. Pull requests stay open as suggestions; I carry good changes over by hand and then close the PR.
