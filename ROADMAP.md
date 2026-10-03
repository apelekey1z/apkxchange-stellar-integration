# Proposed roadmap and budget

Review version, 3 October 2026. The proposed SCF request is $123,500. This is an estimate for future Stellar delivery, not an awarded grant, a supplier quote or guaranteed disbursement schedule. The applicant approved the revised request; fixed team fees, task effort and incremental service allocation still require final validation.

## Indicative delivery calendar

| Phase | Period | Completion date | Estimated phase cost |
|---|---|---|---:|
| Tranche 1: integration MVP | Weeks 1–3; 10–30 January 2027 | 30 January | $28,000 |
| Tranche 2: integrated testnet | Weeks 4–6; 31 January–20 February | 20 February | $32,750 |
| Tranche 3: mainnet build | Weeks 7–9; 21 February–13 March | Part of tranche 3 | Part of $62,750 |
| External-user validation, fixes and reporting | Weeks 10–11; 14–27 March | Part of tranche 3 | Part of $62,750 |
| Final corrections and completion buffer | Week 12; 28 March–3 April | 3 April | Included in tranche 3 |

The calendar assumes an initial funded start on 10 January 2027 and requires confirmation with SCF following award approval and payment. Mainnet rollout depends on technical, operational, partner and applicable regulatory prerequisites. Schedule changes require agreement; delays do not automatically extend approved deadlines.

## Cost basis and phase allocation

Costs are grouped by integration work, testing and services. Engineering is estimated at 960 hours at $100/hour across the twelve-week build. Operator acceptance and regression testing use a combined $10,500 fixed allowance. Pilot coordination and testing logistics total $8,000. Detailed task estimates remain subject to final review.

| Cost category | Phase 1 | Phase 2 | Phase 3 | Total |
|---|---:|---:|---:|---:|
| Integration engineering | $24,000 | $24,000 | $48,000 | $96,000 |
| Operator acceptance, regression and release testing | $1,750 | $3,500 | $5,250 | $10,500 |
| Pilot coordination and user-testing logistics | $0 | $3,000 | $5,000 | $8,000 |
| Incremental Stellar API/custody services | $2,250 | $2,250 | $4,500 | $9,000 |
| **Estimated phase costs / request** | **$28,000** | **$32,750** | **$62,750** | **$123,500** |

The $9,000 service allowance estimates $3,000/month for three billing periods, including the custody subscription. Only incremental Stellar-related costs supported by actual invoices are included. User testing excludes trading incentives and broad acquisition. The categories are allocated across the deliverables below and are counted once.

## Funded deliverables and verification

Phase budgets above are cost-basis allocations across the following outputs; the work below is not billed a second time as separate allowances.

| Phase | Future Stellar work | Reviewable completion evidence |
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

Initial architecture and component feasibility must be resolved before final application submission. Phase 1 funds implementation, integration acceptance fixtures and MVP verification rather than initial system design or reimbursement for these application documents.

## Separately financed company costs

Company-owned custody/liquidity reserves, gift-card trading inventory, VASP acquisition, legal/entity-registration costs, external security audits and routine operations are outside this SCF Build request. The applicant separately estimates external audit costs at $2,000/month, or $6,000 over three months. VASP/legal and reserve amounts remain separately budgeted and unconfirmed; no licensing completion or committed capital is asserted.

## SCF payments and cash flow

Phase costs above are distinct from SCF's 10%/20%/30%/40% milestone payments.

| Payment trigger | Percentage | Proposed amount |
|---|---:|---:|
| Award acceptance | 10% | $12,350 |
| MVP approval | 20% | $24,700 |
| Testnet approval | 30% | $37,050 |
| Final milestone and agreed onchain outcome | 40% | $49,400 |
| **Total** | **100%** | **$123,500** |

Payments follow milestone review. Phase costs differ from the SCF payment schedule; any interim funding is arranged separately by ApkXchange.

The final milestone requires the panel-agreed onchain outcome described in [Validation](VALIDATION.md), not mainnet deployment alone.

References: [SCF Integration Track](https://stellar.gitbook.io/scf-handbook/scf-awards/build-award/integration-track), [Budget and Deliverable Guidelines](https://stellar.gitbook.io/scf-handbook/scf-awards/build-award/budget-and-deliverable-guidelines).
