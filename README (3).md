# WORLD MODELS FOR PLACES THAT REMEMBER

**ROOM × DVV × World Models Hackathon — March 2026**

> A spatial knowledge graph where every node is a door.  
> Step through and the world generates around you.

---

## The Concept

Most knowledge graphs show you information. This one takes you there.

The graph floats in space around you. Each node is a place, a story, a moment in time — anchored to real community knowledge, real historical assets, real coordinates on earth. You reach out. You pinch a node. The graph dissolves. The world opens.

**The knowledge graph is the map. The world model is the territory.**

---

## Live Demo

🌐 **[dvv-knowledge-graph.vercel.app](https://dvv-knowledge-graph.vercel.app)**

The DVV (Dunsmuir Visionary Village) spatial knowledge graph is live now — three layout modes, full 3D interaction, running in your browser.

---

## Three Layers

### 01 — The Graph
A force-directed 3D knowledge graph built in Three.js. Nodes are concepts, places, people, moments. Edges are relationships. Three layout modes — centralized, decentralized, distributed. This is your compass inside the experience.

### 02 — The World
World Labs Marble API turns community assets — old photographs, spatial scans, oral histories — into navigable 3D environments. Each node in the graph has a world behind it. Pinch a node → the world generates around you.

### 03 — The Memory
Community knowledge as infrastructure. DVV is the first shard — a bioregional community's history, land, and future as navigable space. Real places. Real stories. Real people who lived them.

---

## Stack

| Layer | Tool | Status |
|---|---|---|
| 3D Knowledge Graph | Three.js + force-directed layout | ✅ Live |
| Spatial Web / XR | WebXR Device API | 🔨 Building |
| World Generation | World Labs Marble API | 🔗 Integrating |
| Hand Interaction | WebXR Hand Input API (pinch gesture) | 🔨 Building |
| Deployment | Vercel — browser-native, no install | ✅ Live |
| Stretch: AI Perspectives | Claude API — societies of thought layer | 💡 Stretch |

---

## The Portal Interaction

```
NODE("History / Babe Ruth / Dunsmuir")
  ↓  pinch gesture
  ↓  graph dissolves
  ↓  world model generates
  →  you are standing there

// semantic layer persists
GRAPH  →  overhead as constellation
  ↓  pinch again → next node → next world

// return anytime
PALM UP  →  graph returns
```

---

## Why WebXR

This runs in **any XR browser via URL** — Pico, Quest, Android XR, Vision Pro. No app install. No APK. No SDK dependency. A judge opens a browser, navigates to the URL, and steps inside.

This is what the spatial web looks like when it's community-owned, place-rooted, and accessible.

**Target track:** Best WebSpatial Project with PICO

---

## Architecture

```
DVV Knowledge Graph (Three.js / Vercel)
        │
        ├── WebXR session layer
        │     └── Hand tracking (pinch = node select)
        │
        ├── Per-node world data
        │     ├── Primary:   World Labs Marble API
        │     ├── Fallback:  Gaussian splat (Polycam scan)
        │     └── Emergency: 360° panorama / equirectangular
        │
        └── Societies of Thought (stretch)
              └── Claude API — multiple AI perspectives
                  inhabiting the graph as persistent lenses
```

---

## Roadmap (Hackathon Build)

- [x] DVV knowledge graph — Three.js, live on Vercel
- [x] Multiple layout modes (centralized / decentralized / distributed)
- [x] Node interaction and graph navigation
- [ ] WebXR session entry
- [ ] Hand pinch gesture → node selection
- [ ] World Labs Marble API integration
- [ ] Portal transition (graph dissolves → world opens)
- [ ] Return gesture (palm up → graph returns)
- [ ] 2–3 fully realized node worlds (History, Land, Future)

---

## Project Context

ROOM is a semantic memory layer for the spatial internet — a persistent, community-owned knowledge infrastructure where space is the primary interface for meaning-making.

DVV (Dunsmuir Visionary Village) is a bioregional community in Northern California building a vision for regenerative place-based living. This knowledge graph is their first spatial shard — history, land, and future made navigable.

This hackathon iteration is the convergence of:
- Spatial knowledge graphs as navigation systems
- World model generation from community assets
- WebXR as the open, browser-native delivery layer

---

## Looking For

Building this at the World Models Hackathon (March 2026). Looking for:

- **Three.js / WebXR** — session entry, hand tracking, gesture interaction
- **World Labs Marble API** — world generation pipeline, portal transitions  
- **Shader / Spatial UI** — GLSL, Three.js materials, particle systems

Find me at the mixer or reach out.

---

## Author

**innercartography** — spatial epistemologist, independent builder  
Working at the intersection of spatial computing, knowledge infrastructure, and regenerative community design.

🐙 [github.com/innercartography](https://github.com/innercartography)  
🌐 [dvv-knowledge-graph.vercel.app](https://dvv-knowledge-graph.vercel.app)

---

*ROOM — Semantic Memory Layer for the Spatial Internet*  
*© 2026 innercartography*
