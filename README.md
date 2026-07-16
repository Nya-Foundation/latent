<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="branding/logo-lockup.svg">
    <img src="branding/logo-lockup-light.svg" alt="Latent" width="360">
  </picture>
</p>

<p align="center"><strong>Every image carries its recipe.</strong></p>

<p align="center">
  <a href="https://latent.moe">latent.moe</a>
</p>

---

**Latent** is a gallery for AI-generated art that refuses to lose the metadata.

Most galleries strip an image down to pixels. Latent reads the generation recipe on upload —
prompt, negative prompt, model, sampler, seed, LoRAs, and the full Danbooru-style tag set — and
keeps all of it searchable, browsable, and comparable. Including the metadata other tools throw
away: NovelAI's stealth alpha-channel steganography, ComfyUI's node graphs, and the EXIF comments
buried in JPEG exports.

## What it does

- 🧾 **Recipe-first showcase** — every public piece displays how it was made, with the raw
  metadata preserved verbatim. Like it? The full recipe is right there.
- 📦 **Designer inventory** — upload and manage your work, public or private, with series
  grouping, bulk actions, and ZIP export. Images with no generation metadata are politely refused.
- 🔬 **Tag analysis** — filter by tags, models, samplers, and parameters; per-tag and per-model
  analytics with distinctive-tag ranking and usage trends.
- 🎨 **Style Studio** — hold a concept fixed and vary one dimension — artist, character, series,
  LoRA, or model — to see how each renders it, side by side.
- 🌏 **Three languages** — English, 中文, 日本語.

## Reads what others can't

| Generator | Where the recipe hides |
| --- | --- |
| NovelAI | PNG text chunks — or gzip bits hidden in the alpha channel |
| ComfyUI | The executed node graph, traced through wildcard/concat/editor-node chains |
| Stable Diffusion / A1111 | The `parameters` text chunk |
| SwarmUI · InvokeAI | Their native PNG chunks |
| JPEG / WebP exports | EXIF `UserComment`, ASCII or UTF-16 |

## Open source — coming soon 🌱

Latent will be released as free software under the **AGPL-3.0** — free forever, in both senses.
The code is getting its final polish in a private repository; this placeholder will become the
real thing.

Until then: browse the gallery at **[latent.moe](https://latent.moe)**, and watch this repo to be
notified when the source lands.

---

<p align="center"><sub>User-uploaded artwork remains © its respective creators.</sub></p>
