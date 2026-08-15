<div align="center">

# Golibjon Sultonmurodov

**Full-Stack Web3 Engineer | Cloud & DevOps**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/golibjon-developer)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:sultonmurodovgolib@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/GOLIBJON-developer)
[![GitLab](https://img.shields.io/badge/GitLab_DevOps-FC6D26?style=flat&logo=gitlab&logoColor=white)](https://gitlab.com/golibjon-sultonmurodov)

</div>

---

I build production-grade decentralized applications and the infrastructure that ships them. My work spans two layers most developers only touch one of: Solidity smart contracts and full-stack Web3 frontends, and the GitOps pipelines — Docker, Kubernetes, ArgoCD, Terraform — that get them from `git push` to a running production system in under 3 minutes.

Four dApps deployed and Etherscan-verified on Sepolia. Nineteen logic bugs self-audited and fixed before deployment. A CI/CD pipeline optimized for 41% faster builds and an 87% smaller Docker image. I think about a project's full lifecycle — contract to container to cluster — not just the layer I'm asked to touch.

---

## ⚙️ Cloud & DevOps

**End-to-end GitOps pipeline:** `git push` → Docker build → registry push → Kubernetes rollout → ArgoCD sync → live, in under 3 minutes.

- 🐳 **Docker image optimization** — reduced a production Next.js image from 1.85 GB to 237 MB (**87% smaller**) using multi-stage builds and standalone output; 55.4 MB runtime footprint.
- ⚡ **CI/CD acceleration** — cut GitHub Actions build time from 4m 59s to 2m 55s (**41% faster**) with BuildKit cache mounts and tuned layer-cache export strategy.
- 🔄 **ArgoCD self-healing, stress-tested** — deleted a live Kubernetes namespace entirely; full infrastructure and application recovered automatically within seconds, zero manual intervention.
- ☸️ **Multi-path infrastructure deployment** — deployed the same workload three ways (EC2 + Ansible, EKS + Helm, EKS + ArgoCD GitOps) to understand the real tradeoffs, not just follow one tutorial.
- 🔐 **OIDC-based CI/CD auth** — GitHub Actions authenticates to AWS via short-lived OIDC tokens, no long-lived static credentials.

`Kubernetes` `ArgoCD` `Docker` `Terraform` `Ansible` `GitHub Actions` `AWS (EKS/ECR/IAM)` `Prometheus` `Grafana` `Linux`

---

## 🔗 Web3 Portfolio

### ⚡ [Raffle — Decentralized On-Chain Lottery](https://github.com/GOLIBJON-developer/Lottery)
[![Live](https://img.shields.io/badge/Live-000000?style=flat&logo=vercel)](https://raffle-mod.vercel.app)
[![Contract](https://img.shields.io/badge/Sepolia-Verified-2ECC71?style=flat&logo=ethereum)](https://sepolia.etherscan.io/address/0xc2cb8835769662d48E31A4272Bfde1A2530DD9b4)
[![Tests](https://img.shields.io/badge/Tests-101_passing-2ECC71?style=flat)]()
[![CI](https://github.com/GOLIBJON-developer/Lottery/actions/workflows/test.yml/badge.svg)](https://github.com/GOLIBJON-developer/Lottery/actions/workflows/test.yml)

Trustless lottery with Chainlink VRF v2.5 & Automation. No server. No admin draw button. 101 Foundry tests. Gas-optimized variant with 55% cold SLOAD reduction. Self-audited 7 logic bugs before deployment. Deployed via the GitOps pipeline above — containerized, CI/CD'd, and ArgoCD-synced.

`Solidity` `Foundry` `Chainlink VRF` `Chainlink Automation` `Next.js 14` `Wagmi` `Viem`

---

### 🚀 [PumpClone — Bonding Curve Token Launchpad](https://github.com/GOLIBJON-developer/fun-pump)
[![Live](https://img.shields.io/badge/Live-000000?style=flat&logo=vercel)](https://clone-pumpfun.vercel.app)
[![Contract](https://img.shields.io/badge/Sepolia-Verified-2ECC71?style=flat&logo=ethereum)](https://sepolia.etherscan.io/address/0x4C7702154e1E3f0cAbD4DaF96BB533F3678d7A01)
[![CI](https://github.com/GOLIBJON-developer/fun-pump/actions/workflows/test.yml/badge.svg)](https://github.com/GOLIBJON-developer/fun-pump/actions/workflows/test.yml)

PumpFun-inspired launchpad with a linear bonding curve — anyone can launch an ERC20 token permissionlessly. Factory pattern, slippage protection, IPFS/Pinata metadata, struct packing for 18% gas reduction on `buy()`.

`Solidity` `Foundry` `Factory Pattern` `Next.js 15` `Wagmi` `IPFS/Pinata`

---

### 🖼️ [NFT Marketplace — Multi-Currency Web3 dApp](https://github.com/GOLIBJON-developer/nft-marketplace)
[![Live](https://img.shields.io/badge/Live-000000?style=flat&logo=vercel)](https://nft-marketplace-mod.vercel.app)
[![Contract](https://img.shields.io/badge/Sepolia-Verified-2ECC71?style=flat&logo=ethereum)](https://sepolia.etherscan.io/address/0x340C12a94DD8BB553E2259884079B99afc132b8a)
[![Tests](https://img.shields.io/badge/Tests-101_passing-2ECC71?style=flat)]()

ETH, USDC, USDT payments in a single listing. EIP-2981 on-chain royalties enforced by the contract. 7-day emergency withdrawal timelock. 30% storage reduction via struct packing. 101 Foundry tests.

`Solidity` `EIP-2981` `Foundry` `Next.js 15` `Wagmi` `Viem` `Tailwind`

---

### 🏛️ [CrowdfundingDAO — Decentralized Crowdfunding + On-Chain Governance](https://github.com/GOLIBJON-developer/CrowdFundingDAO)
[![Live](https://img.shields.io/badge/Live-000000?style=flat&logo=vercel)](https://crowdfundingdaoapp.vercel.app)
[![Factory](https://img.shields.io/badge/4_Contracts-Verified-2ECC71?style=flat&logo=ethereum)](https://sepolia.etherscan.io/address/0x9c19ae6ff68c981827a7d6b4a6820f36f0c2637e)
[![Tests](https://img.shields.io/badge/Tests-124_passing-2ECC71?style=flat)]()
[![CI](https://github.com/GOLIBJON-developer/CrowdFundingDAO/actions/workflows/test.yml/badge.svg)](https://github.com/GOLIBJON-developer/CrowdFundingDAO/actions/workflows/test.yml)

OpenZeppelin Governor v5 + 2-day TimelockController. ERC20Votes token minted on contribution, burned on refund. Factory pattern for campaign isolation. 124 Foundry tests including 7 invariant properties.

`Solidity` `OZ Governor v5` `ERC20Votes` `TimelockController` `Foundry` `Next.js 14`

---

## 🛠 Tech Stack

**Cloud & DevOps**
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat&logo=argo&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat&logo=ansible&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)

**Blockchain**
![Solidity](https://img.shields.io/badge/Solidity-363636?style=flat&logo=solidity&logoColor=white)
![Foundry](https://img.shields.io/badge/Foundry-black?style=flat)
![Chainlink](https://img.shields.io/badge/Chainlink-375BD2?style=flat&logo=chainlink&logoColor=white)
![OpenZeppelin](https://img.shields.io/badge/OpenZeppelin-4E5EE4?style=flat&logo=openzeppelin&logoColor=white)
![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=flat&logo=ethereum&logoColor=white)

**Frontend & Backend**
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat&logo=react&logoColor=61DAFB)

---

## 📜 Certifications

- 🏅 **DevOps Engineer Professional** — Iceberg Data Lab
- 🏅 **Advanced Foundry** — Cyfrin Updraft (Mar 2026)
- 🏅 **Solidity Smart Contract Development** — Cyfrin Updraft (Jun 2025)
- 🏅 **Project Management Professional (PMP)** — Coursera (Apr 2023)
- 🏅 **Full Stack Web Development** — Iceberg Data Lab

---

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=GOLIBJON-developer&theme=default&show_icons=true&hide_border=true&count_private=true)

</div>
