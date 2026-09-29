# 🏠📐 OmniBuild 3D

**Browser-based isometric home and structure designer with a canvas workspace, property editing, local projects, and JSON snapshots.**

🏷️ Maintained in [qamotech/ob3d](https://github.com/qamotech/ob3d) · 🌐 Public repository

## ✨ What is here

- 🏗️ Designer workspace for arranging structures and editing their properties.
- 🧲 Snap control, isometric view, undo/redo, and workspace diagnostics.
- 🖼️ Local gallery with project loading and deletion controls.
- 💾 Browser storage and JSON snapshots for project handling.

## 🧭 Try the project

Launch Designer, arrange a small structure, inspect its properties, save a project, and check it in the local gallery. Keep a JSON copy before clearing browser data.

## 🚀 Local setup

```sh
git clone https://github.com/qamotech/ob3d.git
cd ob3d
```

Use a current browser. Serve the repository root to preserve relative assets and a stable browser origin:

```sh
python -m http.server 8000
```

Open `http://localhost:8000/index.html`. Keep related assets beside the entry file. No npm setup is declared in the inspected repository.

## 🗂️ Source map

- 📄 [`index.html`](index.html)

## ⚙️ Configuration & data

Local projects depend on browser storage. Diagnostics are application controls, not evidence that every workflow has passed a test suite.

Keep credentials, private exports, customer records, and personal information out of commits and screenshots. A local browser demo is not evidence of account security, reliable persistence, or connected external services. Preserve exports before changing storage keys or resetting an application.

## 🧪 Verification checklist

- 🔎 Confirm the entry file and asset paths above exist in your checkout.
- ▶️ Start the documented runtime and inspect browser or terminal errors.
- 🧭 Exercise the project-specific workflow described above using sample data.
- 📱 Check narrow and wide layouts when the project has a browser interface.
- 💾 Verify save/export and recovery behavior before trusting important work to it.
- 📝 Record the exact command, browser, operating system, and outcome of your checks.

This guide was prepared from repository files and manifests. It does not claim a fresh build, deployment, security audit, or full functional test of this project.

## 🤝 Contributions & useful reports

Keep changes focused and explain the user-visible result. Preserve existing assets and configuration unless a change requires updating them. Include reproduction steps, expected and actual behavior, and relevant screenshots with personal information removed. For UI work, include the viewport and browser; for runtime issues, include the command and error text.

## 🛠️ Maintenance priorities

- 📚 Keep this guide aligned with implemented behavior and current entry points.
- 🧪 Add or maintain checks for the core workflow before expanding features.
- ♿ Review labels, keyboard navigation, contrast, and responsive layout.
- 📦 Document external services, asset rights, and deployment prerequisites.

## 📜 Licensing & attribution

This documentation update does not grant a new software or asset license. Consult existing license files, source headers, package metadata, and original asset terms; resolve inconsistencies with the owner before redistribution. Third-party names and resources retain their own terms.

---

## 📚 Preserved earlier documentation

The material below is retained verbatim for history and project-specific context. Template instructions and older claims may differ from the source inventory above.

# OmniBuild 3D (ob3d)

A massive, zero-dependency, single-file HTML5 isometric home and structure designer running entirely in the browser.

## Features
- 🚀 Zero-Dependency Architecture
- 📐 Drag-and-drop Isometric Building Engine
- 💾 LocalStorage / JSON Snapshot Saving
- 🎨 Full Property Editing & Context Menus
- 🌟 Dozens of UI Animations & Effects

## Usage
Simply open \index.html\ in any modern browser or host via GitHub Pages!
