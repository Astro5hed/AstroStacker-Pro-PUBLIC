# AstroStacker Pro
<img width="3816" height="2092" alt="screenshot" src="https://github.com/user-attachments/assets/40e2bd74-03bf-44ac-a51a-2298f77e086a" />
A Windows desktop app for astrophotography stacking and post-processing, built around
[Siril](https://siril.org/)'s stacking engine with a full suite of additional processing
tools layered on top.

**This repository hosts pre-built Windows releases only — it does not contain the
application's source code.**


## Download

Grab the latest release from the [Releases page](../../releases/latest). Download the
`.zip`, extract it anywhere, and run the `.exe` inside — no installer needed.

**Requirements:** Windows 10/11 (64-bit).

## Built On

AstroStacker Pro is a front-end that runs [Siril](https://siril.org/) for the actual
stacking work, with several additional tools adapted or ported from real, published
PixInsight and Siril scripts:

- **Dark Structure Enhance** — ported from the real DarkStructureEnhance script by
  Carlos Sonnenstein & Oriol Lehmkuhl (PTeam, 2009), licensed GPL v3
- **VeraLux HyperMetric Stretch** — ported from Riccardo Paterniti's real VeraLux
  HyperMetric Stretch script for Siril, licensed GPL-3.0-or-later
- **Blemish Blaster, Star Stretch, NBtoRGB Stars** — ported from Franklin Marek's real
  Seti Astro PixInsight scripts
- **Astro Color Mixer** — adapted from Pat Cosgrove's original PixInsight Astro Color
  Mixer script, via Yannick Dutertre's (Cuiv the Lazy Geek) Siril port

Full credit for the underlying algorithms in these tools goes to their original authors.

## License

See [LICENSE](LICENSE).
