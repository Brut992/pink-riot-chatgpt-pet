# Pink Riot

[Русский](README.ru.md) · **Created entirely using ChatGPT & Codex**

![Pink Riot — original approved character design](assets/pink-riot-master-design.png)

An anime punk companion with black-and-pink twin tails, platform boots and attitude. The creator has confirmed that Pink Riot works in ChatGPT.

### Download → upload → meet Pink Riot

**[Download the pet (WebP)](https://github.com/Brut992/pink-riot-chatgpt-pet/releases/download/v1.0.0/Pink-Riot-web-upload.webp)** · [PNG alternative](https://github.com/Brut992/pink-riot-chatgpt-pet/releases/download/v1.0.0/Pink-Riot-web-upload.png) · [All files](https://github.com/Brut992/pink-riot-chatgpt-pet/releases/tag/v1.0.0)

1. Download **one** of the two pet files above.
2. In ChatGPT, open **Settings → Personalization → Pet → Select pet → Upload pet** (where available).
3. Upload the file and select **Pink Riot**.

The upload sheet is transparent, **1536 × 1872**, below 20 MiB. See the [official Pets guide](https://learn.chatgpt.com/docs/pets). The separate taller v2 atlas is for compatible desktop tooling; use the download above for the web uploader.

### Real animation previews

| Idle | Wave | Jump |
| :---: | :---: | :---: |
| ![Idle](previews/idle.gif) | ![Wave](previews/waving.gif) | ![Jump](previews/jumping.gif) |

![Thinking](previews/running.gif) ![Look directions](previews/look.gif)

These are exports of the actual pet frames. [All nine animations and gaze previews](previews/) include WebP versions that preserve soft transparency. Thinking is the `running` task state; there is no separate Happy state.

### Inside the project

| Files | Purpose |
| --- | --- |
| `Pink-Riot-web-upload.webp` / `.png` | Ready for web upload; choose one |
| `spritesheet.webp`, `spritesheet-v2.png`, `pet.json` | Extended v2: 57 animation frames, 16 gaze directions and neutral |
| [preview.html](preview.html) | Interactive local viewer; download the repository ZIP, extract it, then open this file |
| [Full atlas](spritesheet-v2.png) · [Gaze sheet](look-directions.png) | Inspect every pose |
| `sources/` | Final RGBA frames, accepted source strips and canonical sprite; raster assets, not a layered rig |
| `assets/` | Original approved master design; no third-party references |
| [QA report](QA.md) · [SHA256SUMS](SHA256SUMS) | Checks, limitations and file checksums |

### Credits & permissions

**Created entirely using ChatGPT & Codex.** Character imagery, animations, assembly and QA were produced with these tools from the approved Pink Riot design.

No open-source license has been granted. See [license notice](LICENSE-NOTICE.md). This is an independent community project, not an official OpenAI product.
