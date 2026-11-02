# Khazalite Holds — New Recruit community catalogue

A community-built New Recruit/BattleScribe-format catalogue for the Khazalite Holds, based on the uploaded **“Khazalite Holds Battletome: Rules by Chapter (video transcript extract)”** PDF.

> **Important:** This is not an official Games Workshop publication or an independently verified transcription of the battletome. The source is a paraphrased video transcript. Unclear captions, inferred values, approximate points and missing data are flagged in the catalogue and in `DATA_STATUS.md`. Do not use this as an authoritative tournament rules source without checking the battletome.

## Repository contents

- `Age of Sigmar 4.0 - Khazalite Holds.gst` — minimal Age of Sigmar 4th Edition game-system definition for this standalone community catalogue.
- `Khazalite Holds.cat` — faction catalogue with 27 unit entries, known points values, unit characteristics, available weapon profiles, faction rules, formations, heroic traits, artefacts, spells and prayers.
- `RULES_REFERENCE.md` — human-readable rules index and source notes.
- `DATA_STATUS.md` — missing/uncertain data and validation checklist.
- `CHANGELOG.md` — project history.

## Import into New Recruit

### From GitHub
1. Create a **public** GitHub repository and upload the files in this folder to the repository root (not inside another subfolder).
2. In New Recruit, open **MySystems**.
3. Choose **Add from GitHub**.
4. Paste `your-github-username/your-repository-name` or the full GitHub repository URL and confirm.

New Recruit reads `.gst` and `.cat` files from a repository. Updates are picked up automatically after you update the repository.

### From local files
1. Open **MySystems** in New Recruit.
2. Choose the option to add/upload game data from your device.
3. Select both the `.gst` and `.cat` files.

## Scope and implementation choices

- This is a **standalone community system**, not a replacement for or modification of the official Age of Sigmar data set.
- Unit entries are selectable and known points values are entered so New Recruit can total them.
- Rules are included as readable rule text. They are **not all encoded as automated game logic**; New Recruit is an army builder, not a rules engine.
- No army composition/regiment restrictions were invented because the source transcript does not provide enough detail to implement them reliably.
- Where the transcript gives a points value only for a reinforced size, that limitation is stated in the unit notes.
- Units with no points value in the source are left without a points cost rather than assigned a guessed cost.

## Contributing / corrections

Please check all flagged items against the actual battletome. When correcting an entry, update the catalogue and `DATA_STATUS.md`, and record the change in `CHANGELOG.md`.

## Credits and disclaimer

Rules information is derived from a user-provided paraphrased transcript extract of a video review. The transcript attributes its source to The Honest Wargamer's Khazalite Holds review (19 October 2026). This repository is an unofficial fan-made data conversion and is not affiliated with, endorsed by, or sponsored by Games Workshop or New Recruit.
