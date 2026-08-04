# Dfns (dfns)

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

Dfns is a wallet-as-a-service and MPC key-management infrastructure provider. Its API lets businesses create programmable, non-custodial wallets backed by multi-party-computation key shares, sign and broadcast transactions across many blockchains, and govern every action through a programmable policy engine with delegated signing, approvals, and User Action Signing.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/dfns/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/dfns/refs/heads/main/apis.yml)

## Tags

- Wallets
- MPC
- Key Management
- Digital Assets
- Web3
- Non-Custodial

## Timestamps

- **Created:** 2026-07-01
- **Modified:** 2026-07-01

## APIs

### Dfns Wallets API

Create and manage programmable non-custodial wallets on many blockchain networks, and read wallet addresses, asset balances, NFTs, and on-chain history.

- **Human URL:** [https://docs.dfns.co/d/api-docs/wallets](https://docs.dfns.co/d/api-docs/wallets)
- **Base URL:** `https://api.dfns.io`

#### Tags

- Wallets
- Balances
- NFTs

#### Properties

- [Documentation](https://docs.dfns.co/d/api-docs/wallets)
- [API Reference](https://docs.dfns.co/d/api-docs/wallets/api-reference)
- [OpenAPI](openapi/dfns-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dfns.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dfns.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dfns Keys API

Create and manage standalone MPC keys (scheme/curve) independent of a single network, and generate raw signatures directly from a key.

- **Human URL:** [https://docs.dfns.co/d/api-docs/keys](https://docs.dfns.co/d/api-docs/keys)
- **Base URL:** `https://api.dfns.io`

#### Tags

- Keys
- MPC
- Signing

#### Properties

- [Documentation](https://docs.dfns.co/d/api-docs/keys)
- [OpenAPI](openapi/dfns-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dfns.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dfns.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dfns Transfers API

Initiate native, token (ERC-20/SPL), and NFT transfers from a wallet; Dfns builds, signs, and broadcasts the transaction and tracks its status.

- **Human URL:** [https://docs.dfns.co/d/api-docs/wallets/transfer-asset-from-wallet](https://docs.dfns.co/d/api-docs/wallets/transfer-asset-from-wallet)
- **Base URL:** `https://api.dfns.io`

#### Tags

- Transfers
- Payments
- Broadcast

#### Properties

- [Documentation](https://docs.dfns.co/d/api-docs/wallets/transfer-asset-from-wallet)
- [OpenAPI](openapi/dfns-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dfns.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dfns.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dfns Transactions API

Sign and broadcast caller-supplied transactions - including smart contract calls - from a wallet, and list transaction requests and their status.

- **Human URL:** [https://docs.dfns.co/d/api-docs/wallets/broadcast-transaction-from-wallet](https://docs.dfns.co/d/api-docs/wallets/broadcast-transaction-from-wallet)
- **Base URL:** `https://api.dfns.io`

#### Tags

- Transactions
- Broadcast
- Smart Contracts

#### Properties

- [Documentation](https://docs.dfns.co/d/api-docs/wallets/broadcast-transaction-from-wallet)
- [OpenAPI](openapi/dfns-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dfns.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dfns.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dfns Signatures API

Generate signatures (hash, message, EIP-712, transaction, PSBT) from a wallet or key without broadcasting, and retrieve signature request status.

- **Human URL:** [https://docs.dfns.co/d/api-docs/wallets/generate-signature-from-wallet](https://docs.dfns.co/d/api-docs/wallets/generate-signature-from-wallet)
- **Base URL:** `https://api.dfns.io`

#### Tags

- Signatures
- Signing
- EIP-712

#### Properties

- [Documentation](https://docs.dfns.co/d/api-docs/wallets/generate-signature-from-wallet)
- [OpenAPI](openapi/dfns-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dfns.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dfns.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dfns Policy Engine and Approvals API

Define policies that govern activities (e.g. signing) with rules and actions (block, request approval), and drive the approval workflow via decisions.

- **Human URL:** [https://docs.dfns.co/d/api-docs/policy-engine](https://docs.dfns.co/d/api-docs/policy-engine)
- **Base URL:** `https://api.dfns.io`

#### Tags

- Policy Engine
- Approvals
- Governance

#### Properties

- [Documentation](https://docs.dfns.co/d/api-docs/policy-engine)
- [OpenAPI](openapi/dfns-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dfns.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dfns.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dfns Webhooks API

Register HTTPS webhooks to receive events for wallet, transfer, signature, and policy activity; ping endpoints and inspect the event delivery log.

- **Human URL:** [https://docs.dfns.co/d/api-docs/webhooks](https://docs.dfns.co/d/api-docs/webhooks)
- **Base URL:** `https://api.dfns.io`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://docs.dfns.co/d/api-docs/webhooks)
- [OpenAPI](openapi/dfns-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dfns.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dfns.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dfns Permissions and Auth API

Manage permissions and assignments, users, login and delegated login, and the User Action Signing challenge/complete flow that authorizes sensitive operations.

- **Human URL:** [https://docs.dfns.co/d/api-docs/authentication](https://docs.dfns.co/d/api-docs/authentication)
- **Base URL:** `https://api.dfns.io`

#### Tags

- Permissions
- Auth
- User Action Signing

#### Properties

- [Documentation](https://docs.dfns.co/d/api-docs/authentication)
- [API Reference](https://docs.dfns.co/d/api-docs/authentication/user-action-signing)
- [OpenAPI](openapi/dfns-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dfns.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dfns.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dfns Service Accounts API

Create and manage service accounts (machine identities) and their access tokens for server-to-server API access, including activate/deactivate.

- **Human URL:** [https://docs.dfns.co/d/api-docs/authentication/service-account-management](https://docs.dfns.co/d/api-docs/authentication/service-account-management)
- **Base URL:** `https://api.dfns.io`

#### Tags

- Service Accounts
- Machine Identity
- Access Tokens

#### Properties

- [Documentation](https://docs.dfns.co/d/api-docs/authentication/service-account-management)
- [OpenAPI](openapi/dfns-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dfns.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dfns.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dfns Networks API

Estimate network fees and perform read-only smart contract calls against supported blockchain networks without creating a transaction.

- **Human URL:** [https://docs.dfns.co/d/api-docs/networks](https://docs.dfns.co/d/api-docs/networks)
- **Base URL:** `https://api.dfns.io`

#### Tags

- Networks
- Fees
- Blockchain Reads

#### Properties

- [Documentation](https://docs.dfns.co/d/api-docs/networks)
- [OpenAPI](openapi/dfns-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dfns.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dfns.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/dfns)
- [LinkedIn](https://www.linkedin.com/company/dfns)
- [Website](https://www.dfns.co/)
- [Documentation](https://docs.dfns.co/)
- [Plans](plans/dfns-plans-pricing.yml)
- [Rate Limits](rate-limits/dfns-rate-limits.yml)
- [Fin Ops](finops/dfns-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
