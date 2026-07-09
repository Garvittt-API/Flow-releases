
<div align="center">

<!-- HEADER BANNER -->
<img src="https://images.unsplash.com/photo-1614149162883-504ce4d13909?q=80&w=1200&auto=format&fit=crop" alt="Flow Music Banner" style="border-radius: 15px; margin-bottom: 20px; width: 100%; max-height: 250px; object-fit: cover;"/>

<!-- APP LOGO -->
<!-- Replace 'icon.png' with the actual path to your blue icon file inside your repository -->
<img src="icon.png" alt="Flow Music Logo" width="140" height="140" style="border-radius: 28px; box-shadow: 0 10px 30px rgba(0, 150, 255, 0.3); margin-bottom: 20px;"/>

# 🎵 FLOW MUSIC PLAYER
### *Redefining Android Audio Architecture with Modular Power.*

<p align="center">
  <a href="https://github.com/Garvittt-API/Flow-releases/releases">
    <img src="https://img.shields.io/github/v/release/Garvittt-API/Flow-releases?style=for-the-badge&color=007BFF&logo=github&labelColor=1a1a1a" alt="Latest Release">
  </a>
  <img src="https://img.shields.io/badge/Platform-Android_9.0%2B-3DDC84?style=for-the-badge&logo=android&logoColor=white&labelColor=1a1a1a" alt="Platform">
  <img src="https://img.shields.io/badge/Architecture-Modular_.EAPK-FFD700?style=for-the-badge&logo=code-igniter&logoColor=black&labelColor=1a1a1a" alt="Architecture">
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge&labelColor=1a1a1a" alt="License">
</p>

<h4>
  <a href="#-the-flow-experience">Experience</a> • 
  <a href="#-supported-platforms">Platforms</a> • 
  <a href="#-installation-terminal">Installation</a> • 
  <a href="#-modular-architecture">Architecture</a>
</h4>

---

</div>

## ✨ The Flow Experience

Flow isn't just a music player; it is a highly scalable audio engine built on a modular framework. By decoupling the core playback engine from music sources, Flow allows you to inject custom `.eapk` modules to stream, download, and manage audio from anywhere.

| 🧩 **True Modularity** | ⚡ **Lightweight & Fast** |
| :--- | :--- |
| Inject custom `.eapk` plugins to expand functionality instantly without updating the core app. | Written for modern Android devices, ensuring zero bloat, fast startup times, and smooth animations. |
| 🎨 **Dynamic UI** | 🛡️ **Total Privacy** |
| A highly polished interface that adapts to your music, offering a premium listening experience. | No hidden trackers. Flow plays your music, your way, on your device. |

---

## 🌐 Supported Platforms

Flow's modular `.eapk` framework currently supports seamless integration with the following media servers and streaming platforms:

<div align="center">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS6um_bMioNod-TuAgqrmxHpkAbP7NKweT65O0-gI8ESw&s=10" width="70" style="margin: 15px;" alt="YouTube Music"/>
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQLWTwW6G3u6BD3EKtlDvGQh2b1hR1F8NXhhdH34kEHEA&s=10" width="70" style="margin: 15px;" alt="Deezer"/>
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQEzmPtxMIa4TqQPN8pwGny-xfU4IA6O6yZPM6hrdPmD_YPNJjehdm7Qls3&s=10" width="70" style="margin: 15px;" alt="Jellyfin"/>
  <img src="https://static.vecteezy.com/system/resources/thumbnails/067/941/728/small/jiosaavn-logo-rounded-hd-free-png.png" width="70" style="margin: 15px;" alt="JioSaavn"/>
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTAXZYUmaT3qdSVLRyYTPCnj_WtxUzTK4tFGKHExCsB_w&s" width="70" style="margin: 15px;" alt="Groove Music"/>
</div>

<p align="center">
  <i>More platforms can be added dynamically by importing new extension modules!</i>
</p>

---

## 🚀 Installation Terminal

Follow this procedural pipeline to establish your localized Flow installation environment.

```mermaid
graph LR
    A[Download Flow APK] -->|Install| B(Enable Unknown Sources)
    B --> C{Launch Base Engine}
    C -->|Core Active| D[Import .EAPK Plugin]
    D --> E((Unrestricted Audio Flow))
    
    style A fill:#0052CC,stroke:#fff,stroke-width:2px,color:#fff
    style C fill:#1a1a1a,stroke:#007BFF,stroke-width:2px,color:#fff
    style E fill:#009944,stroke:#fff,stroke-width:2px,color:#fff

```

### 🔹 Phase 1: Deploy Core Application Engine

1. Access the master distribution vault via the **[Flow Releases Page](https://github.com/Garvittt-API/Flow-releases/releases)**.
2. Initialize execution on your target device by downloading the latest system `.apk` asset.
3. Permit system authorization overrides if prompted (*"Allow installation from Unknown Sources"*).
4. Run the installer script, execute file unpacking, and launch **Flow**.

### 🔹 Phase 2: Inject Driver Extensions

1. Capture your preferred plugin module from the official **[Flow Extensions Vault](https://github.com/Garvittt-API/Flow-extension/releases/tag/extension)**.
2. Fire up Flow ➔ Locate and trigger the Control Action button in the **Top Right Corner**.
3. It will open the **'Music Extensions'** hub.
4. Press the **Add (+)** utility button and click on the **File** selection criteria option.
5. Choose your downloaded `.eapk` module asset inside the Android Storage File Tree wrapper to hot-load the music framework instantly.

---

## 🏗️ Modular Architecture

Flow utilizes a unique **Core-to-Plugin** bridge design:

* **The Engine (Core):** Handles UI rendering, media session management, audio focus, and background playback.
* **The Nodes (.eapk):** Isolated plugin binaries that act as content resolvers. They scrape, fetch, and deliver audio metadata and streams back to the core.

> **Why this matters:** If a music source breaks or changes its API, you don't need to wait for a full app update. Just swap or update the specific `.eapk` extension!

---

## 🔗 Project Ecosystem

Navigate the Flow architecture repositories here:

* ⚙️ **System Master Engine:** [Garvittt-API/Flow-releases](https://www.google.com/search?q=https://github.com/Garvittt-API/Flow-releases) *(Core Application)*
* 🔌 **Plugin Integration Matrix:** [Garvittt-API/Flow-extension](https://github.com/Garvittt-API/Flow-extension) *(.eapk Modules)*

---

## 📬 Maintenance & Support Protocol

Encountered an optimization flaw or have a structural suggestion to present? Flow thrives on community debugging and feature requests.

* **Bug Reports & Features:** File an analytical operational report directly inside the repository's **Issues Tracker**.
* **Direct Comm-Link:** Connect via formal transmission pipelines at **[garvitchoudhary2315@gmail.com](https://www.google.com/search?q=mailto%3Agarvitchoudhary2315%40gmail.com)**.
