# ApkXchange Stellar Integration

Documentation for ApkXchange Trade Rail's proposed Stellar integration, prepared for review of its SCF Build application.

**Status: proposed integration; not yet deployed.** This repository documents future work. It does not contain the production application source, prove completed Stellar implementation, or imply an SCF award or partner endorsement.

## Product and proposed scope

ApkXchange is an established Ghana-based gift-card trading platform preparing to expand across African and international markets. Its existing product provides the foundation for planned Stellar USDC settlement and P2P experiences.

The proposed funded integrations are:

- **Trustless Work:** role-authorized USDC escrow funding, release and supported dispute/resolution paths.
- **Stellar Disbursement Platform:** approved USDC disbursement batches through a supported recipient onboarding route.

Soroswap and other swap integrations are outside this application scope. GHS/RMB payment rails, other networks and broader product features are separate from the proposed Stellar work.

## Documentation

- [Proposed architecture](ARCHITECTURE.md)
- [Milestones and proposed budget](ROADMAP.md)
- [Validation and onchain outcome](VALIDATION.md)

## Product demonstrations

- [Stellar concept demo](https://youtu.be/3UKZscvLBQ4): planned integration illustrated with sample data.
- [Upcoming ApkXchange product update](https://youtu.be/T5QsW58CPos): supporting mobile/web preview. Upcoming features are not evidence of live Stellar functionality.

## Delivery proposal

The SCF request is $150,000, allocated $45,000 / $45,000 / $60,000 across three delivery milestones. The indicative twelve-week schedule runs from 10 January to 3 April 2027, subject to funding confirmation and agreement with SCF. Work estimates and named capacity require final validation before submission.

William Apelekey will lead hands-on integration work, with technical architecture/review responsibilities to be confirmed with CTO Jefferey Ashitey. Fredrick Apelekey and Kenneth Wireko support suitable operational acceptance and user validation work.

## Documentation boundaries

These documents describe proposed application-level interfaces and controls. Customer data, gift-card material, private configuration, credentials and production infrastructure details are excluded. Detailed signer/account compatibility and component behavior remain subject to technical validation.
