# The5ers Discount Code, Deals History & Dataset

As of November 2026, the verified The5ers discount code is NKY03MTJGM — 5% OFF, which can be applied on the checkout page anytime. The newest is "New Year Offer: $2.5K High Stakes Account for $12".

- Code: NKY03MTJGM
- Discount: 5% off (headline discount of the code; individual challenge plans on the firm page may list different percentages)
- Valid: Standing code — no published expiry date
- Last deal published: 2025-12-22
- Trustpilot: [4.7/5 (42963 reviews)](https://www.trustpilot.com/review/the5ers.com)
- GitHub repository: [The5ers Discount Code & Deals History Repository](https://github.com/propfirmdiscounts/the5ers-deals)
- Activate: [Activate The5ers Discount Code](https://propfirmdiscount.com/go/the5ers)
- Firm page: [The5ers Page on PropFirmDiscount](https://propfirmdiscount.com/prop-firm/the5ers/)
- Full dataset: [All Prop Firm Discount Codes Dataset](https://github.com/propfirmdiscounts/prop-firm-discount-codes)
- Code record: [The5ers API Record](https://propfirmdiscount.com/api/prop-firm-codes/)

## Latest The5ers deal: New Year Offer: $2.5K High Stakes Account for $12

- Published: 2025-12-22
- Offer ends: Ended
- Offer: Only $12
- Event: New Year's Eve
- Scope: $2.5K High Stakes Account
- Code: this deal carries its own limited-time campaign code, shown on the deal page below
- Deal page: [The5ers Deal Page](https://propfirmdiscount.com/deals/the5ers/the5ers-new-year-high-stakes-deal/)

## The5ers Discount Code & Deals History FAQ

**What is the The5ers discount code?**

NKY03MTJGM. It is verified by PropFirmDiscount.com and takes 5% off The5ers challenges and accounts.

**Does the The5ers discount code expire?**

No. It is a standing code — there is no start date and no end date. Promotional deals are separate and are dated individually; the current one is listed above.

**How much is the current The5ers deal?**

**New Year Offer: $2.5K High Stakes Account for $12** — published 2025-12-22. Offer ends: Ended. The offer is Only $12.

---

## The5ers Deals History

Total deals tracked: **2**

### 2025 (2 deals)

| Deal Date | Title | Discount | Expires | Event | Deal Link |
|---|---|---|---|---|---|
| 2025-12-22 | The5ers: New Year Offer: $2.5K High Stakes Account for $12 | Only $12 | Ended | New Year's Eve | [View Deal](https://propfirmdiscount.com/deals/the5ers/the5ers-new-year-high-stakes-deal/) |
| 2025-11-25 | The5ers: Black Friday: 15% Off All Accounts + 5% Off Select High Stakes | 15% off | Ended | Black Friday | [View Deal](https://propfirmdiscount.com/deals/the5ers/the5ers-black-friday-promotion/) |

---

## About the The5ers Discount Code & Deals History Dataset

This repository mirrors every deal **The5ers** has published on PropFirmDiscount.com, regenerated from the live API.

- Data source: [PropFirmDiscount.com](https://propfirmdiscount.com)
- Prop firm profile: [The5ers Profile](https://propfirmdiscount.com/prop-firm/the5ers/)
- All firms: [All Prop Firms Directory](https://github.com/propfirmdiscounts/prop-firm-discount-codes)

## The5ers Deals History Dataset: Field Definitions

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
| `event` | The seasonal campaign this deal was tagged with on the site (`Halloween`, `Black Friday`), or `null` when it belongs to no event. The event never changes what the deal is worth — it names the occasion the deal was run for. |
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

## Data Freshness & Verification

Deal history above is the source of truth for what changed and when. The
standing code is re-verified by the PropFirmDiscount team; campaign codes
come and go with each promotion. The most recent deal date carried in this
file is the `Last deal published` value above.

## Data License

Data © PropFirmDiscount. Codes may be referenced with attribution and a link to [PropFirmDiscount.com](https://propfirmdiscount.com).
