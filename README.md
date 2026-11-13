# Growth Audit — Liftoff

**Live:** https://bterzic123.github.io/liftoff-flow-rebuild/

Liftoff gives every new lifter a rank and a date to reach the next one, then shows everyone the same “7 Days for Free” paywall. This audit has five ranked ideas and a clickable prototype of the first launch, rebuilt in Liftoff’s own design: three new lifters (two from Meta ads, one from Apple Ads) side by side, from install to Pro and back into the app.

## The five ideas

| # | Idea | Screen | Expected effect |
| :-- | :-- | :-- | :-- |
| 1 | Open Pro on their rank and the date they could reach the next one | Pro | CR +15–20% to trial |
| 2 | Make the loader read their answers back | Loader | CR +10–15% to trial |
| 3 | Start each ad install on the question its ad asked | First rank | CR +5–15% to trial |
| 4 | Put your reviews next to the button, and ask for a rating after the first workout | Pro | CR +10–15% to trial |
| 5 | Turn three trial screens into one timeline | Pro | CR +3–8% to trial |

Impact ranges are Adapty’s expected effect from teardowns and A/B tests across subscription apps, not measured lift for Liftoff.

## Grounding

Screens, copy and rank cards come from a capture of the Liftoff iOS onboarding (US storefront, early 2025). The 7-day free trial and $79.99 a year ($6.66 a month as the paywall shows it) are from Liftoff’s paywall and Apple’s purchase sheet in that capture. 4.8 from 102K ratings, 4M+ lifters and 600+ exercises are from the US App Store listing, read on 13 November 2026. Ads are Meta creatives as AppMagic sees them; Apple Ads terms and share of voice are AppMagic’s US reading for 13 October to 13 November 2026. In the prototype, ranks and dates come from a stand-in formula; Liftoff’s own rank model replaces it.

## Run it locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000/ (or `/?view=proto` for the prototype).

Prepared by Adapty · [Book a demo](https://calendly.com/d/cty4-37z-zqj)
