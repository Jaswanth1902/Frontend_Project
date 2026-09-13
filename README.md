<div align="center">

![Web Systems Banner](assets/web_systems_banner.svg)

# 🌐 Web Systems Core: Modular Component Architecture & State Systems
### *Modern React 18, State Persistence, Accessible Patterns & Emil Kowalski Design Engineering*

[![Frontend: React 18](https://img.shields.io/badge/Frontend-React_18_%7C_Vite-61DAFB?style=flat-square&logo=react&logoColor=black)](https://github.com/Jaswanth1902/Amazon_clone)
[![State: Redux / Context](https://img.shields.io/badge/State-Redux_%7C_Context_API-764ABC?style=flat-square&logo=redux&logoColor=white)](https://github.com/Jaswanth1902/Amazon_clone)
[![Aesthetic: Emil Kowalski UI](https://img.shields.io/badge/Aesthetic-Kowalski_Craft_%7C_Atelier-C5A059?style=flat-square)](https://github.com/Jaswanth1902/Amazon_clone)
[![License: MIT](https://img.shields.io/badge/License-MIT-C5A059.svg?style=flat-square)](LICENSE)

*A clean full-stack web application showcasing modular component decomposition, persistent cart state, responsive layouts, and tactile micro-interactions.*

</div>

---

## ⚡ The Architectural Vision

Modern web development often suffers from bloated third-party dependencies, sluggish re-renders, and inaccessible component hierarchies.

**Web Systems Core** exemplifies clean frontend architecture:
- **Modular Component Decomposition**: Atomic design hierarchy separating presentational atoms from container state orchestrators.
- **Deterministic State Persistence**: Redux Toolkit / Context state synchronized with browser storage.
- **Emil Kowalski Tactile Feedback**: Physics-based `:active` scaling (`transform: scale(0.97)`), responsive easing curves (`cubic-bezier(0.23, 1, 0.32, 1)`), and zero layout-thrashing animations.

---

## 🏗️ State & Component Flow

```mermaid
flowchart TD
    UserAction([User Interaction: Add to Cart / Filter]) --> PresentationalComponent[Presentational Component]
    PresentationalComponent --> ActionDispatcher[Action Dispatcher / Hook]
    ActionDispatcher --> StateStore[(Global State Store)]
    StateStore --> LocalStorageSync[Persistent Storage Sync]
    StateStore --> ReRenderSubscriber[Subscribed View Components]
    ReRenderSubscriber --> DOMUpdate[Lighthouse-Optimized DOM Render]
```

---

## 🧩 Antigravity Skills & Tooling

- **`emil-design-eng`**: Tactile feedback, responsive custom easing curves, zero `transition: all`.
- **`react-best-practices`**: Memoized selectors and zero unnecessary parent re-renders.
- **`lighthouse-auditor`**: Enforcing >90 scores across Performance, Accessibility, and Best Practices.

---

## 📄 License

Distributed under the [MIT License](LICENSE). Maintained by [Jaswanth Reddy](https://github.com/Jaswanth1902) — *Passionate learner & creative problem solver learning from and giving back to the open-source community.*
