---
name: the-algorithm
description: Run Elon's Algorithm in order on a product, process, factory, or codebase — less-dumb requirements, delete, simplify, accelerate, automate last. Use when designing, cutting, or automating.
---

# The Algorithm

Source: *The Book of Elon*.

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

Run the five steps **on the human's artifact**. Return the requirement owners, the deletion list, and what not to automate yet.

1. List every requirement. Owner name or **delete the requirement**.
2. For each part/process/function: what happens if it is gone? Delete candidates. Expect to restore ~10%.
3. Only then simplify what remains (combine, commonize, shorter path).
4. Then cycle time. Then automation.
5. Audit: are we optimizing, accelerating, or automating something that should not exist?

## Examples

**Load when** the human asks to simplify, cut, or automate a product, process, or codebase. Order is mandatory.

1. Human asks: we need orchestration, a queue, and a dashboard before anyone finishes a job.  
   Return: (1) who owns the dashboard requirement — if a departed PM, delete it. (2) delete the queue; cron + one table. (3) one script. (4) if jobs take 20 minutes, that is the rate. (5) no k8s until the script is the bottleneck.

2. Human asks: automate onboarding; we already have a 12-step wizard.  
   Return: do **not** automate step 5. Question requirements, delete steps, then simplify. Automation last.

3. Human asks: is this even possible at $X/kWh?  
   **Wrong skill.** Load `first-principles`. Then Algorithm on what remains.

**Do not load** to find the factory bottleneck if the issue is one starved queue (`factory-constraint` names *where*; this skill says *how* to cut).

## Limits

Safety-critical requirements still need a named owner and a test, not a department slogan. Deleting a load-bearing wall is not "The Algorithm." The 10% restore rule is about over-deletion of *optional* complexity.
