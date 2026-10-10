# multi-agent-code-generator
Multi-agent AI system that designs, writes, and tests software automatically. Architect models → judge synthesizes → Claude Code executes → tests → loop until done. Powered by OpenRouter free models.
# AI Dev Team

Multi-agent system that designs, codes, and tests software automatically.

## How it works
1. Multiple architect models generate solutions
2. Judge model synthesizes the best answer
3. Claude Code executes the prompt into working code
4. Report goes back to judge for review
5. Judge either approves and sends to testing, or returns fixes
6. Loop until the app is done

## Stack
- Python
- OpenRouter API (free models)
- Claude Code

## Status
Work in progress. Core loop works, edge cases under development.

## Roadmap
- [ ] Better error handling
- [ ] Web UI
- [ ] Support for local models
