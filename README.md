# 🏛 ARCHOVA ($ARCH)

**The Living Incubator of Solana**  
Archova is a decentralized, living archive that transforms collective ideas into on-chain creations.  
Every idea is an **Arc** — a seed of potential — and the community decides which ones awaken and evolve into real projects.

---

## 🌍 Core Concept

Archova exists as an open, evolving library of on-chain ideas — half incubator, half archive.

- Each **Arc** begins as a submitted idea (title, pitch, description, ticker).  
- Every Arc lives inside the **Library**, publicly visible and votable.  
- When an Arc gains enough support, it **awakens** — transitioning from concept to a funded, community-driven project.  
- Holders of `$ARCH` act as **Curators** — the collective intelligence guiding what should exist next on Solana.

Archova is not a static DAO — it’s a **living mechanism for creative evolution**.

---

## 🧬 Philosophy

Archova is inspired by the idea that **every meme, idea, or fragment has potential**.  
Instead of ideas dying in chats and discords, Archova immortalizes them — giving the community the tools to curate, fund, and evolve them together.

**“If GitHub is where developers build,  
and Mirror is where writers publish,  
Archova is where ideas awaken.”**

---

## 🧩 Navigation & UX Flow

### Main Sections
- **Home (`/`)**
  - Intro + connect wallet.
  - “Create Arc” button.
  - “View Library” CTA.

- **Create Arc (`/archive`)**
  - Form to submit a new Arc (title, pitch, description, optional ticker idea).
  - Requires connected wallet.
  - On submit, Arc is added to CMS with status `seeded`.

- **Library (`/library`)**
  - Displays all active Arcs.
  - Each card shows:
    - Title, pitch, votes, progress bar, and status.
    - Two buttons: **Support** and **View Arc**.
  - Support = +1 vote (wallet-gated).
  - View Arc = opens dynamic detail page.

- **Arc Detail (`/arch/{slug}`)**
  - Full description, live progress, support stats.
  - Confetti effect when supported.
  - Share/Copy link to post on X.
  - Real-time progress recalculations.

---

## 🔁 Arc Lifecycle

1. **Seeded**  
   - Fresh idea submitted by a curator.
   - Votes start at 0.  
   - Displayed in the Library.

2. **Awakening**  
   - When votes reach 50% of threshold (default 100 votes).  
   - Status updates visually (glow/pulse effect).

3. **Awakened**  
   - When votes reach or exceed the full threshold.  
   - The Arc is “alive” — can now receive funding or transition to a real project.
   - Eligible for Treasury grants from `$ARCH`.

---

## 💰 Tokenomics — $ARCH

| Parameter | Description |
|------------|-------------|
| **Token Name** | Archova |
| **Ticker** | `$ARCH` |
| **Network** | Solana (SPL) |
| **Total Supply** | 1B ARCH |
| **Utility** | Curation, Voting Power, Proposal Creation, Governance, Access |

### Utility Breakdown
- **Curation Power** → Each `$ARCH` = proportional voting power.
- **Proposal Creation** → Requires 5,000 ARCH to submit new governance proposals.
- **Treasury Governance** → 1 ARCH = 1 vote on fund allocation.
- **Creator Rewards** → 2% of Treasury distributed weekly to top Arc creators.

---

## ⚖️ Governance

Governance is fully transparent and incremental:
- **Voting Contracts**: Holders can vote on on-chain proposals.
- **Proposal Lifecycle**: Created → Pending → Approved → Executed.
- **Treasury**: Controlled by Curators via multi-sig and on-chain voting.
- **Upgrades**: All future modules (funding, incubation, staking) must be approved by vote.

---

## 🗳 Voting System

- Every Arc is voteable through on-chain or wallet-authenticated off-chain signatures.
- Each vote increases `votes` count in CMS (mirroring real voting power).
- Votes are logged in the `Votes` collection (wallet + slug + timestamp).
- One vote per wallet per Arc (anti-spam enforced).

Thresholds (default):
- **Seeded → Awakening**: 50 votes.
- **Awakening → Awakened**: 100 votes.

---

## 🪙 Rewards

### Creator Rewards
Each verified Arc creator receives **5% of total votes as bonus ARCH** when their Arc awakens.

### Supporter Rewards
Top supporters (measured by unique votes) receive **weekly random airdrops**.

### Treasury Pool
All unclaimed tokens and voting fees accumulate in the Treasury, used to fund awakened Arcs.

---

## 🔗 Wallet & Web3 Integration

- **Connect Wallet:** Phantom (primary) + Solflare support.
- **Session Storage:** Stores wallet address in `session.arch_wallet`.
- **Wallet-gated actions:**
  - Create Arc
  - Support Arc
  - Submit proposal (Phase 2)
- **Front-end checks:** Prevents interaction without connected wallet.
- **Visual feedback:** Wallet address + status visible in header.

---

## 🔮 Future Modules (Phase 2–3)

| Module | Description |
|---------|-------------|
| **Funding Pool** | On-chain staking and automated treasury payouts for awakened Arcs. |
| **Arc Launchpad** | One-click token launch for awakened Arcs, connected to Pump.fun or Jupiter. |
| **Archive Explorer** | 3D gallery visualization of all Arcs as constellations. |
| **Arc Chat** | On-chain comment thread + idea discussions. |
| **AI Archiver** | Suggests related ideas using GPT-based embeddings (semantic clustering). |
| **Builder Tools** | Templates, resources, and mentor matching for awakened Arcs. |

---

## 💡 Example Arc Lifecycle

1. Alice connects wallet → submits *DreamForge* Arc.  
2. The community supports it → 100 votes reached.  
3. Status = “Awakened.”  
4. DreamForge gets access to Archova funding pool.  
5. Alice mints `$DRMF` token using the Launchpad module.  
6. DreamForge becomes a standalone Solana project — born from the Archova ecosystem.

---

## 🔐 Security & Verification

- All submissions are linked to wallet addresses.
- Each Arc is immutable once created (except status updates).
- Votes are single-wallet-per-Arc (preventing spam).
- All token movements are transparent on Solscan.
- Planned audit for Phase 2 smart contracts.

---

## 🧭 Roadmap

| Phase | Title | Focus |
|-------|--------|-------|
| **Phase 1** | The Living Library | Core submission & voting (✅ done) |
| **Phase 2** | Awakening Protocol | Funding, proposals, and governance (🟡 in progress) |
| **Phase 3** | On-Chain Incubator | Launchpad & Builder tools (🔜 planned) |
| **Phase 4** | Archova DAO | Full decentralization and AI-assisted curation (🚀 future) |

---

## 💫 The Vision

> Archova is where forgotten ideas go to be reborn.  
> A collective consciousness that curates the next generation of Solana projects.  
> Not everything deserves to live — but everything deserves a chance to awaken.

---

**Website:** [archova.xyz](https://archova.fun)  
**Token:** `$ARCH` on Solana  
**Docs:** `/docs` (you’re here)  
**Repository:** [github.com/archova](https://github.com/archova)

---

*“Archive the impossible.  
Awaken the forgotten.”*
