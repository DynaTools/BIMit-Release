[Italiano](README.md) · [Português](README.pt.md) · **English**

# BIMit — plugin for Autodesk Revit

[![Latest version](https://img.shields.io/github/v/release/DynaTools/BIMit-Release?label=version)](https://github.com/DynaTools/BIMit-Release/releases/latest)
![Revit 2022–2026](https://img.shields.io/badge/Revit-2022%E2%80%932026-0696D7)
![Windows 10 | 11](https://img.shields.io/badge/Windows-10%20%7C%2011-555)

BIMit assigns the **WBS** to the elements of your model, exports **sheets and views** in every format
in one go and adds the tools Revit is missing for **parameters**, the **model** and **MEP** systems.
With **Claude (MCP)** you can also ask Claude to do it for you, in plain English.

BIMit is free during the **beta**.

**[Download the latest version (MSI)](https://github.com/DynaTools/BIMit-Release/releases/latest)** ·
[Guide](https://unibim.io/en/bimit/guide/) · [unibim.io/en/bimit](https://unibim.io/en/bimit/)

## What it does

| Tool | What it does |
|---|---|
| **WBS** | Start from the standard WBS or from your own structure, set the parameters once for the whole project, change only what each category needs, check the preview and write to the model. |
| **Export sheets and views** | PDF, DWG, DGN, DWF, NWC, IFC and images in one go: paper size from the title block, file names from parameters, only new sheets or sheets with a changed revision, queue, report, scheduled exports, drawing list in Excel, profiles to share with your team. |
| **Parameters** | Add shared parameters to all the categories you choose, find and delete empty or unused project parameters, remove the parameters you don't need from loaded families. |
| **Model** | Unpin pinned elements category by category, move a level together with everything that depends on it, export the model to CSV tables for an AI assistant. |
| **MEP** | Sleeves and openings where systems cross walls, floors, beams and other elements; space separation lines from the room boundaries of a linked model. |
| **Claude (MCP)** | Connect Claude with your own account: it uses every BIMit tool on the open model, even across several Revit sessions open at the same time. Every change can be undone with Ctrl+Z. |

## Requirements

- Windows 10 or 11
- Autodesk Revit 2022, 2023, 2024, 2025 or 2026
- A BIMit account, which you create from the plugin the first time you start it

## Installation

1. Close Revit.
2. Download `BIMit_Setup_<version>.msi` from the [latest release](https://github.com/DynaTools/BIMit-Release/releases/latest).
3. Double-click it. **No administrator rights needed**: BIMit installs for your user, into every
   Revit version on the computer.
4. Open Revit: you'll find the **BIMit** tab.

### Digitally signed installer

The installer is signed with a **Certum** code-signing certificate issued to
**GIAVONI PAULO AUGUSTO**. To check it: right-click the `.msi` file → *Properties* →
*Digital Signatures*. If Windows SmartScreen shows a warning, check that the publisher is
GIAVONI PAULO AUGUSTO and choose *More info* → *Run anyway*.

## Updates

Automatic: BIMit downloads the new version, verifies its integrity and installs it when you close Revit.

## Uninstall

*Windows Settings* → *Apps* → *Installed apps* → **BIMit** → *Uninstall*.
To also delete your account and data: in Revit, *BIMit* → *Account* → *Delete account*.

## Guide and documents

| | Italiano | Português | English |
|---|---|---|---|
| Guide | [Guida](https://unibim.io/it/bimit/guida/) | [Guia](https://unibim.io/pt/bimit/guia/) | [Guide](https://unibim.io/en/bimit/guide/) |
| Privacy | [Informativa privacy](https://unibim.io/it/bimit/privacy/) | [Privacidade](https://unibim.io/pt/bimit/privacidade/) | [Privacy](https://unibim.io/en/bimit/privacy/) |
| Terms | [Termini d'uso](https://unibim.io/it/bimit/termini/) | [Termos de uso](https://unibim.io/pt/bimit/termos/) | [Terms of use](https://unibim.io/en/bimit/terms/) |

The guide also opens from the **Guide** button in every plugin window, at the right section.

## Support

- In the plugin: the **Feedback** button at the top of every window.
- Email: paulo.giavoni@gmail.com

---

© DynaTools · Autodesk and Revit are registered trademarks of Autodesk, Inc. BIMit is not affiliated
with or endorsed by Autodesk.
