# Diego Oris
### Systems Engineer • Cryptography, Web3 & Interactive 3D

```go
const (
    Location = "São Paulo, Brazil"
    Focus    = "Blockchain Core, High-Performance SaaS, Geoprocessing & Unity 3D"
)
```

I design and build high-security digital custody systems, custom Layer-1 blockchains, geoprocessors, and interactive 3D engines. My focus is on shipping optimized, production-ready code that is mathematically sound and highly resilient.

---

### 🛠️ Featured Open Source Libraries

#### 📦 [`cryptoseed`](https://www.npmjs.com/package/cryptoseed) — Mnemonic Seed Recovery Engine
A high-performance cryptographic utility developed to recover damaged or miswritten physical seed phrase backups. Originally engineered in 2023 for a cybersecurity and digital custody agency in Switzerland, now open-sourced and published on NPM.

```bash
# Install the CLI tool globally
npm install -g cryptoseed

# Run the recovery wizard against damaged BIP39 phrases
cryptoseed recovery --words "word1 word2 word3 ... word12" --dict english
```

*   **Algorithms:** Levenshtein distance spell-checking against BIP39 dictionaries (10 languages) and parallel backtracking/brute-force searches for out-of-order words.
*   **Derivation:** Deterministic address mapping across 39 distinct blockchains (Bitcoin Taproot/Bech32, EVM, Solana, TRON, Waves, Cardano, Monero).
*   **Privacy:** Optional balance verification via public RPCs or private nodes running on localhost to protect public key network privacy.

---

#### 🗺️ [`pdf-to-maps`](https://www.npmjs.com/package/pdf-to-maps) — Geoprocessor & 3D Interactive Cartography
A 100% offline geoprocessing NPM library that parses georeferenced land deed PDFs (SIGEF/INCRA), calculates polygon closure constraints, performs geodetic-to-cartesian conversions (SIRGAS2000 UTM), and exports professional GIS deliverables.

```bash
# Run the geoprocessing tool on a land deed PDF
npx pdf-to-maps process --input land_deed.pdf --output-format geojson
```

*   **Interactive 3D:** Automatically compiles responsive, realistic 3D WebGL isometric maps (Three.js), QGIS-compliant GeoJSON, AutoCAD-compatible DXF files, and custom 2D drawing sheets.
*   **Security:** Fully verified with GitHub Actions CI/CD and **SLSA Level 3 Provenance** for tamper-proof distribution.

---

### 🌐 Key Production Deployments

#### 🛡️ [B2 Wallet](https://github.com/D-H-O-R-A/b2-wallet) — Multi-Chain Self-Custodial Suite
A security-first, multi-wallet Web3 browser extension and mobile wallet supporting EVM networks, Solana, UTXO chains, Tron, Waves, Stellar, Cardano, Polkadot, Monero, and Zcash.
*   **Cryptography:** Uses **Argon2id KDF** to defend against GPU-based brute-force attacks and authenticated **AES-256-GCM** block ciphers for encrypting the local keychain state.
*   **Diagnostics:** Features dynamic state management, hardware-accelerated fluid transitions, and real-time smart contract diagnostics.

#### ⛓️ [Zero Swap & GIC Smart Chain](https://www.youtube.com/watch?v=dEN2WaxQB4Q) — EVM Layer-1 & DeFi Ecosystem
Designed and deployed a proprietary EVM-compatible Layer-1 blockchain (GIC Smart Chain) based on Go-Ethereum, establishing genesis parameters, validator node networks, Clique PoA consensus, WSS/RPC endpoints, and custom block explorer configurations.
*   **DeFi Layer:** Built Zero Swap, a complete DeFi suite with Uniswap V2 AMM swaps ($x \cdot y = k$), MasterChef yield farms, secure multi-sig bridges (lock-and-mint validators), and an ERC-721/1155 NFT marketplace with lazy minting and royalties.

#### ⚖️ [Solucione Multas](https://solucionemultas.com.br/) — Legal Tech Enterprise Platform
Co-founded and engineered an enterprise-grade Legal Tech system as CTO. Integrates a customer portal, an administrative telemetry panel, and an automated conversational WhatsApp Business API chatbot for user assessment and CRM intake.

#### 👼 [Anjo Online](https://anjoonline.com.br/) — Philanthropic SaaS
A high-reliability memorial and ceremony streaming SaaS built on Next.js/NestJS, containerized on Google Cloud Run with PostgreSQL and Redis caching. Features smart regional payment gateways: TWINT for Switzerland and Mercado Pago for Brazil.

---

### 💻 Technologies & Stack

*   **Blockchain Core & Smart Contracts:** Go-Ethereum (Geth), Solidity (0.8.x), Ride (Waves Core), Plutus (Cardano), TVM (Tron), Hardhat, Foundry, Slither, Echidna (Fuzzing), Gnosis Safe, OpenZeppelin.
*   **Interactive 3D & Mobile:** Unity 2D/3D (C#), WebGL, Universal Render Pipeline (URP), Shader Graph, Proj4.js, Three.js, Flutter, React Native.
*   **Backend & Infrastructure:** Node.js, NestJS, Go, Python, PostgreSQL, PostGIS (spatial queries), Redis, BullMQ, Docker, Kubernetes, Google Cloud Run, AWS (ECS, RDS, KMS), Terraform, GitHub Actions.
*   **Frontend & Tooling:** Next.js, React, TypeScript, TailwindCSS, Framer Motion, Zustand, i18n, PWA.

---

### 🔗 Let's Connect

```yml
contacts:
  whatsapp: "+55 (11) 97428-9097"
  email:    "diegoantunes2301@gmail.com"
  x:        "https://x.com/diegoorisderoa"
  telegram: "https://t.me/diegoorisderoa"
  medium:   "https://medium.com/@diegoorisderoa"
```
