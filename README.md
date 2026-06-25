<div align="center">

```
╔══════════════════════════════════════════════════════════╗
║          TENYOKJ  //  ON-CHAIN SYSTEMS ENGINEER          ║
╚══════════════════════════════════════════════════════════╝
```

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=20&duration=3500&pause=800&color=22C55E&center=true&vCenter=true&width=700&lines=Solidity+%26+Vyper+Developer;DAO+Infrastructure+Builder;AMM+%26+DeFi+Protocol+Engineer;On-chain+Systems+Architect;Building+Real+Web3+Infrastructure" />

[![Portfolio](https://img.shields.io/badge/🌐_Portfolio-tenyokj.vercel.app-22C55E?style=flat-square&labelColor=0d1117)](https://tenyokj.vercel.app)
[![Telegram](https://img.shields.io/badge/Telegram-@tenkoffj-2CA5E0?style=flat-square&logo=telegram&labelColor=0d1117)](https://t.me/tenkoffj)
[![Gmail](https://img.shields.io/badge/Gmail-dv842449-EA4335?style=flat-square&logo=gmail&labelColor=0d1117)](mailto:dv842449@gmail.com)
[![Reddit](https://img.shields.io/badge/Reddit-PralineSeparate5261-FF4500?style=flat-square&logo=reddit&labelColor=0d1117)](https://www.reddit.com/user/PralineSeparate5261/)

</div>

---

## `$ whoami`

Solidity & Vyper developer focused on **building real blockchain infrastructure** — systems that communities actually use to coordinate, govern, and build together.

I'm not interested in hype. I'm interested in **on-chain primitives that work**.

```python
tenyokj = {
    "focus"      : ["DAO infrastructure", "DeFi protocols", "Smart contract architecture"],
    "languages"  : ["Solidity", "Vyper", "TypeScript", "Rust", "Python"],
    "philosophy" : "ship contracts that are boring in the best possible way — secure, tested, immutable",
    "currently"  : "designing upgradeable governance systems + AMM curve research",
}
```

> *I love the moment when after a long day you sit down at your desk, open your laptop, and start building.*
> *Writing smart contracts, committing code, pushing changes — that's real relaxation.*

---

## `$ ls ./tech-stack`

### ⛓ Blockchain

![Solidity](https://img.shields.io/badge/Solidity-363636?style=for-the-badge&logo=solidity)
![Vyper](https://img.shields.io/badge/Vyper-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=for-the-badge&logo=ethereum)
![Hardhat](https://img.shields.io/badge/Hardhat-F7DF1E?style=for-the-badge&logo=ethereum&logoColor=black)
![Foundry](https://img.shields.io/badge/Foundry-FF6B35?style=for-the-badge&logo=ethereum&logoColor=white)
![Ethers.js](https://img.shields.io/badge/Ethers.js-2535A0?style=for-the-badge&logo=ethereum)
![OpenZeppelin](https://img.shields.io/badge/OpenZeppelin-4E5EE4?style=for-the-badge&logo=openzeppelin)
![Chainlink](https://img.shields.io/badge/Chainlink-375BD2?style=for-the-badge&logo=chainlink)

### 🖥 Frontend

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![TheGraph](https://img.shields.io/badge/The_Graph-6f4cff?style=for-the-badge&logo=thegraph)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

### ⚙️ Backend & Tooling

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql)
![IPFS](https://img.shields.io/badge/IPFS-65C2CB?style=for-the-badge&logo=ipfs&logoColor=white)

<div align="center">
<img src="https://skillicons.dev/icons?i=solidity,ts,js,react,nextjs,nodejs,rust,python,git,github,docker,graphql,tailwind,vite,vscode,npm" />
</div>

---

## `$ cat ./what-i-build.md`

```
┌─────────────────────────────────────────────────────────┐
│  DAO GOVERNANCE SYSTEMS                                  │
│  → proposal lifecycle, vote delegation, timelock ctrl   │
│                                                         │
│  AMM & DEFI PROTOCOLS                                   │
│  → custom curve design, liquidity math, fee mechanics   │
│                                                         │
│  UPGRADEABLE CONTRACT ARCHITECTURES                     │
│  → UUPS / transparent proxy patterns, storage layout    │
│                                                         │
│  ON-CHAIN COORDINATION TOOLS                            │
│  → multisig infra, treasury management, role systems    │
│                                                         │
│  FULL-STACK WEB3 APPLICATIONS                           │
│  → subgraph indexing, wallet UX, real-time on-chain UI  │
└─────────────────────────────────────────────────────────┘
```

---

## `$ cat ./vyper-philosophy.md`

I write contracts in both **Solidity** and **Vyper** — and I choose deliberately.

**Vyper** is my go-to when:
- the contract is a DeFi primitive (AMM, vault, stablecoin mechanics)
- I want readability to be a security property, not just a nice-to-have
- auditability matters more than flexibility

```vyper
# @version ^0.3.10
# Vyper: no inheritance, no overloading, no footguns.
# If you can't read it in 5 minutes, something's wrong.

owner: address
balances: HashMap[address, uint256]

@external
def deposit():
    self.balances[msg.sender] += msg.value
```

**Solidity** is my tool when:
- I need upgradeable proxy patterns
- complex inheritance or interface compliance is required
- ecosystem tooling heavily favors it (Hardhat plugins, OZ, etc.)

---

## `$ cat ./smart-contract-workflow.md`

My development process is security-first:

```
1. spec        →  write invariants before writing code
2. draft       →  implement with minimal complexity
3. test        →  100% branch coverage, fuzz testing, fork tests
4. review      →  static analysis (Slither, Mythril)
5. audit       →  peer review + external eyes
6. deploy      →  staged rollout, monitoring from day one
```

Tools in my workflow: **Hardhat** · **Foundry** · **OpenZeppelin upgradeable** · **Slither** · **test fixtures** · **fork testing against mainnet**

---

## `$ ./stats.sh`

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=tenyokj&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=22C55E&icon_color=22C55E&text_color=c9d1d9" width="48%"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=tenyokj&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=22C55E&text_color=c9d1d9" width="40%"/>

</div>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com?user=tenyokj&theme=github-dark-blue&hide_border=true&background=0D1117&ring=22C55E&fire=22C55E&currStreakLabel=22C55E"/>

</div>

---

## `$ git log --graph --oneline`

<div align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=tenyokj&theme=github-compact&bg_color=0d1117&color=22C55E&line=22C55E&point=ffffff&hide_border=true"/>
</div>

---

## `$ cat ./lets-connect.md`

Open to collaboration on:

- **DAO & governance infrastructure** — building voting systems, delegation, execution layers
- **DeFi protocol design** — AMMs, lending, yield strategies, tokenomics
- **Audit & security reviews** — pair reviews, invariant testing
- **Open source Web3 tooling** — anything that makes the ecosystem better
- **Early-stage startup ideas** — if you're building something real, let's talk

```
📬  Telegram  →  t.me/tenkoffj
📧  Gmail     →  dv842449@gmail.com
🌐  Portfolio →  tenyokj.vercel.app
👾  Reddit    →  u/PralineSeparate5261
```

---

<div align="center">

```
╔══════════════════════════════════════════════════════════╗
║   Building the on-chain infrastructure of what's next   ║
║                    — block by block —                    ║
╚══════════════════════════════════════════════════════════╝
```

</div>
