# FerrumCraft

Precision-engineered voxel infrastructure powered by **Pure Rust**.

The goal of the **FerrumCraft** organization is to bridge the gap between high-performance systems programming and the web, starting with the most ambitious "clean-room" implementation of a Minecraft-compatible runtime.

---

## 🔬 Core Projects

### [betVM](https://github.com/FerrumCraft/betVM)
The "Better Enhanced/Extended TeaVM." This is a **clean-room JVM implementation written entirely in Rust**. Unlike traditional transpilers, betVM is a dedicated execution environment designed to interpret Java bytecode directly within a WebAssembly context. 
*   **Status:** Active Development
*   **Purity:** 100% Rust logic (excluding WASM-bindgen requirements).

### [WebCraft-RS](https://github.com/WebCraft-RS)
The high-speed entry point. This repository functions as a specialized **downloader and starter** for the ecosystem. It manages Minecraft version manifests, handles asset orchestration, and bootstraps the betVM runtime.
*   **Status:** Active Development
*   **Purity:** 100% Rust Wasm (though as a website itself it has HTML, CSS, and JS)

---

## 🛠 Our Philosophy: "Pure Rust"

We believe in the power of the Rust ecosystem to deliver safety and performance. When we say "Pure Rust," we refer to the **logic, memory management, and runtime execution**. 

### What you will find in our repos:
*   **🦀 100% Rust Logic**: No JavaScript shims, no C++ glue, no garbage-collected compromises.
*   **⚙️ Native Build Scripts**: We use `.sh`, `.bat`, and extensionless scripts for what they were intended for: **automation**. These are the tools that handle the "heavy lifting" of the build pipeline, not the logic of the game.
*   **🏗️ CI/CD Infrastructure**: Standard `.yaml` configurations for GitHub Actions to ensure every commit meets our performance benchmarks.

---

## 🚀 Mission

We are building a future where complex, bytecode-heavy applications can run in the browser without the overhead of traditional emulation or the "jank" of transpilation. By utilizing Rust's zero-cost abstractions, FerrumCraft is reclaiming the web for high-performance gaming.

---

*"It's not just a port; it's a new foundation."*
