# Awesome-Mobile-Raster-Graphics-Editor

# Top Mobile Raster Graphics Editor Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on GPU-Accelerated Painting, Layer-Based Illustration & Touch-Optimized Photo Editing*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Mobile Raster Graphics Editors**. These tools bring pixel-based painting, photo retouching, and illustration to tablets and phones — brushes, layers, masks, and filters — with a spectrum running from polished commercial iPad apps to open-source editors like Krita for Android and Capy Canvas that run across platforms without subscriptions.

**Examples** include Krita for Android, Capy Canvas, and the commercial platforms (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, GPU-native rendering, and offline mobile painting — especially relevant as **Krita's Android port brings desktop-class tools to tablets** and **Capy Canvas** emerges as a cross-platform Procreate alternative built on wgpu .

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **Procreate** — **The iPad painting standard.** GPU-optimized brush engine, gesture-based interface, animation tools, and Apple Pencil integration. **One-time purchase** (~$12.99). **Trade-offs**: **iPad-only**, closed-source, and no Android or desktop version . **Best for iPad artists** wanting the most polished mobile painting experience available.

- **Adobe Photoshop on iPad** — **Desktop-class raster editing on Apple's tablet.** Layer compositing, masks, selections, and Creative Cloud sync. **Subscription required**. **Best for Adobe subscribers** needing Photoshop compatibility and cloud round-tripping on an iPad, accepting subscription costs and iPad-only availability.

- **Clip Studio Paint** — **The comic and manga creation standard.** Panel tools, perspective rulers, vector layers, and 3D model import for professional illustration workflows. **Subscription or one-time purchase** depending on platform and version . **Best for comic artists** needing panel layouts, screentones, and professional publishing tools on tablet or desktop.

- **MediBang Paint** — **The free cross-platform illustration app.** Free with premium subscription options, **180 default brushes with 700+ additional brushes** via subscription, comic panel tools, screentones, 60 fonts, and **PSD/CMYK support** for professional publishing . **Cloud sync and collaborative drawing** across devices . **Available on iPad, iPhone, and Android** . **Best for comic and manga creators** wanting a free, lightweight app with professional publishing features, accepting ads and subscription prompts for premium brushes .

## Open-Source GitHub Projects

- **Krita for Android** — **The desktop painting standard ported to tablets.** GPL-licensed, **Krita 5.3.2.1** (June 2026) with **Android arm64 support** for tablets and ChromeOS devices . **A direct port of the PC version**, giving Android users access to the same advanced brush engine, layers, color management, animation tools, and customizable panels . **The honest caveats**: **still considered beta/early access** — occasional bugs and crashes are possible . **The interface is exactly as on Windows**, which works well on larger tablet screens but can feel cluttered on smaller devices, with tiny icons and buried panels . **Requires a tablet with at least 4GB RAM** and a pressure-sensitive stylus for comfortable use . **Best for Android tablet artists** wanting desktop-class painting tools without subscriptions, accepting that it is a port rather than a mobile-first redesign .

- **Capy Canvas** — **The cross-platform GPU-accelerated painting and photo editing app.** **Free, open-source, GPU-accelerated** with **wgpu** (Rust-native WebGPU), targeting **120+ frames per second with brushes thousands of pixels wide** . **Available on Linux, Windows, macOS, iPad, Android, and the web** — one app across all platforms . **Three workspaces**: **Sketch** (tribute to Procreate's roots), **Paint** (simulated physical media for illustration), and **Photo** (wide-gamut HDR editing) . **Brush engine includes** pencil, charcoal, ink, bristle, watercolor, oil, and airbrush with pressure/tilt, paper grain, and color mixing . **Layers** with groups, clipping layers, masks, blend modes, editable fills, and selection layers . **Effects** via linked non-destructive chains, adjustment layers, and effect masks . **Color**: sRGB, Display P3, Adobe RGB, ProPhoto RGB, ICC profiles, 8/16-bit SDR, and 16/32-bit float HDR . **The honest caveat**: **in active development** — evaluate stability and mobile feature parity before committing a production workflow . **Best for artists** wanting a modern, GPU-native open-source Procreate alternative that runs on multiple platforms.

### Additional Strong Open-Source Options

- **Fossify Paint** — **The privacy-focused Android drawing app.** **Open-source, available on F-Droid**, with brush size/color customization, canvas background options, and **PNG, JPG, and SVG export** . **Works completely offline** with no intrusive permissions . **The honest caveat**: **raster-first** — SVG export is supported but the drawing model is pixel-based, not true vector path editing . **Best for simple doodling and sketching** on Android with privacy in mind .

- **Pocket Paint** — **The lightweight Android painting app.** Open-source, available on F-Droid, with a simple interface for basic drawing and painting tasks . **Best for quick sketches** on Android without ads or subscriptions.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Mobile raster editors differ significantly in platform support, touch optimization, and feature depth. **Procreate remains the most polished iPad painting experience** but is iPad-only and closed-source . **Krita for Android brings desktop-class tools to tablets** but is **still beta** with an interface that was not designed for mobile screens — it works best on larger tablets with 4GB+ RAM . **Capy Canvas is actively developed** with a GPU-native engine and cross-platform ambitions, but mobile stability should be verified . **MediBang Paint is free and cross-platform** with PSD/CMYK support, but premium brushes require ads or subscription . **The choice often comes down to platform**: iPad users have Procreate and Photoshop, Android tablet users have Krita (with caveats) and Capy Canvas (when stable), and casual Android users have Fossify Paint for simple sketching.
- Self-hosted open-source solutions require proper app installation from F-Droid, GitHub releases, or the Play Store (for Krita), and awareness that mobile painting apps are limited by available RAM (4GB+ recommended for Krita) and screen size compared to desktop tools.

---

**Made for mobile artists, illustrators, and developers choosing raster editing tools that match their tablet platform and painting workflow.**
Let's make mobile raster graphics editing more open, GPU-native, and touch-optimized.
