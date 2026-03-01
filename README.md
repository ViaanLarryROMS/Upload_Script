# GDRIVE Uploader made by Viaan

Dual-ISP optimized ROM release uploader with Google Drive + GoFile support.

Built for passion-driven ROM servers like **Placebo**.

---

## ✨ Features

- Google Drive upload via rclone
- Built-in GoFile mirror upload (no external script required)
- Upload mode selection (Drive / GoFile / Both)
- Dual ISP optimized (10 transfer threads)
- Automatic SHA256 generation
- OTA ZIP auto-skip
- Recovery image separation (`recovery/`)
- Automatic Drive folder link generation
- Release metadata JSON generation
- Upload lock protection
- Clean release summary output

---

## 📋 Requirements

- Python 3
- rclone
- curl
- jq

Install dependencies (Debian/Ubuntu):

```bash
sudo apt install rclone curl jq
