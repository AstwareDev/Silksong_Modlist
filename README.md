<div align="center">

<!-- LOGO SECTION -->
<img src="Assets/Media/icon_transparent.png" alt="Nexus Forge Logo" width="200" height="200" />

# Silksong Modlist
### The Central Nervous System for Nexus Forge

<p>
  <a href="https://github.com/AstwareDev/Silksong_Modlist/blob/main/mods.json">
    <img src="https://img.shields.io/badge/Database-Live-success?style=for-the-badge&logo=mongodb" alt="Database Live" />
  </a>
  <a href="#">
    <img src="https://img.shields.io/badge/Game-Silksong-red?style=for-the-badge&logo=nintendo" alt="Game" />
  </a>
  <a href="#">
    <img src="https://img.shields.io/badge/Timeline-2026-blueviolet?style=for-the-badge" alt="Current Year" />
  </a>
</p>

<p>
    <b>The master repository feeding the Nexus Forge Mod Manager.</b><br>
    <i>Enhancing Pharloom since launch day.</i>
</p>

</div>

---

## 🧶 About

This repository serves as the **remote database** for the Nexus Forge Mod Manager. It acts as the backbone for the community, delivering the master list of mods, dependency trees, and cached documentation to thousands of Weavers daily.

By decoupling the data from the application, Nexus Forge receives real-time updates on new mods (like the inevitable *Zoteboat DLC* or *Fishing Minigame Fixes*) without requiring an app update.

## 📂 Repository Structure

The architecture is streamlined for high-speed fetching.

```text
Silksong_Modlist/
├── 📄 mods.json            # The Master List. Metadata, versioning, and direct download links.
├── 📂 Assets/
│   ├── 📂 Markdowns/       # Cached READMEs (for viewing mod details inside the Manager).
│   └── 📂 Media/           # Icons and visual assets used by the Manager UI.
└── 📄 README.md            # Documentation.
