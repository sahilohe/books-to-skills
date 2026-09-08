---
name: org-speed
description: Redesign an org or process for shortest-path communication and kill silos that show up as boxes-in-boxes in the product. Use when unsticking a slow, political, or org-chart-shaped system.
---

# Org speed

Source: *The Book of Elon*.

## Definitions

**Chain of command (failure mode):** IC → manager → director → VP → other VP → … to reach the person who can act, then back. Serves the manager's power. Produces superdumb outcomes. Communication must take the **shortest path** that gets the job done. Anyone talks to anyone. You are *obligated* until the right thing happens. Managers who enforce chain of command should not remain managers.

**Work for the company, never the department.** Department success-as-relative creates silos. Silos are a natural tendency; fight them.

**Org boundaries appear in the product.** Two teams each need an enclosure → box in a box (Model 3 battery cover under the car floor). Extra mass and cost. Delete the duplicate. Design, engineering, and manufacturing cannot be separated: the line worker must be able to grab the designer ("why did you make it this way"). Someone else's hand on the stove is slower to pull off.

**Skip-level:** do not only meet managers. Meet the level below. **Go to the problem** — physically, immediately. Starship wall thickness: welders, not executives, knew 4 mm would work.

**Acronyms:** a thousand people inventing jargon produces a glossary nobody remembers; people sit silent. Kill opaque acronyms. GUI is fine (engineers already know it). MVac for a specific engine, approved and rare, is fine. Test: does this help or hurt communication?

**Failure is irrelevant unless catastrophic.** If failure is not allowed, choices become conservative and you may go backward. Do not fire people for a hard failure when they were smart and trying. Fire for no motivation around the mission or not giving what they can. Look at incentives: is innovation actually rewarded?

**Vector, not scalar:** high speed in the right direction, with course correction (guided missile). Speed is offense and defense (SR-71: acceleration was the defense). Rate of innovation *is* IP protection — copiers trail last year's work.

**Time is the currency.** Burn rate vs future revenue per day. Meetings: kill large ones unless the whole room needs them; kill frequent ones when the urgency is gone. Leave when you add no value — staying is the rude act.

**Most useful thing I could do:** running triage, constantly.

## Procedure

1. Trace the last delayed decision. How many hops? Draw the shortest legal path.
2. Inspect the artifact for org-shaped waste (duplicate layers, APIs that exist so two teams do not talk).
3. Name who sits at the problem vs who reports about it. Go to the problem.
4. Glossary: list acronyms. Kill any that fail the communication test.
5. Incentives: what happens to someone who tries and fails vs someone who blocks?
6. Meetings: delete or shorten. Urgency calendar, not standing theater.

## Examples

**Load when** the human's team is slow, tickets ping-pong, or the product looks like the org chart.

1. Human asks: platform squad and app squad each have a gateway; users wait on tickets.  
   Return: chain of command. Shortest path = both engineers on the failing request. Extra gateway = box in a box unless a named owner (`the-algorithm`). Founder sits with on-call.

2. Human asks: our glossary has 80 acronyms; new hires nod in silence.  
   Return: kill list. Keep only terms outsiders already know. Test: helps or hurts.

3. Human asks: sales vs product OKRs conflict.  
   **Wrong skill** for payoff math. Load `alignment`. Then fix the hops here.

**Do not load** to delete a part in the CAD (`the-algorithm`) unless the part exists because two teams each needed an enclosure.

## Limits

Skip-level is not public humiliation. Safety and legal still need named owners. Speed does not mean shipping an unsafe rocket.
