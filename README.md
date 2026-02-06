# interview-skill

A Claude Code skill that interviews you about your project before writing anything. Instead of jumping straight into code, it asks questions about implementation, UI, UX, tradeoffs, and edge cases until it actually understands what you want. Then it writes a spec.

## How it works

1. You tell it what you're building
2. It asks you questions (skipping the obvious ones)
3. It keeps going until there's nothing left to clarify
4. It writes the spec to a file

## Install

Drop `SKILL.md` into your `.claude/skills/` directory (or wherever you keep skills).

## Why

Specs written without enough context end up vague or wrong. This skill forces the conversation to happen first.
