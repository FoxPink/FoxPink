[![header](https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a1a2e,100:16213e&height=250&section=header&text=FoxPink&fontSize=70&fontColor=00d2ff&fontAlignY=32&desc=Frontend%20Engineer%20%7C%20Web3%20Security%20Researcher&descAlignY=52&descSize=18)](https://github.com/FoxPink)

<p align="center">
  <a href="https://readme-typing-svg.demolab.com">
    <img src="https://readme-typing-svg.demolab.com?lines=Frontend+Engineer+(React+%2F+Next.js);Smart+Contract+Security+Researcher;DeFi+Bug+Hunter+%26+Responsible+Disclosure;EVM+Gas+Optimization+%26+SLOAD+Surgery;Production-Grade+Full-Stack+Development&font=Fira+Code&weight=500&size=15&duration=2500&pause=800&color=00D2FF&center=true&width=700&height=50&repeat=true&background=FFFFFF00" alt="Typing SVG" />
  </a>
</p>

---

### About

Frontend engineer by trade, Solidity security researcher by passion. I build UIs with React and Next.js, then tear down EVM smart contracts to find what breaks. Every bug I find becomes a PR with a test case and a gas benchmark.

---

### How I Work

```
1. Fork the target repo
2. Identify vulnerable patterns (unsafe transfer, SLOAD loops, oracle manipulation)
3. Write a PoC forge test proving the bug
4. Fix + benchmark gas savings
5. Submit PR with detailed writeup
```

---

### Live Track Record

| Protocol | Component | Impact | Findings | PR |
| :--- | :--- | :---: | :--- | :---: |
| **Moonwell** ($500M+ TVL) | `Comptroller`, `MErc20`, `xWELLRouter` | Critical | 3 unsafe ERC20 transfers, 2 raw approves, 9 SLOAD caches | [#666](https://github.com/moonwell-fi/moonwell-contracts-v2/pull/666) |
| **Extra Finance** | `StakingRewards.sol` | High | Raw `.transfer()` -> `safeTransfer`, 8 SLOAD caches | [#6](https://github.com/ExtraFi/extra-contracts/pull/6) |
| **darwin** | `BasketVault.sol` | Critical | NAV/share price manipulation, dead code removal | [#1](https://github.com/dyonisos100/darwin/pull/1) |
| **Tokemak v1** | `DefiRound.sol`, `EventProxy.sol` | High | Chainlink oracle staleness, SLOAD loops | [#18](https://github.com/Tokemak/tokemak-smart-contracts-public/pull/18) |
| **Tokemak v2** | `RedstoneOracle.sol`, `Balancer*Vault.sol` | High | Missing roundId validation, SLOAD loops | [#2](https://github.com/Tokemak/v2-core-pub/pull/2) |
| **SafeBase** | `Treasury.sol` | High | USDT silent transfer failure | [#6](https://github.com/natalya-bbr/SafeBase/pull/6) |
| **basedollar** | `TroveManager.sol` | High | OOG in liquidation, 10.5k gas/trove | [#138](https://github.com/basedollar/basedollar/pull/138) |
| **grip-foundation** | `ServiceEscrow.sol` | Gas | 3 SLOAD cache hotspots, 4k-6k gas saved | [#1](https://github.com/grip-foundation/protocol/pull/1) |

---

### Tech Stack

**Frontend**

<p>
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />
  <img src="https://img.shields.io/badge/shadcn%2Fui-000000?style=for-the-badge&logo=shadcnui&logoColor=white" />
</p>

**Security**

<p>
  <img src="https://img.shields.io/badge/Solidity-363636?style=for-the-badge&logo=solidity&logoColor=white" />
  <img src="https://img.shields.io/badge/Foundry-000000?style=for-the-badge&logo=ethereum&logoColor=white" />
  <img src="https://img.shields.io/badge/Hardhat-FFF100?style=for-the-badge&logo=ethereum&logoColor=black" />
  <img src="https://img.shields.io/badge/Slither-5E5CE6?style=for-the-badge&logo=ethereum&logoColor=white" />
  <img src="https://img.shields.io/badge/Echidna-FF6B6B?style=for-the-badge&logo=ethereum&logoColor=white" />
  <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" />
</p>

---

### GitHub

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=FoxPink&show_icons=true&theme=radical&hide_border=true&count_private=true&include_all_commits=true&border_radius=8" height="170" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=FoxPink&layout=compact&theme=radical&hide_border=true&border_radius=8" height="170" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=FoxPink&theme=radical&hide_border=true&border_radius=8" />
</p>

---

### Contact

```yaml
email: aduy000@gmail.com
github: FoxPink
```

<p align="center">
  <i>"Don't trust the narrative. Trust the EVM state."</i>
</p>

[![footer](https://capsule-render.vercel.app/api?type=waving&color=0:16213e,50:1a1a2e,100:0d1117&height=120&section=footer)](https://github.com/FoxPink)
