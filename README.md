# BlinkenSand
A GPU born from silence — forged in Verilog, rising from grains of sand to glow with pixels.


It begins with sand and ends in pixels — logic born of silence, etched in code, and lit by purpose.

> _“From the dust of silicon, a dream of light.”_

---

## Overview

BlinkenSand is an open-source experimental GPU architecture — minimal, modular, and silicon-ready.  
It is built from the ground up with no abstraction layers, no bloated drivers — just pure hardware and handcrafted logic.

---

## Goals

- [ ] **Framebuffer** core in BRAM
- [ ] **Raster engine** (draw pixels, lines, rectangles)
- [ ] **Basic VGA/HDMI** video output (e.g., 640x480 @ 60Hz)
- [ ] **Simple bus/register interface** for external CPU/MCU control
- [ ] **Sprite engine** (for 2D graphics)
- [ ] Optional: **Shader simulation** using minimal ALU logic
- [ ] Long term: **FPGA and ASIC-ready IP core**

---

## Project Structure

```

BlinkenSand/
├── rtl/             # Verilog HDL files
│   ├── framebuffer.v
│   ├── vga\_driver.v
│   └── raster\_engine.v
├── sim/             # Simulation testbenches
│   ├── framebuffer\_tb.v
│   └── waveforms/
├── docs/            # Design notes, diagrams, specs
├── vlsi/            # Schematic, layout, and ASIC work (planned)
├── LICENSE
└── README.md

````

----

## Tools Used

| Purpose        | Tool(s)                                               |
|----------------|-------------------------------------------------------|
| Simulation     | **Icarus Verilog**, **Verilator**, **GTKWave**        |
| Synthesis      | **Yosys**, **NextPNR**                                |
| Layout/VLSI    | **KLayout**, **Magic VLSI**, **OpenLane** *(planned)* |
| Documentation  | **Markdown**, **LaTeX**                               |
| Diagrams       | **Draw.io**, **Inkscape**                             |
| PCB/Board sim  | **KiCad**, **LibrePCB**                               |

----

## Philosophy

No legacy stacks. No middleware. No “hello world” excuses.
**BlinkenSand** is a resurrection of the early spirit of computing — where builders created their own light, bit by bit.

* From Verilog to silicon
* From ideas to waveforms
* From sand to light


## Author

Made with grit and glow by **Kartik**
If you want to license BlinkenSand for commercial use, contact me via GitHub or LinkedIn.

---

## Future Directions

* [ ] Bus-compatible IP core with Wishbone/AHB-Lite interface
* [ ] Python simulator for algorithm modeling
* [ ] Open-source FPGA board support
* [ ] ASIC tapeout via TinyTapeout or OpenLane
* [ ] Add a real-time debug interface over UART or SPI

---

**Follow the glow. Build from silence. BlinkenSand.**

```

````

---

<div align="center" style="padding: 1em; background-color: #f3f3f3; border: 1px solid #ccc; border-radius: 10px; font-family: monospace; color: #333;">

<i>
I didn’t build this to impress anyone. <br>
I built it because something inside me needed to speak — <br>
in gates, in glow, in silence. <br><br>

<strong>BlinkenSand</strong> is not a product. <br>
It’s a statement. <br>
A return to the raw. To the sand beneath the silicon. <br><br>

No bloat, no noise — just pure logic wired with intention. <br>
If it lights up, it’s not just a display. <br>
It’s proof that I was here. <br><br>

— <b>Kartik</b><br>
<code>Bare hands. Bare Verilog. Bare soul.</code>
</i>

</div>

---

