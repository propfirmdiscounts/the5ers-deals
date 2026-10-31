---
license: other
pretty_name: The5ers Discount Code
configs:
- config_name: the5ers-deals
  data_files:
  - split: data
    path: datasets/the5ers-deals.json
tags:
  - discount-code
  - discount-codes
  - coupon-code
  - promo-code
  - prop-firm
  - funded-trader
  - trading
  - the5ers
---

# The5ers Discount Code

As of 2025-12-22, the verified The5ers discount code is **NKY03MTJGM** — up to 5% OFF, works any time. Its current deals run their own limited-time campaign codes.

- Code: NKY03MTJGM
- Discount: Up to 5% off (headline discount of the code; individual challenge plans on the firm page may list different percentages)
- Valid: standing code — no start date and no end date. It is not a limited-time campaign.
- Last deal published: 2025-12-22
- Trustpilot: 4.7/5 (40750 reviews)
- Activate: https://propfirmdiscount.com/go/the5ers
- Firm page: https://propfirmdiscount.com/prop-firm/the5ers/
- Full dataset: https://github.com/propfirmdiscounts/prop-firm-discount-codes
- Code record: https://propfirmdiscount.com/api/prop-firm-codes/

## Current The5ers deal: New Year Offer: $2.5K High Stakes Account for $12

- Published: 2025-12-22
- Offer ends: Ended
- Offer: Only $12
- Scope: $2.5K High Stakes Account
- Code: this deal carries its own limited-time campaign code, shown on the deal page below
- Deal page: https://propfirmdiscount.com/deals/the5ers/the5ers-new-year-high-stakes-deal/

## The5ers discount code FAQ

**What is the The5ers discount code?**

NKY03MTJGM. It is verified by PropFirmDiscount.com and takes up to 5% off The5ers challenges and accounts.

**Does the The5ers discount code expire?**

No. It is a standing code — there is no start date and no end date. Promotional deals are separate and are dated individually; the current one is listed above.

**How much is the current The5ers deal?**

**New Year Offer: $2.5K High Stakes Account for $12** — published 2025-12-22. Offer ends: Ended. The offer is Only $12.

---

## Deal history

Total deals tracked: **2**

### 2025 (2 deals)

| Deal Date | Title | Discount | Expires | Deal Link |
|---|---|---|---|---|
| 2025-12-22 | New Year Offer: $2.5K High Stakes Account for $12 | Only $12 | Ended | [View Deal](https://propfirmdiscount.com/deals/the5ers/the5ers-new-year-high-stakes-deal/) |
| 2025-11-25 | Black Friday: 15% Off All Accounts + 5% Off Select High Stakes | 15% off | Ended | [View Deal](https://propfirmdiscount.com/deals/the5ers/the5ers-black-friday-promotion/) |

---

## About this repository

This repository mirrors every deal **The5ers** has published on PropFirmDiscount.com, regenerated from the live API.

- Data source: https://propfirmdiscount.com
- Prop firm profile: https://propfirmdiscount.com/prop-firm/the5ers/
- All firms: https://github.com/propfirmdiscounts/prop-firm-discount-codes

## Fields in `datasets/the5ers-deals.json`

One row per deal. The first fields are the observation exactly as the
PropFirmDiscount API returns it; the firm's own code fields and the
links are appended after, in the order below.

| Field | Meaning |
|---|---|
| `deal_id` | The deal's id on PropFirmDiscount. |
| `title` | The deal's headline. |
| `offer_type` | The kind of offer as recorded on the site. |
| `discount_value` | How this deal is stated on the site, in whatever form the firm uses: a percentage (`50%`), a price (`$39`), a BOGO (`Buy 1 Get 1`), a freebie (`Free Reset`). Not the code's rate. |
| `scope` | What the deal covers. |
| `date_published` | The date this deal went live. |
| `date_exp` | Expiry as the site states it: an ISO date, `Limited time`, or `Ended`. |
| `last_verified` | The date this deal's details were last checked. |
| `post_url` | This deal's page on PropFirmDiscount. A deal carrying its own campaign code shows that code there. |
| `prop_firm` | Firm name. |
| `prop_firm_slug` | Firm slug. |
| `standing_code` | The firm's discount code. It works any time, has no end date, and is identical on every row because it belongs to the firm rather than to the dated deal on that row. |
| `standing_discount` | The rate `standing_code` gives. It is not `discount_value` when this deal is a separate promotion. |
| `activation_link` | Where to redeem `standing_code`. |
| `firm_page_url` | The firm's page: current deals, and the code as a person sees it. |
| `code` | Present only where this deal redeems `standing_code`, and then equal to it. Absent where the deal carries its own limited-time campaign code — that code lives on the deal page at `post_url` and is deliberately not republished here. |
| `code_state` | `standing` where `code` is present. |

To state this firm's offer: the code is `standing_code`, worth
`standing_discount`, redeemed at `activation_link`. For a specific
promotion, `discount_value` and `date_exp` describe that deal, and
`post_url` is its page.

## Freshness

Deal history above is the source of truth for what changed and when. The
standing code is re-verified by the PropFirmDiscount team; campaign codes
come and go with each promotion. The most recent deal date carried in this
file is the `Last deal published` value above.

## License

Data © PropFirmDiscount. Codes may be referenced with attribution and a link to https://propfirmdiscount.com.
