<a name="top"></a>
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E50914,100:0B0B0B&height=200&section=header&text=eos-orbdata&fontSize=70&fontColor=ffffff&fontAlignY=38&desc=Red%20%26%20black%20branding%20assets%20for%20E-OS&descAlignY=60&descSize=18&animation=fadeIn" alt="eos-orbdata"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=900&color=E50914&center=true&vCenter=true&width=760&lines=Fonts%2C+icons%2C+wallpaper+%26+UI+assets+for+E-OS;Red%2Fblack+login+greeter+%26+launcher+icon;Branding+fork+of+redox-os%2Forbdata" alt="tagline"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/license-MIT-E50914?style=for-the-badge&labelColor=0B0B0B" alt="MIT"/>
  <img src="https://img.shields.io/badge/part%20of-E--OS-E50914?style=for-the-badge&labelColor=0B0B0B" alt="part of E-OS"/>
  <img src="https://img.shields.io/badge/upstream-redox--os%2Forbdata-E50914?style=for-the-badge&labelColor=0B0B0B" alt="upstream"/>
  <img src="https://img.shields.io/badge/type-assets%20%2F%20data-E50914?style=for-the-badge&labelColor=0B0B0B" alt="assets"/>
</p>

<p align="center">
  <a href="#-what-is-this">What</a> ·
  <a href="#-contents">Contents</a> ·
  <a href="#%EF%B8%8F-how-its-used">Usage</a> ·
  <a href="#-credits--license">License</a>
</p>

<p align="center"><img src="https://raw.githubusercontent.com/Gh0s777tt/Gh0s777tt/main/assets/divider.svg" width="100%" alt=""/></p>

## 🎨 What is this?

`eos-orbdata` holds the **branding and shared desktop data** for [**E-OS**](https://github.com/Gh0s777tt/E-OS) — the red/black look of the system: the **login greeter wallpaper**, the **launcher icon**, application & mime icons, and the bundled **Fira** font family.

It is a downstream **branding fork** of [`redox-os/orbdata`](https://gitlab.redox-os.org/redox-os/orbdata) (MIT), re-skinned to the Ghost Empire **deep-black + Netflix-red** identity used across E-OS.

## 📦 Contents

| Path | What it holds |
|---|---|
| `usr/share/fonts/` | Fira **Sans** & **Mono** (Regular / Bold / SemiBold) — the E-OS system fonts |
| `usr/share/icons/apps/` | Application icons (terminal, files, calculator, browser, …) |
| `usr/share/icons/actions/` · `mimetypes/` | Action & file-type icons |
| `usr/share/ui/` | Wallpaper, login background and UI chrome (red/black) |
| `usr/share/applications/` | `.desktop` entries & mime associations |

## 🛠️ How it's used

This repository is consumed by the **E-OS build** as the `orbdata` recipe. The Orbital compositor and the login greeter read these assets at build time and pack them into the E-OS image — which is why swapping a wallpaper or icon here re-skins the booted system.

```bash
# Pulled in automatically by the E-OS build.
# Full system build lives in the main project:
#   https://github.com/Gh0s777tt/E-OS
```

## 🎯 Branding

Everything follows the E-OS palette — **`#E50914`** (Netflix-red) on **`#0B0B0B`** (deep black). The login greeter, wallpaper and launcher icon are all built from these assets.

## 📄 Credits & License

- Upstream: [`redox-os/orbdata`](https://gitlab.redox-os.org/redox-os/orbdata) — **MIT**.
- This fork is likewise **MIT**. Bundled third-party assets keep their original licenses — e.g. the **Fira** fonts (`usr/share/fonts/**/License.txt`, SIL OFL) and the icon set (`usr/share/icons/LICENSE`).

<p align="center"><img src="https://raw.githubusercontent.com/Gh0s777tt/Gh0s777tt/main/assets/divider.svg" width="100%" alt=""/></p>

<div align="center">

### 🩸 Part of the **GHOST EMPIRE** ecosystem

[**E-OS**](https://github.com/Gh0s777tt/E-OS) · Rust microkernel OS &nbsp;·&nbsp; Minecraft infrastructure suite &nbsp;·&nbsp; Discord &amp; streaming platforms — forged under **Empire Forge**.

<a href="https://discord.gg/Egf88V9UdH"><img src="https://img.shields.io/badge/Discord-Join%20the%20Empire-5865F2?style=for-the-badge&logo=discord&logoColor=white&labelColor=0B0B0B" alt="discord"/></a>
<a href="mailto:ghostt77@empire-forge.com"><img src="https://img.shields.io/badge/Email-Empire%20Forge-E50914?style=for-the-badge&logo=maildotru&logoColor=white&labelColor=0B0B0B" alt="email"/></a>
<a href="https://donatr.ee/ghost77/"><img src="https://img.shields.io/badge/%E2%9D%A4%20Support-Donate-E50914?style=for-the-badge&labelColor=0B0B0B" alt="donate"/></a>

<sub><i>Black. Red. Production-grade. — © GHOST EMPIRE · Empire Forge</i></sub>

<a href="#top">▲ back to top</a>

</div>
