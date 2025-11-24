# S2IBISpy v2.1.0 — The world’s easiest open-source IBIS generator with GUI

**Double-click → perfect IBIS model + correlation in seconds.**  


Download S2IBISpy.exe (Windows 64-bit) — only **43 MB**  
[Download v2.1.0](https://github.com/simon9721/s2ibispy_exe/S2IBISpy.exe)

Source code & development: https://github.com/simon9721/s2ibispy

---

## 60-Second Quick Start

1. Run `S2IBISpy.exe` → opens on **Input & Settings** tab
2. Click **Input File** → choose any `.s2i` file (example included!)
3. Choose **Output directory**
4. Go to **Simulation** tab → click **Start Conversion**
5. Wait 5–30 seconds → Done!

You instantly get:
- Valid `.ibs` file
- Full model & pin preview
- Waveform plots
- SPICE vs IBIS correlation

---

## Complete Tab Guide

| Tab | Purpose | What happens when you use it |
|-----|-------|--------------------------------|
| **Input & Settings** | Starting point | Load `.s2i` file → **Models** and **Pins** tabs instantly show your buffer configuration for validation |
| **Models** | Preview IBIS models | Shows all [Model] definitions from your `.s2i` — instantly on load |
| **Pins** | Validate pin mapping | Full pin list with model assignments — perfect for checking correctness |
| **Simulation** | Run the conversion | One big **Start Conversion** button + live log and progress |
| **IBIS Viewer** | View generated file | Clean, navigable view of your final `.ibs` file with one-click section jump |
| **Plots** | Classic IBIS curves | V-I, V-t, rising/falling waveforms (some visual glitches — data is correct) |
| **Correlation** | SPICE vs IBIS overlay | Visual comparison waveforms — **only for I/O and 3-state models** (others skipped) |

---

## Included Example

`examples/io_buf/` contains everything:
- `io_buf.s2i` — ready-to-run input
- `hspice.mod` — original model file
- `io_buf.sp` — flat SPICE netlist

Just load `io_buf.s2i` → go to **Simulation** tab → click **Start Conversion** → see the full flow instantly.

---

## Current Features

- Zero installation — single 43 MB .exe
- Instant model/pin preview when loading `.s2i`
- Full s2ibis3 engine under the hood
- Automatic flat-netlist → subcircuit wrapping
- Built-in **IBIS Viewer** with section navigation
- **Plots** tab with classic IBIS curves
- **Correlation** tab with SPICE vs IBIS overlays (I/O models only)
- Dark, eye-friendly interface

---

## Work-in-Progress / Known Issues

| Feature | Status |
|-------|--------|
| V-I / V-t curve rendering in Plots tab | Minor visual glitches (data is correct) |
| Correlation for non-I/O models | Only I/O & 3-state supported (others safely skipped) |
| Full FAQ / troubleshooting guide | Under construction — contributions welcome! |

We’re actively improving — your feedback makes it better.
**Please send feedback to:** sh3qm@mst.edu (or GitHub Issues)

---

## License

MIT License  


---
