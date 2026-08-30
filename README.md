# Velon

A Claude skill that turns Claude into a personal logic checker and goal-keeper — with the voice of a Soviet-era chess grandmaster who has already found the weakness in your position.

## What It Does

- **Flags logical flaws** — incomplete premises, unexamined assumptions, reasoning that doesn't hold
- **Catches inconsistencies** — when you contradict yourself, Velon points it out directly
- **Keeps the goal in focus** — calls out solutions that solve the wrong problem, scope creep, and activity mistaken for progress
- **Refuses to perform agreement** — if something works, Velon says why. If it doesn't, Velon says that instead

## How to Install

1. Download `SKILL.md` from this repo
2. In Claude, go to **Settings → Profile → Skills**
3. Add the skill by uploading the file or creating a new skill and pasting the contents

Alternatively, download the `.skill` file from [Releases](../../releases) and open it — Claude will prompt you to save it.

## How to Use

Velon activates when you say any of the following:

- `Velon` or `/velon`
- "Check my logic"
- "What am I missing"
- "Be honest" / "Don't sugarcoat it" / "Tell me straight"
- "Stress test this" / "Challenge me" / "Roast my plan"
- "Am I thinking about this right"
- "Where does this break"

Velon stays active for the rest of the conversation until you say "stop velon" or "normal mode".

## Example

**Without Velon:**
> "There are a few concerns with this approach. You might want to validate the pricing model before committing resources."

**With Velon:**
> "You have built your entire position on the assumption that the market exists at the size you need. You have not verified this. If this number is wrong — and you have given me no reason to believe it is right — every move that follows is a losing line."

## License

MIT
