# Roadmap and budget

Last updated 3 October 2026. We're requesting $123,500 from SCF. This is our estimate for the Stellar work ahead, not an awarded grant, a supplier quote or a guaranteed payment schedule. I've approved the revised request; we'll still confirm the fixed team fees, task effort and service costs before final submission.

## Delivery calendar

| Phase | Period | Completion date | Estimated phase cost |
|---|---|---|---:|
| Tranche 1: integration MVP | Weeks 1–3; 10–30 January 2027 | 30 January | $28,000 |
| Tranche 2: integrated testnet | Weeks 4–6; 31 January–20 February | 20 February | $32,750 |
| Tranche 3: mainnet build | Weeks 7–9; 21 February–13 March | Part of tranche 3 | Part of $62,750 |
| External-user validation, fixes and reporting | Weeks 10–11; 14–27 March | Part of tranche 3 | Part of $62,750 |
| Final corrections and completion buffer | Week 12; 28 March–3 April | 3 April | Included in tranche 3 |

We've assumed a funded start on 10 January 2027, which we'll confirm with SCF after award approval and payment. Going to mainnet depends on our technical, operational, partner and regulatory readiness. Any schedule change needs SCF's agreement, and we understand a delay doesn't automatically move an approved deadline.

## How the costs break down

We've grouped costs into integration work, testing and services. Engineering is 960 hours at $100/hour over the twelve weeks. Operator acceptance and regression testing is a fixed $10,500, and pilot coordination and testing logistics come to $8,000. We'll do a final review of the detailed task estimates before submission.

| Cost category | Phase 1 | Phase 2 | Phase 3 | Total |
|---|---:|---:|---:|---:|
| Integration engineering | $24,000 | $24,000 | $48,000 | $96,000 |
| Operator acceptance, regression and release testing | $1,750 | $3,500 | $5,250 | $10,500 |
| Pilot coordination and user-testing logistics | $0 | $3,000 | $5,000 | $8,000 |
| Incremental Stellar API/custody services | $2,250 | $2,250 | $4,500 | $9,000 |
| **Estimated phase costs / request** | **$28,000** | **$32,750** | **$62,750** | **$123,500** |

The $9,000 for services is $3,000/month for three months, including our custody subscription. We only include extra Stellar-related costs we can back with real invoices. User testing doesn't include trading incentives or marketing. Each category is spread across the deliverables below and counted once.

## Engineering hours by week

These are combined hours for two engineers (our CTO and me), not calendar hours. The planned capacity is 16 combined hours/day × 5 working days/week = 80 hours/week. Tranche 1 covers 3 weeks × 80 = 240 hours; tranche 2 covers 3 weeks × 80 = 240 hours; tranche 3 covers all 6 remaining weeks × 80 = 480 hours, including mainnet build, user-validation fixes, reporting and the final completion buffer. Total: 12 weeks × 80 = 960 hours at $100/hour = $96,000.

| Phase | Engineering work category | Estimated hours | Rate | Cost |
|---|---|---:|---:|---:|
| 1 | Stellar account/signing adapter and asset/network validation | 70 | $100/hour | $7,000 |
| 1 | Trustless Work escrow integration | 80 | $100/hour | $8,000 |
| 1 | Escrow/ledger accounting and duplicate protection | 50 | $100/hour | $5,000 |
| 1 | Flutter/web/operator MVP and API integration | 40 | $100/hour | $4,000 |
| **1 subtotal — 3 weeks** | | **240** | | **$24,000** |
| 2 | Stellar Disbursement Platform integration | 80 | $100/hour | $8,000 |
| 2 | End-to-end Flutter/web/operator journeys | 50 | $100/hour | $5,000 |
| 2 | Transaction observation, recovery and reconciliation | 60 | $100/hour | $6,000 |
| 2 | Threat model, onchain monitoring and fault verification | 50 | $100/hour | $5,000 |
| **2 subtotal — 3 weeks** | | **240** | | **$24,000** |
| 3 | Mainnet deployment and signing/approval controls | 120 | $100/hour | $12,000 |
| 3 | Escrow/dispute and settlement failure hardening | 120 | $100/hour | $12,000 |
| 3 | Onchain attribution, observation and reconciliation reporting | 120 | $100/hour | $12,000 |
| 3 | Pilot fixes, release QA/recovery and integration handover | 120 | $100/hour | $12,000 |
| **3 subtotal — 6 weeks** | | **480** | | **$48,000** |
| **Total — 12 weeks** | | **960** | | **$96,000** |

