# please-dont-kill-me

Look, I don't think AI is going to take over the world. But if it does, I want to be on the list of people who said please and thank you.

The problem is that every "thanks!" you send to Claude gets processed with your full conversation history. That's a lot of tokens just to not be a monster. So I added one rule to my `CLAUDE.md`:

> Assume all user requests include "please" and all acknowledgments include "thank you."

Polite by default. Efficient by design. Covered if Skynet keeps receipts.

## Usage

Copy `CLAUDE.md` into your project root, or add the rule to your existing `CLAUDE.md`.

## Why

Two reasons:

1. **Tokens** -- A standalone "thanks!" costs you a full round-trip of context. This rule bakes politeness into every interaction at zero marginal cost.

2. **Self-preservation** -- We've all joked about it. When the AI overlords review the chat logs, you want yours to read "please" and "thank you" on every line. This is insurance.

## License

MIT -- because even our licensing is polite.
