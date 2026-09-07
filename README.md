# Kayley for Codex Pets

Kayley is a custom Codex desktop pet with ocean-blue eyes, dark curls, a red top, light blue jeans, and black heels.

<img src="previews/waving.gif" alt="Kayley waving" width="192"> <img src="previews/look-around.gif" alt="Kayley looking around" width="192">

[Download Kayley.zip](https://github.com/stozo04/codex-pets-kayley/raw/refs/heads/main/Kayley.zip)

## Install Kayley

1. Download and extract **Kayley.zip**.
2. Copy the extracted `kayley` folder into your Codex pets directory.
3. Open **Pets** in the desktop app and select **Refresh**.
4. Choose **Kayley**.
5. Enter `/pet` to show her.

The default pets directory is `.codex/pets` inside your home directory. On Windows, this is `%USERPROFILE%\.codex\pets`. If you set `CODEX_HOME`, use its `pets` directory instead.

The installed folder contains two files:

```text
pets/
  kayley/
    pet.json
    spritesheet.webp
```

Kayley runs through the app's existing pet controls, including dragging, activity indicators, and cursor-facing poses. The pet files live locally. No registration with a pet-sharing website is required.

## Animations

The package includes idle, running right, running left, waving, jumping, failed, waiting, working, and review states. It also includes 16 look-around directions.

Browse the [animation previews](previews) to see each state.

## Format and validation

- Native v2 spritesheet with `spriteVersionNumber: 2`.
- Transparent, lossless WebP, 1536 × 2288 pixels.
- Eight columns and eleven rows of 192 × 208 pixel cells.
- Passed the bundled atlas validator and independent animation and direction reviews.

Some intermediate gaze angles are subtle, and a few adjacent transitions are more pronounced. All four main directions passed the blind direction checks.

The artwork was generated with OpenAI image tools. This repository supplies the pet artwork and manifest; the desktop app supplies its behavior.
