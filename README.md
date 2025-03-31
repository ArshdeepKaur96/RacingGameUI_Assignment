# Racing Game UI - Unreal Engine Assignment

![Unreal Engine](https://img.shields.io/badge/Unreal%20Engine-5.3+-black.svg?style=flat&logo=unrealengine)
![UMG](https://img.shields.io/badge/UI-Framework-UE5-blue.svg)

## 📌 Overview
A dynamic racing game HUD built with Unreal Engine's UMG system that displays:
- Real-time race timer (MM:SS:MS)
- Previous lap records
- Lap counter progress
- Vehicle speed (optional)

## 🎯 Assignment Requirements
| Component | Status |
|-----------|--------|
| Current Race Time | ✅ Implemented |
| Previous Lap Time | ✅ Implemented |
| Lap Counter | ✅ Implemented |
| Speed Display | ✅ Optional Bonus |

## 🛠️ Technical Implementation
### Blueprint Architecture
```mermaid
graph TD
    A[PlayerPawn] -->|Provides Data| B[RaceManager]
    B -->|Updates| C[WBP_RaceHUD]
    C -->|Displays| D[UI Elements]
