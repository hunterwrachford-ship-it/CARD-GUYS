# 🃏 CARD GUYS — Monster TCG Shop Sim

Run a trading-card shop where every customer is a stylized 3D monster, with **ORACLE** — a hyper-intelligent in-game AI that designs your TCGs, reads your sales data, and calls your shots.

**Play:** open `index.html` in any browser (internet needed once, to load Three.js for the 3D shop).

## Features
- **3D shop** — the shop floor is a real-time 3D scene (Three.js): drag to orbit, scroll to zoom. Wooden floor, counter, shelf units displaying your actual products, warm lighting. Monster customers are 3D procedural chibi creatures that walk in the door, browse and chat via speech bubbles. Falls back to 2D sprites if WebGL is unavailable.
- **ORACLE, the shop AI** — type any theme ("spooky deep-sea set", "lava golem tcg") and it parses the theme, architects a 6-card set (cost curve, rarity spread, keywords, flavor), forecasts demand from your actual sales history, optimizes every price, and briefs you every morning.
- **Every card & figure is unique** — creatures are procedurally generated (seeded bodies, faces, horns, wings, patterns, palettes), rendered at high fidelity with element-themed scenes, gradient shading and rarity frames.
- **Card versions** — Normal, **Alt Art**, **Gold**, **Rainbow** (holo foil), and **Voxel** — each rendered differently and priced differently.
- **Figurines & Duel Sets** — sculpt glossy figurines (spotlight, pedestal, specular shading, chase variants), or bundle card + figure into premium Duel Sets. Figurines, Cards, or Both.
- **Tournaments** — host the Monster Masters Invitational: live bracket sim, entry fees, prize, hype and a demand surge for the champion's tribe.
- **Release drops** — schedule limited drops with marketing spend; fans rush the door and pay a premium. Sell out clean for rep, under-stock and face restock rage.
- **📱 Phone** — *MarketWatch* daily price indices, *GradeSpot* (send cards away, get 1–10 graded slabs worth more), and *Messages* where sponsors text you deals.
- **🛠️ Build shop** — Hugo's Building Shop: decorations become 3D props (neon sign, rug, posters, lava lamp, jukebox, espresso machine) and machines give permanent upgrades.
- **Economy loop** — day cycle: prep → open → close, rent due nightly, reputation gates tournaments/drops/duel sets, hype decays, bankruptcy ends the run.

## How to play
1. In the **ORACLE** tab, click **"Design my starter set"** (or type any theme).
2. In the proof modal, print cards in whichever version you like.
3. Set prices in **Inventory** (ORACLE → "Optimize my prices" helps).
4. Hit **🔔 Open Shop** and watch 3D monsters buy. Survive rent. Get rep.
5. Rep 10 → tournaments · Rep 15 → drops · Rep 25 → duel sets.
