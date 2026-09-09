# 🎮 Minecraft-configs

A centralized, version-controlled repository to store and manage Minecraft configuration files, data packs, server properties, and plugin settings across multiple game versions and platforms.

---

## 🚀 Project Overview

**Minecraft-configs** provides a structured and reproducible environment for managing Minecraft setups. Whether running a local Java server, a Bedrock realm, or testing version-specific features, this repository ensures:

* **Reproducibility:** Quickly restore or mirror server and client configurations across different environments.
* **Version Management:** Track setting changes across major Minecraft releases without configuration drift.
* **Cross-Platform Support:** Keep Java Edition and Bedrock Edition configs cleanly organized in one location.
* **Streamlined Setup:** Spin up new game instances or test environments with pre-configured settings.

---

## 📂 Repository Structure

The folder hierarchy separates settings by platform (`Java` or `Bedrock`) and game version:

```text
Minecraft-configs/
├── Bedrock/
│   ├── 1.19/
│   └── 1.20/
├── Java/
│   ├── 1.19/
│   └── 1.20/
├── .gitignore
├── LICENSE
└── README.md
```
---

## 📝 Notes

* **Excluded Files:** Large binary files such as plugin/mod `.jar` files, world saves, and full server logs are explicitly excluded via `.gitignore`. Only lightweight, text-based configuration files (`.yml`, `.json`, `.properties`, `.toml`) are tracked.
* **Strict Version Mapping:** Each directory strictly matches its respective Minecraft version. Configurations should not be shared across major versions without verifying compatibility.

---

## 📄 License

This repository is licensed under the [MIT License](LICENSE).

While maintained primarily for personal game configuration and server administration, feel free to fork, reference, or adapt this structure for your own Minecraft deployments.
