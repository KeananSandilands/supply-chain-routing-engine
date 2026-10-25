# supply-chain-routing-engine

A zero-dependency C99 routing engine built to simulate multi-constraint pathfinding, network cost analysis, and supply chain logistics with deterministic memory management and a real-time visual interface.

## Highlights

* **Pure C99 Architecture:** Zero third-party dependencies, compiling on standard C toolchains (`-std=c99 -Wall -Wextra`).
* **Deterministic Memory:** Predictable layout control designed for high-throughput node evaluation and low-latency execution.
* **Multi-Constraint Pathfinding:** Solves complex networks across distance, cost, capacity, and time windows.
* **Visual Simulation Interface:** Renders graph topologies, live route recalculations, and network stress points directly.

## Quickstart

```bash
# Clone repository
git clone [https://github.com/YOUR_USERNAME/supply-chain-routing-engine.git](https://github.com/YOUR_USERNAME/supply-chain-routing-engine.git)
cd supply-chain-routing-engine

# Build and run
clang -std=c99 -O3 -Wall -Wextra src/*.c -o bin/routing_engine
./bin/routing_engine
