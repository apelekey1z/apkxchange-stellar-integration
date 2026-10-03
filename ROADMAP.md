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

Engineering estimates use five workdays per week, including Sunday. William's planned allocation is 10 hours/day at an estimated $100/hour; Jefferey's is 6 hours/day at an estimated $100/hour. Over twelve weeks this is 600 and 360 hours respectively. Availability is not itself proof of required effort: hours must map to future integration tasks and exclude ordinary operations, previously completed work and duplicate billing.

Fredrick's proposed $6,000 fixed fee covers approximately 150 hours of operator acceptance/readiness work. Ebenezer's proposed $4,500 covers approximately 150 hours of independent operator regression/retesting. Kenneth's proposed $6,000 covers approximately 100 hours of pilot coordination and structured feedback. These fixed fees are planning estimates, not market-rate claims or agreed contracts. Technical security verification remains with the engineers; operator testing does not replace an external audit.

| Cost and delivery owner | Phase 1 | Phase 2 | Phase 3 | Total |
|---|---:|---:|---:|---:|
| William: 150 / 150 / 300 engineering hours | $15,000 | $15,000 | $30,000 | $60,000 |
| Jefferey: 90 / 90 / 180 engineering hours | $9,000 | $9,000 | $18,000 | $36,000 |
| Fredrick: operator acceptance and release readiness | $1,000 | $2,000 | $3,000 | $6,000 |
| Ebenezer: independent operator QA and regression | $750 | $1,500 | $2,250 | $4,500 |
| Kenneth: narrow pilot coordination and user feedback | $0 | $2,250 | $3,750 | $6,000 |
| Narrow user-testing logistics | $0 | $750 | $1,250 | $2,000 |
| Incremental integration API/custody service allowance | $2,250 | $2,250 | $4,500 | $9,000 |
| **Estimated phase costs / request** | **$28,000** | **$32,750** | **$62,750** | **$123,500** |

The $9,000 service allowance uses the upper applicant estimate of $3,000/month for three monthly billing periods. Phase attribution is proportional to the 3/3/6-week delivery split; actual invoices and billing dates may differ. Include only the incremental Stellar-related portion, confirm network/asset/signing compatibility and apportion shared services. Ordinary ongoing custody subscriptions and unrelated-network use are excluded. The custody subscription is already within this combined allowance, not an additional fee. If the justified cost is lower, revise the allowance rather than spend to its ceiling.

Kenneth's $6,000 plus $2,000 logistics constitute the full $8,000 user-validation allowance. Do not add another $8,000 or charge promotional influence, trading rewards or broad user acquisition to this request.

## Funded deliverables and verification

Phase budgets above are cost-basis allocations across the following outputs; the work below is not billed a second time as separate allowances.

| Phase | Future Stellar work | Reviewable completion evidence |
|---|---|---|
| 1 | Account/signing adapter and asset/network validation | Verified transaction-intent signing and account tests |
| 1 | Trustless Work escrow roles and supported lifecycle | Funding, approval, release and supported dispute/refund paths with role tests |
| 1 | Escrow/ledger accounting and idempotency | Reconciliation, replay and uncertain-submission tests |
| 1 | Incremental Flutter/web/operator MVP and implemented API contracts | Recorded acceptance flows and reproducible MVP report |
| 1 | Fredrick/Ebenezer operator acceptance | Independent permission/approval cases and defect evidence |
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

Payments follow acceptance/review and are not guaranteed cash before each phase. If costs follow the phase estimates, cumulative spend before MVP approval is $28,000 against $12,350 received, implying $15,650 to bridge. Before testnet approval, cumulative spend is $60,750 against $37,050 received, implying $23,700 to bridge. Before final approval, cumulative spend is $123,500 against $74,100 received, implying $49,400 to bridge. Actual timing depends on invoices, work payments and SCF review; company financing availability must be confirmed separately.

The final milestone requires the panel-agreed onchain outcome described in [Validation](VALIDATION.md), not mainnet deployment alone.

References: [SCF Integration Track](https://stellar.gitbook.io/scf-handbook/scf-awards/build-award/integration-track), [Budget and Deliverable Guidelines](https://stellar.gitbook.io/scf-handbook/scf-awards/build-award/budget-and-deliverable-guidelines).
