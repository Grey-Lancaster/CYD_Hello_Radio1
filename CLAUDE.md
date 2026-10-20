# CLAUDE.md

CYD_Hello_Radio1: a release-style repo that holds only a prebuilt firmware binary, `CYD_Hello_radio.bin`, for the "CYD Hello Radio" project on a Cheap Yellow Display (ESP32), with WiFi manager. The repo description says it is meant for the ESPHome Web installer. Public repo.

## Layout
- `CYD_Hello_radio.bin` - the firmware image (about 1.3 MB). There is no source, build config, README or CI in this repo.
- `LICENSE` - GNU GPL v3.

## What to know
- Nothing here builds. I found no source for the firmware in this repo, so do not invent build or flash commands. The source is not in this repo; ask the owner where it lives before attempting changes to behaviour.
- The binary's flash offset and layout are not documented here. Check with the owner before telling anyone how to flash it (a merged image flashed at offset 0 is a guess, not something recorded in the repo).
- Treat `CYD_Hello_radio.bin` as an artifact: replace it only with a new build the owner provides, and never edit it by hand.

## Deploy
- Push to `main`. There are no tags, releases or workflows.
