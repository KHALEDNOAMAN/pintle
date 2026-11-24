# Pintle - CXL 3.1 Controller Design Guide

## Overview
Hardware CXL 3.1 coherent memory pool controller and multi-head fabric switch.

## Architecture
| Module | Function |
|--------|----------|
| Memory Pool Controller | CXL.mem coherent access |
| Fabric Switch | Multi-head routing |
| Coherence Engine | Cache line tracking |
| Flow Control | Credit-based arbitration |

## CXL 3.1 Features
| Feature | Support |
|---------|--------|
| CXL.io | PCIe I/O |
| CXL.cache | Device caching |
| CXL.mem | Host-managed memory |
| Fabric | Multi-switch topology |

## Build
`bash
make compile
make simulate
`

## Simulation
- Bluesim for cycle-accurate testing
- Verilator for fast validation
