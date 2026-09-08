---
name: org-speed
description: Design communication and incentives for shortest-path execution — skip chain of command, kill silos that show up as boxes-in-boxes in the product, skip-level to the problem. Use when a team, company, or process is slow, political, or shipping org-chart-shaped work.
---

# Org speed

From *The Book of Elon* (Designing the Organization). Use on **founding** and **creating**. Pair with `alignment` for incentive math and `the-algorithm` for the artifact itself.

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

## Example (founding)

Two squads, "platform" and "app," each with an API gateway "for isolation." Users wait on a ticket that ping-pongs.

That is chain of command. Shortest path: one engineer from each squad on a call with the failing request. The extra gateway is a box in a box — delete unless a named person owns the requirement (`the-algorithm` step 1). Skip-level: founder sits with the on-call, not the VP slide.

## Limits

Skip-level is not public humiliation. Safety and legal still need named owners. Speed does not mean shipping an unsafe rocket.
