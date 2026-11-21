
# PerkStack

**PerkStack** is an independent referral directory that brings together referral offers for credit cards, shopping, wireless services, fitness, food delivery, and rides.

The website provides referral links, advertised rewards, eligibility information, and clear disclosures about potential referrer compensation.

**Live website:** https://ayushvjain3108.github.io/google-pixel-referrals/

## Referral Programs

| Program | Category | Benefit for New User | Benefit for Referrer |
|---|---|---|---|
| Discover | Credit Cards | $100 statement credit | $100 |
| Chase | Credit Cards | Eligible card offers | $50 |
| American Express | Credit Cards | Eligible welcome offers | $75 or $175 |
| Capital One Shopping | Shopping | Reported $80 reward | Reported $80 reward |
| Google Fi Wireless | Wireless | $60 Fi bill credit | $60 Fi bill credit |
| Planet Fitness | Fitness | Join for $1 down | One free membership month |
| Uber Eats | Food Delivery | $20 off first order of $25+ | $15 off next order of $25+ |
| Lyft | Rides | 50% off one eligible ride in Detroit | 50% off next ride, up to $10 |

All referral offers are subject to eligibility requirements, availability, and the individual provider's terms.

Reward amounts may change without notice. The referral landing page determines the actual offer.

## Current Referral Links

### Discover

Referral link:
https://i.capitalone.com/JzWpzTWF3

Reported offer: $100 for the new cardmember and $100 for the referrer, subject to qualifying conditions.

### Chase

Referral link:
https://www.referyourchasecard.com/18n/MQDR3LAD54

Eligible cards identified by the referrer:
- Chase Freedom Unlimited
- Chase Freedom Flex

Reported referrer reward: $50.

New applicants should review the current welcome offer shown on the application page.

### American Express

Referral link:
https://americanexpress.com/en-us/referral/blue-cash-everyday-credit-card?ref=AYUSHVhkId&XL=MNZNS

Cards identified by the referrer include:
- Blue Cash Everyday
- Delta SkyMiles Gold

Additional American Express cards may be available through the referral page.

Reported referrer reward: $75 or $175, depending on the eligible offer.

### Capital One Shopping

Referral link:
https://capitaloneshopping.com/r/ac56d302-6083-4469-8bbd-1575cf9e3805

Reported offer: $80 for the new user and $80 for the referrer after qualifying actions.

### Google Fi Wireless

Referral link:
https://g.co/fi/r/KDWEY9

Referral code: `KDWEY9`

Reported offer:
- New customer: $60 Google Fi bill credit.
- Referrer: $60 Google Fi bill credit.

Qualifying service activation, billing, and account requirements apply.

### Planet Fitness

Referral link:
https://www.planetfitness.com/referrals?referralCode=NBHQSP7S

Referral code: `NBHQSP7S`

Reported offer:
- New member: Join for $1 down.
- Referrer: One free month of membership.

Membership dues, annual fees, and additional conditions may apply.

### Uber Eats

Referral link:
https://ubereats.com/feed?promoCode=eats-bgicioyc29

Promo code: `eats-bgicioyc29`

Reported offer:
- New customer: $20 off the first eligible order of $25 or more.
- Referrer: $15 off the next eligible order of $25 or more.

### Lyft

Referral link:
https://www.lyft.com/i/AYUSH30621?utm_medium=2pa_iacc

Reported offer:
- New rider: 50% off one eligible ride in Detroit.
- Referrer: 50% off the next eligible ride, up to $10.

Geographic, eligibility, and promotion restrictions apply.

## Expired Campaigns

### Google Store Pixel Referral Program

**Status: Expired**

The Google Pixel 10% referral campaign ended on November 19, 2026.

Previous referral codes are no longer advertised as redeemable.

The campaign previously offered eligible buyers a 10% discount on qualifying Google Pixel purchases through single-use referral codes.

PerkStack may publish new Google Store referral promotions if another eligible campaign becomes available.

## Website Features

- Static HTML website hosted through GitHub Pages
- Responsive design for desktop and mobile
- Referral cards grouped into categories
- Client-side category filtering
- Referral buttons linking to official signup pages
- Copy buttons for applicable referral codes
- Expired campaign information
- Referral compensation disclosure
- Search-engine metadata
- JSON-LD structured data
- `robots.txt` and `sitemap.xml` for crawler discovery
- Supplemental `llms.txt` describing referral programs

The site does not require a backend, database, or user accounts.

## Repository Structure

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

## Updating Referral Offers

Referral information is maintained directly inside `index.html`.

To update an offer:

1. Open `index.html`.
2. Find the HTML article corresponding to the referral.
3. Update the advertised rewards, eligibility details, or referral URL.
4. Update any associated copy-button `data-code` value when changing a referral code.
5. If the offer has expired, move it to the expired campaign section or clearly mark it as expired.
6. Update the page's last-modified date.
7. Commit the changes to GitHub.

When referral programs are added or removed, also update:
- The referral count and category information.
- Search-engine metadata.
- JSON-LD structured data.
- This README.
- `llms.txt`.

## Deployment

PerkStack is hosted using GitHub Pages.

Live URL:
https://ayushvjain3108.github.io/google-pixel-referrals/

Changes committed to the publishing branch are deployed through the repository's configured GitHub Pages workflow.

## Search Engine and AI Discoverability

PerkStack is designed to make its referral information readable by standard search crawlers and AI systems that retrieve public web pages.

Referral information is included directly in the HTML rather than loaded from a remote API.

The website includes:
- Descriptive page titles and metadata
- Search-engine-friendly HTML
- Structured data
- Canonical URL
- XML sitemap
- Robots instructions
- An informational `llms.txt` file

These features improve accessibility and provide context, but do not guarantee indexing, search ranking, or inclusion in AI-generated responses.

## Referral Disclosure

PerkStack is independently maintained.

The website owner may receive referral rewards when visitors use the listed referral links and complete qualifying actions.

Rewards may include:
- Cash or statement credits
- Shopping rewards
- Membership discounts
- Wireless bill credits
- Promotional discounts

PerkStack is not owned, sponsored, affiliated with, or endorsed by any of the companies listed on the website.

All trademarks belong to their respective owners.

Visitors should verify offers directly with the provider before signing up, applying for credit, or making purchases.

## Last Updated

November 20, 2026.
