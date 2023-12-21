# 🛡 Audits & Security

At zkSwap Finance, we place a paramount emphasis on the security of our code and the safety of user funds. We recognize the pivotal role these elements play in establishing trust and fostering a secure environment for our users. To achieve this objective, we have implemented a stringent approach encompassing multiple audits and robust security measures.

All contracts are VERIFIED on [zkSync Explorer](../usdzf-token/smart-contracts.md) \
All Audits: [zkSwap Finance Github](https://github.com/ZkSwapFinance/Audit-Reports)

## Audited by Certik

Our platform is **being undergone** a comprehensive audit conducted by [Certik](https://www.certik.com/), a renowned security auditing firm. The preliminary results of this meticulous evaluation have positioned us in the top 10% of audited projects, attesting to the high level of security we maintain.

[Certik](https://www.certik.com/)'s audit is widely acknowledged and esteemed in the blockchain and cryptocurrency industry. Their exhaustive review process involves a careful examination of our smart contracts, codebase, and overall system architecture. Through this rigorous assessment, we have showcased our unwavering commitment to upholding the highest standards of security and reliability for our users.

For more details, please visit: [https://skynet.certik.com/projects/zkswap-finance](https://skynet.certik.com/projects/zkswap-finance)

## Audited by Vital Block

[Vital Block](https://vitalblock.org/) offers an extensive security evaluation for smart contracts and blockchain code, pinpointing vulnerabilities and suggesting effective solutions. The company also deliver a professional, thorough, swift, and easily comprehensible smart contract security audit. Vital Block's approach involves in-depth, penetrative analyses encompassing static, manual, automated, and intelligent methods to ensure comprehensive coverage.

Detailed Report: [Vital Block Github](https://github.com/Vital-block/Smart-Contract-Audit/blob/main/ZKSWAP%20FINANCE%20AUDIT%20REPORT.pdf)

<figure><img src="../.gitbook/assets/image (42).png" alt="" width="563"><figcaption><p><a href="https://twitter.com/VB_Audit/status/1674643373574045696">https://twitter.com/VB_Audit/status/1674643373574045696</a></p></figcaption></figure>

## Audited by MythX

MythX™ is a premier automatic security analysis service for Ethereum smart contracts by _**ConsenSys Software Inc™**_. Its mission is to ensure development teams avoid costly errors and make smart contracts more secure and trustworthy.

**MythX™ passed badge:**&#x20;

* mainnet-contracts: [https://github.com/ZkSwapFinance/mainnet-contracts](https://github.com/ZkSwapFinance/mainnet-contracts)
* zf-periphery: [https://github.com/ZkSwapFinance/zf-periphery](https://github.com/ZkSwapFinance/zf-periphery)

| Smart Contract      | Address                                                                                                                              | Audit Report                                                                                                         |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------- |
| Router              | [0x18381c0f738146Fb694DE18D1106BdE2BE040Fa4](https://explorer.zksync.io/address/0x18381c0f738146Fb694DE18D1106BdE2BE040Fa4#contract) | [Report](https://github.com/ZkSwapFinance/Audit-Reports/blob/main/2\_MythX\_DEX\_Full\_Report.pdf)                   |
| ZF Token            | [0x31C2c031fDc9d33e974f327Ab0d9883Eae06cA4A](https://explorer.zksync.io/address/0x31C2c031fDc9d33e974f327Ab0d9883Eae06cA4A#contract) | [Report](https://github.com/ZkSwapFinance/Audit-Reports/blob/main/4\_MythX\_Token\_Full\_Report.pdf)                 |
| ZF Farm             | [0x9F9D043fB77A194b4216784Eb5985c471b979D67](https://explorer.zksync.io/address/0x9F9D043fB77A194b4216784Eb5985c471b979D67#contract) | [Report](https://github.com/ZkSwapFinance/Audit-Reports/blob/main/5\_MythX\_Farm\_Full\_Report.pdf)                  |
| TGE Launchpad       | [0x723b715987b7E1B6C7872809b5B694dA153eAdD6](https://explorer.zksync.io/address/0x723b715987b7E1B6C7872809b5B694dA153eAdD6#contract) | [Report](https://github.com/ZkSwapFinance/Audit-Reports/blob/main/4\_MythX\_Token\_Full\_Report.pdf)                 |
| Galxe Campaign Pool | [0x3Cd6A09A60867643C80A2e6e22ab4D83368e0F89](https://explorer.zksync.io/address/0x3Cd6A09A60867643C80A2e6e22ab4D83368e0F89)          | [Report](https://github.com/ZkSwapFinance/Audit-Reports/blob/main/6\_MythX\_Galxe\_Campaign\_Pool\_Full\_Report.pdf) |

## Timelock Controllers & Multisig Wallets Security Mechanism

Utilized for safeguarding the platform's smart contracts, [Timelock Controllers](https://docs.zkswap.finance/contracts-and-audits/smart-contracts) and [Multisig Wallets](https://docs.zkswap.finance/contracts-and-audits/multisig-wallets) serve to introduce delays in actions by the contract owner, showcasing commitment and mitigating risks within the realm of DeFi.

* [Timelock 24 hours](https://docs.zkswap.finance/contracts-and-audits/smart-contracts): Delay Transaction 24 hours. Utilized for the ZF Farm, Treasury, Team Fund, Operation & Marketing Fund, to manage any possible  changes.
* [Timelock 48 hours](https://docs.zkswap.finance/contracts-and-audits/smart-contracts): Delay Transaction 48 hours. Utilized for the Factory, ZF Token, yZF DAO staking pool, ZF Contribution Reward Pool, TGE Participants Rewards Pool to manage any possible changes.
* [Timelock 7 days](https://docs.zkswap.finance/contracts-and-audits/smart-contracts): Delay Transaction 7 days. Utilized for the ZF/ETH Initial Liquidity contract to manage any possible changes.
* [Multisig Wallets](https://docs.zkswap.finance/contracts-and-audits/multisig-wallets) are used to control the above timelock controllers and mitigate the risk of any private key leakage.
