# Diego Henrique Oris de Roa Antunes (Diego Oris)
### **CTO • Web3 Architect • 3D Systems & Cryptography Engineer**

<p align="left">
  <a href="https://wa.me/5511974289097"><img src="https://img.shields.io/badge/WhatsApp-Contact%20Direct-25D366?style=flat-square&logo=whatsapp&logoColor=white" /></a>
  <a href="mailto:diegoantunes2301@gmail.com"><img src="https://img.shields.io/badge/Email-diegoantunes2301%40gmail.com-ea4335?style=flat-square&logo=gmail&logoColor=white" /></a>
  <a href="https://x.com/diegoorisderoa"><img src="https://img.shields.io/badge/X%20%2F%20Twitter-%40diegoorisderoa-1DA1F2?style=flat-square&logo=x&logoColor=white" /></a>
  <a href="https://t.me/diegoorisderoa"><img src="https://img.shields.io/badge/Telegram-Chat-0088cc?style=flat-square&logo=telegram&logoColor=white" /></a>
</p>

---

I am a **CTO, Web3 Architect, and 3D Interactive Systems Engineer** with **6+ years of professional experience** delivering production-grade platforms globally (Switzerland, USA, Brazil). I specialize in designing and shipping mathematically secure cryptography systems, low-level blockchain protocols, scalable enterprise SaaS architectures, and high-performance **3D/WebGL simulation engines**. 

I bridge the gap between high-level business models and low-level bytecode execution, managing entire technical roadmaps from genesis blocks to hardware-accelerated 3D shaders.

---

## ⚡ Flagship Project: B2 Wallet
### **Multi-Chain Self-Custody Browser Extension & Mobile App (EVM, Solana, UTXO & Alt-Chains)**
> **Core Stack:** React, Vite, TypeScript, Ethers.js, WebCrypto API, Argon2id KDF, AES-256-GCM.  
> **Coverage:** EVM Layer-2s, Solana, UTXO chains, Tron, Waves, Stellar, Cardano, Polkadot, Monero, and Zcash.

