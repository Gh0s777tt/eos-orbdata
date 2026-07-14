# eos-orbdata

**E-OS fork of [`redox-os/orbdata`](https://gitlab.redox-os.org/redox-os/orbdata).** Part of the [**E-OS**](https://github.com/Gh0s777tt/E-OS) ecosystem — a hardened, Crimson-branded downstream of [Redox OS](https://www.redox-os.org).

This repository is **Orbital data / assets** (icons, wallpapers, UI art).

## E-OS changes vs upstream

- E-OS **branding assets** — the crimson greeter background, login art, and diamond-E start icon.

## How it's pinned

The E-OS build pins this fork in [`recipes/gui/orbdata/recipe.toml`](https://github.com/Gh0s777tt/E-OS/blob/main/recipes/gui/orbdata/recipe.toml):

- branch **`master`** · rev **`27131a5326b4`**
- up to date with upstream

## Build standalone

This fork is normally built by the E-OS cookbook (`make CI=1 …` in the [main repo](https://github.com/Gh0s777tt/E-OS)). To build it on its own you need the Redox toolchain; see the main repo's [build guide](https://github.com/Gh0s777tt/E-OS/blob/main/docs/building.md).

## Hosting

**GitLab (source of truth):** https://gitlab.com/e-os/eos-orbdata  
**GitHub (read-only mirror):** https://github.com/Gh0s777tt/eos-orbdata

## License

MIT (inherited from upstream Redox). The E-OS project as a whole is AGPL-3.0; see the [main repo](https://github.com/Gh0s777tt/E-OS/blob/main/LICENSE).

---
[E-OS main repo](https://github.com/Gh0s777tt/E-OS) · [Docs](https://github.com/Gh0s777tt/E-OS/tree/main/docs) · [Upstream](https://gitlab.redox-os.org/redox-os/orbdata)
