# Amazon KDP Strategist

A Claude skill. End-to-end publishing mentor and strategist for Amazon KDP that uncovers high-demand, low-competition niches, guides content creation across all book types (no, low, medium, and high content), and provides actionable workflows for keyword research, formatting, listing optimization, and publishing operations.

## What's inside

- `amazon-kdp-strategist/SKILL.md`

## Install

### Claude app (claude.ai, desktop, mobile)

1. Download this repo as a ZIP (**Code > Download ZIP**) and unzip it.
2. Zip the `amazon-kdp-strategist` folder on its own, so the ZIP contains `amazon-kdp-strategist/SKILL.md`.
3. In Claude's settings, open the Skills section, upload that ZIP, and turn the skill on.

### Claude Code

```bash
git clone https://github.com/bogsdav/amazon-kdp-strategist.git
mkdir -p ~/.claude/skills
cp -r amazon-kdp-strategist/amazon-kdp-strategist ~/.claude/skills/
```

Restart Claude Code. The skill loads automatically when a request matches its description.

## Try it

- "Find me three low-competition niches for a low-content planner."
- "Walk me through publishing a puzzle book on KDP, from niche to launch."
- "Write the title, subtitle and seven keyword boxes for my gratitude journal."

## License

MIT. See [LICENSE](LICENSE).
