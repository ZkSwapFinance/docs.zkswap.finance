---
description: Comprehensive details of the zkSwap Finance smart contracts
---

# 🔎 Smart Contracts

### Core Contracts

<table data-full-width="false"><thead><tr><th>Name</th><th>Address</th><th>Owner</th></tr></thead><tbody><tr><td>Router (Verified)</td><td><a href="https://explorer.zksync.io/address/0x18381c0f738146Fb694DE18D1106BdE2BE040Fa4#contract">0x18381c0f738146Fb694DE18D1106BdE2BE040Fa4</a></td><td>No contract owner</td></tr><tr><td>Factory (Verified)</td><td><a href="https://explorer.zksync.io/address/0x3a76e377ED58c8731F9DF3A36155942438744Ce3#contract">0x3a76e377ED58c8731F9DF3A36155942438744Ce3</a></td><td><p>No contract owner</p><p>Fee Setter:  <a href="https://explorer.zksync.io/address/0x97F03B2F6246Da8ff336f37ad3b047f7C3f74E59#contract">Timelock Core 48 hours</a></p></td></tr><tr><td>ZF Token (Verified)</td><td><a href="https://explorer.zksync.io/address/0x31C2c031fDc9d33e974f327Ab0d9883Eae06cA4A#contract">0x31C2c031fDc9d33e974f327Ab0d9883Eae06cA4A</a></td><td><a href="https://explorer.zksync.io/address/0x97F03B2F6246Da8ff336f37ad3b047f7C3f74E59#contract">Timelock Core 48 hours</a></td></tr><tr><td>ZF Farm (Verified)</td><td><a href="https://explorer.zksync.io/address/0x9F9D043fB77A194b4216784Eb5985c471b979D67#contract">0x9F9D043fB77A194b4216784Eb5985c471b979D67</a></td><td><a href="https://explorer.zksync.io/address/0xcE043a95f415D7873585E92904ea11955Ba38fE5#contract">Timelock Core 24 hours</a></td></tr><tr><td>yZF (DAO Staking Pool, Verified)</td><td><a href="https://explorer.zksync.io/address/0x4Ca2aC3513739ceBF053B66a1d59C88d925f1987#contract">0x4Ca2aC3513739ceBF053B66a1d59C88d925f1987</a></td><td><a href="https://explorer.zksync.io/address/0x97F03B2F6246Da8ff336f37ad3b047f7C3f74E59#contract">Timelock Core 48 hours</a></td></tr><tr><td>ZF Paymaster</td><td><a href="https://explorer.zksync.io/address/0xABcA8CFDfa2a4285A4704BF960fb45E49821762F#contract">0xABcA8CFDfa2a4285A4704BF960fb45E49821762F</a></td><td><a href="https://app.safe.global/settings/setup?safe=zksync:0x0D64C4eb0547C1F51b78Fb1A53583dC9042238C0">Multisig Core Wallet</a></td></tr></tbody></table>

### &#x20;Project Funds Contracts (Timelocked)