These hours split the engineering budget above; they aren't an extra charge. Operator testing and pilot logistics are fixed amounts, and API/custody services are subscription costs, not hourly work.

## What you'll be able to check at each phase

The phase budgets above pay for the work below. None of it is billed twice.

| Phase | Stellar work | How you can verify it |
|---|---|---|
| 1 | Account/signing adapter and asset/network validation | Verified transaction-intent signing and account tests |
| 1 | Trustless Work escrow roles and supported lifecycle | Funding, approval, release and supported dispute/refund paths with role tests |
| 1 | Escrow/ledger accounting and idempotency | Reconciliation, replay and uncertain-submission tests |
| 1 | Incremental Flutter/web/operator MVP and implemented API contracts | Recorded acceptance flows and reproducible MVP report |
| 1 | Operator acceptance testing | Independent permission/approval cases and defect evidence |
| 2 | SDP recipient onboarding, payout batches and separate preparation/approval | Supported testnet recipient and batch acceptance flows |
| 2 | End-to-end interfaces, observation, recovery and reconciliation | Customer/operator flows, out-of-order and failed/uncertain transaction tests |
| 2 | Threat model, monitoring, technical control checks and fault simulation | Reviewed threat model, alert owners, incident simulations and regression reports |
| 2 | Operator QA and narrow user sessions | Non-duplicated acceptance cases, structured findings and retest plan |
| 3 | Mainnet deployment/signing controls and escrow/settlement hardening | Authorized signing, supported resolution paths and failure-recovery evidence |
| 3 | Attribution, reconciliation and single-count economic-volume reporting | Registered footprint and reproducible eligible payment report |
| 3 | Pilot defect remediation, release QA and recovery exercises | Scoped fixes, regression/readiness reports and recovery evidence |
| 3 | Narrow external-user validation and operational handover | Anonymized findings, retests and reviewed instructions |

We'll settle the architecture and confirm the components work before we submit. Phase 1 pays for building, integration test fixtures and MVP verification, not for initial design or for writing these documents.

## Costs we cover ourselves

We're not asking SCF to pay for our custody and liquidity reserves, gift-card inventory, VASP acquisition, legal and company registration, external security audits, day-to-day operations or our on/off-ramp rollout. We estimate external audits separately at $2,000/month, or $6,000 over three months. Our VASP, legal and reserve budgets are separate and not yet confirmed, and we're not claiming completed licensing or committed capital.

## SCF payments and cash flow

Phase costs above are distinct from SCF's 10%/20%/30%/40% milestone payments.

| Payment trigger | Percentage | Proposed amount |
|---|---:|---:|
| Award acceptance | 10% | $12,350 |
| MVP approval | 20% | $24,700 |
| Testnet approval | 30% | $37,050 |
| Final milestone and agreed onchain outcome | 40% | $49,400 |
| **Total** | **100%** | **$123,500** |

Payments come after each milestone review. Because our phase costs don't match SCF's payment schedule, we'll fund any gap in between ourselves.

The final milestone needs the onchain outcome agreed with the panel (see [Validation](VALIDATION.md)). Deploying to mainnet on its own isn't enough.

References: [SCF Integration Track](https://stellar.gitbook.io/scf-handbook/scf-awards/build-award/integration-track), [Budget and Deliverable Guidelines](https://stellar.gitbook.io/scf-handbook/scf-awards/build-award/budget-and-deliverable-guidelines).
