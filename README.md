# Modern-EDA-Algorithm-Project
# 🚀 Congestion-Aware Global Routing Algorithm (A* + Rip-Up & Reroute)

This project implements a **fast and congestion-aware global routing algorithm** using the **A\*** search algorithm combined with a **rip-up and reroute (RRR)** strategy. It is designed for VLSI physical design flows, where efficient net routing is essential to minimize wirelength and avoid routing congestion.

---

## 📌 Features

- Grid-based representation of the routing region
- A* search with Manhattan heuristic and congestion-aware cost function
- Rip-up and reroute to resolve local congestion
- Support for `.grid` benchmark input format
- Logs wirelength, congestion statistics, and rerouted paths
- Output summary saved to `rounting_output.txt`

---

## 📈 Benchmarking

Tested on small and large grid sizes:
- 10×10 (Basic)
- 324×324 (Large scale, 100+ nets)
- 557x463 Grid
- ISPD 2008 Global rounting benchmarks
  
Performance evaluated based on:
- Total wirelength
- Congestion distribution
- Routing success under different thresholds

---
