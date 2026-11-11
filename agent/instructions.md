Act as a Principal Full-Stack Web Engineer. Write a complete production-ready Single Page Application (SPA) designed to be hosted 100% free on Vercel without requiring any paid infrastructure or credit cards. 

The application must combine two major gaming & earning modules into a single dark-mode, mobile-first responsive dashboard UI:

1. AVIATOR / CRASH CASINO GAME MODULE:
- Real-time multiplier canvas with dynamic curve/plane flight animation ($1.00x upwards to random crash point).
- Provably Fair system using HMAC-SHA256 client/server seeds.
- Live betting controls: Manual Cashout, Auto Cashout setting, Auto Bet toggle.
- Real-time multiplayer simulate feed: Live bets list, recent multipliers history bar ($1.20x, $5.40x, $1.02x, etc.).
- Internal wallet integration: Deduct bet amount on place, credit (Bet x Multiplier) on cashout. Crash before cashout loses bet.

2. CLOUD MINING & VIRTUAL HARDWARE NODES MODULE:
- Node Leases: Users can lease virtual nodes (Normal Pods, Special Rigs, Overdrive Arrays) using internal PKR/crypto balance.
- Serverless Realtime Yield Engine: Calculate earnings using time-delta logic (Yield = Rate * Elapsed Time) upon page load and continuous micro-increments so no 24/7 background server execution is required.
- Dynamic Node Configurator & Active Rigs overview dashboard with countdown sync timers.

3. CORE WALLET & NETWORKING FEATURES:
- Multi-tier Referral System (Tier 1: 10%, Tier 2: 3%, Tier 3: 1%).
- Internal P2P Balance Transfers between users with 0 fees.
- Deposit & Cashout Request Modal: Supports EasyPaisa, JazzCash, and USDT TRC20 manual payment verification workflows with Transaction ID (TID) logging.
- Daily Lucky Spin Wheel and Daily Check-in rewards.

4. ADMINISTRATIVE SYSTEM & SECURITY:
- Secret Admin Portal (5-tap logo unlock feature): Manage pending deposit approvals, user balances, node definitions, broadcast banners, and user block/unblock toggles.
- Zero External Backend Required: Use client-side JS + Firebase Realtime Database / Firestore for state sync and Vercel edge compatibility.
- Styling: Premium dark UI (#040814 theme, Tailwind CSS or pure CSS glassmorphism, Google Plus Jakarta Sans font, FontAwesome icons).

Provide the code as a clean, single-file HTML/JS/CSS solution or modular Next.js / React app optimized for instant Vercel Git deployment.