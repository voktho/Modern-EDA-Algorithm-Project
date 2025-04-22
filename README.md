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

Check Release for benchmark Evaluation (link : https://github.com/voktho/Modern-EDA-Algorithm-Project/releases/tag/ISPD2008_Benchmark_Input_Output)

Tested on small and large grid sizes:
- 10×10 (Basic)
- 324×324 (Large scale, 100+ nets)
- 557x463 Grid Size (Maximum)
- ISPD 2008 Global rounting benchmarks (adaptec, newblue, bigblue)
  
Performance evaluated based on:
- Total wirelength
- Congestion distribution (max congestion, average congestion)
- Routing success under different thresholds

---
