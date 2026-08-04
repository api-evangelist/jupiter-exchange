# Jupiter (jupiter-exchange)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Jupiter is the leading Solana DEX aggregator and liquidity infrastructure platform. APIs cover Swap (token exchanges), Tokens (metadata and verification), Price (USD pricing), Lend (yield and borrowing), Trigger (limit orders), Recurring (DCA), Prediction (event markets), and Perps (leveraged trading). The Developer Platform issues a single API key across products.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/jupiter-exchange/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/jupiter-exchange/refs/heads/main/apis.yml)

## Tags

- Web3
- Solana
- DEX
- Aggregator
- Swap
- Limit Orders
- DCA
- Perpetuals

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

### Jupiter Swap API

Quote and swap endpoints aggregating Solana DEX liquidity.

- **Human URL:** [https://developers.jup.ag/docs/swap-api](https://developers.jup.ag/docs/swap-api)
- **Base URL:** `https://lite-api.jup.ag/swap/v1`

#### Tags

- Swap
- Aggregator
- Solana

#### Properties

- [Documentation](https://developers.jup.ag/docs/swap-api)
- [Postman Collection](collections/jupiter-exchange.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/jupiter-exchange.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Jupiter Price API

USD pricing for Solana tokens, with batch lookup and best-route prices.

- **Human URL:** [https://developers.jup.ag/docs/price-api](https://developers.jup.ag/docs/price-api)
- **Base URL:** `https://lite-api.jup.ag/price/v3`

#### Tags

- Prices
- Solana
- Tokens

#### Properties

- [Documentation](https://developers.jup.ag/docs/price-api)
- [Postman Collection](collections/jupiter-exchange.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/jupiter-exchange.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Jupiter Tokens API

Verified Solana token list and metadata.

- **Human URL:** [https://developers.jup.ag/docs/tokens-api](https://developers.jup.ag/docs/tokens-api)
- **Base URL:** `https://tokens.jup.ag`

#### Tags

- Tokens
- Metadata
- Solana

#### Properties

- [Documentation](https://developers.jup.ag/docs/tokens-api)
- [Postman Collection](collections/jupiter-exchange.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/jupiter-exchange.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Jupiter Trigger (Limit Order) API

Limit order placement, query, and cancellation on Solana.

- **Human URL:** [https://developers.jup.ag/docs/trigger-api](https://developers.jup.ag/docs/trigger-api)
- **Base URL:** `https://lite-api.jup.ag/trigger/v1`

#### Tags

- Limit Orders
- Solana

#### Properties

- [Documentation](https://developers.jup.ag/docs/trigger-api)
- [Postman Collection](collections/jupiter-exchange.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/jupiter-exchange.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Jupiter Recurring (DCA) API

Recurring (dollar-cost-averaging) order automation on Solana.

- **Human URL:** [https://developers.jup.ag/docs/recurring-api](https://developers.jup.ag/docs/recurring-api)
- **Base URL:** `https://lite-api.jup.ag/recurring/v1`

#### Tags

- DCA
- Recurring
- Solana

#### Properties

- [Documentation](https://developers.jup.ag/docs/recurring-api)
- [Postman Collection](collections/jupiter-exchange.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/jupiter-exchange.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Jupiter Perps API

Leveraged perp trading endpoints on Jupiter Perps.

- **Human URL:** [https://developers.jup.ag/docs/perps-api](https://developers.jup.ag/docs/perps-api)
- **Base URL:** `https://perps-api.jup.ag`

#### Tags

- Perpetuals
- Solana

#### Properties

- [Documentation](https://developers.jup.ag/docs/perps-api)
- [Postman Collection](collections/jupiter-exchange.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/jupiter-exchange.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://jup.ag/)
- [Documentation](https://developers.jup.ag/docs)
- [Pricing](https://portal.jup.ag/pricing)
- [Git Hub](https://github.com/jup-ag)
- [Plans](plans/jupiter-exchange-plans-pricing.yml)
- [Rate Limits](rate-limits/jupiter-exchange-rate-limits.yml)
- [Fin Ops](finops/jupiter-exchange-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
