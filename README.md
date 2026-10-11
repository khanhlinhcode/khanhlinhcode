<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/profile-header-dark.png">
  <source media="(prefers-color-scheme: light)" srcset="./assets/profile-header-light.png">
  <img alt="Tô Khánh Linh — Software Engineer building mobile, web, backend, AI/RAG, IoT, and blockchain systems" src="./assets/profile-header-light.png" width="100%">
</picture>

<p align="center">
  <a href="https://khanh-linh-portfolio.vercel.app/"><strong>Portfolio</strong></a>
  &nbsp;·&nbsp;
  <a href="https://fartamarket.company"><strong>Farta Market</strong></a>
  &nbsp;·&nbsp;
  <a href="https://nlp-academic-search.streamlit.app/"><strong>RAG Demo</strong></a>
</p>

## Engineering profile

I am a Computer Science engineer who builds complete software systems—from mobile
and web interfaces to secure APIs, retrieval pipelines, edge devices, and
blockchain-backed verification. I care about clear architecture, explicit
contracts, security boundaries, accessibility, and evidence that the software
actually works.

Based in **Cần Thơ, Việt Nam** and open to **Mobile Developer** and
**Full-stack Software Engineer** opportunities.

## What I work with

**Mobile**<br>
`Flutter` `Dart` `Riverpod` `Dio` `iOS` `Android` `SQLite` `Secure Storage`

**Frontend**<br>
`React` `Next.js` `TypeScript` `JavaScript` `Vite` `Redux Toolkit`
`TanStack Query` `SCSS` `Tailwind CSS` `Accessibility`

**Backend & APIs**<br>
`Laravel` `PHP` `Node.js` `NestJS` `FastAPI` `REST` `Sanctum` `MFA`
`Rate Limiting` `Idempotency`

**AI, Machine Learning & RAG**<br>
`Python` `PyTorch` `scikit-learn` `Qdrant` `BM25` `Dense Retrieval` `RRF`
`Semantic Verification` `Recommendation Systems` `NLP`

**IoT & Edge Computing**<br>
`Raspberry Pi` `ESP32` `MediaPipe` `OpenCV` `MQTT` `PlatformIO` `Firebase`
`Embedded C++`

**Blockchain**<br>
`Solidity` `Hardhat` `ethers.js` `IPFS` `MetaMask` `Smart Contracts`

**Data, infrastructure & quality**<br>
`MySQL` `PostgreSQL` `MongoDB` `Redis` `Docker` `Linux` `GitHub Actions`
`Vitest` `Playwright` `Pytest` `Flutter Test`

## Selected systems

### Farta commerce platform

An end-to-end commerce ecosystem spanning a Flutter customer app, an accessible
React storefront, and a Laravel API. The implementation covers authentication,
catalog, cart, COD/SePay checkout, order tracking, capability authorization,
idempotency, inventory controls, and privacy-aware network logging.

[`Mobile`](https://github.com/khanhlinhcode/Farta_Mobile) ·
[`Storefront`](https://github.com/khanhlinhcode/Farta_Market) ·
[`Laravel API`](https://github.com/khanhlinhcode/BE_Farta-Market-) ·
[`TypeScript commerce system`](https://github.com/khanhlinhcode/farta-commerce)

**Core stack:** `Flutter` `React` `Laravel` `Sanctum` `MySQL` `Playwright`

### Semantically verified academic RAG

A hybrid academic search and RAG system that combines lexical and dense
retrieval, streams grounded answers, validates citations, maps claims to
evidence, and fails closed when verification cannot support the response.

[`Source`](https://github.com/khanhlinhcode/NLP-Academic-Search-RAG-Engine) ·
[`Live demo`](https://nlp-academic-search.streamlit.app/) ·
[`API documentation`](https://nlp-academic-search-api.onrender.com/docs)

**Core stack:** `Python` `FastAPI` `Qdrant` `BM25` `RRF` `Streamlit`

### Edge-AI drowsiness detection

An IoT system where a Raspberry Pi processes camera input with MediaPipe and
OpenCV, sends real-time state through MQTT to an ESP32 alert device, and exposes
status and history to a Flutter monitoring application.

[`Source`](https://github.com/khanhlinhcode/Drowsy_IOT)

**Core stack:** `Raspberry Pi` `ESP32` `MediaPipe` `OpenCV` `MQTT` `Flutter`

### CertChain

A certificate issuance, revocation, and public verification system. Critical
certificate state is anchored in a Solidity smart contract, while the product
layer provides QR verification, IPFS document storage, and administrative
workflows.

[`Source`](https://github.com/khanhlinhcode/BlockChain)

**Core stack:** `Next.js` `TypeScript` `Node.js` `Solidity` `Hardhat` `IPFS`
`MongoDB`

### Recommendation systems

A full-stack book recommendation environment for comparing User-CF, Item-CF,
matrix factorization, content-based retrieval, and weighted hybrid models—with
evaluation tooling, a FastAPI service, and a React interface.

[`Source`](https://github.com/khanhlinhcode/HTGY)

**Core stack:** `Python` `scikit-learn` `FastAPI` `React` `SQLAlchemy`
`Playwright`

### TinyVietLM

A reproducible research foundation for a small Vietnamese decoder-only language
model. The current scope covers audited corpus preparation, deterministic data
artifacts, Byte-Level BPE tooling, portable compute checks, and explicit human
approval gates; model training is intentionally not claimed as complete.

[`Source`](https://github.com/khanhlinhcode/TinyVietLM)

**Core stack:** `Python` `PyTorch` `Byte-Level BPE` `MLOps` `Data Provenance`

## Engineering principles

- **Build across boundaries.** Product UI, API contracts, persistence, security,
  and deployment should form one coherent system.
- **Keep the server authoritative.** Money, inventory, permissions, payment
  state, and idempotency belong at trusted boundaries.
- **Make AI evidence-aware.** Retrieval provenance, citation validation, and
  honest refusal matter more than confident-looking output.
- **Design for failure.** Offline states, retries, stale responses, partial
  availability, and abuse controls are part of the product—not afterthoughts.
- **Verify before claiming.** Tests, builds, runtime evidence, and explicit
  limitations are part of delivery.

## Current direction

I am currently deepening my work in Flutter product engineering, secure
transactional systems, retrieval quality, and edge-to-cloud software. For
collaboration or opportunities, visit
[khanh-linh-portfolio.vercel.app](https://khanh-linh-portfolio.vercel.app/).
