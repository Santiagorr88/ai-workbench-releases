# AI Workbench — releases

This repository only hosts **release binaries** and **update metadata** for AI Workbench. The source code is private and not published here.

## Install (Linux)

Download from [Releases](https://github.com/Santiagorr88/ai-workbench-releases/releases/latest):

- **AppImage** (recommended, updates itself):
  ```bash
  chmod +x "AI-Workbench-<version>.AppImage"
  ./AI-Workbench-<version>.AppImage
  ```
  Needs FUSE 2 (`sudo apt install libfuse2t64` on Ubuntu 24.04).
- **.deb**:
  ```bash
  sudo apt install ./ai-workbench_<version>_amd64.deb
  ```

AI Workbench checks this repository for new versions and asks before downloading or installing anything.

## Channels

- `latest-linux.yml` — stable
- `beta-linux.yml` — beta (pre-releases like `0.3.0-beta.1`)
- `alpha-linux.yml` — dev (pre-releases like `0.3.0-alpha.1`)
