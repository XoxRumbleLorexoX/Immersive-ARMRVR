# Immersive Parametric Modeler - ARMRVR


A production-grade, VR/MR-first, multi-user parametric modeling system for engineers, makers, and designers — supporting full MCAD and ECAD interoperability, AI-assisted modeling, and future expansion into Vision Pro and WebXR ecosystems.

---

## 🚀 Project Goals & Milestones

### ✅ MVP Goals (3-Month Target)
1. **Unity Front-End (Meta Quest 3)**
   - [ ] Multi-user enabled XR scene with Photon Fusion/Normcore
   - [ ] VR interaction: grab, move, sketch, extrude
   - [ ] Local parameter editing via 3D UI

2. **OpenCascade Integration**
   - [ ] Import & visualize: `.step`, `.iges`, `.stl`, `.brep`
   - [ ] Basic parametric shape generation (box, cylinder, etc.)
   - [ ] Parametric editing interface

3. **ECAD Format Support**
   - [ ] Load `.brd`, `.kicad_pcb`, `.sch`, `.gerber`
   - [ ] 3D visualization of PCB layouts
   - [ ] Link components to MCAD constraints

4. **AI Integration (Local)**
   - [ ] Ollama assistant: command to parametric operation
   - [ ] Placeholder UI for text-to-3D pipeline

5. **GitHub Repository Structure**
   - [ ] Modular codebase
   - [ ] Documentation folder for internal planning
   - [ ] MIT License, `README.md`, `.gitignore`, CI config

---

## 📂 Directory Structure

```bash
/immersive-parametric-modeler/
│
├── /client/                     # Unity VR client (Meta Quest 3)
│   ├── Scenes/
│   ├── Scripts/
│   ├── Prefabs/
│   └── UI/
│
├── /server/                     # Optional cloud backend (API, AI, sync)
│   ├── meshgen_api/
│   ├── parametric_api/
│   └── auth/
│
├── /kernel/                     # OpenCascade bridge and wrappers
│   └── cad_core/
│
├── /ai_assistant/               # Ollama integration + text command parsing
│   └── parser.py
│
├── /ecad/                       # ECAD file parsers & visualizers
│   ├── gerber/
│   ├── kicad/
│   └── eagle/
│
├── /exports/                    # CAD export modules (STEP, STL, OBJ, etc)
│
├── /docs/                       # Planning docs, UX wireframes, architecture
│   ├── goals.md
│   ├── formats.md
│   └── roadmap.pdf
│
├── LICENSE
├── README.md
└── .gitignore
```

---

## 🌐 Supported Formats (Planned)

### 🔍 MCAD
- `.step`, `.stp`
- `.iges`, `.igs`
- `.stl`, `.obj`, `.fbx`
- `.brep`, `.glb`, `.gltf`

### 🛠️ ECAD
- `.brd`, `.kicad_pcb`, `.sch`
- `.gerber` (RS-274X)
- `.dxf`, `.bom`, `.net`

### 📄 Script/Data
- `.scad`, `.json`, `.yaml`, `.toml`
- `.urdf`, `.sdf` (for robotics config)

---

## 🚪 Future-Proofing

- [ ] Support for Apple Vision Pro (Unity PolySpatial or RealityKit bridge)
- [ ] WebXR version (browser-based access)
- [ ] Full cloud mode: mesh + parametric compute on remote servers
- [ ] Text-to-3D with DALL·E, Hunyuan, TRELLIS, FlexiCubes

---

## ✉️ Contribution & Community

- All contributions will follow GitHub Issues + PR process
- Clear module ownership & code standards
- Monthly update logs & roadmap reviews
- External contributors welcome post-MVP

---

## 🌍 License

MIT License — use freely with attribution. Commercial licenses and integrations will be offered in the future.
