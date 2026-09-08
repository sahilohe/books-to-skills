# Books to Skills

Agent skills from three Eric Jorgenson books: *The Anthology of Balaji*, *The Almanack of Naval Ravikant*, *The Book of Elon*.

Each skill is a procedure an agent can run on real work — investing, founding, creating — not a quote dump and not a mood board. Load `SKILL.md` in any agent that supports skills.

They are not the books. They are not endorsed by the authors or the people the books are about.

## Pack

All skills are in [`skills/agentic/`](skills/agentic/). Install the whole directory.

| Skill | Source | Use when |
|-------|--------|----------|
| [tech-value](skills/agentic/tech-value/) | Balaji | Pricing impact vs hours; is this technology or theater |
| [truth-types](skills/agentic/truth-types/) | Balaji | Diligence, media, "studies show," on-chain claims |
| [idea-maze](skills/agentic/idea-maze/) | Balaji | Choosing or stress-testing a company idea |
| [ship-stack](skills/agentic/ship-stack/) | Balaji | Building: idea → mockup → … → profits |
| [frontier-invest](skills/agentic/frontier-invest/) | Balaji | What to fund, found, or join |
| [alignment](skills/agentic/alignment/) | Balaji | Incentives, hiring, politics as the team scales |
| [leverage](skills/agentic/leverage/) | Naval | Wealth vs wages; code/media vs hours |
| [judgment](skills/agentic/judgment/) | Naval | High-leverage decisions |
| [first-principles](skills/agentic/first-principles/) | Elon | Cost floors, Idiot Index, "always been expensive" |
| [the-algorithm](skills/agentic/the-algorithm/) | Elon | Simplify/delete/automate a product or process |
| [org-speed](skills/agentic/org-speed/) | Elon | Slow orgs, chain of command, org-shaped products |
| [scale-path](skills/agentic/scale-path/) | Elon | New tech: expensive/low-volume first, then mass |

### By project type

- **Investing:** `frontier-invest`, `tech-value`, `truth-types`, `judgment`, `idea-maze`, `scale-path`
- **Founding:** `idea-maze`, `ship-stack`, `alignment`, `leverage`, `org-speed`, `scale-path`
- **Creating:** `first-principles`, `the-algorithm`, `ship-stack`, `leverage`, `org-speed`

Left out on purpose: happiness, grind-as-identity, transhumanism, media careers. Those do not change how an agent ships an artifact. Use the books for those.

## Install

Copy skill directories into your agent's skills folder. Each directory must contain `SKILL.md` with YAML frontmatter (`name`, `description`).

```bash
cp -R skills/agentic/* <your-skills-dir>/
```

Examples: `~/.cursor/skills/`, `~/.claude/skills/`, or a project-local skills directory.

## Disclaimer

Not affiliated with Eric Jorgenson, Balaji Srinivasan, Naval Ravikant, Elon Musk, or their publishers. Interpretations and packaging errors are ours. The source books remain copyright of their authors; do not add copies of the books here.

## Sources

- [The Anthology of Balaji](https://balajianthology.com)
- [The Almanack of Naval Ravikant](https://navalmanack.com)
- [The Book of Elon](https://thebookofelon.com)
