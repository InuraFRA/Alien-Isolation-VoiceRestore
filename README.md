# AlienIsolationVoiceRestore

**The Alien can hear your voice again.**  
**L'Alien peut de nouveau entendre votre voix.**

A free, unofficial microphone-reactivity mod for *Alien: Isolation* on Windows, created by **InuraFRA (Inura)**.

[**Download v1.0.0 (Steam / Epic)**](https://github.com/InuraFRA/Alien-Isolation-VoiceRestore/releases/tag/v1.0.0) · [Direct ZIP download](https://github.com/InuraFRA/Alien-Isolation-VoiceRestore/releases/download/v1.0.0/AlienIsolationVoiceRestore_v1.0.0.zip)

---

## English

### What does it do?

AlienIsolationVoiceRestore detects microphone activity and sends sound-perception events through the game's existing `NPC_FakeSense` system. **Speaking can attract the Alien's attention** when it is present in gameplay.

- Automatic startup with the included ASI loader — **no manual injector**.
- Gameplay-tested on the **specific Steam and Epic Games builds** listed below.
- Uses the **default Windows microphone**; no Kinect or speech recognition needed.
- No microphone audio recordings, playback, loopback or network transmission.

### Installation

1. Download **`AlienIsolationVoiceRestore_v1.0.0.zip`** from [Releases](https://github.com/InuraFRA/Alien-Isolation-VoiceRestore/releases/tag/v1.0.0). **Do not download GitHub's automatically generated “Source code” archives** — they do not contain the mod.
2. Close the game and open its installation directory containing **`AI.exe`**.
3. **If `d3d11.dll` already exists, do not overwrite it.** Other mods, ReShade or loaders may use this file; coexistence is untested.
4. Copy these **three files** from the ZIP next to `AI.exe`:
   - `AlienIsolationVoiceRestore.asi`
   - `AlienIsolationVoiceRestore.ini`
   - `d3d11.dll`
5. Launch via Steam or Epic. Remain quiet for approximately **three seconds when microphone capture begins** to allow calibration. Then speak near the Alien during gameplay.

Remove identified older AIVR files first, avoiding duplicate AIVR `.asi` copies. The ZIP includes **`README_EN.md`** with complete installation, troubleshooting and uninstall guidance.

### Compatibility and limitations

Gameplay was verified with the shortened ASI filename on **Steam and Epic Games on October 28, 2026**, for these exact `AI.exe` builds:

| Edition | Tested `AI.exe` SHA256 |
| --- | --- |
| Steam | `02f4c4a0392452d5ed7cfbf978e29d3235d8de48c8f4b4f734b930943ed3670b` |
| Epic Games | `aeca9fbf00cabda8dbb78bddf39e4d40095a97d6ec9d4ee1b482f87e84597a81` |

Other builds, mod loaders, combinations of mods and some scene-transition scenarios are **not validated**. v1.0.0 has no microphone selector, in-game sensitivity controls or speech recognition.

Microphone input is processed locally. No raw microphone recordings are saved or transmitted. Diagnostic logs may include numeric audio levels and game-state information; review them before sharing.

### Integrity, credits and permissions

Official v1.0.0 download SHA256:

`2e2e67991f540996cb1a9495499e9cc646c21e503ca0d90906ea39c5594e166c`

The ZIP contains `SHA256SUMS.txt`, `LICENSE_AIVR.txt`, `LOADER_NOTICE.txt`, `ULTIMATE_ASI_LOADER_LICENSE.txt` and `CREDITS_AND_AI.md`.

**AIVR is free but not open source.** Redistribution permissions for original AIVR components are described in `LICENSE_AIVR.txt`. The included **Ultimate ASI Loader by ThirteenAG** is separately licensed under **MIT**.

Created and gameplay-tested by **Inura**, with substantial development assistance from **OpenAI Codex and ChatGPT**. This is an unofficial fan mod, not endorsed by SEGA, Creative Assembly or the *Alien* rights holders.

### Special Thanks

**To my brother, Eridwyn** — Even beyond this project, you helped light my way when I was lost in the dark. Thank you for being there when I needed it most.

---

## Français

### Présentation

**AlienIsolationVoiceRestore** permet à l'Alien de réagir à l'activité sonore captée par votre microphone grâce au système de perception existant du jeu. Il ne reconnaît pas les mots : **parler peut attirer l'attention de l'Alien**.

Le mod démarre automatiquement avec le jeu grâce au chargeur ASI fourni, sans injecteur manuel ni Kinect. Il utilise le **microphone Windows par défaut** et n'enregistre ni ne transmet ta voix.

### Installation rapide

1. Téléchargez le ZIP joint à [**la release v1.0.0**](https://github.com/InuraFRA/Alien-Isolation-VoiceRestore/releases/tag/v1.0.0), et non les archives « Source code » générées automatiquement par GitHub.
2. Fermez le jeu et trouvez le dossier contenant `AI.exe`.
3. **Si `d3d11.dll` existe déjà, ne l'écrasez pas.** Il peut appartenir à un autre mod.
4. Copiez à côté de `AI.exe` les fichiers `AlienIsolationVoiceRestore.asi`, `AlienIsolationVoiceRestore.ini` et `d3d11.dll`.
5. Lancez le jeu normalement. Restez silencieux environ **trois secondes au début de la capture** pour permettre la calibration, puis parlez à proximité de l'Alien.

**Compatibilité confirmée en jeu sur les versions précises Steam et Epic testées le 28 octobre 2026.** Les autres versions et associations avec d'autres mods ne sont pas garanties.

Pour les instructions complètes, les limites et la désinstallation, consultez **`README_FR.md` dans l'archive**. Le code source AIVR reste privé ; ses droits de redistribution figurent dans `LICENSE_AIVR.txt`. Le chargeur tiers conserve sa licence MIT.

### Remerciements

**À mon frère, Eridwyn** — Même au-delà de ce projet, tu as éclairé mon chemin lorsque j'étais perdu dans l'obscurité. Merci d'avoir été là quand j'en avais le plus besoin.

---

**Official downloads / Téléchargements officiels :** [GitHub Releases](https://github.com/InuraFRA/Alien-Isolation-VoiceRestore/releases)

## Support the creator / Soutenir le créateur 💜

If you enjoy my independent creations, you can leave a **completely optional tip** on [Ko-fi — Inura](https://ko-fi.com/inura).

All public releases remain free. Donations do not provide exclusive content, early access or development commitments.

---

Si vous appréciez mes créations indépendantes, vous pouvez me soutenir par un **don entièrement facultatif** sur [Ko-fi — Inura](https://ko-fi.com/inura).

Mes créations publiques restent gratuites, sans contenu exclusif ni contrepartie obligatoire.
