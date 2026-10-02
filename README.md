# RAM2GS (GW4201D) - 8MB Apple IIGS Expansion Card

This repository is a modified fork of the Garrett's Workshop **RAM2GS (GW4201D)** Apple IIGS RAM expansion card.

* **Original Hardware Design:** Zane Kaminski and Garrett Fellers ([Garrett's Workshop](https://github.com/garrettsworkshop))
* **Modifications & Production Preparation:** Chuntak Kwan ([svretrogames](https://github.com/svretrogames))

Both original and modified works are licensed under **Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)**.

---

## Modifications in This Fork

* **Garrett's Workshop Logo Removal:** Removed Garrett's Workshop branding and logos from all PCB silkscreen layers.
* **Licensing Attribution:** Added Creative Commons BY-SA 4.0 attribution markings to the back silkscreen of all PCBs.
* **Makefile Updates:** Updated the top-level `Makefile` for compatibility with Linux build environments and KiCad command-line tools (`kicad-cli`).
* **Generated Files Removal:** Remove gerber and documentation files from source.

---

## Prerequisites & Dependencies

This repository depends on shared KiCad symbol and footprint libraries maintained by Garrett's Workshop (`GW_Parts` and `stdpads`).

To successfully build manufacturing artifacts, clone both dependency repositories into the **same parent directory** alongside this project:

```text
workspace/
├── GW_Parts/
├── stdpads/
└── RAM2GS/

