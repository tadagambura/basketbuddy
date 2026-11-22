# BasketBuddy: Spec

**Rank in portfolio:** #13 of 15 (easiest → hardest) · **Difficulty:** Medium (sync)

## One-liner

Shopping lists that remember: reusable lists, estimated totals, shared shopping.

## Problem / audience

- **Who it's for:** Households doing a weekly shop.
- **The problem it solves:** Rewriting the same list each week; not knowing the total until the till.

## MVP features (ship with only these)

1. Lists with quantities and estimated prices
2. Reusable / template lists
3. Running estimated total
4. Store-specific lists

## Not in MVP

- Shared lists live between people (needs sync)
- Price history
- Unlimited lists

## Monetisation

| Model | Detail |
|---|---|
| Free | Lists, with ads |
| Paid | £1.99/month: sharing + price history + unlimited |
| Ads | Light |

Prices are starting points from the portfolio brief; test before committing.

## Platform & stack

- **Platform:** Expo + Supabase for sharing.
- **Stack:** shared portfolio foundation (Expo, PostHog, RevenueCat, AdMob). See the portfolio roadmap.
- **Data:** Device only solo; Supabase for shared lists.

## Growth engine hooks

- **Shareable output:** Limited; lean on budgeting and meal-plan content.
- **Content pillars:** Cheap weekly shops; Meal-plan lists; Supermarket comparisons

## Notes

Crowded category. Pairs naturally with WorthIt (unit prices) for cross-promotion.

## Launch checklist

- [ ] Name checked on App Store / Play Store / trademark search
- [ ] MVP features done and tested
- [ ] Privacy policy + terms
- [ ] Landing page
- [ ] Analytics wired
- [ ] Payments / ads wired
- [ ] Added to growth-engine as an app config
