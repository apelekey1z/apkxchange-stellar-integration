# Proposed roadmap and budget

Review version, 3 October 2026. The $150,000 request and dates are proposals, not an awarded grant or guaranteed disbursement schedule. Work-package owners, effort, rates and availability require final validation before submission.

## Indicative delivery calendar

| Phase | Period | Completion date | Planning allocation |
|---|---|---|---:|
| Tranche 1: integration MVP | Weeks 1–3; 10–30 January 2027 | 30 January | $45,000 |
| Tranche 2: integrated testnet | Weeks 4–6; 31 January–20 February | 20 February | $45,000 |
| Tranche 3: mainnet build | Weeks 7–9; 21 February–13 March | Part of tranche 3 | Part of $60,000 |
| External-user validation, fixes and reporting | Weeks 10–11; 14–27 March | Part of tranche 3 | Part of $60,000 |
| Final corrections and completion buffer | Week 12; 28 March–3 April | 3 April | Included in tranche 3 |

The calendar assumes an initial funded start on 10 January 2027 and requires confirmation with SCF following award approval and payment. Mainnet rollout depends on technical, operational, partner and applicable regulatory prerequisites. Schedule changes require agreement; delays do not automatically extend approved deadlines.

## Work-package allocations

| Milestone / future work | Planning allocation | Evidence |
|---|---:|---|
| 1: Stellar account/signing adapter and asset validation | $12,000 | Verified transaction-intent signing, network/asset controls and account tests |
| 1: Trustless Work escrow roles and lifecycle integration | $12,000 | Supported fund/approve/release/dispute/refund paths and role tests |
| 1: Escrow/internal-ledger accounting and idempotency | $8,000 | Reconciliation, replay and uncertain-submission tests |
| 1: Incremental Stellar customer/operator interfaces | $7,000 | Reviewable Flutter/web/operator MVP |
| 1: Architecture, API contracts and MVP verification | $6,000 | Reviewed documents and reproducible acceptance report |
| **Milestone 1** | **$45,000** | |
| 2: SDP recipient/batch integration and approvals | $10,000 | Supported testnet recipient onboarding and payout batches |
| 2: End-to-end Stellar Flutter/web/operator journeys | $9,000 | Testnet customer and operator acceptance flows |
| 2: Observation, recovery and reconciliation | $10,000 | Duplicate/out-of-order processing, failed/uncertain transaction recovery |
| 2: Threat model, monitoring and control verification | $8,000 | Reviewed threat model, ownership, alerts and simulated incidents |
| 2: Integration QA and fault simulation | $5,000 | Repeatable regression and fault reports |
| 2: Narrow user-testing sessions and findings | $3,000 | Recorded flow findings and retest plan; no incentives |
| **Milestone 2** | **$45,000** | |
| 3: Mainnet deployment and signing/approval controls | $12,000 | Deployment verification and authorized signing tests |
| 3: Escrow/dispute and settlement failure hardening | $12,000 | Validated supported resolution paths and failure recovery |
| 3: Onchain attribution and economic-volume reporting | $9,000 | Registered footprint and reproducible single-count payment metrics |
| 3: Pilot defect remediation and release engineering | $10,000 | Scoped issues, fixes and regression evidence |
| 3: Release QA and recovery exercises | $7,000 | Readiness and recovery acceptance reports |
| 3: Narrow external-user validation | $5,000 | Usability/acceptance findings, excluding paid trading incentives |
| 3: Integration documentation and operational handover | $5,000 | Reviewed user/operator instructions and technical handover |
| **Milestone 3** | **$60,000** | |
| **Total** | **$150,000** | |


These are planning allowances, not validated supplier quotes or final labor estimates. Existing product/redesign work is reused, not billed again. Liquidity, trading inventory, licensing/legal costs, external audit fees and routine operations are outside this Build request. Narrow user-testing allocations total $8,000 and exclude trading incentives.

## Payment and outcome distinction

Under the current Integration Track model, acceptance/MVP/testnet/final payments are 10%/20%/30%/40%. The $45,000 first-phase allocation includes the $15,000 acceptance advance and $30,000 MVP payment. These are not guarantees of cash available before work starts.

The final milestone requires the panel-agreed onchain outcome described in [Validation](VALIDATION.md), not mainnet deployment alone.

Reference: [SCF Integration Track](https://stellar.gitbook.io/scf-handbook/scf-awards/build-award/integration-track).
