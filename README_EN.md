![Alt text](bgmain2.png)

[🇷🇺 Русский](README.md) · **🇬🇧 English**

# Monster Hunter: Emulation Compendium

A single entry point for emulating entries in the series. Pick a game → expand the block → open the full guide repository.

## 📋 Quick Search

| Game | Platform | Emulator | Difficulty | Guide |
|------|----------|----------|------------|-------|
| [Monster Hunter Freedom Unite](https://github.com/blisterbaby42/mhfu-complete-guide) | PSP | PPSSPP | 🟢 working ROM + patches/config (optional) | [→ repo](https://github.com/blisterbaby42/mhfu-complete-guide) |
| [Monster Hunter 4 Ultimate](https://github.com/blisterbaby42/mh4u-guide) | 3DS | Citra\Azahar | 🔴lot of setup for MP \ 🚧 in progress | [→ repo](https://github.com/blisterbaby42/mh4u-guide) |
| [Monster Hunter Generations Ultimate](https://github.com/blisterbaby42/mhgu-guide-pc) | Switch | Ryujinx | 🟡 firmware/keys | [→ repo](https://github.com/blisterbaby42/mhgu-guide-pc) |

🟢 works out of the box · 🟡 patches/settings/keys needed · 🔴 manual tinkering

---

## Monster Hunter Freedom Unite (PSP)

<details>
<summary><b>MHFU</b> · PPSSPP · 🟢 working .ISO + patches and config</summary>

**Guide:** [blisterbaby42/mhfu-complete-guide](https://github.com/blisterbaby42/mhfu-complete-guide)

**What's inside:**
- Patched ISO (Google Drive) or original JAP ROM + [patcher v1.4.0](https://github.com/FUComplete/Patch/releases/tag/v1.4.0) to create the patched ROM and `CONFIG.BIN`
- [Online config editor](https://fucomplete.github.io/assets/config_editor.html) — true damage, mini-map scale, GH drink buff, etc.
- [Athena ASS](https://www.mediafire.com/file/6z6dgks3kjc4u5g/%5BPSP_MHF1%5DAthena%27s_%2A.S.S-viciousShadow%27s_MHF1_Edition_v96.zip) — for finding optimal armor mixes
- [Online weapon trees](https://mhfu.vallode.com/smithy/)
- Mods: [MHFU Texture Port](https://github.com/Monkbreh/MHFU-Texture-Port) · [Nexus Mods](https://www.nexusmods.com/monsterhunterfreedomunite/mods/36)

</details>

---

## Monster Hunter 4 Ultimate (3DS)

<details>
<summary><b>MH4U</b> · 3DS · 🚧 guide in progress</summary>

**Guide:** [blisterbaby42/mh4u-guide](https://github.com/blisterbaby42/mh4u-guide)

**What's already there:**
- Cheats and patches for performance/graphics: 60 FPS (switch to 30 by holding R), game speed up/slow down, disable FSAA and dithering
- QoL cheats: access item box in the Gathering Hall, change equipment in the hall (L+UP)
- [HD textures](https://www.dropbox.com/scl/fi/azn0yh82si223p9lieam2/0004000000126300.7z?rlkey=yl5gcv8jsgdc70t4osqun8e74&st=6jyt7oew&e=1&dl=0)

**Important:** the repository is actively updated — always check the current README before use.

</details>

---

## Monster Hunter Generations Ultimate (Switch)

<details>
<summary><b>MHGU</b> · Ryujinx · 🟡 firmware and keys</summary>

**Guide:** [blisterbaby42/mhgu-guide-pc](https://github.com/blisterbaby42/mhgu-guide-pc)

**What's inside (step by step):**
1. **Game:** ROM + update 1.4.0 (torrent) or prepatched versions
2. **Emulator:** [Ryujinx 1.3.3](https://git.ryujinx.app/ryubing/ryujinx/-/releases/1.3.3)
3. **Switch firmware:** via `Actions → Install Firmware` (NX_Firmware 21.1.0)
4. **DLC:** add the folder with the ROM and DLC in `Options → Settings → Interface`
5. **Keys (`prod.keys`):** via `Actions → Install keys` — both title and prod keys are required
6. **60–120 FPS:** mod into the `/mods` folder (Google Drive link; if dead — [GBAtemp thread](https://gbatemp.net/threads/monster-hunter-generations-ultimate-60-fps-hack.553053/))
7. **Multiplayer:** `Options → Settings → Network` + allow inbound in firewall; in-game `Hunter Connect → Find`

**Extra tools:**
- [Save Manager for MHXX/MHGU](https://gbatemp.net/threads/mhxx-mhgu-save-manager.668514/)
- [Armor Set Builder](https://mhxx.wiki-db.com/sim/?hl=en)

</details>

---

## Common Materials and Tools

- **MHFU patcher:** [FUComplete/Patch](https://github.com/FUComplete/Patch/releases/tag/v1.4.0)
- **MHFU config editor (browser):** [fucomplete.github.io](https://fucomplete.github.io/assets/config_editor.html)
- **MHFU textures:** [MHFU-Texture-Port](https://github.com/Monkbreh/MHFU-Texture-Port) · [Nexus Mods](https://www.nexusmods.com/monsterhunterfreedomunite/mods/36)
- **Athena ASS (MHFU):** [MediaFire](https://www.mediafire.com/file/6z6dgks3kjc4u5g/%5BPSP_MHF1%5DAthena%27s_%2A.S.S-viciousShadow%27s_MHF1_Edition_v96.zip)
- **MHFU weapon trees:** [mhfu.vallode.com/smithy](https://mhfu.vallode.com/smithy/)
- **MH4U HD textures:** [Dropbox](https://www.dropbox.com/scl/fi/azn0yh82si223p9lieam2/0004000000126300.7z?rlkey=yl5gcv8jsgdc70t4osqun8e74&st=6jyt7oew&e=1&dl=0)
- **MHGU Save Manager:** [GBAtemp](https://gbatemp.net/threads/mhxx-mhgu-save-manager.668514/)
- **MHGU Armor Set Builder:** [mhxx.wiki-db.com/sim](https://mhxx.wiki-db.com/sim/?hl=en)

---

## ✅ Guide Status

| Guide | Status |
|-------|--------|
| MHFU (PSP) | ✅ ready (with patches and mods) |
| MH4U (3DS) | 🚧 in progress |
| MHGU (Switch) | ✅ ready (step-by-step Ryujinx setup) |

> Missing an entry in the series? Open an [issue](https://github.com/blisterbaby42/mhfu-complete-guide/issues) in any of the repositories — I'll add it to the queue.
