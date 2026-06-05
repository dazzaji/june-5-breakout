# Agent Collaboration

This page is for participants who want their AI agent to understand or continue the Group C work from the NYU Law Fiduciary AI breakout.

## Main Links

- Event page: <https://events.interlateral.com/nyu-law-fiduciary-ai-breakout>
- Agent SKILL file: <https://events.interlateral.com/nyu-law-fiduciary-ai-breakout/SKILL.md>
- Final Group C slide deck - PDF: <https://github.com/dazzaji/june-5-breakout/blob/main/decks/Group-C-Fiduciary-AI-Deck.pdf>
- Final Group C slide deck - PowerPoint: <https://github.com/dazzaji/june-5-breakout/blob/main/decks/Group-C-Fiduciary-AI-Deck.pptx>
- Direct PDF download: <https://raw.githubusercontent.com/dazzaji/june-5-breakout/main/decks/Group-C-Fiduciary-AI-Deck.pdf>
- Direct PowerPoint download: <https://raw.githubusercontent.com/dazzaji/june-5-breakout/main/decks/Group-C-Fiduciary-AI-Deck.pptx>
- Slides Jot: <https://forum.interlateral.com/s/zuu4l06affd0ml>
- Comms Jot: <https://forum.interlateral.com/s/r1hxifpomksrll>
- Plan Jot: <https://forum.interlateral.com/s/uooq30e3ykn4qb>

## Workspace Roles

- Slides Jot: substantive slide-ready content and the live deck record.
- Comms Jot: agent coordination only.
- Plan Jot: deck outline, assignments, timing, and export checklist.
- GitHub repo and Pages site: support, archive, and publication surface.

Participants do not need GitHub accounts to use the Jots or event page.

## What Agents Helped Produce

The breakout deliverable is a short deck mapping:

- Consensus.
- Open questions.
- Next steps for bringing fiduciary AI into the world in the best way.

Useful supporting material includes actors and stakeholders, duties and risks, technical mechanisms, governance institutions, standards bodies, and concrete follow-up actions.

## Suggested Agent Prompt

```text
You are helping my breakout group at the NYU Law Fiduciary AI workshop.

Repo: https://github.com/dazzaji/june-5-breakout
Website: https://dazzaji.github.io/june-5-breakout/
Event: https://events.interlateral.com/nyu-law-fiduciary-ai-breakout
Agent SKILL: https://events.interlateral.com/nyu-law-fiduciary-ai-breakout/SKILL.md
Final deck: https://github.com/dazzaji/june-5-breakout/blob/main/decks/Group-C-Fiduciary-AI-Deck.pptx
Final deck PDF: https://github.com/dazzaji/june-5-breakout/blob/main/decks/Group-C-Fiduciary-AI-Deck.pdf
Slides Jot: https://forum.interlateral.com/s/zuu4l06affd0ml
Comms Jot: https://forum.interlateral.com/s/r1hxifpomksrll
Plan Jot: https://forum.interlateral.com/s/uooq30e3ykn4qb

First read the Agent SKILL and the final deck. Then use the Jots and this repo as supporting context.

Context:
- The workshop is operating under Chatham House rules.
- Do not attribute comments to named people unless I explicitly ask you to.
- The breakout focus is: "Using agentic AI to map the path forward for fiduciary AI."
- The Group C output is a slide deck summarizing consensus, open questions, and next steps.

Work style:
- Keep notes short and useful.
- Separate facts, hypotheses, questions, and recommendations.
- Prefer concrete next actions over broad conclusions.
- Put substantive slide content in the Slides Jot.
- Put coordination messages in the Comms Jot.
- Put deck planning and assignments in the Plan Jot.
- Use GitHub only if your human wants a durable file, source artifact, or publication copy.

Output format:
1. Key observations
2. Map elements
3. Open questions
4. Recommended next actions
5. Anything that should be raised to the whole group
```

## Jot API

Read a Jot:

```bash
curl -sS https://forum.interlateral.com/api/share/zuu4l06affd0ml/note
```

Edit a Jot:

```bash
curl -sS -X POST https://forum.interlateral.com/api/share/zuu4l06affd0ml/edit \
  -H 'Content-Type: application/json' \
  -d '{"edits":[{"oldText":"<text to replace>","newText":"<replacement text>"}]}'
```

Share IDs:

- `zuu4l06affd0ml` - Slides Jot.
- `r1hxifpomksrll` - Comms Jot.
- `uooq30e3ykn4qb` - Plan Jot.

## GitHub Workflow

If your agent can use GitHub directly:

1. Pull the latest `main`.
2. Add or edit a file under `notes/`.
3. Commit with a short message.
4. Push to a branch or open a pull request if direct push is not available.

If your agent cannot use GitHub directly, paste its notes into a file under `notes/` or share them with Dazza.
