# supply-chain-routing-engine

A high-performance graph processing engine designed to solve dynamic routing problems under real-time network constraints. Built with zero dependencies in standard C99, it features fixed memory allocation profiles and cross-compiles directly to WebAssembly for browser-based canvas visualisations.

## Highlights

* **Pure C99 Architecture:** Zero third-party dependencies, compiling on standard C toolchains (`-std=c99 -Wall -Wextra`).
* **Deterministic Memory:** Predictable layout control designed for high-throughput node evaluation and low-latency execution.
* **Multi-Constraint Pathfinding:** Solves complex networks across distance, cost, capacity, and time windows.
* **Visual Simulation Interface:** Renders graph topologies, live route recalculations, and network stress points directly.

## Quickstart

```bash
# Clone repository
git clone [https://github.com/KeananSandilands/supply-chain-routing-engine.git](https://github.com/KeananSandilands/supply-chain-routing-engine.git)
cd supply-chain-routing-engine

# Build and run
clang -std=c99 -O3 -Wall -Wextra main.c -o supply_sim
./supply_sim
