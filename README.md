# Skill Onboarding

**From zero to Skill Builder in 15 minutes.** A hands-on skill that teaches you how to create, evaluate, and iterate on Claude Code / Codebuddy skills -- by actually building them.

## What is this?

This is a **skill** (a markdown-driven instruction set for AI coding assistants like Claude Code and Codebuddy). When loaded, it turns your AI into a personal skill-building coach that walks you through creating your first skill, exploring the skill marketplace, and engineering high-quality skills with tests and benchmarks.

## How to use

### Quick start (Claude Code)

```bash
# Clone to your skills directory
git clone https://github.com/howoneai/skill-onboarding.git ~/.claude/skills/skill-onboarding

# Start a new conversation and say:
# "teach me skills" or "I want to learn about skills"
```

### Quick start (Codebuddy)

```bash
git clone https://github.com/howoneai/skill-onboarding.git ~/.codebuddy/skills/skill-onboarding

# Start a new conversation and say:
# "teach me skills"
```

That's it. The AI will automatically detect the skill and guide you through the entire journey.

## What you'll learn

| Stage | What happens |
|-------|-------------|
| 0 | Open an interactive explainer page -- 30 seconds to get the big picture |
| 1 | Build your first working skill from scratch |
| 2 | Experience 3 things skills can do that plain prompts can't |
| 3 | Find, evaluate, and fork skills from the community marketplace |
| 4 | Graduate with a cheat sheet and daily workflow |
| 5 (optional) | Get personalized skill recommendations based on your work |
| 6 (optional) | Set up a "skill inbox" -- drop materials in, AI turns them into skills |
| 7 (optional) | Engineer skills with test cases, benchmarks, and description optimization |

## Included tools

```
scripts/
  init_skill.py           # Scaffold a new skill
  show-skills.sh          # List all installed skills across directories
  evaluate-skill.sh       # Auto-evaluate skill quality (structure + content)
  package_skill.py        # Package a skill for sharing
  run_loop.py             # Description trigger-rate optimization loop
  aggregate_benchmark.py  # Aggregate benchmark data across iterations

agents/
  grader.md               # Sub-agent for evaluating test assertions
  comparator.md           # Blind comparison sub-agent
  analyzer.md             # Benchmark analysis sub-agent

assets/
  skill-explainer.html    # Interactive visual explainer
  eval_review.html        # Description optimization review page
```

## Tell your AI how to use this

Copy-paste this to your AI:

> I just installed the skill-onboarding skill. Teach me how to create and use skills -- start from Stage 0.

Or simply say "learn skills" / "teach me skills" in a new conversation. The AI will pick it up automatically from the `description` field in `SKILL.md`.

## License

Apache 2.0
