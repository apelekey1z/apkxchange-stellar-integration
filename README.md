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

The proposed SCF request is $123,500, with estimated phase costs of $28,000 / $32,750 / $62,750 across three delivery milestones. Phase costs differ from the SCF payment percentages; see the roadmap for the funding schedule. The indicative twelve-week schedule runs from 10 January to 3 April 2027, subject to funding confirmation and agreement with SCF. The budget uses team-provided engineering time/rate estimates and proposed fixed testing fees. Detailed task effort, fees and incremental service costs require final validation before submission.

ApkXchange has five operating team members. William Apelekey leads hands-on integration delivery alongside CTO Jefferey Ashitey. Fredrick Apelekey and Ebenezer (Administrator 2) support operator acceptance and regression testing; Kenneth Wireko coordinates narrow pilot sessions and structured user feedback. Only future integration-specific work is charged to this proposal.

## Documentation boundaries

These documents describe proposed application-level interfaces and controls. Customer data, gift-card material, private configuration, credentials and production infrastructure details are excluded. Detailed signer/account compatibility and component behavior remain subject to technical validation.
