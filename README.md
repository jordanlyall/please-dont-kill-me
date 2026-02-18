# polite-prompt

I want to say please and thank you to Claude, but I don't want to waste tokens on it.

So I added a rule to my `CLAUDE.md`:

> Assume all user requests include "please" and all acknowledgments include "thank you."

Polite by default. Efficient by design.

## Usage

Copy `CLAUDE.md` into your project root, or add the rule to your existing `CLAUDE.md`.

## Why

Every message you send gets processed with the full conversation history. A standalone "thanks!" costs you a full round-trip of context. This rule lets you skip the pleasantries without being a monster.

## License

MIT
