## Hi, I'm FoxPink 🦊⚡

**Web3 Security Researcher & EVM Gas Optimizer** — Specializing in structural vulnerability discovery, economic attack mitigation, and production-grade gas optimizations across the Base ecosystem.

---

### 📊 Live Track Record

| Protocol | Component | Impact | Issue | PR |
| :--- | :--- | :---: | :--- | :---: |
| **Moonwell** ($500M+ TVL) | `Comptroller`, `MErc20`, `xWELLRouter` | 🔴 High | 3 unsafe ERC20 transfers, 2 raw approves, 9 SLOAD caches | [#666](https://github.com/moonwell-fi/moonwell-contracts-v2/pull/666) |
| **Extra Finance** | `StakingRewards.sol` | 🔴 Medium | Raw `.transfer()` → `safeTransfer`, 4 storage loops cached | [#6](https://github.com/ExtraFi/extra-contracts/pull/6) |
| **basedollar** | `TroveManager.sol` | 🔴 Medium | OOG in liquidation, 10.5k gas/trove saved | [#138](https://github.com/basedollar/basedollar/pull/138) |
| **darwin** | `BasketVault.sol` | 🔴 High | NAV/share price manipulation fix + gas | [#1](https://github.com/dyonisos100/darwin/pull/1) |
| **SafeBase** | `Treasury.sol` | 🔴 Medium | USDT silent transfer failure | [#6](https://github.com/natalya-bbr/SafeBase/pull/6) |
| **grip-foundation** | `ServiceEscrow.sol` | 🟡 Gas | 4k–6k gas saved via SLOAD caching | [#1](https://github.com/grip-foundation/protocol/pull/1) |
| **Tokemak v1** | `DefiRound.sol`, `EventProxy.sol` | 🔴 Medium | Chainlink oracle staleness, SLOAD loops | [#18](https://github.com/Tokemak/tokemak-smart-contracts-public/pull/18) |
| **Tokemak v2** | `RedstoneOracle.sol`, `Balancer*Vault.sol` | 🔴 Medium | Missing roundId validation, SLOAD loops | [#2](https://github.com/Tokemak/v2-core-pub/pull/2) |

---

### 🛠️ Arsenal

- **Languages:** Solidity (0.4–0.8), Yul/Assembly, TypeScript, Rust
- **Frameworks:** Foundry, Hardhat, ApeWorX
- **Security:** Slither, Aderyn, Echidna, Mythril
- **Expertise:** DeFi logic flaws, price oracle manipulation, flash loan vectors, storage layout optimization (SLOAD/SSTORE), ERC20 non-compliance

---

### 📡 Contact

- **Email:** [Your Email]
- **GitHub:** [FoxPink](https://github.com/FoxPink)

---

> *"Don't trust the narrative. Trust the EVM state."*
