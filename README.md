# Books to Skills

Skills for **agents that work for a human** on that human's investing, founding, and creating work.

## Who these are for

**The agent reads the skill. The human gets the work.**

The human assigns a task — a memo, company, product, hire, factory, channel. The agent loads the matching skill and returns an artifact: maze, verdict, ranked list, req, patch, go/no-go. Not a pep talk. Not a celebrity voice.

Typical loop: human asks → agent loads a skill below → agent returns the work product → human decides.

Works in any system that loads `SKILL.md` directories (Cursor, Claude, a project folder). Not one IDE.

Not for: reading Balaji, Naval, or Elon as a substitute for this pack; life, mood, or grind coaching; tasks outside investing, founding, and creating.

Methods are derived from Eric Jorgenson's *The Anthology of Balaji*, *The Almanack of Naval Ravikant*, and *The Book of Elon*. Not the books, and not endorsed by the authors or the people the books are about.

## Pack

All skills are in [`skills/agentic/`](skills/agentic/). Copy that directory into the agent's skills folder.

| Skill | Source | Use when |
|-------|--------|----------|
| [tech-value](skills/agentic/tech-value/) | Balaji | Pricing impact vs hours; is this technology or theater |
| [truth-types](skills/agentic/truth-types/) | Balaji | Diligence, media, "studies show," on-chain claims |
| [idea-maze](skills/agentic/idea-maze/) | Balaji | Choosing or stress-testing a company idea |
| [ship-stack](skills/agentic/ship-stack/) | Balaji | Building: idea → mockup → … → profits |
| [frontier-invest](skills/agentic/frontier-invest/) | Balaji | What to fund, found, or join |
| [alignment](skills/agentic/alignment/) | Balaji | Incentives, politics, burn vs bus number |
| [hire-underpriced](skills/agentic/hire-underpriced/) | Balaji, Elon | Geniuses no one knows yet; exceptional ability |
| [distribution](skills/agentic/distribution/) | Balaji | Product vs channel; paired growth metrics |
| [execute](skills/agentic/execute/) | Balaji | List-rank-iterate; one thing per person |
| [media-system](skills/agentic/media-system/) | Balaji | Detect infotainment vs usable media; build go-direct |
| [mission-filter](skills/agentic/mission-filter/) | Elon, Balaji | Useful vs status; don't argue, build |
| [leverage](skills/agentic/leverage/) | Naval | Wealth vs wages; code/media vs hours |
| [judgment](skills/agentic/judgment/) | Naval | High-leverage decisions |
| [first-principles](skills/agentic/first-principles/) | Elon | Cost floors, Idiot Index, "always been expensive" |
| [the-algorithm](skills/agentic/the-algorithm/) | Elon | Simplify/delete/automate a product or process |
| [org-speed](skills/agentic/org-speed/) | Elon | Slow orgs, chain of command, org-shaped products |
| [scale-path](skills/agentic/scale-path/) | Elon | New tech: expensive/low-volume first, then mass |
| [factory-constraint](skills/agentic/factory-constraint/) | Elon | Factory is the product; attack the bottleneck |

- **Investing:** `frontier-invest`, `tech-value`, `truth-types`, `judgment`, `idea-maze`, `scale-path`, `media-system`, `mission-filter`
- **Founding:** `idea-maze`, `ship-stack`, `execute`, `distribution`, `hire-underpriced`, `alignment`, `leverage`, `org-speed`, `scale-path`, `media-system`, `mission-filter`
- **Creating:** `first-principles`, `the-algorithm`, `factory-constraint`, `ship-stack`, `execute`, `hire-underpriced`, `leverage`, `org-speed`, `media-system`, `mission-filter`

Happiness, grind-as-identity, and transhumanism are not in this pack.

## Install

```bash
cp -R skills/agentic/* <your-skills-dir>/
```

Examples: `~/.cursor/skills/`, `~/.claude/skills/`, or a project-local skills directory.

## Attribution

Not affiliated with Eric Jorgenson, Balaji Srinivasan, Naval Ravikant, Elon Musk, or their publishers. Interpretations and packaging errors are ours. The source books remain copyright of their authors.

- [The Anthology of Balaji](https://balajianthology.com)
- [The Almanack of Naval Ravikant](https://navalmanack.com)
- [The Book of Elon](https://thebookofelon.com)
