# Audiomack — the Audiomack+ paywall, personalized from the onboarding

**Live page: https://plykhvar-glitch.github.io/audiomack-paywall-rebuild/**

The Audiomack+ paywall that follows onboarding, rebuilt in Audiomack's own design and fed by what the
onboarding already asks: the artists picked in "What do you want to listen to?" and what opened Plus.
Change them under the phone and the paywall rewrites itself. Flip **Today** to see the screen as it
ships. English and Spanish, plus a walkthrough under 30 seconds.

## The five changes

| # | Change | Today | Now | Expected impact |
| :-- | :-- | :-- | :-- | :-- |
| 1 | Their artists on the paywall | The same five faces and "Audiomack is FREE" for everyone | The artists they picked fill the bubbles with their name pills; "Your Burna Boy, Asake & Tems, ad-free" | CR +15–20% |
| 2 | What they reached for, first | Only ads on this screen; the Plus screen's four benefits in one fixed order | A Download tap leads with Unlimited Downloads ("All of Burna Boy, offline"), a Plus-only track with the full catalog | CR +10–15% |
| 3 | The trial, spelled out | "We do have a subscription for 6,99 €/month"; the 7 free days only on the button | Today 0 € · Day 7 6,99 €/month · cancel before and you are not charged | CR +10–15% |
| 4 | Your rating, under the button | Nothing between the two buttons | "★ 4.8 · 2M ratings on the App Store" | CR +10–15% |
| 5 | A month free when they choose ads | "Continue for free on ad-supported" ends it | A Free vs Plus sheet with the 30 days free you already run on audiomack.com/plus, same 6,99 €/month | ARPU +10–15% |

*Impact ranges are Adapty's expected effect from teardowns and A/B tests across subscription apps —
not measured lift for Audiomack.*

The price, the 7-day trial and the paywall copy come from the Audiomack iOS app; the 4.8 rating from
2M ratings from the US App Store listing (25K ratings on the Spanish listing, used on the Spanish
screen); the 30-day trial from audiomack.com/plus; artist photos from audiomack.com. "Today" is rebuilt
from the iOS paywall; its bubble faces stand in for the ones it shows.

## Run locally

```bash
python3 -m http.server 8000
```
