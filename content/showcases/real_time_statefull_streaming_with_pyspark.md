---
title: "Smarter Baggage Tracking with Real-Time Data"
date: 2025-07-25
draft: false
image: "/showcases/spark_4_0.jpg"
description: "How OnBased uses Databricks and Spark 4.0’s new transformWithStateInPandas API to deliver real-time, lifecycle-aware baggage visibility for airlines."
tags: ["databricks", "spark", "stateful-streaming", "aviation", "baggage-tracking"]
---

## Smarter Baggage Tracking with Real-Time Data  

Air travel generates a constant stream of baggage events: check-ins, scans, loadings, and transfers.  
The challenge? These events arrive in fragments, across systems, and at different times. Turning this noisy flow into a clear, reliable picture of where each bag is in its journey is anything but simple.  

At **OnBased**, we solved this by building a **stateful streaming pipeline** on Databricks, powered by the latest Spark 4.0 technology. Instead of treating each baggage event in isolation, our system **remembers the story of every bag** — from check-in to arrival — and continuously updates it in real time.  

### What This Enables  
- **Full lifecycle tracking** – follow each bag across multiple flights and transfers.  
- **Accurate event correlation** – connect scattered scans into a single journey.  
- **Dynamic enrichment** – merge baggage data with live flight leg information as it happens.  

### Why It Matters  
With the new **transformWithStateInPandas API**, our engineers can model complex rules in plain Pandas, making the system faster to build, easier to maintain, and more adaptable to new airline data sources.  

The result: **airlines gain real-time, lifecycle-aware baggage visibility** — reducing mishandling, improving passenger experience, and unlocking smarter operational decisions.  

