# Dallas Fischer (Dalrae)

I am a software engineer focused on **distributed systems, real-time simulation, and multiplayer architecture**, with particular emphasis on **authoritative server design**, **latency compensation**, and **performance-critical gameplay systems**. My work spans backend engineering, networking, and game systems, with a strong bias toward first-principles design over framework dependency.

---

## Technical Focus

- Real-time authoritative multiplayer systems  
- Server-side simulation and deterministic game logic  
- Client-side prediction, interpolation, and reconciliation  
- Bandwidth-aware state replication and spatial partitioning  
- Behavioral anomaly detection and anti-cheat systems  
- Reverse engineering of closed systems via instrumentation and observation  

**Languages:**  
JavaScript · TypeScript · Lua · PHP · MySQL

---

## Projects

### Protect The President - Custom FiveM Multiplayer Platform

**Protect The President** is a fully original, team-based multiplayer game mode for FiveM, engineered from the ground up without reliance on ESX, vRP, or other prebuilt frameworks.

The system models a constrained adversarial escort scenario in which one team is responsible for safely extracting a high-value player entity while an opposing team attempts interdiction. The architecture prioritizes **determinism, scalability, and low-latency state coherence**.

#### Core Systems

- **Authoritative Game State Management**  
  Complete server ownership of round lifecycle, player roles, win conditions, and mission state. Client authority is intentionally minimized.

- **Dynamic Temporal Simulation**  
  In-game time progression is modulated based on gameplay phase to improve pacing and visibility while maintaining immersion.

- **Behavior-Driven Anti-Cheat**  
  Detects movement anomalies, input inconsistencies, and unauthorized UI usage through server-side heuristics rather than signature matching.

- **Real-Time Discord Role Synchronization**  
  Player permissions are continuously reconciled against live Discord role state without requiring reconnects.

- **Scenario-Aware Loadout and Spawn Logic**  
  Equipment, objectives, and spawn topology are derived from server-defined scenario graphs rather than static configuration.

#### Architecture & Performance

- **Custom RageUI-Based VIP Interface**  
  Purpose-built UI avoids the overhead of general-purpose menu frameworks and minimizes client tick cost.

- **HTML/CSS nUI Rendering Pipeline**  
  All text and interface elements are rendered via nUI rather than native draw calls, enabling resolution independence, richer layout control, and improved performance.

- **Multi-Map World Transitions**  
  Seamless transitions between Cayo Perico, North Yankton, and custom environments using asset preloading, routing buckets, and controlled state migration.

- **Telemetry & Instrumentation**  
  Server-side collection of round metrics (survival time, eliminations, mission outcomes) for analytics and balancing.

- **Tick-Conscious Server Design**  
  Systems are structured to avoid unnecessary per-frame evaluation, maintaining stability under high player concurrency.

This project is a long-running, continuously evolved codebase with distinct branding, integrated commerce, and live operations support.

---

### Powerline.io — Server Emulator (Reverse Engineered)

A complete, ground-up **server emulator for Powerline.io**, developed without access to the original backend code.

The system reconstructs gameplay, networking behavior, and synchronization semantics exclusively through live observation, packet analysis, and controlled experimentation.

Key components include:

- Authoritative multiplayer simulation with client input buffering  
- Predictive interpolation and latency compensation  
- Spatial partitioning via quad-based indexing for collision detection  
- High-throughput broadcast filtering using view-frustum culling  
- Deterministic PvP tail-collision resolution  
- Macro scripting engine for automated movement and testing  
- Live telemetry, diagnostics, and frame-level replay tooling

All gameplay logic, networking, and synchronization were independently derived. No proprietary server assets or source code were used.

---

## Supporting Systems & Tooling

- **Interpolation Engine**  
  Predictive positioning and smoothing for high-latency multiplayer scenarios.

- **SQL Batch Optimizer**  
  Queue-based write aggregation to reduce transactional overhead under load.

- **Camera Tweening System (FiveM)**  
  Deterministic cinematic camera transitions for scripted scenes and dynamic focus.

- **Locales Translation Pipeline**  
  Batch conversion of configuration files across 25+ languages.

---

## Engineering Philosophy

I approach game systems as **distributed simulations**, not scripts.

My design principles emphasize:
- Explicit state ownership  
- Measurable performance characteristics  
- Minimal abstraction leakage  
- Graceful degradation under load  

I am particularly interested in the boundary between **client perception** and **server truth**, and how careful engineering can make that boundary effectively invisible to players.

---

## Contact

- **Discord:** dalrae0  
- **Website:** https://dalr.ae  
- **GitHub:** https://github.com/Dalrae1
