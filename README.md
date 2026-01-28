<div align="center">

<img src="Assets/Media/icon_transparent.png" alt="Nexus Forge Logo" width="150" height="150" />

# Silksong Modlist

**Central database repository for the Nexus Forge Mod Manager.**

<!-- FUNCTIONAL BUTTONS -->
<p>
  <!-- 1. Website Redirect -->
  <a href="https://YOUR_WEBSITE_LINK_HERE">
    <img src="https://img.shields.io/badge/Website-Nexus%20Forge-blue?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website" />
  </a>
  
  <!-- 2. Download Manager -->
  <a href="https://YOUR_DOWNLOAD_LINK_HERE">
    <img src="https://img.shields.io/badge/Download-Manager-success?style=for-the-badge&logo=windows&logoColor=white" alt="Download" />
  </a>

  <!-- 3. Open Database -->
  <a href="mods.json">
    <img src="https://img.shields.io/badge/Data-mods.json-orange?style=for-the-badge&logo=json&logoColor=white" alt="View Database" />
  </a>
</p>

</div>

---

## About
This repository serves as the backend infrastructure for Nexus Forge. It decouples mod data from the application logic, allowing for dynamic updates to the mod list without requiring an application update.

## Repository Structure

*   **`mods.json`**: The master list containing metadata, versioning, and download URLs for all indexed mods.
*   **`Assets/Markdowns/`**: Contains raw `.md` files for individual mods, used for displaying documentation within the manager.
*   **`Assets/Media/`**: UI assets and icons.

```text
Silksong_Modlist/
├── Assets/
│   ├── Markdowns/       # Local copies of mod readmes
│   └── Media/           # Application icons
├── mods.json            # Main database file
└── README.md
