# Immersive-ARMRVR

# Immersive Parametric Modeler

A production-ready, multi-user, VR/MR-first parametric modeling platform built for makers, engineers, and designers. Think Fusion 360 meets Gravity Sketch — with ECAD + MCAD support and AI-powered text-to-3D generation.

## 🚀 Project Vision

- Full parametric modeling in immersive 3D space (Meta Quest 3, Apple Vision Pro)
- ECAD & MCAD integration (STEP, BRD, KiCad, Gerber)
- Multi-user collaboration in real-time
- Local-first engine using OpenCascade (free kernel)
- Modular AI assistant for basic commands and full text-to-3D generation
- Future-ready architecture with optional cloud offload

## ✨ Core Features (Planned)

- Sketch, extrude, fillet, revolve in VR with live parametric control
- Import/export: STEP, IGES, STL, BREP, BRD, KiCad, GLTF
- Text/voice prompt: “Create a 40mm gear with 3mm bore” → 3D object
- Multi-user design sessions with version history
- VR UI for geometry editing, constraints, and assemblies

## 🛠️ Tech Stack

- Unity 2022 LTS (XR Toolkit, Meta SDK)
- OpenCascade for geometry kernel
- Photon Fusion or Normcore (multi-user)
- Ollama + TRELLIS / FlexiCubes / Hunyuan (AI backend)
- GitHub-hosted modular codebase

## 📁 Directory Overview

```bash
/client/         # Unity front-end
/server/         # Optional cloud backend (text-to-3D API, storage)
/kernel/         # OpenCascade integration
/ai_assistant/   # AI command parsing
/docs/           # UX designs, planning docs
