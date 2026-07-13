---
title: "Synthetic Traffic Model Generator for SUMO (2024-2025)"
excerpt: ""
collection: software
---

This repository provides a Python-based tool to generate synthetic traffic models for SUMO ([Simulation of Urban MObility](https://eclipse.dev/sumo/)) and compare traffic simulations with and without road closures.

It automates dataset generation, simulation setup, and the extraction of metrics such as traffic counts, speeds, Floating Car Data (FCD), trip information, and lane-level detector data.

The configuration is fully customizable via a TOML file (`config.toml`), allowing you to adjust simulation settings, traffic profiles, sensor coverage, and different types of roadwork scenarios.

[Gitlab project](https://gitlab.com/traffic-sim/syntheticscenariogenerator)
