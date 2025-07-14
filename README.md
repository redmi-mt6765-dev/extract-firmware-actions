# DumprX Firmware Extractor

A minimal GitHub Actions workflow for extracting firmware from a direct URL.

## Features
- Download and extract firmware.
- Push dumps to GitHub or GitLab.
- Optional Telegram notifications.

## Setup
1. Fork this repository.
2. Add these secrets in **Settings > Secrets > Actions**:
   - `USER_GITHUB_TOKEN`
   - `USER_GITHUB_ORG`
   - `GITLAB_TOKEN`
   - `GITLAB_GROUP`
   - `TG_BOT_TOKEN`
   - `TG_CHAT_ID`

## Usage
Trigger the workflow from the **Actions** tab:
- Select **extract firmware**.
- Provide `target-url` (direct firmware download link).

## License
MIT License © 2025 DumprX
