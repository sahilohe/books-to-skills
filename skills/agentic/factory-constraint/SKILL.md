---
name: factory-constraint
description: Find the single constraint that sets throughput on a factory, pipeline, or CI, and attack that — the production system is the product. Use when a prototype works but output does not.
---

# Factory constraint

Source: *The Book of Elon*.

## Definitions

**If we don’t make stuff, there is no stuff.** Goods do not appear from a magic economy. Progress is not automatic; humans make technology or it does not happen. Over-allocation into law/finance vs making is a stated mis-weighting.

**Factory is the product:** the machine that builds the machines. Tesla’s epiphany: to scale sustainable energy you design the *plant*, not only the car. More innovation potential in manufacturing than in the car design — a philosophical bet. A giant factory burns money every minute it is not producing.

**Design is overrated; production is underrated.** Designing a rocket from a book is "trivial" next to getting one to orbit. Car prototype is easy; production is hard. There is no eureka that replaces the line. 1,000%–10,000% more work in the production system than in the product, worse as the product is more new. SpaceX spent ~10–100× on the manufacturing system vs the Raptor design. They built rockets *then* the factory because the production system is harder.

**The constraint:** the line moves as fast as the slowest, least lucky part. 9,999 things working and one not → that one *is* the rate. Same for the least lucky or least competent **supplier** (fire, quake, tsunami, hail, tornado, sunk ship, border shoot-out delaying trunk carpet).

**Manufacturing competitiveness:** scale × technology. Maximize both. Plants are giant for that reason. Gigacasting: toy cars are cheap because they are cast — ask if physics forbids a car-sized machine; five suppliers said no, one said maybe → take maybe as yes.

**Prototype vs volume:** prototypes are easy and fun. Volume at reliable quality and affordable price is excruciating. That is the moat.

Applies to software factories too: CI, data pipelines, support queues, inference clusters — the *system that emits the thing*, not the demo.

## Procedure

1. Name the artifact vs the machine that emits it. Which are you actually designing this week?
2. List the path from input to shipped unit (or merged change, or trained model in prod).
3. Find the **one** step that sets throughput. Do not average. Do not "improve everything 5%."
4. Attack that constraint (`the-algorithm` on *that* step). Then re-measure; the constraint moves.
5. Supplier / dependency: who is least lucky or least competent on the critical path? Dual-source or pull in-house if they *are* the rate.
6. Scale × tech: are you growing volume on an unimproved process (no moat) or improving the process at low volume (not yet a factory)?
7. Stop celebrating prototypes as if they were production (`scale-path`).

## Examples

**Load when** a prototype works but output does not, or design is being polished while the line/CI/queue is stuck.

1. Human asks: model demos well; "just productize." Jobs wait 14 hours in one queue; the model card is being redesigned.  
   Return: the queue is the factory. Attack that. Dual-path the GPU vendor if they are the rate.

2. Human asks: we add features; weekly deploys got slower.  
   Return: name the one step that sets throughput (tests, review, flaky suite). Do not "improve everything 5%."

3. Human asks: make the battery cheaper from first principles.  
   **Wrong skill** for the floor. Load `first-principles`. Then this skill on the plant that emits the pack.

**Do not load** to skip v1 and build a platform (`ship-stack`: SaaS first).

## Limits

Safety-critical steps are still constraints — do not delete them; staff and instrument them. "Factory" is not an excuse to overbuild infrastructure before v1 (`ship-stack`: SaaS first). Physics still wins (`first-principles`).
