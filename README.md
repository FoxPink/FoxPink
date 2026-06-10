```
  ███████╗ ██████╗ ██╗  ██╗██████╗ ██╗███╗   ██╗██╗  ██╗
  ██╔════╝██╔═══██╗╚██╗██╔╝██╔══██╗██║████╗  ██║██║ ██╔╝
  █████╗  ██║   ██║ ╚███╔╝ ██████╔╝██║██╔██╗ ██║█████╔╝ 
  ██╔══╝  ██║   ██║ ██╔██╗ ██╔═══╝ ██║██║╚██╗██║██╔═██╗ 
  ██║     ╚██████╔╝██╔╝ ██╗██║     ██║██║ ╚████║██║  ██╗
  ╚═╝      ╚═════╝ ╚═╝  ╚═╝╚═╝     ╚═╝╚═╝  ╚═══╝╚═╝  ╚═╝
```

Frontend Engineer · Web3 Security Researcher · EVM Gas Optimizer

---

### track-record

| protocol | component | impact | findings | pr |
| :--- | :--- | :---: | :--- | :---: |
| moonwell | `Comptroller`, `MErc20`, `xWELLRouter` | critical | 3 unsafe ERC20 transfers, 2 raw approves, 9 SLOAD caches | [#666](https://github.com/moonwell-fi/moonwell-contracts-v2/pull/666) |
| extra-finance | `StakingRewards.sol` | high | raw `.transfer()` -> `safeTransfer`, 8 SLOAD caches | [#6](https://github.com/ExtraFi/extra-contracts/pull/6) |
| darwin | `BasketVault.sol` | critical | NAV/share price manipulation, dead code removal | [#1](https://github.com/dyonisos100/darwin/pull/1) |
| tokemak-v1 | `DefiRound.sol`, `EventProxy.sol` | high | Chainlink oracle staleness, SLOAD loops | [#18](https://github.com/Tokemak/tokemak-smart-contracts-public/pull/18) |
| tokemak-v2 | `RedstoneOracle.sol`, `Balancer*Vault.sol` | high | missing roundId validation, SLOAD loops | [#2](https://github.com/Tokemak/v2-core-pub/pull/2) |
| safebase | `Treasury.sol` | high | USDT silent transfer failure | [#6](https://github.com/natalya-bbr/SafeBase/pull/6) |
| basedollar | `TroveManager.sol` | high | OOG in liquidation, 10.5k gas/trove | [#138](https://github.com/basedollar/basedollar/pull/138) |
| grip-foundation | `ServiceEscrow.sol` | gas | 3 SLOAD cache hotspots, 4k-6k gas saved | [#1](https://github.com/grip-foundation/protocol/pull/1) |

---

### stack

```
frontend   │  React  Next.js  TypeScript  Tailwind  shadcn/ui
security   │  Solidity  Foundry  Hardhat  Slither  Echidna  Rust
```

---

### stats

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=FoxPink&theme=github-compact&hide_border=true&area=true&custom_title=activity" width="95%" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=FoxPink&show_icons=true&theme=github_dark&hide_border=true&count_private=true&include_all_commits=true&border_radius=6" height="160" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=FoxPink&layout=compact&theme=github_dark&hide_border=true&border_radius=6" height="160" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=FoxPink&theme=github_dark_blue&hide_border=true&border_radius=6" />
</p>

---

### contact

```
email: aduy000@gmail.com
web:   github.com/FoxPink
```

<p align="right">
  <i>don't trust the narrative. trust the EVM state.</i>
</p>