*   **Defense-Grade Local Security:** Implemented a secure key derivation and storage system utilizing **Argon2id KDF** to protect seed phrases against high-performance GPU-based brute-force attacks, combined with authenticated **AES-256-GCM block ciphers** for encrypting the local state.
*   **Performance:** Fluid, hardware-accelerated UI transitions, a multi-currency responsive SVG dashboard, and real-time smart contract diagnostic engines tracking transaction payloads.
*   **Repository:** [View B2 Wallet](https://github.com/D-H-O-R-A/b2-wallet)

---

## 🎮 3D Engineering & Spatial Computing

I design high-performance interactive 3D simulations, real-time spatial cartography compilers, and custom game engines, targeting WebGL, desktop, and mobile environments.

<p align="center">
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 800 380" width="100%" style="background: #0d1117; border-radius: 16px; border: 1px solid #30363d; box-shadow: 0 10px 30px rgba(0,0,0,0.5);">
    <defs>
      <!-- Gradients -->
      <linearGradient id="cyan-grad" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#00f2fe" />
        <stop offset="100%" stop-color="#4facfe" />
      </linearGradient>
      <linearGradient id="purple-grad" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#b92b27" />
        <stop offset="100%" stop-color="#1565c0" />
      </linearGradient>
      <linearGradient id="neon-grad" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#ec008c" />
        <stop offset="100%" stop-color="#fc6767" />
      </linearGradient>
      <linearGradient id="green-grad" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#00ff87" />
        <stop offset="100%" stop-color="#60efff" />
      </linearGradient>
      
      <!-- Glow Filters -->
      <filter id="glow-cyan" x="-20%" y="-20%" width="140%" height="140%">
        <feGaussianBlur stdDeviation="6" result="blur" />
        <feComposite in="SourceGraphic" in2="blur" operator="over" />
      </filter>
      <filter id="glow-purple" x="-20%" y="-20%" width="140%" height="140%">
        <feGaussianBlur stdDeviation="8" result="blur" />
        <feComposite in="SourceGraphic" in2="blur" operator="over" />
      </filter>
      <filter id="glow-green" x="-20%" y="-20%" width="140%" height="140%">
        <feGaussianBlur stdDeviation="6" result="blur" />
        <feComposite in="SourceGraphic" in2="blur" operator="over" />
      </filter>

      <!-- Embedded CSS Animation Styles -->
      <style>
        .grid-line { stroke: #21262d; stroke-width: 0.5; }
        .axis-line { stroke: #30363d; stroke-dasharray: 4,4; }
        
        /* Floating animations */
        @keyframes float-top {
          0% { transform: translateY(0px); }
          50% { transform: translateY(-10px); }
          100% { transform: translateY(0px); }
        }
        @keyframes float-mid {
          0% { transform: translateY(0px); }
          50% { transform: translateY(-6px); }
          100% { transform: translateY(0px); }
        }
        @keyframes float-bot {
          0% { transform: translateY(0px); }
          50% { transform: translateY(-4px); }
          100% { transform: translateY(0px); }
        }
        
        /* Pulsing Glows */
        @keyframes glow-pulse {
          0% { opacity: 0.4; }
          50% { opacity: 0.9; }
          100% { opacity: 0.4; }
        }
        
        /* Data Flow dash offset */
        @keyframes flow {
          to { stroke-dashoffset: -40; }
        }
        
        /* Rotating animations */
        @keyframes spin-cw {
          from { transform: rotate(0deg); }
          to { transform: rotate(360deg); }
        }
        @keyframes spin-ccw {
          from { transform: rotate(0deg); }
          to { transform: rotate(-360deg); }
        }

        .layer-top { animation: float-top 6s ease-in-out infinite; }
        .layer-mid { animation: float-mid 5s ease-in-out infinite; }
        .layer-bot { animation: float-bot 4s ease-in-out infinite; }
        
        .pulse-circle { animation: glow-pulse 3s ease-in-out infinite; }
        .data-stream { stroke-dasharray: 8, 12; animation: flow 2s linear infinite; }
        
        .interactive-block {
          transition: all 0.4s cubic-bezier(0.16, 1, 0.3, 1);
          cursor: pointer;
        }
        .interactive-block:hover {
          filter: brightness(1.2) drop-shadow(0 0 15px var(--hover-color));
          transform: scale(1.03);
        }
      </style>
    </defs>

    <!-- Perspective Background Grid -->
    <g opacity="0.45">
      <!-- Perspective lines (Isometric Projection simulated grid) -->
      <line class="grid-line" x1="100" y1="350" x2="700" y2="50" />
      <line class="grid-line" x1="150" y1="350" x2="750" y2="50" />
      <line class="grid-line" x1="50" y1="350" x2="650" y2="50" />
      <line class="grid-line" x1="200" y1="350" x2="800" y2="50" />
      
      <line class="grid-line" x1="100" y1="50" x2="700" y2="350" />
      <line class="grid-line" x1="150" y1="50" x2="750" y2="350" />
      <line class="grid-line" x1="50" y1="50" x2="650" y2="350" />
      <line class="grid-line" x1="200" y1="50" x2="800" y2="350" />
      
      <!-- Axes -->
      <line class="axis-line" x1="400" y1="20" x2="400" y2="360" />
    </g>

    <!-- Background Laser Connection Paths (Connecting Layers) -->
    <g>
      <!-- Vertical main data trunk -->
      <line x1="400" y1="100" x2="400" y2="280" stroke="#1f2937" stroke-width="2" />
      
      <!-- Glowing data flow lines (dash offset animated) -->
      <path class="data-stream" d="M 280,260 L 400,280 L 520,260 L 400,190 Z" fill="none" stroke="#00ff87" stroke-width="1.5" />
      <path class="data-stream" d="M 400,280 L 400,190 L 400,100" fill="none" stroke="#00f2fe" stroke-width="2" />
      <path class="data-stream" d="M 250,170 L 400,190 L 550,170" fill="none" stroke="#fc6767" stroke-width="1.5" />
    </g>

    <!-- LAYER 3: BOTTOM (AI & Spatial PostGIS Data Mesh) -->
    <g class="layer-bot" style="--hover-color: #00ff87;">
      <!-- Main Isometric Base Plate -->
      <polygon class="interactive-block" points="400,250 560,280 400,310 240,280" fill="#161b22" stroke="#30363d" stroke-width="1.5" />
      
      <!-- Glowing active circuit tracks -->
      <polygon points="400,260 520,280 400,300 280,280" fill="none" stroke="url(#green-grad)" stroke-width="1" opacity="0.6" />
      
      <!-- Core Pulsing Radar rings -->
      <ellipse cx="400" cy="280" rx="40" ry="10" fill="none" stroke="#00ff87" stroke-width="1" class="pulse-circle" opacity="0.7" filter="url(#glow-green)" />
      <ellipse cx="400" cy="280" rx="80" ry="20" fill="none" stroke="#00ff87" stroke-width="0.5" class="pulse-circle" opacity="0.3" />

      <!-- High-precision spatial coordinate nodes -->
      <circle cx="280" cy="280" r="4" fill="#00ff87" filter="url(#glow-green)" />
      <text x="250" y="298" fill="#8b949e" font-family="monospace" font-size="10">PostGIS</text>
      
      <circle cx="520" cy="280" r="4" fill="#00ff87" filter="url(#glow-green)" />
      <text x="500" y="298" fill="#8b949e" font-family="monospace" font-size="10">UTM SIRGAS</text>

      <circle cx="400" cy="300" r="5" fill="#00ff87" filter="url(#glow-green)" />
      <text x="375" y="318" fill="#00ff87" font-family="monospace" font-size="10" font-weight="bold">AI Engine</text>
    </g>

    <!-- LAYER 2: MIDDLE (Unity 3D / WebGL Graphic Compilers) -->
    <g class="layer-mid" style="--hover-color: #ec008c;">
      <!-- Main Isometric Plate -->
      <polygon class="interactive-block" points="400,160 560,190 400,220 240,190" fill="#161b22" stroke="#30363d" stroke-width="1.5" />
      
      <!-- Connection lasers to adjacent entities -->
      <line x1="280" y1="190" x2="400" y2="190" stroke="url(#neon-grad)" stroke-width="1" />
      <line x1="520" y1="190" x2="400" y2="190" stroke="url(#neon-grad)" stroke-width="1" />

      <!-- Spinning isometric 3D wireframe cube (simulated through paths) -->
      <g transform="translate(400,190) scale(1.3, 0.7) rotate(45)">
        <!-- Cube vertices & polygons -->
        <polygon points="-15,-15 15,-15 15,15 -15,15" fill="none" stroke="url(#neon-grad)" stroke-width="1.5" filter="url(#glow-purple)" />
        <line x1="-15" y1="-15" x2="-15" y2="-15" stroke="#ec008c" stroke-width="2" />
      </g>
      
      <!-- Floating mesh nodes -->
      <circle cx="280" cy="190" r="4.5" fill="#ec008c" filter="url(#glow-purple)" />
      <text x="250" y="208" fill="#8b949e" font-family="monospace" font-size="10">Shader Graph</text>

      <circle cx="520" cy="190" r="4.5" fill="#fc6767" filter="url(#glow-purple)" />
      <text x="500" y="208" fill="#8b949e" font-family="monospace" font-size="10">Three.js / WebGL</text>

      <circle cx="400" cy="170" r="5" fill="#ec008c" filter="url(#glow-purple)" />
      <text x="375" y="152" fill="#fc6767" font-family="monospace" font-size="10" font-weight="bold">Unity Engine</text>
    </g>

    <!-- LAYER 1: TOP (Web3 & Secure Cryptography Core) -->
    <g class="layer-top" style="--hover-color: #00f2fe;">
      <!-- Main Isometric Plate -->
      <polygon class="interactive-block" points="400,70 560,100 400,130 240,100" fill="#161b22" stroke="#4facfe" stroke-width="1.5" />
      
      <!-- Hexagonal central processing block (Representing B2 Wallet keychain) -->
      <polygon points="400,85 425,95 425,115 400,125 375,115 375,95" fill="url(#cyan-grad)" opacity="0.85" filter="url(#glow-cyan)" />
      
      <!-- Floating orbiting cryptographic security node paths -->
      <ellipse cx="400" cy="100" rx="60" ry="15" fill="none" stroke="#00f2fe" stroke-width="1" stroke-dasharray="6,15" opacity="0.7" />
      
      <!-- Satellite orbiting keys -->
      <circle cx="340" cy="100" r="4" fill="#00f2fe" filter="url(#glow-cyan)" />
      <text x="290" y="118" fill="#8b949e" font-family="monospace" font-size="10">Argon2id KDF</text>

      <circle cx="460" cy="100" r="4" fill="#00f2fe" filter="url(#glow-cyan)" />
      <text x="440" y="118" fill="#8b949e" font-family="monospace" font-size="10">AES-256-GCM</text>

      <circle cx="400" cy="100" r="6" fill="#ffffff" filter="url(#glow-cyan)" />
      <text x="375" y="60" fill="#00f2fe" font-family="monospace" font-size="10" font-weight="bold">B2 Cryptography</text>
    </g>
  </svg>
</p>


### 🗺️ [pdf-to-maps](https://www.npmjs.com/package/pdf-to-maps) — Real-Time 3D WebGL Cartography Compiler
*   **The Pipeline:** Parses georeferenced land deed PDFs (SIGEF/INCRA) offline, resolves high-precision polygon closure constraints, performs ellipsoidal geodetic conversions (SIRGAS2000 UTM Projections), and compiles **interactive 3D WebGL isometric models** on-the-fly.
*   **Advanced Graphics:** Renders detailed 3D terrain boundaries, height maps, and spatial meshes in the browser utilizing **Three.js** and WebGL, alongside AutoCAD-compliant DXF CAD layouts and QGIS-compliant GeoJSON schemas.
*   **DevOps:** Built with strict GitHub Actions CI/CD and **SLSA Level 3 Provenance** for secure, signed NPM package delivery.

### 🧩 Match Blocks MVP — Unity 2D/3D Gameplay Engine
*   **The Architecture:** Candy-crush style match game custom-built on a data-driven, strictly decoupled FSM (Finite State Machine) loop and global Event Bus to keep graphics rendering isolated from mathematical match resolution.
*   **Visual Juice & VFX:** Implemented custom **Shader Graph** effects for high-end rendering transitions, procedural particle generators, DOTween custom animations, and an asset-streaming system utilizing **Unity Addressables**.
*   **Stack:** Unity 2022 LTS, C#, Universal Render Pipeline (URP), Object Pooling, Seeded Deterministic RNG, Unity Ads/IAP/Analytics.

---

### 🏛️ [Parque Arqueológico de São João Marcos](https://www.saojoaomarcos.com.br/) — Interactive 3D Historical Reconstruction & Virtual Museum
*   **The Project:** Collaborated as the lead developer to create an interactive georeferenced virtual museum for the first archaeological park in Brazil (São João Marcos, Rio de Janeiro). Reconstructed the entire historical 18th-century town flooded in the 1940s into a high-fidelity interactive digital environment.
*   **The Engineering:** Programmed the real-time 3D environments, spatial mapping coordinates, highly optimized WebGL/mobile layouts, georeferenced terrain meshes, and interactive building nodes. Enabled visitors to virtually walk through reconstructed ruins and historical landmarks with rich historical overlays.
*   **Stack:** Unity 3D, C#, WebGL, Three.js, Custom Shaders, Georeferenced Terrain Meshes, Spatial Mapping.

---

## 🚀 Recent Enterprise Deployments (2026)

### ⚖️ [Solucione Multas](https://solucionemultas.com.br/) — Legal Tech Enterprise SaaS Ecosystem
*   **The Venture:** Co-founded and built from the ground up as CTO, owning the complete technical roadmap.
*   **The Architecture:** Unifies a high-converting public landing portal, a secure dedicated Client Area (User Portal) for case tracking, and a centralized administrative telemetry control panel.
*   **Automation:** Built an automated conversational chatbot via the WhatsApp Business API that executes initial user triage and feeds structured data directly into backend systems.
*   **Stack:** React + Vite, TypeScript, TailwindCSS, Firebase (Firestore Real-time Sync, Cloud Functions, Auth, FCM), Facebook Conversions API.

### 👼 [Anjo Online](https://anjoonline.com.br/) — Philanthropic Memorial SaaS
*   **The System:** A compassionate virtual memorial and real-time ceremony streaming SaaS built for absolute data privacy and global performance.
*   **Regional Payment Gateways:** Custom payment gateway routing using Mercado Pago for Brazil and **Swiss TWINT** for operations in Switzerland.
*   **Infrastructure:** Engineered a NestJS backend deployed on containerized Google Cloud Run nodes, syncing via Redis caching and PostgreSQL ACID-compliant databases.
*   **Stack:** Next.js, React, TypeScript, Node.js, NestJS, PostgreSQL, Redis, Google Cloud Run, Firebase Cloud Messaging (FCM), i18n (6 languages).

### 📱 [Click Serviços](https://clickservico.com/) — Enterprise Multi-Platform Marketplace
*   **The System:** A complete service marketplace connecting verified local service professionals with users through one-tap bookings and real-time messaging.
*   **The Architecture:** Combines responsive Next.js administrative dashboards and high-performance native iOS and Android applications compiled with Flutter.
*   **Geospatial Queries:** Backed by NestJS on Google Cloud Run utilizing a PostgreSQL database with **PostGIS** for real-time spatial geolocation queries.
*   **Stack:** Flutter, Next.js, React, TypeScript, NestJS, PostgreSQL, PostGIS, Google Cloud Run, Redis, Mercado Pago.

---

### 🌱 [Young Market](https://www.youngmarket.com.br/) — Custom Blockchain Core & Athlete Crowd-Tokenization MVP
*   **The Venture:** Served as **Founding CTO** (Equity Partner), designing and building the initial MVP from the ground up.
*   **The Architecture:** Developed a proprietary blockchain core on top of the Waves network. Designed and programmed custom smart contracts in Ride, implemented atomic swap interoperability bridges to Ethereum, and engineered athlete image-rights tokenization mechanics.
*   **Integrations:** Developed a custom mobile application interface, integrated Stripe, and built a custom payment gateway for direct fiat-to-token purchases. Pivoted the core system mechanics to comply with Brazilian CVM crowdfunding regulations.
*   **Stack:** Waves Core Basis, Ride, React Native, TypeScript, Node.js, Stripe, CVM Compliance.

---

## 🛠️ Main Tech Ecosystem

```yaml
Blockchain Core: Solidity (0.8.x), Ride (Waves), WebCrypto API, Hardhat, Foundry, Slither, OpenZeppelin, Ethers.js
3D & Spatial:    Unity 3D/2D (C#), WebGL, URP (Universal Render Pipeline), Shader Graph, Three.js, Proj4.js
Backend & Cloud: NestJS, Node.js, Go, Python, PostgreSQL, PostGIS, Redis, Google Cloud Run, AWS (ECS, RDS, KMS), Terraform
Frontend & Mobile: Next.js 14, React, TypeScript, TailwindCSS, Flutter, React Native, PWA
```

---

## 📈 Analytics & GitHub Stats

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=d-h-o-r-a&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Diego's GitHub Stats" width="400" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=d-h-o-r-a&layout=compact&theme=tokyonight&hide_border=true" alt="Diego's Top Languages" width="350" />
</p>

---

## 🔄 Recent GitHub Activity & Commits
<!-- START_SECTION:activity -->
#### 🛠️ Recent Contributions
- **b2-wallet:** Refactored complete application event listeners; modularized `app-events-modals.js` and `app-events-config.js` (~3,700 lines optimized)
- **b2-wallet:** Created recursive codebase architecture markdown documentation under `src/js/README.md`
- **pdf-to-maps:** Optimized coordinates conversion algorithms utilizing geodetic projections (SIRGAS2000)
- **b2-wallet:** Added robust multi-wallet routing with bip39 keychain configuration
- **click-servicos-app:** Optimized PostGIS geolocation query parameters on Google Cloud Run NestJS backend
<!-- END_SECTION:activity -->


---

## 💬 Get in Touch

I partner with teams to architect secure Web3 protocols, high-performance backends, and interactive 3D/simulation environments.

*   💬 **WhatsApp:** [+55 (11) 97428-9097](https://wa.me/5511974289097)
*   📧 **Direct Email:** [diegoantunes2301@gmail.com](mailto:diegoantunes2301@gmail.com)
*   🐦 **X (Twitter):** [@diegoorisderoa](https://x.com/diegoorisderoa)
*   ✈️ **Telegram:** [@diegoorisderoa](https://t.me/diegoorisderoa)
*   📝 **Medium Articles:** [@diegoorisderoa](https://medium.com/@diegoorisderoa)
