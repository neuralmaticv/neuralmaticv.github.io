---
title: "Congestion Collapse Simulator"
date: 2025-12-05
draft: false
tags: ["Rust", "systems", "simulation", "networking", "queueing theory"]
description: "A Rust simulator that models synchronous request/reply systems under load to demonstrate congestion collapse and queueing dynamics."
hidemeta: true
ShowReadingTime: false
---

**congestion-collapse-sim** is a Rust-based simulator that demonstrates congestion collapse — the phenomenon where an overloaded server wastes resources processing requests that clients have already abandoned due to timeouts.

The simulator makes it easy to explore configurable parameters like arrival rates, worker counts, queue sizes, and timeouts. A notable finding: **LIFO queue discipline reduces timeouts under overload** compared to FIFO, at the cost of fairness.

**Links**
- [GitHub - neuralmaticv/congestion-collapse-sim](https://github.com/neuralmaticv/congestion-collapse-sim)
