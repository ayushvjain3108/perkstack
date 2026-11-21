
# PerkStack

**PerkStack** is an independent, static referral directory for credit cards, shopping, wireless service, fitness, and rides.

**Live website:** https://ayushvjain3108.github.io/google-pixel-referrals/

The site shows reported referral offers, eligibility details, referrer compensation, and links to participating services. **The provider's live offer and terms always control.** This is not an official website of any listed brand.

## Current referral programs

| Program | New-user benefit | Referrer benefit | Notes |
|---|---|---|---|
| Discover | Reported $100 statement credit | Reported $100 | Qualifying application, approval and purchase requirements apply |
| Chase Freedom Unlimited / Flex | Review card-specific welcome offer | Reported $50 | No separately reported friend-referral bonus; verify public-sharing eligibility |
| American Express | Review personalized card welcome offer | Reported $75 or $175 | Eligible cards/offers vary; verify public-sharing eligibility |
| Capital One Shopping | Reported $80 Shopping Rewards | Reported $80 Shopping Rewards | New user must qualify and use the extension regularly over their first 90 days, generally roughly weekly |
| Google Fi Wireless | $60 eligible Fi bill credit | $60 eligible Fi bill credit | Qualifying activation, 30 days of service and first bill payment required |
| Planet Fitness | Join for $1 down, subject to fees | One free membership month | Referrer limited to three free months per calendar year |
| Lyft | Review eligible new-rider promotion | Possible referral reward | Detroit-area offer; monetary reward amounts intentionally omitted per Lyft sharing restrictions |

### Referral links

- Discover: https://i.capitalone.com/JzWpzTWF3
- Chase: https://www.referyourchasecard.com/18n/MQDR3LAD54
- American Express: https://americanexpress.com/en-us/referral/blue-cash-everyday-credit-card?ref=AYUSHVhkId&XL=MNZNS
- Capital One Shopping: https://capitaloneshopping.com/r/ac56d302-6083-4469-8bbd-1575cf9e3805
- Google Fi: https://g.co/fi/r/KDWEY9 (code: `KDWEY9`)
- Planet Fitness: https://www.planetfitness.com/referrals?referralCode=NBHQSP7S (code: `NBHQSP7S`)
- Lyft: https://www.lyft.com/i/AYUSH30621?utm_medium=2pa_iacc
  - Official Lyft promotions: https://www.lyft.com/rider/promo
  - Lyft referral rules: https://www.lyft.com/terms/referrals

### Programs not publicly listed

The personal **Uber Eats** referral link and code have been **removed**. Uber's general referral rules restrict posting personal referrals on publicly accessible coupon/referral websites. Do not restore that code or link without obtaining confirmation that this particular offer permits public promotion.

**Google Store Pixel 10% referral codes** are listed only as an *expired campaign*; the campaign closed November 19, 2026. No old codes are displayed as redeemable.

## Site features

- Single responsive `index.html` page with static, crawler-readable referral content
- Client-side category filters and copy buttons where applicable
- Clear compensation and eligibility disclosures
- JSON-LD `WebSite`, `WebPage`, `ItemList`, and FAQ metadata
- `robots.txt`, `sitemap.xml`, and optional `llms.txt` for crawler context
- No database, backend or user accounts

## Repository files

```text
google-pixel-referrals/
├── index.html
├── README.md
├── robots.txt
├── sitemap.xml
├── llms.txt
├── BingSiteAuth.xml
└── google58782a455da5f2c7.html
```

## Updating an offer

1. Edit the relevant static `<article>` card in `index.html`.
2. Confirm the provider's current referral terms and whether publicly indexed website sharing is allowed.
3. Change any link, reward description, eligibility wording, and copy-button `data-code` together.
4. Update the JSON-LD `ItemList`, homepage count, metadata, and any category buttons if the active program list changes.
5. Keep this README and `llms.txt` in sync; update `sitemap.xml`'s `<lastmod>` on publication.
6. Commit to the configured GitHub Pages publishing branch.

**Note:** Public social sharing permission does not necessarily authorize an indexed referral directory. In particular, recheck personalized **Chase** and **Amex** referral terms before expanding promotion. Lyft online promotions must follow its referral rules, including links to the official Lyft promotion information and restrictions on stating reward amounts.

## Referral disclosure

The owner may receive cash, statement credits, shopping rewards, free membership months, bill credits, or other promotional benefits when a qualifying referral completes the required actions. Offers are not guaranteed, and credit-card applications may result in a credit inquiry. PerkStack is independently maintained and is not affiliated with or endorsed by the listed companies.

## Search and AI visibility

Offer details are rendered as HTML, readable without JavaScript. The sitemap and `llms.txt` supply additional context but **do not guarantee** search or AI indexing. Maintain accurate terms and review each offer regularly.

Last reviewed: November 20, 2026.
