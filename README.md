# Starlancer Mod Tools

A preservation mirror of community modding tools for **Starlancer** (Digital Anvil / Microsoft, 2000) — the space-combat sim set in the same universe as *Freelancer*. Original tools were gathered from [download.wcnews.com/files/starlancer/](https://download.wcnews.com/files/starlancer/).

These tools are 24+ years old, written for Windows 95/98/2000/XP. Many work fine on modern Windows, but expect to use compatibility mode, run in a VM, or run installers under Wine for the InstallShield-packaged ones. None of these were made by me — see [Credits](#credits).

---

## Tools

### Save-game editors

| File | Tool / Version | Author |
|---|---|---|
| [`sse.zip`](sse.zip) ([readme](readmes/sse.txt)) | **StarLancEdit 1.11** — edits `MYGAME*.IFF` save files | Raidersoft Technologies |
| [`SSGEdt.zip`](SSGEdt.zip) ([readme](readmes/SSGEdt.txt)) | **StarLancer Saved Game Editor 1.0** — edits callsign, kills, rank, level, mission, difficulty in saves & multiplayer profiles | Twister (Twisted Media) |

### Level / ship / stat editors

| File | Tool / Version | Author |
|---|---|---|
| [`SLEDIT2Beta.zip`](SLEDIT2Beta.zip) | **SLEdit 2.0 Beta** — full InstallShield installer (ship swap, stat editing, HOG editor) | Dustin |
| [`sledit_2_1beta.zip`](sledit_2_1beta.zip) | **SLEdit 2.1 Beta** — updated `SLEdit.exe` only | Dustin |
| [`sledit2_16.zip`](sledit2_16.zip) ([readme](readmes/sledit2_16.txt)) | **SLEdit 2.16** — final patch release (drops into an existing SLEdit install) | Dustin |
| [`sltool14.zip`](sltool14.zip) ([info](readmes/sltool14_basic_info.txt), [new](readmes/sltool14_new_info.txt), [whatsnew](readmes/sltool14_whatsnew.txt)) | **SL Tool 1.4** — SHP model viewer + attachment editor (engine flames, hardpoints) | Mario "HCl" Brito |
| [`hexcheat.zip`](hexcheat.zip) ([readme](readmes/hexcheat.txt)) | **Hex-edited stat files** — pre-modded `SHIPSTATS.BIN` / `GUNSTATS.BIN` / `MISSILESTATS.BIN`, drop-in (not a tool, modded content) | Userunfriendly |

### HOG archive tools

| File | Tool / Version | Author |
|---|---|---|
| [`slextract.zip`](slextract.zip) ([readme](readmes/slextract.txt)) | **SLExtract** — extracts files from Starlancer's `.HOG` archives (binary) | DraconPern & KingLord |
| [`slextractSC.zip`](slextractSC.zip) ([readme](readmes/slextractSC.txt)) | **SLExtract source code** — Visual C++ 6 / MFC source | DraconPern & KingLord |

### 3D model converters / plugins

| File | Tool / Version | Author |
|---|---|---|
| [`lwo2sl.zip`](lwo2sl.zip) ([readme](readmes/lwo2sl.txt)) | **LWO2SL** — LightWave Object → Starlancer SHP converter (DOS) | Mario "HCl" Brito |
| [`milkshape_shp_plugin.zip`](milkshape_shp_plugin.zip) ([readme](readmes/milkshape_shp_importer.txt)) | **MilkShape SHP Importer** — import Starlancer ships into MilkShape 1.4.5+ | Mario "HCl" Brito |
| [`ms_shp_exporter.zip`](ms_shp_exporter.zip) ([readme](readmes/ms_shp_exporter.txt)) | **MilkShape SHP Exporter** — export MilkShape models to SHP (supports material effects, translucency, etc.) | Mario "HCl" Brito |

---

## Credits

All tools, plugins, and modded files in this repository were created by their respective authors:

- **Dustin** — SLEdit (all versions)
- **Mario "HCl" Brito** — SL Tool, LWO2SL, MilkShape SHP Importer/Exporter
- **DraconPern & KingLord** — SLExtract (binary and source)
- **Raidersoft Technologies** — StarLancEdit (SSE)
- **Twister / Twisted Media** — StarLancer Saved Game Editor (SSGEdt)
- **Userunfriendly** — hex-edited stat files

If you are an author and want your work removed (or want attribution corrected), please open an issue.

## Source & disclaimer

Original distribution: [download.wcnews.com/files/starlancer/](https://download.wcnews.com/files/starlancer/).

This is a **preservation mirror**. I did not write any of the tools or content in this repository and claim no ownership over them. The `LICENSE` file (Unlicense) applies only to this repository's curation, README, and structure — **not** to the contents of the archived zip files, which remain under whatever terms their original authors specified (typically freeware, see each readme).

Original archives in `*.zip` are preserved bit-for-bit. Plain-text readme excerpts in [`readmes/`](readmes/) are extracted verbatim from those archives so you can preview a tool without downloading it.
