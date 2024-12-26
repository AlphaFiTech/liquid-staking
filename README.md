**stSUI: The Enhanced Open-Source LST Framework for Sui**

stSUI is an **open-source Liquid Staking Token (LST) framework** that empowers anyone **to easily launch their own LST**s on the Sui network. Forked from the **SpringSui framework**, stSUI builds on its foundation with key enhancements to boost rewards, efficiency, and security. 

**Key Improvements in stSUI:**

**No Reward Loss During Rebalancing**

stSUI eliminates reward loss caused by validator rebalancing.
Unlike SpringSui, where withdrawals remove tokens from the last validator—triggering rebalancing and skipped rewards—stSUI ensures proportional withdrawals across validators, preserving rewards without interruption.

**Unstake Fee Redistribution 🔄**

**A 0.01% unstake fee** discourages system gaming.
Unlike SpringSui, stSUI redistributes these fees back to users, boosting APR and aligning incentives for long-term stakers.

**Real-Time Pricing for Continuous Rewards**

In SpringSUI, the price of the LST relative to SUI updates only once per day. In stSUI, however, the price continuously updates as the unstaking fee is redistributed to all other stakers. This means you can earn rewards even for a few extra hours if you keep your SUI staked — maximizing yields with more flexibility.

**Flash Staking for Yield Strategies ⚡**

stSUI supports flash staking, enabling low gas costs for DeFi strategies, making it ideal for yield optimization.

**Secure Framework with Fee Caps 🔒**

Introduces an additional Fee Collection Cap to limit admin cap usage, enhancing security.
If the Fee Collection Cap is compromised, it can be regenerated using the admin cap—ensuring long-term safety for future projects built on the stSUI framework.

----------
 
**We extend our gratitude to SpringSui** for open-sourcing the code and introducing SIP-31 and SIP-33, which enabled instant unstaking and fungible LSTs—paving the way for further innovations like stSUI.

