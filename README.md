![Alt text](bgmain2.png)

**🇷🇺 Русский** · [🇬🇧 English](README_EN.md)

# Monster Hunter Emulation Compendium

Единая точка входа по частям серии на эмуляторах. Выбери игру → разверни блок → перейди в репозиторий с полным гайдом.

## Быстрый поиск

| Игра | Платформа | Эмулятор | Сложность |
|------|-----------|----------|-----------|
| [Monster Hunter Freedom Unite](https://github.com/blisterbaby42/mhfu-complete-guide) | PSP | PPSSPP | 🟢 патчи/конфиг (опционально) |
| [Monster Hunter 4 Ultimate](https://github.com/blisterbaby42/mh4u-guide) | 3DS | Citra\Azahar | 🔴 будет много твиков / 🚧 WIP |
| [Monster Hunter Generations Ultimate](https://github.com/blisterbaby42/mhgu-guide-pc) | Switch | Ryujinx\Eden(WIP) | 🟡 прошивка/ключи |

> 🟢 из коробки · 🟡 нужны патчи/настройки/ключи · 🔴 ручная возня

---

### Monster Hunter Freedom Unite (PSP)

<details>
<summary><b>MHFU</b> · PPSSPP · 🟢 готовый ROM + патчи и конфиг</summary>

[Гайд](https://github.com/blisterbaby42/mhfu-complete-guide)

**Что внутри:**
- Патченый ISO (Google Drive) или оригинальный JAP ROM + [патчер v1.4.0](https://github.com/FUComplete/Patch/releases/tag/v1.4.0) для создания патченного рома и `CONFIG.BIN`
- [Онлайн-редактор конфига](https://fucomplete.github.io/assets/config_editor.html) — true damage, масштаб миникарты, GH drink buff и др.
- [Athena ASS](https://www.mediafire.com/file/6z6dgks3kjc4u5g/%5BPSP_MHF1%5DAthena%27s_%2A.S.S-viciousShadow%27s_MHF1_Edition_v96.zip) — поиск оптимальных миксов брони
- [Ветки оружия онлайн](https://mhfu.vallode.com/smithy/)
- Моды: [MHFU Texture Port](https://github.com/Monkbreh/MHFU-Texture-Port) · [Nexus Mods](https://www.nexusmods.com/monsterhunterfreedomunite/mods/36)

</details>

---

### Monster Hunter 4 Ultimate (3DS)

<details>
<summary><b>MH4U</b> · 3DS · 🚧 в процессе</summary>

[Гайд](https://github.com/blisterbaby42/mh4u-guide)

**Что уже есть:**
- Читы-патчи для производительности/графики: 60 FPS (переключение на 30 по удержанию R), ускорение/замедление игры, отключение FSAA и дизеринга
- QoL чит-коды
- [HD-текстуры](https://www.dropbox.com/scl/fi/azn0yh82si223p9lieam2/0004000000126300.7z?rlkey=yl5gcv8jsgdc70t4osqun8e74&st=6jyt7oew&e=1&dl=0)
- [ ] TODO: настройка мультиплеера через встроенные онлайн комнаты
- [ ] TODO: настройка мультиплеера через PortHole

**Важно:** репозиторий активно пополняется — перед использованием сверяйся с актуальным README.

</details>

---

### Monster Hunter Generations Ultimate (Switch)

<details>
<summary><b>MHGU</b> · Ryujinx · 🟡 прошивка и ключи</summary>

[Гайд](https://github.com/blisterbaby42/mhgu-guide-pc)

**Что внутри (пошагово):**
1. **Игра:** ROM + update 1.4.0 (торрент) или prepatched-версии
2. **Эмулятор:** [Ryujinx 1.3.3](https://git.ryujinx.app/ryubing/ryujinx/-/releases/1.3.3)
3. **Прошивка Switch:** через `Actions → Install Firmware` (NX_Firmware 21.1.0)
4. **DLC:** добавить папку с ромом и DLC в `Options → Settings → Interface`
5. **Ключи (`prod.keys`):** через `Actions → Install keys` — нужны оба: title и prod
6. **60–120 FPS:** мод в папку `/mods` (ссылка на Google Drive; если дедлинк — [GBAtemp-тред](https://gbatemp.net/threads/monster-hunter-generations-ultimate-60-fps-hack.553053/))
7. **Мультиплеер:** `Options → Settings → Network` + разрешить входящие в файрволе; в игре `Hunter Connect → Find`

**Доп. инструменты:**
- [Save Manager для MHXX/MHGU](https://gbatemp.net/threads/mhxx-mhgu-save-manager.668514/)
- [Armor Set Builder](https://mhxx.wiki-db.com/sim/?hl=en)

</details>

---

## 🔧 Общие материалы и инструменты

- **Патчер MHFU:** [FUComplete/Patch](https://github.com/FUComplete/Patch/releases/tag/v1.4.0)
- **Редактор конфига MHFU (браузер):** [fucomplete.github.io](https://fucomplete.github.io/assets/config_editor.html)
- **Текстуры MHFU:** [MHFU-Texture-Port](https://github.com/Monkbreh/MHFU-Texture-Port) · [Nexus Mods](https://www.nexusmods.com/monsterhunterfreedomunite/mods/36)
- **Athena ASS (MHFU):** [MediaFire](https://www.mediafire.com/file/6z6dgks3kjc4u5g/%5BPSP_MHF1%5DAthena%27s_%2A.S.S-viciousShadow%27s_MHF1_Edition_v96.zip)
- **Ветки оружия MHFU:** [mhfu.vallode.com/smithy](https://mhfu.vallode.com/smithy/)
- -----------------------------------------------------------------------------------
- **HD-текстуры MH4U:** [Dropbox](https://www.dropbox.com/scl/fi/azn0yh82si223p9lieam2/0004000000126300.7z?rlkey=yl5gcv8jsgdc70t4osqun8e74&st=6jyt7oew&e=1&dl=0)
- -----------------------------------------------------------------------------------
- **Save Manager MHGU:** [GBAtemp](https://gbatemp.net/threads/mhxx-mhgu-save-manager.668514/)
- **Armor Set Builder MHGU:** [mhxx.wiki-db.com/sim](https://mhxx.wiki-db.com/sim/?hl=en)

---

## ✅ Статус гайдов

| Гайд | Статус |
|------|--------|
| MHFU (PSP) | ✅ готов (с патчами и модами) |
| MH4U (3DS) | 🚧 in progress |
| MHGU (Switch) | ✅ готов (пошаговая настройка Ryujinx, Eden позже) |

> Нет нужной части серии? Открой [issue](https://github.com/blisterbaby42/mhfu-complete-guide/issues) в любом из репозиториев — добавлю в очередь.
