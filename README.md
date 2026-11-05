# AGENTS.md for risk and finance

A drop-in instruction file that tells coding agents how to work in risk and finance without making things up: verify before asserting, gate actions by consequence, stop when a control fails, and keep a record that answers four questions.

It was shared as the take-home kit from the invited talk "Designing Oversight In: governing agentic AI in financial institutions" at IOCRF 2026, the 2nd International Online Conference on Risk and Financial Management (MDPI), on 3 November 2026. Slides and every source: [sarthakgpt.com/talks](https://sarthakgpt.com/talks/).

## Install

Save `AGENTS.md` in the root of your repository.

| Tool | What to do |
|---|---|
| Codex, Cursor, GitHub Copilot coding agent, Windsurf, Zed and other AGENTS.md tools | Nothing else. They read `AGENTS.md` from the root. |
| Claude Code | Read automatically when the project has no `CLAUDE.md`. If it has one, add `@AGENTS.md` as its first line. |
| Copilot chat in the IDE | Also copy it to `.github/copilot-instructions.md`. |
| Anything else | Point the tool's instruction-file setting at `AGENTS.md`, or paste it into the system prompt. |

Instruction files are context, not enforcement. For anything that must never happen, add a permission rule or a pre-action hook in your tool as well.

## Using it

Replace the tier examples with your own systems before relying on it. Issues and pull requests with improvements from practice are welcome.

Not legal, regulatory or investment advice.

## Citation

If you use or adapt it, please cite it. See `CITATION.cff`, or use the "Cite this repository" button.

Author: Sarthak Gupta ([sarthakgpt.com](https://sarthakgpt.com))
