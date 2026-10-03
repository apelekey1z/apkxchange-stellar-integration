# Proposed validation and onchain outcome

This is a future acceptance plan, not a report of completed tests or existing Stellar usage. The proposed threshold remains subject to SCF panel ratification.

## Integration verification

- Confirm signer/account compatibility, allowed assets/networks and verified transaction intents.
- Demonstrate supported escrow funding, release and dispute/resolution paths, including unauthorized and stale-state rejection.
- Demonstrate supported SDP recipient onboarding, independently approved batches and per-recipient reconciliation.
- Verify duplicate/out-of-order handling, uncertain submission recovery and single-count ledger effects.
- Complete the threat model, monitoring ownership and recovery exercises.
- Obtain controlled external-user acceptance evidence before final completion.

## Outcome metric

Primary metric: genuine external-user USDC payment volume successfully settled on Stellar and attributable to ApkXchange's registered integration accounts and escrow contracts.

Proposed completion target: at least $10,000 in settled USDC payment volume over 14 consecutive days. The indicative measurement period is 14–27 March 2027, within weeks 10–11 of the proposed schedule. The threshold, measurement window and attributable onchain footprint will be agreed with the SCF panel. Calendar dates assume an initial funded start on 10 January 2027 and require confirmation following award approval and payment. This is a proposed pilot acceptance target, not existing Stellar traction or a guaranteed forecast.

Tracking and reporting: record each completed economic payment against its internal trade/payment ID and confirmed Stellar transaction references. Verify the correct network, USDC asset identity, successful transaction result, amount and approved destination. Reconcile the report with the application ledger and registered onchain accounts/contracts. Count each economic payment once: funding an escrow, releasing it and subsequently paying out the same value must not be added together as separate volume.

Exclude testnet activity, team-controlled transfers, circular/self-directed transfers, failed transactions and artificial or incentivized volume. Refunds and reversals are removed from eligible settled volume and shown separately. Record exclusions and provide a reproducible summary with eligible transaction references, aggregated volume and supporting reconciliation evidence. Public reporting will not contain customer identity records, gift-card material or private account mappings.

Completion evidence: a reproducible report demonstrating the panel-agreed threshold within the agreed measurement period, together with milestone acceptance and reconciliation evidence. Mainnet deployment alone does not satisfy this outcome.

