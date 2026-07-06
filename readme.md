# The Legend of Sword and Fairy (仙剑奇侠传) — English Translation Patch v4.0

> A comprehensive terminology revision and translation cleanup for the classic Chinese RPG, built upon the SDLPal platform and the v3.3 translation by Nostaljaded.

---

## What Is This?

This is a fan-made English translation patch for **The Legend of Sword and Fairy** (仙剑奇侠传), the 1995 DOS/Windows RPG classic by Softstar. This patch applies to both PalDOS and PalWIN versions through the SDLPal source port.

v4.0 is a **second-pass terminology revision** — a systematic cleanup of item names, skill names, character names, enemy names, and status effects based on a comprehensive, authoritatively-reviewed Chinese–English terminology table (仙剑一术语表).

---

## What's New in v4.0

### Terminology Standardization (100% Coverage)

Every translatable entity in the game has been reviewed against a curated terminology table covering **all** game text categories:

| Category | Count | Highlights |
|----------|-------|------------|
| **Items** | 230+ | Weapons, armor, consumables, key items, talismans, gu insects |
| **Skills & Spells** | 100+ | Healing arts, elemental magic, sword techniques, summons |
| **Characters** | 260+ | Main cast, NPCs, villagers, guards, shopkeepers, storytellers |
| **Enemies** | 150+ | All monsters and bosses through all chapters |
| **Status Effects** | 20+ | Poisons, ailments, buffs, HP/MP indicators |
| **System/UI Terms** | 60+ | Menus, stats, save/load, battle commands |

### Key Naming Improvements

- **Item abbreviations expanded** — `Seal G` → `RemedSeal`, `Seal S` → `RecSeal`, `Seal X` → `SoulSeal`, `R Fruit` → `MouseFruit`, `D Grass` → `DragGrass`, etc.
- **Weapon names standardized** — `Red Tassel Blade` → `RedTassel`, `Twin Dragon Sword` → `DDragonSwd`, `PL Sword` → consistent format, etc.
- **Spell names made readable** — `FirstAid` → `QiHeal`, `L.Heal` → `LightHeal`, `H.Heal` → `HeavyHeal`, `WineGod` retained, etc.
- **Character names revised** — `Ah Nu` → `Anu`, `Sword Master` → `Sword Saint`, `Master Ling Yue` → `Mistress Lingyue`, `Queen` → `Shaman Queen`, `King` → `Shaman King`, `Chief Priestess` → standardised, etc.
- **Enemy names cleaned** — `Pig-Head Man` → `Pig Ogre`, `Old Weirdo` → `Weird Elder`, `Small Thunder God` → `Thunderlet`, `Green Beastman` → `Blue Beastman`, etc.
- **Gu (蛊) system names harmonised** — all gu insects now follow consistent naming: `DeadBug` → `3CorpseGu`, `SilkBug` → `GoldSilkGu`, `StealthBug` → `StealthGu`, etc.
- **Elemental orbs & pearls unified** — `WindJewel` → `WindPearl`, `Thun.Jewel` → `Thun.Pearl`, `Nuwa Jewel` → `NuwaPearl`, etc.
- **Consistent Pinyin formatting** — NPC names now use compact Pinyin: `Ji Sanniang`, `Song Hewen`, `Jiang Shaoyun`, `Han Mengci`, etc.

### Walkthrough Update

The full walkthrough HTML (`pal.htm` / `monster.htm`) has been systematically proofed and updated to use the revised terminology throughout.

---

## Installation

### Prerequisites

