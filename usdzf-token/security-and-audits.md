# Security & Audits

<figure><img src="../.gitbook/assets/image (42).png" alt=""><figcaption><p><a href="https://twitter.com/VB_Audit/status/1674643373574045696">https://twitter.com/VB_Audit/status/1674643373574045696</a></p></figcaption></figure>

All contracts are verified on [zkSync Explorer](smart-contracts.md)&#x20;

All audits: [https://github.com/ZkSwapFinance/Audit-Reports](https://github.com/ZkSwapFinance/Audit-Reports)

### DEX Audit #1 : [Vital Block](https://vitalblock.org/)

zkSwap Finance is backed by Vital Block for security.&#x20;

Report: [https://github.com/Vital-block/Smart-Contract-Audit/blob/main/ZKSWAP%20FINANCE%20AUDIT%20REPORT.pdf](https://github.com/Vital-block/Smart-Contract-Audit/blob/main/ZKSWAP%20FINANCE%20AUDIT%20REPORT.pdf)

### DEX Audit #2 : [MythX](https://mythx.io/)

zkSwap Finance's codebase successfully PASSES security analysis by MythX, ConsenSys's premier service.

Report: [https://github.com/ZkSwapFinance/Audit-Reports/blob/main/2\_MythX\_DEX\_Full\_Report.pdf](https://github.com/ZkSwapFinance/Audit-Reports/blob/main/2\_MythX\_DEX\_Full\_Report.pdf)

### TGE Audit #3 : [MythX](https://mythx.io/)

TGE Launchpad's codebase successfully PASSES security analysis conducted by MythX, ConsenSys's premier service.

Report: [https://github.com/ZkSwapFinance/Audit-Reports/blob/main/3\_MythX\_TGE\_Full\_Report.pdf](https://github.com/ZkSwapFinance/Audit-Reports/blob/main/3\_MythX\_TGE\_Full\_Report.pdf)

### Token Audit #4 : [MythX](https://mythx.io/)

ZF Token's codebase successfully PASSES security analysis conducted by MythX, ConsenSys's premier service.

Report: [https://github.com/ZkSwapFinance/Audit-Reports/blob/main/4\_MythX\_Token\_Full\_Report.pdf](https://github.com/ZkSwapFinance/Audit-Reports/blob/main/4\_MythX\_Token\_Full\_Report.pdf)

### Farming Audit #5 : [MythX](https://mythx.io/)

ZF Farm's codebase successfully PASSES security analysis conducted by MythX, ConsenSys's premier service.

Report: [https://github.com/ZkSwapFinance/Audit-Reports/blob/main/5\_MythX\_Farm\_Full\_Report.pdf](https://github.com/ZkSwapFinance/Audit-Reports/blob/main/5\_MythX\_Farm\_Full\_Report.pdf)

### Galxe Campaign Pool Audit #6 : [MythX](https://mythx.io/)

Galxe Campaign Pool's codebase successfully PASSES security analysis conducted by MythX, ConsenSys's premier service.

Report: [https://github.com/ZkSwapFinance/Audit-Reports/blob/main/6\_MythX\_Galxe\_Campaign\_Pool\_Full\_Report.pdf](https://github.com/ZkSwapFinance/Audit-Reports/blob/main/6\_MythX\_Galxe\_Campaign\_Pool\_Full\_Report.pdf)



### Timelock Security Mechanism

Timelocks in smart contracts delay actions from contract owner to demonstrate commitment and reduce risks in DeFi.

* Timelock 6 hours: Delay Transaction 6 hours. Utilized in the Farm Contract to manage emissions and the new incentive pool.&#x20;
* Timelock 24 hours: Delay Transaction 24 hours. Utilized in the Token, TreasuryLock, and TeamFundLock Contracts to manage any changes voted on by users.
* Timelock 7 days: Delay Transaction 7 days. Utilized in the Liquidity Lock Contracts to manage any changes voted on by users.
