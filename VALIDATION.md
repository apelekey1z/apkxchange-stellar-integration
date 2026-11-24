# Validation and onchain outcome

This is how we'll prove the integration works once it's built. It's a plan, not a report of tests we've already run or existing Stellar usage, and the target below needs the SCF panel's agreement.

## What we'll verify

- Our signer and account setup works, only allowed assets and networks are accepted, and every transaction matches its recorded intent.
- Escrow funding, release and dispute resolution work, and unauthorized or out-of-date actions are rejected.
- SDP recipient onboarding works, batches are approved by a second person, and every recipient is reconciled.
- Duplicate and out-of-order events are handled, uncertain submissions are recovered, and the ledger counts everything once.
- The threat model is done, every alert has an owner, and we've practised recovery.
- Real external users have tested it in a controlled pilot before we call it complete.

## How we'll measure success

Our main measure is USDC payment volume from genuine external users, settled on Stellar through ApkXchange's registered accounts and escrow contracts.

Our target: at least $10,000 in settled USDC payments over 14 consecutive days, roughly 14–27 March 2027 (weeks 10–11 of the schedule). We'll agree the threshold, the window and which onchain accounts count with the SCF panel. The dates assume a funded start on 10 January 2027 and will be confirmed after award approval and payment. It's a pilot target we're setting ourselves, not existing Stellar traction or a guaranteed forecast. Our on/off-ramp customers, who already move between cedis and stablecoins with us, are where we expect this volume to come from.

How we'll track it: we record each completed payment against its internal trade/payment ID and confirmed Stellar transaction references. We check the network, the USDC asset, that the transaction succeeded, the amount and the approved destination, then reconcile the report with our ledger and our registered accounts and contracts. Each payment counts once: funding an escrow, releasing it and later paying out the same money are never added up as separate volume.

We leave out testnet activity, transfers controlled by our team, circular or self-directed transfers, failed transactions and anything artificial or incentivized. Refunds and reversals come off the total and are shown separately. We'll list what we excluded and publish a summary anyone can reproduce, with the eligible transaction references, the total volume and our reconciliation. It won't include customer identities, gift-card codes or which account belongs to whom.

To show we're done, we'll provide that report showing we hit the agreed target in the agreed window, along with our milestone acceptance and reconciliation evidence. Being live on mainnet isn't enough on its own.