- A copy of **The Legend of Sword and Fairy** (PalDOS or PalWIN version)
- [SDLPal](https://github.com/sdlpal/sdlpal) — the cross-platform source port (Windows build included in v3.3 base)

### Steps

1. **Back up** your original `m.msg`, `sss.mkf`, and `word.dat` (plus `wor16.asc`, `wor16.fon` for PalDOS).
2. **Extract** the files for your game version (`dos_files/` or `win_files/`) into the game directory, overwriting when prompted.
3. **Run** the included `sdlpal.exe` (Windows), or download the latest SDLPal for your platform from [github.com/sdlpal/sdlpal](https://github.com/sdlpal/sdlpal).
4. **Configure** `sdlpal.cfg` — set `MessageFileName=m_eng.slf` for English (or `m_cht.slf` / `m_chs.slf` for Traditional/Simplified Chinese).
5. **Optional**: Enable touch overlay (`UseTouchOverlay=1`) for touch-based devices. See [sdlpal.cfg documentation](https://github.com/sdlpal/sdlpal/blob/master/docs/sdlpal.cfg.example) for more options.

### v4.0 Patch Files

This release contains the corrected `.slf` localization files. If you already have the v3.3 base installed, simply overwrite with the updated `m_eng.slf` (and corresponding `dos_files/` / `win_files/` content).

---

## Hotkeys

| Key | General | Adventure | Battle |
|-----|---------|-----------|--------|
| **Enter / Space** | OK / Search / Speak | — | — |
| **Esc / Insert / Alt** | Menu / Cancel | — | — |
| **Q** | — | Quit Game | Flee Battle |
| **W** | — | Equip Item | Use Projectiles |
| **E** | — | Use Item | Use Item |
| **R** | — | — | Repeat Last Command |
| **A** | — | — | Auto Attack |
| **S** | — | Status Screen | Status Screen |
| **D** | — | — | Defend |
| **F** | — | Spell | Auto Spell |
| **Page Up/Down** | — | Scroll menus | — |
| **Home/End** | — | First/Last item | — |

---

## Known Issues & Limitations

- Some dialogue may still have text overflow — character-count checking was only done through roughly 55% of the script (stopped at PalWIN "Don't… you have relatives?" and checked from "This door is locked" to end).
- Some rhymes, opera lines, and poetry remain in the original Chinese (non-critical to main plot).
- A few item/spell names could still benefit from better translations — suggestions welcome.
- This translation aims for faithfulness; it is not a literary re-write.

---

## Credits

### v4.0 (2026)
- **DodgeHo** — Terminology revision, systematic term-table curation, walkthrough update, and release

### v3.0–v3.3 (2015–2019)
- **Nostaljaded** — SDLPal ENG support, cross-referencing original Chinese lines, Equip/Status screen refactoring, translated poetry, text cleanup (40–55%), and ongoing maintenance

### v2.x and Earlier
- **Xire** and unmentioned translators — Original English translation (v2.5)
- **chamine** — PalDialogs Tool
- **Pantamorph** and others — Preserving and distributing the original translated files
- Administrators of the Chinese Paladin English Forum

### SDLPal
- **Whistler** — Original SDLPal
- **SuperMouse (louyihua)** and the SDLPal team — International/Unicode support fork & merge
- **PalMusicFan** — Assistance in making the SDLPal translation port possible

---

## Contact & Community

I am **DodgeHo**, a long-time fan of the series. Feedback, corrections, and collaboration are always welcome.

- **Email**: [asdsay@gmail.com](mailto:asdsay@gmail.com)
- **Discord**: `daoanlandodge`
- **QQ Group**: [1064586216](https://jq.qq.com/?_wv=1027&k=1064586216)

### Other Community Hubs

- Chinese Paladin English Forum: [fairysword.windy-goddess.net](http://fairysword.windy-goddess.net/phpBB/viewforum.php?f=3)
- RPG Codex Thread: [rpgcodex.net](http://www.rpgcodex.net/forums/index.php?threads/the-legend-of-sword-and-fairy-aka-chinese-paladin.99662/)

---

## A Note on Translation Quality

> Chinese is a compact language — bound to be lost-in-translation. The original translators had to work within severe character-width limits (now alleviated by SDLPal). This patch builds on their work, focusing on consistency and accuracy rather than literary flair.

Excerpt from the extended SDLPal translation of the iconic night scene:

```
既不回頭，何必不忘；
既然無緣，何需誓言。
今日種種，似水無痕，
明夕何夕，君已陌路。

You ain't returning, why remember me?
We ain't meant to be, why make promises?
Today will just be sweet memories;
Come tomorrow, we'll just be strangers.
```

Good games are meant to be shared. Enjoy!

---

*May better translators step forward to bring this game to an even wider audience.*