| Name                                  | Address                                                                                                                              | Owner                                                                                                             |
| ------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------- |
| Treasury (Verified)                   | [0xffdEF45585b57E294487c72F01043D5dee3F069f](https://explorer.zksync.io/address/0xffdEF45585b57E294487c72F01043D5dee3F069f#contract) | [Timelock Funds 24 hours](https://explorer.zksync.io/address/0x4305CF9f4Ad5427D6614e7207803E2426497917A#contract) |
| Team Fund (Verified)                  | [0x922fAA26538dB5f373177933554E2e09930c6447](https://explorer.zksync.io/address/0x922fAA26538dB5f373177933554E2e09930c6447#contract) | [Timelock Funds 24 hours](https://explorer.zksync.io/address/0x4305CF9f4Ad5427D6614e7207803E2426497917A#contract) |
| Operation & Marketing Fund (Verified) | [0x81D9EC35c43338CF26318ce8CE67e4E1548de473](https://explorer.zksync.io/address/0x81D9EC35c43338CF26318ce8CE67e4E1548de473#contract) | [Timelock Funds 24 hours](https://explorer.zksync.io/address/0x4305CF9f4Ad5427D6614e7207803E2426497917A#contract) |
| ZF/ETH Initial Liquidity (Verified)   | [0x16E29D067d9c65F445b7890Eb5dDae950C660d23](https://explorer.zksync.io/address/0x16E29D067d9c65F445b7890Eb5dDae950C660d23#contract) | [Timelock Funds 7 days](https://explorer.zksync.io/address/0x6521385CE3bf30dE58e402e5AeD567b436736a75#contract)   |

### Timelock Controllers&#x20;

| Name                               | Address                                                                                                                              | Admin                                                                                                                  |
| ---------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| Timelock Core 48 hours (Verified)  | [0x97F03B2F6246Da8ff336f37ad3b047f7C3f74E59](https://explorer.zksync.io/address/0x97F03B2F6246Da8ff336f37ad3b047f7C3f74E59#contract) | [Multisig Core Wallet](https://app.safe.global/settings/setup?safe=zksync:0x0D64C4eb0547C1F51b78Fb1A53583dC9042238C0)  |
| Timelock Core 24 hours (Verified)  | [0xcE043a95f415D7873585E92904ea11955Ba38fE5](https://explorer.zksync.io/address/0xcE043a95f415D7873585E92904ea11955Ba38fE5#contract) | [Multisig Core Wallet](https://app.safe.global/settings/setup?safe=zksync:0x0D64C4eb0547C1F51b78Fb1A53583dC9042238C0)  |
| Timelock Funds 7 days (Verified)   | [0x6521385CE3bf30dE58e402e5AeD567b436736a75](https://explorer.zksync.io/address/0x6521385CE3bf30dE58e402e5AeD567b436736a75#contract) | [Multisig Funds Wallet](https://app.safe.global/settings/setup?safe=zksync:0xF1802d9a70Bdc6F6EffD65d44b33226eE0E6A821) |
| Timelock Funds 24 hours (Verified) | [0x4305CF9f4Ad5427D6614e7207803E2426497917A](https://explorer.zksync.io/address/0x4305CF9f4Ad5427D6614e7207803E2426497917A#contract) | [Multisig Funds Wallet](https://app.safe.global/settings/setup?safe=zksync:0xF1802d9a70Bdc6F6EffD65d44b33226eE0E6A821) |

### ZF Token Minters

| Name                                     | Address                                                                                                                              | Owner                                                                                                                 |
| ---------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------- |
| ZF Farm (Verified)                       | [0x9F9D043fB77A194b4216784Eb5985c471b979D67](https://explorer.zksync.io/address/0x9F9D043fB77A194b4216784Eb5985c471b979D67#contract) | [Timelock Core 24 hours](https://explorer.zksync.io/address/0xcE043a95f415D7873585E92904ea11955Ba38fE5#contract)      |
| yZF (DAO Staking Pool, Verified)         | [0x4Ca2aC3513739ceBF053B66a1d59C88d925f1987](https://explorer.zksync.io/address/0x4Ca2aC3513739ceBF053B66a1d59C88d925f1987#contract) | [Timelock Core 48 hours](https://explorer.zksync.io/address/0x97F03B2F6246Da8ff336f37ad3b047f7C3f74E59#contract)      |
| Swap2Earn Rewards Pool (Verified)        | [0xF4dAc6647f4c56DE2a8BE120e5a830B5bD5Aae91](https://explorer.zksync.io/address/0xF4dAc6647f4c56DE2a8BE120e5a830B5bD5Aae91#contract) | [Multisig Core Wallet](https://app.safe.global/settings/setup?safe=zksync:0x0D64C4eb0547C1F51b78Fb1A53583dC9042238C0) |
| ZF Contribution Reward Pool (Verified)   | [0xD4343Eb137E531BeBe118115aC1fABb13B125f3B](https://explorer.zksync.io/address/0xD4343Eb137E531BeBe118115aC1fABb13B125f3B#contract) | [Timelock Core 48 hours](https://explorer.zksync.io/address/0x97F03B2F6246Da8ff336f37ad3b047f7C3f74E59#contract)      |
| TGE Participants Rewards Pool (Verified) | [0x791D413897064c4e288a580362f374C243e56823](https://explorer.zksync.io/address/0x791D413897064c4e288a580362f374C243e56823#contract) | [Timelock Core 48 hours](https://explorer.zksync.io/address/0x97F03B2F6246Da8ff336f37ad3b047f7C3f74E59#contract)      |
| Team Fund (Verified)                     | [0x922fAA26538dB5f373177933554E2e09930c6447](https://explorer.zksync.io/address/0x922fAA26538dB5f373177933554E2e09930c6447#contract) | [Timelock Funds 24 hours](https://explorer.zksync.io/address/0x4305CF9f4Ad5427D6614e7207803E2426497917A#contract)     |
| Operation & Marketing Fund (Verified)    | [0x81D9EC35c43338CF26318ce8CE67e4E1548de473](https://explorer.zksync.io/address/0x81D9EC35c43338CF26318ce8CE67e4E1548de473#contract) | [Timelock Funds 24 hours](https://explorer.zksync.io/address/0x4305CF9f4Ad5427D6614e7207803E2426497917A#contract)     |
