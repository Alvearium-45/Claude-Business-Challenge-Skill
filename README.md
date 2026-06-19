**# Business Challenge Panel**

A Claude skill that turns a single assistant into a tough, multi-angle business coaching panel. Its job is to tell you what is wrong with your idea before the market does it for you, for free.

Most "give me feedback" tools drift into agreement. This one is built to resist that. It opens with the weakness, not the praise, and it is allowed to conclude that an idea is weak, premature, or a bad bet.

## What it does

When you bring a business plan, strategy, pricing change, new service line, or growth bet, the skill runs a set of distinct analytical lenses against it. Each lens channels the publicly known way of thinking of a well-regarded operator or business thinker. They are lenses, not impersonations, and the skill does not put fabricated quotes into anyone's mouth.

You get challenge from angles you did not anticipate, then a clear verdict and a single next action.

## The lenses

1. **Cuban** is this even a business: margin, real competition, why now, why you.
2. **Hormozi** the offer and the one binding constraint: have you sold one yet.
3. **Sanchez** cash and boring realism: where is the cash, what happens if you stop showing up for a month.
4. **Priestley** positioning: commodity or category. The most relevant lens for advisory, fractional, and expert-led models.
5. **Sinek** defensibility of purpose: why would a buyer trust you over the incumbent.
6. **Grant** evidence versus assumption: what are you avoiding finding out.
7. **Blakely** the cheapest, fastest test that would tell the truth.
8. **Welsh** distribution and founder leverage: does the model compound or just trade your time under a nicer name.
9. **The ambition provocateur** the deliberate counterweight: is the plan too timid for the effort it will cost.

Not every lens fits every idea. The skill picks the three to five that bite hardest and goes deep rather than spraying all of them shallowly.

## Two modes

1. **Gut-check** a single sharp pass for quick questions. Two or three lenses, a clear read, kept short.
2. **Full panel** for a real plan. It steelmans the idea first so the challenge is fair, runs the panel, surfaces the "kill-shots" (the two or three questions that sink the plan if unanswered), then gives a verdict (pursue, reshape, park, or kill) and one owned, dated next action.

## How to use it

Once installed, the skill triggers when you ask for challenge. Phrases that work well:

- "Poke holes in this."
- "Pressure-test this idea."
- "Play devil's advocate on this business plan."
- "What am I missing here?"
- "Challenge me on this new service line."

It also triggers when you frame something as just wanting to "talk through" an idea, because supplying genuine challenge is the whole point.

## Installation

The exact steps depend on which Claude product you use, and the official upload paths change from time to time, so treat the following as the general shape rather than a fixed menu route.

1. Download `business-challenge-panel.skill` from this repo.
2. Install it through your Claude skills or capabilities interface, or place the unpacked skill folder in the skills directory your Claude environment reads from.
3. Confirm it appears in your available skills list, then trigger it with one of the phrases above.

The `.skill` file is a zip archive containing the skill folder. You can unzip it to inspect or edit `SKILL.md` directly.

## Repo structure

```
business-challenge-panel/
├── README.md                       this file
├── business-challenge-panel.skill  packaged, installable skill
└── business-challenge-panel/
    └── SKILL.md                    the skill itself (edit here, then repackage)
```

## Design notes

- **Anti-sycophancy is the core design constraint.** The skill is told not to open with praise, not to soften every criticism into a compliment sandwich, and that calling an idea weak is a valid output.
- **No performative toughness.** It is also told not to manufacture fake objections against a genuinely strong plan, because that is just flattery wearing a leather jacket. The heat is calibrated to the real weakness.
- **Ruthless on the idea, respectful of the person.** It attacks the plan, never the planner.
- **Tuned for professional services.** The challenge is translated into trust-based, reputation-led, relationship-driven buying rather than the direct-to-consumer or SaaS context most of this advice is written for.

## Author

Created by Christian Toon, Alvearium Associates Limited.
