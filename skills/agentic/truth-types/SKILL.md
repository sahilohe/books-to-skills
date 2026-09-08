---
name: truth-types
description: Classify claims as scientific, technical, political, economic, or cryptographic truth and pick a matching check. Use when diligencing, fact-checking, or reviewing a study, protocol, or press claim.
---

# Types of truth

Source: *The Anthology of Balaji*.

## Definitions

**Scientific truth:** independently reproducible. Form today is a journal paper; **substance** is replication. Maxwell's equations have trillions of replications. Last week's paper may not share a dataset. Peer review is usually delayed email-length criticism, not confirmation. Prestige (lab, journal, h-index) is not replication. There are almost no career incentives to replicate — it is not "novel."

**Technical truth:** true even if nobody believes it. Math, genetics, biochemistry, "what is this virus made of." Math is exact; science is approximate. Computers let people replicate *calculations* if the raw table is public even when they cannot replicate the wet lab.

**Political truth:** true if enough people treat it as real. Money, borders, presidents, status. Changeable by rewriting brains. Politics is tribes, not truth. A truth that makes your tribe lose goes untold. Gaffe = politician saying an obvious truth they are not supposed to say. Signal **repeaters** (summaries, outrage) are not signal **sources** (raw data, primary URLs, plots).

**Economic truth:** revealed by incentives and P&L. Unpopular *fact* is often innovation; unpopular *opinion* is heresy; popular fact is triviality. A narrative that keeps failing contact with reality loses money to people who are right.

**Cryptographic truth:** who signed what, when, included in which log. Verifies attestation, not that the sensor was calibrated. Oracles assert off-chain facts onto a chain; they inherit the honesty of the off-chain world.

## Rules

- Every statistic is a distillation of a raw table. **Ask for the table.**
- Argue with signal sources, not repeaters. If they cannot produce plots or primary data, you are in a tribal fight.
- The more technical knowledge you have, the less you need reputation as a proxy.
- Data = absolute reckoning; reputation = relative reckoning.
- Do not "solve" political truth with a scientific dashboard. Match mechanism to type.

## Procedure

1. Quote the claim. Split mixed claims.
2. Assign type(s). A protocol can be technical; adoption can be political; revenue can be economic.
3. Name the correct verification (replication / proof / consensus / P&L / signatures).
4. Incentives: who gains if this is false? What does lying cost?
5. Output: what to trust, what to ignore, what to measure next.

## Examples

**Load when** the human hands you a claim, paper, metric, or "studies show" line to check.

1. Human asks: they say the model is SOTA.  
   Return: split types. Scientific only with a public rerun; political if it means "investors believe us"; economic if customers pay; cryptographic if data is attested. Ask for the eval **table**.

2. Human asks: this journalist says our churn is 40%.  
   Return: political/repeater until you have the cohort table. Economic if it hits P&L. Do not argue the headline; get the source.

3. Human asks: the chain says this warehouse temperature is on-chain, so climate policy is settled.  
   Return: cryptographic = who signed what. Does not prove the sensor was calibrated. Compare oracles.

**Do not load** to design a publication or go-direct stack (`media-system`).

## Limits

Verification has cost. Democracies run on cheap political truth; that is a different game. Crypto does not make a lie in the real world true. For feeds, outlets, and building distribution, load `media-system`.
