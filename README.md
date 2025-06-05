# 👋 Hi, I'm Dallas (a.k.a. Dalrae)

I'm a passionate **Software Developer** building multiplayer systems, backend tools, and immersive game mechanics — especially in **FiveM** and real-time environments.

---

## 🧠 About Me

- 🔧 Focused on **reverse engineeering**, **server-side logic**, **game scripting**, and **performance optimization**
- 🎮 Creator of custom **FiveM** game modes and server systems
- 🌐 Fluent in:
  - `JavaScript`, `TypeScript`, `Lua`, `PHP`, `MySQL`
- ⚙️ Tools I use daily:
  - `VSCode`, `Docker`, `Postman`, `NGINX`, `txAdmin`

## 🛠️ Projects I'm Proud Of

### 🛡️ Protect The President – FiveM Server  
A fully custom, performance-focused **team-based multiplayer game mode** for FiveM. One team escorts the President to safety while the other attempts to eliminate them.  
Built entirely from scratch with scalability, efficiency, and real-time sync as core goals.

---

#### 🔧 Core Features

- 🧠 **Custom Game Logic**  
  Fully managed round lifecycle, player states, escort objectives, and team role enforcement.

- 🛡️ **Integrated Anticheat System**  
  Detects and logs known abuse patterns such as movement exploits and unauthorized menu usage.

- 🕓 **Dynamic Time Scaling**  
  In-game time can speed up or slow down depending on gameplay phase (e.g., accelerated nights).

- 🗺️ **Map Logic & Safe Zones**  
  Dynamically restricts areas, defines escort paths, and adapts logic for multiple supported maps.

- 👥 **Real-Time Discord Role Syncing**  
  Player permissions mirror their Discord roles and update live with any changes — no relogging required.

---

#### 🛠️ System Architecture

- 💼 **VIP Menu Built with RageUI**  
  Designed for performance — avoids the overhead of vMenu by using a custom RageUI implementation for faster, smoother interaction.

- 💬 **HTML/CSS-Based UI (nUI)**  
  All in-game text and interface elements use HTML and CSS via nUI — not FiveM natives like `DrawText` — for significantly better performance and resolution scaling.

- 🌍 **Seamless Multi-Map Transitions**  
  Supports smooth switching between:
  - **Cayo Perico**
  - **North Yankton**
  - **Roxwood (custom map)**  
  Transitions are handled cleanly with asset preloading, dimension handling, and minimal disruption to gameplay.

- 📊 **Telemetry & Logging**  
  Tracks round stats such as player kills, mission outcomes, and time survived for review and analytics.

- 💬 **Configurable Broadcast System**  
  Displays round transitions, role assignments, and important match messages using the HTML UI system.

- 🎮 **Loadouts & Spawn Management**  
  Player equipment, spawn locations, and objectives are fully server-defined and scenario-dependent.

- ⚙️ **Optimized Server Tick Handling**  
  Avoids unnecessary processing to maintain high performance, even under heavy load.

---

> Every element of this mode is custom-coded — no dependencies on ESX, vRP, or FiveM's default frameworks. Designed for immersive, replayable gameplay with minimal latency and maximum polish.

#### ⚙️ System Architecture

- 🔁 **Async Player Syncing**  
  Custom-built movement and state syncing optimized for lower bandwidth usage, especially useful during larger player counts or high ping situations.

- 🛡️ **Anticheat Layer**  
  Detects abnormal patterns in movement, shooting, and menu usage. Suspicious behavior is logged and relayed to staff in real-time.

- 🕓 **Dynamic Time System**  
  In-game time accelerates or slows down based on scenario (e.g., night cycles are shortened for better visibility and pacing).

---

> All core systems are original and custom-written — no reliance on prebuilt frameworks like ESX or vRP. The result is a cleaner, faster, and purpose-built game mode.


#### 🛠️ Server Systems:
- 📊 Integrated telemetry for round data (e.g., time survived, kills, mission outcomes)  
- 💬 Configurable event broadcasts and messages for round transitions  
- 🎮 Uses server-defined loadouts, player spawning locations, and mission objectives  
- ⚙️ Built with performance in mind — avoids unnecessary server ticks and keeps client-side processing lean

> This project has been in continuous development with unique branding, gameplay structure, and full Discord + shop integration. Every element is tailored to this game mode — not a mod of existing FiveM frameworks.

### 🌐 Locales Translator  
Simple tool to convert config locales across 25+ languages with batch support.

### 🌀 Interpolation Engine  
Smooth player movement and ping compensation using predictive positioning.

### 🧮 SQL Batch Optimizer  
Reduces individual queries via queue batching and prioritized writes.

### 🎥 Camera Tweener for FiveM  
Cinematic camera transitions for scenes, cutscenes, and dynamic player focus.

### ⚡ Powerline.io Server Emulator  
A fully custom, reverse-engineered **Powerline.io multiplayer server** built from the ground up — without access to the original codebase.  

Features include:
- 🔄 **Multiplayer sync** with real-time interpolation and client input buffering  
- 🐍 Custom snake growth logic, directional input handling, and tight movement physics  
- ⚔️ PvP tail collision detection with optimized spatial queries  
- 🧠 Intelligent broadcasting system using view frustum culling and quad-based partitioning  
- 📊 Developer tools for live telemetry, player diagnostics, and frame replay  
- 🪄 Built-in **macro scripting** engine for automated movement paths and testing  
- 💬 Server-side chat, player states, join/leave broadcasting, and anti-cheat hooks  
- ⚙️ Configurable game rules: growth rate, tail decay, collision radius, and rubberbanding  
- 🧪 Designed for high concurrency testing with minimal latency simulation

> ⚠️ All gameplay logic, networking, and sync were reverse-engineered from live observation and packet captures — no use of original backend source assets.

---

## 🧊 Fun Facts

- 🧠 I reverse-engineered **Powerline.io** and built a functioning server emulator from scratch  
- 📐 I wrote a script that uses **parametric curves** to let snakes draw any path using only key inputs  
- 🔍 I implemented a full **input recorder/replayer** to analyze user movement frame-by-frame  
- 🛡️ I've scripted anticheat, player syncing, and AI behavior for multiplayer games  
- 🕹️ Built systems that simulate **client-side prediction** and **server reconciliation**  
- 🔥 I love making things **feel smooth** — even in a multiplayer world  
- 🧩 I treat game logic like puzzle-solving and love untangling complex systems  
---

## 📫 Let's Connect

- Discord: `dalrae0`
- Website: https://dalr.ae
- GitHub: [github.com/Dalrae1](https://github.com/Dalrae1)


[![Youtube](https://img.shields.io/youtube/channel/subscribers/UCr7j0C6hZRr6fxRJMdwNO4Q?color=FF0000&logo=youtube&style=for-the-badge)](https://www.youtube.com/@Dalrae?sub_confirmation=1)


✨ **Github Stats** <br>
![Github stats](https://github-readme-two-gamma.vercel.app/api?username=dalrae1&show_icons=true&hide_border=true&count_private=true&include_all_commits=true&bg_color=ffffff00&hide_title=true)
