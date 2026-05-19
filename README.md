# Awesome VLSI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome VLSI (Very Large Scale Integration) resources, tools, tutorials, and projects for chip design and verification.

## Contents

- [Learning Resources](#learning-resources)
- [Open Source EDA Tools](#open-source-eda-tools)
- [HDL Languages](#hdl-languages)
- [Simulation & Verification](#simulation--verification)
- [Synthesis Tools](#synthesis-tools)
- [Physical Design](#physical-design)
- [Open Source PDKs](#open-source-pdks)
- [IP Cores & Libraries](#ip-cores--libraries)
- [FPGA Tools](#fpga-tools)
- [Books](#books)
- [Online Courses](#online-courses)
- [YouTube Channels](#youtube-channels)
- [Blogs & Websites](#blogs--websites)
- [Communities](#communities)
- [Conferences & Journals](#conferences--journals)
- [Projects & Chips](#projects--chips)

---

## Learning Resources

### Tutorials & Documentation
- [Nand2Tetris](https://www.nand2tetris.org/) - Build a computer from scratch
- [ASIC World](http://www.asic-world.com/) - Verilog, SystemVerilog, and VLSI tutorials
- [ChipDev](https://chipdev.io/) - Open-source chip development tutorials
- [VSDOpen](https://www.vlsisystemdesign.com/) - Free VLSI courses and tutorials
- [OpenLane Documentation](https://openlane.readthedocs.io/) - Complete RTL to GDSII flow

### University Courses
- [MIT 6.004 - Computation Structures](https://6004.mit.edu/)
- [Berkeley EECS151/251A - FPGA Lab](https://inst.eecs.berkeley.edu/~eecs151/)
- [Stanford EE271 - Introduction to VLSI Systems](https://web.stanford.edu/class/ee271/)

---

## Open Source EDA Tools

### Complete Flows
- [OpenLane](https://github.com/The-OpenROAD-Project/OpenLane) - Automated RTL to GDSII flow
- [OpenROAD](https://github.com/The-OpenROAD-Project/OpenROAD) - RTL-to-GDSII platform
- [EDALIZE](https://github.com/olofk/edalize) - Python library for interfacing EDA tools
- [Silicon Compiler](https://github.com/siliconcompiler/siliconcompiler) - Modular hardware compilation framework

### Layout Tools
- [Magic](http://opencircuitdesign.com/magic/) - VLSI layout tool
- [KLayout](https://www.klayout.de/) - Layout viewer and editor
- [GDSFactory](https://github.com/gdsfactory/gdsfactory) - Python library for generating GDS layouts

### Schematic Capture
- [Xschem](https://github.com/StefanSchippers/xschem) - Schematic capture and netlisting
- [SKiDL](https://github.com/devbisme/skidl) - Python-based schematic design

---

## HDL Languages

### Verilog/SystemVerilog
- [Verilog-Mode](https://www.veripool.org/verilog-mode/) - Emacs mode for Verilog
- [SystemVerilog.io](https://www.systemverilog.io/) - SystemVerilog resources
- [sv-tests](https://github.com/chipsalliance/sv-tests) - SystemVerilog compliance tests

### Modern HDLs
- [Chisel](https://github.com/chipsalliance/chisel) - Scala-based HDL
- [SpinalHDL](https://github.com/SpinalHDL/SpinalHDL) - Scala-based HDL
- [MyHDL](https://github.com/myhdl/myhdl) - Python-based HDL
- [Amaranth](https://github.com/amaranth-lang/amaranth) - Python-based HDL (formerly nMigen)
- [PyRTL](https://github.com/UCSBarchlab/PyRTL) - Python-based RTL design
- [nMigen](https://github.com/nmigen/nmigen) - Python-based HDL
- [Bluespec](https://github.com/B-Lang-org/bsc) - High-level HDL

### VHDL
- [GHDL](https://github.com/ghdl/ghdl) - Open-source VHDL simulator
- [VUnit](https://github.com/VUnit/vunit) - Unit testing framework for VHDL

---

## Simulation & Verification

### Simulators
- [Verilator](https://github.com/verilator/verilator) - Fast Verilog/SystemVerilog simulator
- [Icarus Verilog](https://github.com/steveicarus/iverilog) - Verilog simulation and synthesis
- [GHDL](https://github.com/ghdl/ghdl) - VHDL simulator
- [Questa](https://eda.sw.siemens.com/en-US/ic/questa/) - Commercial simulator (free starter edition)

### Waveform Viewers
- [GTKWave](http://gtkwave.sourceforge.net/) - Waveform viewer
- [Surfer](https://gitlab.com/surfer-project/surfer) - Modern waveform viewer
- [WaveTrace](https://github.com/Waveform-Analytics/wavetrace) - Web-based waveform viewer

### Verification Tools
- [cocotb](https://github.com/cocotb/cocotb) - Python-based verification framework
- [PyUVM](https://github.com/pyuvm/pyuvm) - UVM in Python
- [SVUnit](https://github.com/tudortimi/svunit) - Unit testing for SystemVerilog
- [riscv-dv](https://github.com/chipsalliance/riscv-dv) - RISC-V verification framework
- [Formal Verification with SymbiYosys](https://github.com/YosysHQ/sby) - Formal verification frontend

---

## Synthesis Tools

- [Yosys](https://github.com/YosysHQ/yosys) - Open-source synthesis suite
- [ABC](https://github.com/berkeley-abc/abc) - Logic synthesis and verification
- [LSOracle](https://github.com/lnis-uofu/LSOracle) - Logic synthesis and optimization

---

## Physical Design

### Place & Route
- [OpenROAD](https://github.com/The-OpenROAD-Project/OpenROAD) - Complete PnR solution
- [Innovus/Genus](https://www.cadence.com/) - Commercial tools (education programs available)
- [nextpnr](https://github.com/YosysHQ/nextpnr) - FPGA place and route

### Static Timing Analysis
- [OpenSTA](https://github.com/The-OpenROAD-Project/OpenSTA) - Static timing analyzer
- [OpenTimer](https://github.com/OpenTimer/OpenTimer) - High-performance timing analysis

### DRC/LVS
- [Magic DRC](http://opencircuitdesign.com/magic/) - Design rule checking
- [Netgen](http://opencircuitdesign.com/netgen/) - LVS tool
- [KLayout DRC](https://www.klayout.de/) - DRC capabilities

### Parasitic Extraction
- [Magic Extract](http://opencircuitdesign.com/magic/) - Parasitic extraction
- [FasterCap](https://www.fastfieldsolvers.com/fastercap.htm) - Capacitance extraction

---

## Open Source PDKs

- [SkyWater 130nm PDK](https://github.com/google/skywater-pdk) - Google + SkyWater open PDK
- [GF180MCU](https://github.com/google/gf180mcu-pdk) - GlobalFoundries 180nm PDK
- [ASAP7](http://asap.asu.edu/) - 7nm predictive PDK
- [FreePDK45](https://www.eda.ncsu.edu/wiki/FreePDK45:Contents) - 45nm educational PDK
- [IHP SG13G2](https://github.com/IHP-GmbH/IHP-Open-PDK) - 130nm open PDK

---

## IP Cores & Libraries

### Processor Cores
- [RISC-V Cores](https://github.com/riscv/riscv-cores-list) - List of RISC-V cores
- [PicoRV32](https://github.com/YosysHQ/picorv32) - Small RISC-V core
- [VexRiscv](https://github.com/SpinalHDL/VexRiscv) - FPGA-friendly RISC-V core
- [Rocket Chip](https://github.com/chipsalliance/rocket-chip) - RISC-V processor generator
- [BOOM](https://github.com/riscv-boom/riscv-boom) - Out-of-order RISC-V core
- [OpenPiton](https://github.com/PrincetonUniversity/openpiton) - Manycore processor
- [OpenSPARC](https://www.oracle.com/servers/technologies/opensparc-overview.html) - SPARC processor

### Memory & Storage
- [OpenRAM](https://github.com/VLSIDA/OpenRAM) - Open-source SRAM compiler
- [Fakeram](https://github.com/Cloud-V/DFFRAM) - SRAM using flip-flops

### Peripherals & Interfaces
- [OpenCores](https://opencores.org/) - Open-source hardware IP
- [LibreCores](https://www.librecores.org/) - Community hub for free and open-source IP
- [PULP Platform](https://github.com/pulp-platform) - Parallel Ultra-Low-Power platform

### Standard Cell Libraries
- [Sky130 Standard Cells](https://github.com/google/skywater-pdk-libs-sky130_fd_sc_hd)
- [Nangate FreePDK45](http://projects.si2.org/openeda.si2.org/projects/nangatelib)

---

## FPGA Tools

### Open Source Toolchains
- [Project IceStorm](https://github.com/YosysHQ/icestorm) - Lattice iCE40 FPGA tools
- [Project Trellis](https://github.com/YosysHQ/prjtrellis) - Lattice ECP5 FPGA tools
- [Project X-Ray](https://github.com/f4pga/prjxray) - Xilinx 7-series FPGA tools
- [F4PGA](https://github.com/chipsalliance/f4pga) - FPGA toolchain (formerly SymbiFlow)

### Frameworks
- [LiteX](https://github.com/enjoy-digital/litex) - SoC builder framework
- [Migen](https://github.com/m-labs/migen) - Python-based HDL and toolbox

---

## Books

### Digital Design
- **Digital Design and Computer Architecture** - Harris & Harris
- **Digital Integrated Circuits** - Jan Rabaey
- **CMOS VLSI Design** - Weste & Harris

### Verification
- **SystemVerilog for Verification** - Chris Spear
- **Writing Testbenches** - Janick Bergeron
- **Verification Methodology Manual** - Janick Bergeron et al.

### Physical Design
- **VLSI Physical Design: From Graph Partitioning to Timing Closure** - Kahng et al.
- **Physical Design of CMOS Integrated Circuits** - John P. Uyemura

### Analog/Mixed-Signal
- **Design of Analog CMOS Integrated Circuits** - Behzad Razavi
- **Analysis and Design of Analog Integrated Circuits** - Gray & Meyer

---

## Online Courses

- [Coursera - VLSI CAD](https://www.coursera.org/specializations/vlsi-chip-design)
- [edX - Hardware Security](https://www.edx.org/learn/computer-science/university-of-maryland-college-park-hardware-security)
- [NPTEL - VLSI Design](https://nptel.ac.in/courses/117106030)
- [VSD - Physical Design](https://www.vlsisystemdesign.com/advanced-physical-design-using-openlane-sky130/)
- [Udemy - VLSI Courses](https://www.udemy.com/topic/vlsi/)

---

## YouTube Channels

- [Robert Feranec](https://www.youtube.com/user/matarofe) - PCB & Hardware design
- [Phil's Lab](https://www.youtube.com/c/PhilsLab) - Electronics & embedded
- [Zero to ASIC](https://www.youtube.com/c/ZeroToASIC) - ASIC design tutorials
- [Digital Design & Computer Architecture](https://www.youtube.com/c/SarahHarrisLectures)
- [Neso Academy](https://www.youtube.com/c/nesoacademy) - Digital electronics

---

## Blogs & Websites

- [ZipCPU](http://zipcpu.com/) - FPGA and digital design blog
- [Ken Shirriff's Blog](http://www.righto.com/) - Reverse engineering chips
- [SemiWiki](https://semiwiki.com/) - Semiconductor news and analysis
- [VLSI Expert](https://vlsi.expert/) - VLSI tutorials and interview prep
- [HDLBits](https://hdlbits.01xz.net/) - Verilog practice problems

---

## Communities

### Forums & Discussion
- [r/FPGA](https://www.reddit.com/r/FPGA/) - FPGA subreddit
- [r/ECE](https://www.reddit.com/r/ECE/) - Electrical engineering
- [EEVblog Forum](https://www.eevblog.com/forum/) - Electronics forum
- [VLSI Discord](https://discord.gg/vlsi) - VLSI Discord community

### Organizations
- [FOSSi Foundation](https://www.fossi-foundation.org/) - Free and Open Source Silicon
- [CHIPS Alliance](https://chipsalliance.org/) - Open-source hardware collaboration
- [OpenHW Group](https://www.openhwgroup.org/) - Open-source processors

---

## Conferences & Journals

### Conferences
- **DAC** - Design Automation Conference
- **ICCAD** - International Conference on Computer-Aided Design
- **ISSCC** - International Solid-State Circuits Conference
- **VLSI Symposia** - VLSI Technology and Circuits
- **DATE** - Design, Automation & Test in Europe
- **ASPDAC** - Asia and South Pacific Design Automation Conference

### Journals
- **IEEE Transactions on VLSI Systems**
- **IEEE Transactions on CAD**
- **IEEE Journal of Solid-State Circuits**
- **ACM Transactions on Design Automation**

---

## Projects & Chips

### Taped Out Chips
- [Google/efabless Open MPW Shuttle](https://efabless.com/open_shuttle_program) - Free tapeout program
- [TinyTapeout](https://tinytapeout.com/) - Educational ASIC project
- [Zero to ASIC Course](https://zerotoasiccourse.com/) - Learn ASIC design with tapeout

### Notable Open-Source Chips
- [OpenTitan](https://opentitan.org/) - Open-source secure microcontroller
- [Libre-SOC](https://libre-soc.org/) - Libre System-on-Chip
- [BlackParrot](https://github.com/black-parrot/black-parrot) - Linux-capable RISC-V multicore
- [PULP](https://github.com/pulp-platform/pulp) - Ultra-low-power parallel platform

---

## Contributing

Contributions welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)
