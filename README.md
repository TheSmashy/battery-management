# Battery Management for Flashlights

This is my personal battery management system for high-drain lithium-ion cells used in flashlights. It covers tracking, charging, maintenance, storage, and safety protocols—especially for 18350 and 18650 cells used in EDC, shorty builds, and high-output hosts.

---

## Battery Inventory & Tracking

- **Spreadsheet-based**:
  - Each cell tracked by serial, chemistry, purchase date, and internal resistance (IR)
  - Cycle count updated per charge
  - Log includes host use and recharge history
- **Cell performance notes**:
  - IR deltas tracked to spot degradation
  - A11s vs M11 v2s vs 30Qs compared

---

## Host-to-Cell Mapping

- **Mapping sheet**:
  - Each host assigned a cell ID
  - Includes driver specs (e.g., 7135×8, Buck 5A) and emitter type
- **Cycle tracking on hosts**:
  - Every full recharge adds to the host cycle counter

---

## Charging & Cleaning Protocol

- **Charger**: XTAR VC4SL
- **Setup**:
  - Terminals cleaned with 99% IPA when needed
  - Microfiber wipe of contacts before IR test
- **Notes**:
  - XTAR IR can be flaky—prep helps reduce misreads
  - Use a high quality 18W QC3.0 charger
  - Use a high quality USB C cable (included cable has damaged units)

---

## Maintenance Routine

- **Quarterly** "Check Cells" task:
  - Full inspection of stockpile
  - Rotation of stored cells to keep IR in range
- **Storage mode**:
  - Long-term cells set to ~3.7–3.8V and stored in dry containers with silica packets
  - Each cell stored in a case or host

---

## Runtime & Performance

- Notes and expected runtime for Group 10 UI (1%-10%-35%-100%)
- Heat and voltage sag tracked for 5A+ lights
- Turbo modes noted as burst-only for thermal and longevity reasons

---

## Safety Considerations

- Never exceed CDR of cell vs light draw
- Always use trusted brands (Samsung, Vapcell, LG)
- Spare cells carried in plastic cases

---

## License

Licensed under the Creative Commons Attribution-ShareAlike 4.0 International License (CC BY-SA 4.0).

You are free to:
- Share — copy and redistribute the material in any medium or format
- Adapt — remix, transform, and build upon the material for any purpose, even commercially

Under the following terms:
- **Attribution** — You must give appropriate credit
- **ShareAlike** — If you remix, transform, or build upon the material, you must distribute your contributions under the same license

More details: [https://creativecommons.org/licenses/by-sa/4.0/](https://creativecommons.org/licenses/by-sa/4.0/)
