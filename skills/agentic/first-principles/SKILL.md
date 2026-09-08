---
name: first-principles
description: Reason from axioms and physics on a cost, architecture, or 'always been expensive' claim. Compute magic-wand floor and Idiot Index. Use when unblocking a product, company, or investment thesis.
---

# First principles

Source: *The Book of Elon*.

## Definitions

**Physics is law; everything else is a recommendation.** Conservation of energy and momentum are not optional. Process, org charts, and "industry practice" are.

**Wishful thinking:** filtering out information that contradicts how you want the world to be. Default stance: assume you are losing even when it looks like you might win.

**Reasoning by analogy:** do it because it is similar to what exists or what others do. Gets slight iterations. Fine for most of the day. Fatal for important new work. "Always been done this way" and "nobody's ever done it" are both analogy, not argument.

**First principles:** break to what you are most confident is true at a foundational level (axioms). Reason up. Check the conclusion against the axioms. For tech: does this violate conservation laws? If yes, it will not work. That only establishes *possibility*, not success.

**Magic wand number:** cost of the raw materials (atoms on the floor) if rearranging them were free. That is the cost *floor*. For rockets, materials were ~1–5% of historical finished cost.

**Idiot Index:** finished cost ÷ materials cost. High index → design too complex or manufacturing inefficient. $13,000 nozzle jacket on $200 of steel. Engineers should know best and worst parts in their system by this index at all times.

**Thinking in limits:** scale the idea to a huge or tiny number and see what breaks. If a part is still expensive at 1 million units/year, volume is not why it is expensive. Tunnels: cities are 3D, roads are 2D; diameter squared drives tunnel cost.

**Platonic ideal product:** the best arrangement of atoms, independent of the tools you already own. Then figure out how to get atoms into that shape. Starting from familiar tools yields a product those tools can make, not the perfect one.

At high volume, good manufacturing can drive cost toward materials plus licensed IP.

## Procedure

1. Write the analogy claim: "X costs Y because historically / competitors / experts say so."
2. Axioms: what must be true physically? What is only habit?
3. Bill of materials: constituents, market prices, magic-wand floor.
4. Idiot Index on the whole and on the worst 3 parts.
5. Limit test: 10× cheaper, 100× volume, 0.1× size — what still holds?
6. Platonic product in one sentence. Gap = the actual engineering problem.
7. Verdict: **possible** (physics allows, index is fat) / **impossible** (laws) / **uninteresting** (floor already reached).

## Examples

**Load when** the human says it is expensive "because it always was," or asks if a design is physically possible.

1. Human asks: inference will always be too expensive for this product.  
   Return: analogy. BOM + magic-wand floor. If Idiot Index is fat, the problem is batching/idle silicon, not physics. Limit at 1M queries/day.

2. Human asks: rockets / batteries / a custom part costs 50× materials. Can we win?  
   Return: index, worst 3 parts, platonic product. Possible vs uninteresting.

3. Human asks: delete the dashboard and the queue.  
   **Wrong skill** for order of deletion. Load `the-algorithm` after you know the thing should exist.

**Do not load** for daily analogical choices (library vs library) or to skip drug/aviation regulation.

## Limits

Most daily choices should stay analogical or you cannot function. First principles is for *important new* work. Possibility ≠ success. Do not "first-principles" your way past regulation on drugs or aviation.
