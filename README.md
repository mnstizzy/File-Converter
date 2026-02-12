# File Converter Pro

File Converter Pro is a modern, locally run toolkit designed for converting, trimming, and extracting media. It also provides integrated tools for acquiring video and audio content. The graphical user interface offers the polished experience of cloud services—featuring responsive buttons, animations, and detailed progress bars—while ensuring all processing occurs strictly on the local machine. No data leaves the local environment unless explicitly initiated by the user for external downloads.

### Key Features

* **Advanced File Conversion:** Supports extensive formats for images, audio, video, documents (via Pandoc), and archives. Includes batch processing capabilities for high-volume workflows.
* **Media Trimmer:** precise video and audio cutting tool featuring visual timeline controls and accurate start/end timestamp adjustments.
* **Media Extraction:** Specialized tools for extracting audio tracks and subtitles from video files.
* **Integrated Downloaders:** Built-in modules for retrieving high-quality video and audio from YouTube, YouTube Music, and various social media platforms.
* **Modern UI/UX:** A CustomTkinter-based interface featuring drag-and-drop support, modular "Bento-style" layouts, and native toolchain status monitoring.
* **Metadata Management:** Tools for editing file tags and cover art.

### Release Integrity

To ensure the security and integrity of the installation, strictly use the official installer. You may verify the file against the SHA-256 hash below.

| File | Algorithm | Hash |
| :--- | :--- | :--- |
| `FileConverterPro_Setup.exe` | SHA256 | `B4016E85F27ECDD179F98B5FB5235A34879E5FF216047BBE9478902486F9F177` |

### Release & Source Policy

* **Distribution:** Official installers are hosted in the releases section of this repository. This repository tracks development updates, bug fixes, and release preparation.
* **Source Access:** Source code is available upon request for auditing or rebuilding purposes. Please refer to the release notes for access instructions.
* **Verification:** Every release includes a `THIRD_PARTY_LICENSES.txt` file and a documented SHA-256 hash to allow users to confirm binary integrity before execution.
* **Build Documentation:** Contributors with build access should consult `private.md` for the pinned dependency list, build commands, and the NSIS packaging workflow.

### License

The core application is released under the **MIT License**.

Redistribution notices for third-party libraries and dependencies are provided in `THIRD_PARTY_LICENSES.txt`. If this software relies on any bundled external tool, please review the upstream license of that specific tool directly.
