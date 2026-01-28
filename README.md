<div align="center">

<img src="Assets/Media/icon_transparent.png" alt="Nexus Forge Logo" width="150" height="150" />

# Silksong Modlist

**Backend data repository for the Nexus Forge Mod Manager.**

</div>

---

## Overview
This repository functions as the remote source for Nexus Forge. It hosts the master JSON list of available mods and their corresponding README files for display within the manager application.

## Repository Structure

*   **`mods.json`**: The core database containing mod metadata, versioning, and download links.
*   **`Assets/Markdowns/`**: Stores individual README files for mods to allow offline or in-app viewing.
*   **`Assets/Media/`**: Stores application icons and visual resources.

```text
Silksong_Modlist/
├── Assets/
│   ├── Markdowns/       # .md files for specific mods
│   └── Media/           # App assets
├── mods.json            # Main database
└── README.md
