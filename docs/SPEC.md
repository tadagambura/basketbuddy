# BasketBuddy: Spec

**Shopping lists that remember** · #22 of 32 · Wave 2: Recurring keepers · Used: Weekly · Harder · Revenue potential: Low–medium · Home & Household · Source: ChatGPT

## One-liner

Reusable grocery lists with quantities, estimated prices and a running total, organised by store and aisle. Share a live list so whoever's at the shop sees what's needed.

## Problem / audience

- **Who it's for:** Households doing a weekly shop.
- **The problem it solves:** Rewriting the same list every week, and not knowing the total until the till.
- **Example:** A user loads their 'weekly shop' template, adds two items, and sees an estimated £54 before leaving home.

## MVP features (ship with only these)

1. Lists with quantities and estimated prices
2. Reusable template lists
3. Running estimated total
4. Store-specific lists and aisle order
5. Receive lists from PlateWeek

## Not in MVP

- Live shared lists between people (needs sync)
- Price history
- Unlimited lists

## Monetisation

| Model | Detail |
|---|---|
| Free | Lists, with ads |
| Premium | £1.99/month: sharing, price history, unlimited lists |
| Ads | Light |

Prices are starting points; test before committing. **Portfolio premium promise:** free has ads; the moment you pay you get no ads, cloud backup and storage, and sync across your devices, plus this app's extras.

## Retention: The Progression Loop

| Stage | Design |
|---|---|
| Cue | Weekly shop day |
| Tiny win | Tick items |
| Progress | Spend vs budget |
| Share | Shared lists |
| Next step | Re-use last week's list |
| Cadence | Weekly |

Follow the portfolio guardrails: no guilt-trip notifications, no fake urgency, progress is
never wiped, at most one notification a day by default.

## Animation and tone: five signature animations

**Playful.** Celebrations, confetti, cute characters, satisfying sounds and mild comic reactions. Nothing tragic.

- Item ticked: it flies into the trolley
- Under budget: the trolley pops a wheelie
- Shared list updated: a paper plane lands on the list
- Forgotten item: it waves from the shelf ('you forgot me!')
- List done: the trolley rolls off into the sunset


## AI

**None.** Not needed. Plain code does everything this app does. (Portfolio rule: plain code first, code does the maths,
cheapest model, shared budget cap, premium-gated.)

## Platform & data

- **Platform:** Expo app + Supabase for sharing.
- **Data:** On the device for solo use; Supabase for sharing.
- **Backend:** Device only; shared data once live list sharing is added. Premium backup and sync use the shared portfolio backend (see the master repo's HOSTING.md).
- **Stack:** shared portfolio foundation (Expo, PostHog, RevenueCat, AdMob, shared Progression Loop module).

## Growth engine

- **Content pillars:** Cheap weekly shops; Meal-plan lists; Supermarket comparisons
- **Shareable output:** Shared lists

## Risks

Crowded with free list apps, and sharing needs a backend.

## Launch checklist

- [ ] Name checked on the App Store, Play Store and a trademark search
- [ ] MVP features done and tested
- [ ] Progression Loop wired (cue, tiny win, progress, milestone, next step)
- [ ] Privacy policy and terms
- [ ] Landing page
- [ ] Analytics wired (D1/D7/D30 retention)
- [ ] Payments / ads wired
- [ ] Added to the Growth & Maintenance Engine as an app config
