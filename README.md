# Dfns (dfns)

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
