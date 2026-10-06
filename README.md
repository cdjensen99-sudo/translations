# Hardwire99 translations

One JSON file per language covers **all Hardwire99 Valheim mods**. ComfortMe is first; other mods add prefixed keys to these same files.

Mods download `{Language}.json` from:

`https://raw.githubusercontent.com/cdjensen99-sudo/translations/main/`

Do **not** translate Valheim piece names such as Bearskin Rug.

## How to review

1. Open the file for your language (`French.json`, `German.json`, …).
2. Change the text on the **right** of each colon. Leave the keys unchanged.
3. Keep the quotes and commas. UTF-8 is required.

`English.json` is the source of truth. Missing keys in another language fall back to English in the mod.

## ComfortMe keys

| Key | What the player sees |
|-----|----------------------|
| `comfortme_category` | Hammer **Categories** row name |
| `comfortme_this_room` | Panel header, then `: N` |
| `comfortme_unsheltered` | After the total when you are not under a roof |
| `comfortme_base` | Always-on +1 |
| `comfortme_shelter` | Roof +1 |
| `comfortme_missing` | After Shelter when you are not sheltered |
| `comfortme_group_*` | Vanilla comfort group labels in the panel |
