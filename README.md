# ApkXchange Stellar Integration

I'm William Apelekey, founder of ApkXchange. This repository explains how we plan to bring Stellar USDC settlement into ApkXchange Trade Rail, and it's the technical companion to our SCF Build application.

To be clear up front: the integration described here is the work we're asking SCF to fund. It isn't live on mainnet yet. This repo doesn't contain our production source code, and nothing in it should be read as an SCF award or a partner endorsement.

## Who we are

ApkXchange is a gift-card trading platform based in Ghana. Customers already use our app and website to buy and sell gift cards, keep balances in their ApkXchange wallet and cash out. We're now expanding across Africa and into international markets, and Stellar USDC is how we want to settle value between people quickly and cheaply.

## Where ApkXchange is heading

Our next major update, rolling out soon, adds on-ramp and off-ramp to ApkXchange. Customers will be able to buy stablecoins with cedis and sell stablecoins back to cedis inside the same app they already use for gift cards.

That changes what ApkXchange is. We're no longer only a gift-card exchange: we're becoming a gift-card and stablecoin fintech. The wallet, ledger, identity checks and trade workflows we've built over the years are the foundation for it, and they're why I believe we're well placed to give people a simple, trustworthy way to exchange fiat for stablecoins and trade their gift cards in one place.

Stellar fits naturally on top of this. Every customer who moves between cedis, stablecoins and gift cards on ApkXchange is a potential Stellar USDC user, and that demand is what the work below is built to serve.

## What we're asking SCF to fund

Two integrations:

- **Trustless Work:** USDC escrow for P2P trades, with role-based funding, release and dispute resolution.
- **Stellar Disbursement Platform:** approved USDC payout batches to customers through a supported recipient onboarding route.

Soroswap and other swap integrations aren't part of this application. Our GHS/RMB payment rails, other networks and the wider product (including the on/off-ramp above) are funded by us separately.

## Documentation

- [Architecture](ARCHITECTURE.md)
- [Milestones and budget](ROADMAP.md)
- [Validation and onchain outcome](VALIDATION.md)

## Demos

- [Stellar concept demo](https://youtu.be/3UKZscvLBQ4): how the planned integration will work, shown with sample data.
- [Upcoming ApkXchange product update](https://youtu.be/T5QsW58CPos): a preview of the new mobile and web app. These upcoming features aren't live Stellar functionality.

## Budget and timeline

We're requesting $123,500, with estimated phase costs of $28,000 / $32,750 / $62,750 across three milestones. Those phase costs don't line up exactly with SCF's payment percentages; the roadmap shows both. We've planned a twelve-week build from 10 January to 3 April 2027, depending on funding confirmation and agreement with SCF. The budget is based on our own engineering time and rate estimates plus fixed testing fees, and we'll finalise the detailed figures before submission.

## Our team

There are five of us. I lead the hands-on integration work alongside our CTO, Jefferey Ashitey. Fredrick Apelekey and Ebenezer (Administrator 2) handle operator acceptance and regression testing, and Kenneth Wireko runs our small pilot sessions and collects structured feedback from users. We only charge this proposal for future integration work.

## What we keep out of this repo

These documents cover the interfaces and controls we plan to build. We've deliberately left out customer data, gift-card codes, private configuration, credentials and production infrastructure details. The exact signer and account setup, and how each component behaves, will be confirmed during technical validation.
