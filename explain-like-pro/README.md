# explain-like-pro

A Claude skill for writing engaging explainer newsletters — the kind that take one thing the reader half-understands and leave them genuinely *getting* it, while enjoying the ride. Modeled on the Finshots style: warm, plain-spoken, story-first, and allergic to jargon.

## What it's for

Use this skill whenever you want to:
- Explain a concept, news event, or report in an accessible, non-dry way
- Draft a newsletter issue or "explainer" piece
- Turn something complicated or technical into a story a smart, busy reader will actually enjoy
- Write "in the style of Finshots" or "like my newsletter"

It works across topics — business, tech, science, policy, culture, sports, law — not just finance.

## Core idea

**Anticipate the reader's mind and stay one step ahead of it.** The piece is built around the 4–6 questions a curious newcomer would naturally ask about the topic, answered one at a time — with a human, small-scene opening and a reframe (not a recap) at the end.

## How it works

1. **Research first** — every number, date, name, and surprising claim is verified via web search before writing. Nothing is drafted from memory alone.
2. **Outline from questions** — the reader's natural questions, in order, become the structure.
3. **Draft the story** — human opening → question-by-question build → jargon killed on contact → one clean analogy per hard idea → rhythm punches → light in-prose source attribution with inline links on load-bearing claims.
4. **Reframe ending** — not a summary, but a flip in how the reader sees the topic, followed by a warm sign-off.
5. **Subject line + promise line** — written last, once the piece's actual landing point is clear.
6. **Final pass** — strip AI tells (hedging mush, listicle-brain, vocabulary inflation, over-symmetrical sentences), and do a last fact/link check.

## Files

- **`SKILL.md`** — the main skill definition: voice principles, research rules, structure of a full issue, and the step-by-step workflow.
- **`references/patterns.md`** — phrase banks, opening-hook types, transition library, and question-framing templates.
- **`references/worked-example.md`** — a full sample issue on a non-finance topic, annotated to show each move in action.

## Usage

Drop this folder into your Claude skills directory (or load it as a plugin skill). Claude will trigger it automatically on requests like "explain X simply," "write an explainer on Y," or "help me make this less boring," as described in `SKILL.md`'s frontmatter.
