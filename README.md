# MystNodes by Kraskus — Umbrel App Store

Umbrel-native store listing **MystNodes by Kraskus** (`mysterium-node`).

It is its own store because Umbrel only lists apps whose ID starts with the store ID,
and the app keeps its existing ID `mysterium-node` (store id `mysterium`).

Add in umbrelOS: **App Store → ⋯ → Community App Stores** →
`https://github.com/kraskuscrypto/Kraskus-Umbrel-Mysterium-Store`.

The app folder is generated from
[`Kraskus-Crypto-Store`](https://github.com/kraskuscrypto/Kraskus-Crypto-Store). Do not edit it here.
The tooling lives in `Kraskus-Umbrel-Store/tools/umbrel-store-gen/`, and `generated-from.json`
records the source commit.


Current release: **2.7.0**. Dashboard improvements include provider readiness, earnings,
traffic and freshness information. Payment handling, node identity, data mounts and the
underlying official node image are preserved. Umbrel's app gateway fronts the dashboard;
the dashboard's direct host-port mapping is removed during generation.

This catalog synchronization does not restart or update an installed node. Catalog and
conversion checks do not constitute a fresh full Umbrel installation test. Current image
qualification is x86-64. This app's payment handling is not the mining-app native-wallet
migration.
