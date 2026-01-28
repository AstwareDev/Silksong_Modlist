<div align="center">

<!-- LOGO SECTION -->
<img src="Assets/Media/icon_transparent.png" alt="Nexus Forge Logo" width="200" height="200" />

# Silksong Modlist
### The Central Nervous System for Nexus Forge

<p>
  <a href="https://github.com/AstwareDev/Silksong_Modlist/blob/main/mods.json">
    <img src="https://img.shields.io/badge/Data-mods.json-blue?style=for-the-badge&logo=json" alt="JSON Data" />
  </a>
  <a href="#">
    <img src="https://img.shields.io/badge/Game-Silksong-red?style=for-the-badge&logo=nintendo" alt="Game" />
  </a>
  <a href="#">
    <img src="https://img.shields.io/badge/Status-Ready-success?style=for-the-badge" alt="Status" />
  </a>
</p>

<p>
    <b>The backend repository feeding the Nexus Forge Mod Manager.</b><br>
    <i>"We are ready before the game is."</i>
</p>

</div>

---

## 🕷️ About

This repository serves as the **remote database** for the Silksong Mod Manager (Nexus Forge). It acts as a Content Delivery Network (CDN) containing the master list of available mods and their cached documentation.

By decoupling the data from the application, we can update the mod list dynamically without requiring users to update the Nexus Forge executable.

## 📂 Repository Structure

The architecture is kept simple for fast fetching and easy maintenance.

```text
Silksong_Modlist/
├── 📄 mods.json            # The Master List. Contains metadata, versions, and download links.
├── 📂 Assets/
│   ├── 📂 Markdowns/       # Local copies of Mod READMEs (for offline viewing/caching).
│   └── 📂 Media/           # Icons and visual assets for the Manager UI.
└── 📄 README.md            # You are here.
