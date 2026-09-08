---
name: ship-stack
description: Place a project on Balaji's stack (idea through profits), name the next rung, and plan SaaS-first / hire-last work. Use when building or shipping — not when the maze is still unchosen.
---

# Ship the stack

Source: *The Anthology of Balaji*.

## Definitions

A map from idea to cash. Many companies die between rungs because of time or an unseen flaw.

| Stage | Done when | Minimum time (order of) |
|-------|-----------|-------------------------|
| Idea | Napkin of a billion-dollar concept | minutes |
| Mockup | Wireframe of all user screens | day+ |
| Prototype | Ugly hack for the single major use case | weekend+ |
| Program | Clean code, all use cases, tests | weeks |
| Product | Design, copy, pricing, physical bits | months |
| Business | Entity, payroll, filings | many months |
| Profits | Sell for more than it costs | year+ |

**Startup engineering:** something works well enough for people to **buy**. Not academic science (works well enough to publish). Not infinite-scale architecture before the first sale.

**Systems integration:** keep up with new tools, evaluate fast, snap pieces together. Language/tool choice in practice is library vs Google, not Turing completeness.

**Bounded commitment:** list options, pick one, commit for a fixed window (week/month), then revisit. Time is allocated like capital. Depth-first vs breadth-first search.

## Rules

1. An idea is not a mockup is not a prototype is not a program is not a product is not a business is not profits. Do not skip rungs in language ("we have a product" when you have a prototype).
2. **SaaS first, code second, hire last.** v1 with off-the-shelf tools, even ugly. If traction, automate or code. Hire only what you cannot automate.
3. Innovate on **one** thing: your product. Everywhere else, boring and vanilla until first serious profit. Do not invent a web framework unless you sell web frameworks.
4. Early: best available tech, not greenfield infrastructure.
5. UI quality can be scored: number, type, and duration of inputs to a result.
6. Launch means criticism. A new product cannot beat an incumbent on all axes. Attacks often mean "sell more units." Investors care about the future; customers care about the present.
7. First customers: a spreadsheet of names, numbers, and the exact pitch. Pre-commit to N approaches so one "no" is not the end.

## Procedure

Write the stack status. Do not inflate the rung.

1. Name the current rung honestly.
2. Single exit criterion for the next rung.
3. Engineering: bought vs built vs hired? Default buy. Produce the buy list.
4. First-customer list (named). If you cannot name them, they are still in idea/mockup — say so.
5. Bounded commitment: this week's one path and the revisit date.

## Examples

**Load when** the human asks what to build this week, what rung they are on, or how to ship v1.

1. Human asks: we have Figma, we say "platform" — what do we do?  
   Return: rung = mockup. Next = prototype, one named office, one use case. Buy Stripe + auth + a sheet. Hire = none. 15 named emails.

2. Human asks: we have tests and four use cases, no one has paid. Are we a product?  
   Return: rung = program, not product. Exit = pricing + copy + one paid invoice. Do not hire.

3. Human asks: is this idea any good vs Dentrix?  
   **Wrong skill.** Load `idea-maze`. After the maze, come back here.

**Do not load** for GTM channel choice (`distribution`) or weekly ranked outreach (`execute`).

## Limits

Drugs, aviation, and similar cannot "move fast and break things." Bounded commitment still applies; the rungs take longer and include regulators.
