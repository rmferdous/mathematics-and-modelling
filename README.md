# Model Lab for Mathematics and Modelling

Learning maths through building models: a self-directed curriculum from GCSE/AS
foundations to complexity economics, one animated agent-based model per phase.
Each build pairs a hand derivation with a simulation, and checks whether the
analytical answer matches what the model does.

All data used is public or synthetic.

---

## How to resume (read this first)

**The rule:** no AI remembers anything between chats. Progress lives in
`progress_log.md`. The LEARNER STATE block at the top of that file is the memory.

### Start a session
1. Open `progress_log.md` and copy the top LEARNER STATE block.
2. Open a new AI chat (Copilot, Claude, ChatGPT - any works).
3. Upload `docs/curriculum.docx` or paste `docs/AI_BRIEFING.md`.
4. Paste the LEARNER STATE and say:
   > Read the briefing, then start today's session. Phase 0 was revised -
   > follow the "Current plan" section of my README, pasted below.
   Then paste the "Current plan" section from this README.
5. Work on paper. The AI sets problems and marks working. It does not solve.

### End a session
1. Ask the AI: "Give me the updated LEARNER STATE block."
2. On GitHub: `progress_log.md` -> pencil icon -> paste the new block at the
   **top** (keep old blocks below) -> Commit changes.
   Commit message: `Session YYYY-MM-DD: <topic>`

### Finish a build
1. Open the phase folder -> Add file -> Upload files.
2. Upload the notebook (`.ipynb`), the animation (`.gif`) and `derivation.md`.
3. Update the Builds table below: set Status to Done and link the GIF.

### Coming back after a break
- Do not restart. Resume from the latest LEARNER STATE.
- First session back is Review only: redo the review list.
- Away more than a month: ask the AI for a 20-minute recap quiz on the
  current phase before any new material.

### Working constraints
- Work laptop: GitHub is browser-only (no cloning). Create, edit and upload
  through the web interface. Typing `folder/file.md` as a new file name
  creates the folder.
- Run notebooks locally where possible. Browser fallbacks: GitHub Codespaces,
  or Google Colab (File -> Open notebook -> GitHub).
- Approved by line manager. Keep all work data out of this repo.
- Use plain characters (`-` not long dashes) to avoid encoding errors.

---

## Current plan (overrides the curriculum doc where they differ)

**Phase 0 revised 2026-10-17.** Diagnostic: A-level Pure Paper 1, June 2022.
No questions answerable. Q1, 2, 3 and 5 recognised. Start below A-level.

| Step | Content | Resource |
|---|---|---|
| 0a | GCSE Higher Paper 1 (non-calculator), cold. Tag each question: confident / unsure / never seen | Corbettmaths or Physics & Maths Tutor |
| 0b | Algebra bootcamp on gaps found in 0a | Corbettmaths |
| 0c | AS Pure (Year 1) | Dr Frost Maths, or Edexcel Pure Mathematics Year 1 textbook |
| 0d | Checkpoint: AS Pure paper | Physics & Maths Tutor |
| End of Phase 0 | A-level Pure Paper 1, **June 2019** (held back - do not look) | Physics & Maths Tutor |

A-level Year 2 content (integration techniques, product rule, etc.) moves into
Phase 1.

**Weekly rhythm (about 1 hour a day):** Learn x2, Practise x2, Build x1, Review x1.
Bad day: one review problem on paper, 15 minutes. Never miss twice.

---

## Builds

| Phase | Maths | Build | Status |
|---|---|---|---|
| 0 | Algebra, functions, logs, series | Growth and discounting visualiser | In progress |
| 1 | Single-variable calculus | Animated contagion ABM vs logistic curve | Not started |
| 2 | Linear algebra | Shock propagation on an input-output network | Not started |
| 3 | Probability | Monte Carlo harness and calibration | Not started |
| 4 | Multivariable calculus | Firms climbing a profit landscape | Not started |
| 5 | Dynamical systems | Goodwin cycle and ABM-to-ODE bridge | Not started |
| 6 | Stochastic processes and networks | Herding and peer effects on networks | Not started |
| Capstone | All | Animated policy lab | Not started |

<!-- When a build finishes, add its GIF below, e.g.
phase1_contagion/contagion.gif -->

---

## Repository map

```
README.md          <- how to resume + current plan (this file)
progress_log.md    <- LEARNER STATE blocks, newest at top
docs/
  curriculum.docx  <- full curriculum, with AI briefing appendix
  AI_BRIEFING.md   <- plain-text copy of the appendix, for pasting
phase0_growth/  ...  phase6_networks/  capstone_policy_lab/
```
