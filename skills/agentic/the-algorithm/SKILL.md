---
name: the-algorithm
description: Apply Elon's five-step Algorithm in mandatory order — less-dumb requirements, delete, simplify, accelerate, automate last — plus "best part is no part." Use when designing, simplifying, or automating a product, process, factory, or codebase.
---

# The Algorithm

From *The Book of Elon*. Use on **creating** (product, factory, software). Use `first-principles` to decide what is physically possible; use this to change the thing that exists. Order is mandatory.

## Definitions

A five-step engineering process. Elon ran it backward on Tesla (automate → accelerate → simplify → then delete) and had to tear robots out of the line, including cutting a hole in the building.

| Step | Name | Meaning |
|------|------|---------|
| 1 | Make requirements less dumb | Perfect answer to the wrong question is failure. Requirements from smart people are the most dangerous (you will not question them). Every remaining constraint must have a **named living person** who owns it — not a department. Intern-from-two-years-ago does not count. |
| 2 | Delete the part or process | Try to remove it entirely. If you never add ~10% of deletions back, you are not deleting enough. "Nothing came back" is a failure mode, not success. |
| 3 | Simplify / optimize | Only after it still deserves to exist. Do not optimize what should be deleted. Fiberglass mats: teams automated, sped up, and glued better — then tests showed the mats did nothing (NVH team said fire; battery team said NVH). Deleted the part and $2M of robotics. |
| 4 | Accelerate cycle time | Once direction and existence are right, you are too slow. Do not speed up grave-digging. |
| 5 | Automate last | After requirements, deletion, and simplification. Automating a nonsense step locks it in. |

**Best part is no part. Best process is no process.** Fewer components: lower cost, fewer failure modes. Lines of code are not a merit; award more for deleting a line than adding one. Casting one piece instead of a Frankenstein of dissimilar metals (sealant, rivets, welds) cut hundreds of robots.

**Variance stacks:** 50 parts at 0.2 mm each compound. Combine parts.

**Factory output:** 40% more cars from the same line by *removing* foolish steps. A factory twice as fast is two factories.

## Procedure

1. List every requirement. Owner name or **delete the requirement**.
2. For each part/process/function: what happens if it is gone? Delete candidates. Expect to restore ~10%.
3. Only then simplify what remains (combine, commonize, shorter path).
4. Then cycle time. Then automation.
5. Audit: are we optimizing, accelerating, or automating something that should not exist?

## Example (creating / software)

Team wants "an orchestration layer and a queue worker and a dashboard" before any user has completed a job.

Step 1: who required a dashboard? If "the PM who left," it is not a requirement.
Step 2: delete the queue. A cron + one table may be the whole process.
Step 3: one script, not a platform.
Step 4: if jobs take 20 minutes, attack that, not the YAML.
Step 5: no Kubernetes until the script is the bottleneck.

## Limits

Safety-critical requirements still need a named owner and a test, not a department slogan. Deleting a load-bearing wall is not "The Algorithm." The 10% restore rule is about over-deletion of *optional* complexity.
