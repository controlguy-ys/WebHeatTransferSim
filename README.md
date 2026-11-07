# WebHeatTransferSim

[![Domain](https://img.shields.io/badge/Domain-Thermal_Modeling_%26_Simulation-FF6600)](#overview)
[![Platform](https://img.shields.io/badge/Platform-Browser_Web_Simulation-0082FC)](#overview)

Interactive browser-based **Heat Transfer & Thermal Conduction/Convection Simulation** workspace for visualizing transient and steady-state temperature distributions in engineering structures.

---

## Overview

`WebHeatTransferSim` explores lightweight, browser-accessible numerical thermal modeling—bringing finite-difference heat transfer intuition (conduction, boundary convection, and thermal diffusivity) directly into a web canvas without requiring heavyweight desktop CAE licenses.

### Core Modeling Concepts

- **Transient 1D / 2D Heat Conduction**: Discretized finite-difference evaluation of Fourier's law across configurable material thermal conductivities ($k$), densities ($\rho$), and specific heat capacities ($c_p$).
- **Boundary Condition Inspection**: Interactive exploration of Dirichlet (fixed temperature), Neumann (heat flux), and convective ($h \cdot \Delta T$) boundary conditions relevant to industrial thermal plates and heat sinks.
- **Browser-First Visualization**: Immediate visual feedback of thermal gradients and time-step stability criteria (Fourier number $\text{Fo}$ constraints).

---

## Related Engineering Simulation Projects

- **[`OpenDigitalTwin`](https://github.com/controlguy-ys/OpenDigitalTwin)** — Browser-first 3D multi-robot workcell and OPC UA digital twin simulator built with Three.js and Node-OPCUA.
- **[`AutomataWiki`](https://github.com/controlguy-ys/AutomataWiki)** — Interactive controls engineering knowledge graph and ontology workbench.
- **[`br-automation-pvi-mcp-server`](https://github.com/controlguy-ys/br-automation-pvi-mcp-server)** — 38-tool MCP server for B&R Automation Studio PLC compilation and real-time PVI telemetry.
