# Forever Young — Codex Pet v2

An unofficial fan-made pet featuring Forever Young from Cygames' *Umamusume: Pretty Derby*, based on her official race outfit. Version 2 keeps the nine animation states from v1 and adds 16 head-and-eye gaze directions.

## Install the native Codex pet

Download and extract `forever-young-codex-pet-v2.zip` from the repository root, then copy the extracted `package/forever-young-v2` folder into `${CODEX_HOME}/pets/`. If `CODEX_HOME` is not set, the destination is `~/.codex/pets/forever-young-v2/`. The resulting layout should be:

```text
~/.codex/pets/forever-young-v2/pet.json
~/.codex/pets/forever-young-v2/spritesheet.webp
```

Open Pets in Codex settings, select Refresh, then choose “フォーエバーヤング v2”.

The nine states are idle, run left/right, wave, jump, sad, waiting, working, and review. The v2 sheet is 1536×2288, arranged as 8 columns by 11 rows of 192×208 cells, with 73 occupied cells: 57 animation frames plus 16 gaze directions.

## Mouse and voice preview

The root `package/forever-young/` directory is the older v1 package; the v2 installation files are inside `forever-young-codex-pet-v2.zip`. Extract that ZIP, then open its `preview.html` in a browser to try the interactive preview: gaze follows the pointer within the page, hovering triggers one jump per entry, and clicking plays the original official voice while she waves. The browser preview only receives pointer coordinates inside the page. These interactions are not part of the native Codex pet interface. The native client uses a Computer Use cursor or text insertion point when available; it does not follow the ordinary desktop pointer or support one-shot hover jumps or click-triggered audio.

## Files and attribution

- `package/forever-young-v2/`: installable Codex pet configuration and sprite sheet.
- `preview.html`, `preview.js`, `interaction.js`: local interactive preview.
- `动作预览/`: animation and gaze previews.
- `official-voice.mp3`: unedited voice audio from the official character page, voiced by Shuri Umiumi.
- `CREDITS.md`: character, audio, and production credits.
- `forever-young-codex-pet-v2.zip`: complete package; its SHA-256 is in the adjacent `.sha256` file.

Forever Young and official materials belong to Cygames and their respective rights holders. This is an unofficial, non-commercial fan project.
