# Awesome VLSI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome VLSI (Very Large Scale Integration) resources, tools, tutorials, and projects for chip design and verification.

## Contents

- [Learning Resources](#learning-resources)
- [Open Source EDA Tools](#open-source-eda-tools)
- [HDL Languages](#hdl-languages)
- [Simulation & Verification](#simulation--verification)
- [Synthesis Tools](#synthesis-tools)
- [Physical Design](#physical-design)
- [Power Analysis & Optimization](#power-analysis--optimization)
- [Test & Debug](#test--debug)
- [AI/ML for Chip Design](#aiml-for-chip-design)
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
- [ChipDev](https://chipdev.io/) - Chip development tutorials
- [OpenLane Documentation](https://openlane.readthedocs.io/) - Complete RTL to GDSII flow
- [HDL Bits](https://hdlbits.01xz.net/) - Interactive Verilog/SystemVerilog practice problems

### University Courses
- [MIT 6.004 - Computation Structures](https://6004.mit.edu/)
- [Berkeley EECS151/251A - FPGA Lab](https://inst.eecs.berkeley.edu/~eecs151/)
- [Stanford EE271 - Introduction to VLSI Systems](https://web.stanford.edu/class/ee271/)

---

## Open Source EDA Tools

### Complete Flows
- [OpenLane](https://github.com/The-OpenROAD-Project/OpenLane) - Complete RTL-to-GDSII automated flow (most popular open-source)
- [OpenROAD](https://github.com/The-OpenROAD-Project/OpenROAD) - Modular RTL-to-GDSII framework
- [EDALIZE](https://github.com/olofk/edalize) - Universal EDA tool interface and flow coordinator
- [Silicon Compiler](https://github.com/siliconcompiler/siliconcompiler) - Modular Python-based compilation framework

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
- [Chisel](https://github.com/chipsalliance/chisel) - Scala-based HDL with advanced abstractions
- [SpinalHDL](https://github.com/SpinalHDL/SpinalHDL) - Scala HDL with hardware generation capabilities
- [MyHDL](https://github.com/myhdl/myhdl) - Python-based HDL for simulation and synthesis
- [Amaranth](https://github.com/amaranth-lang/amaranth) - Modern Python HDL (successor to nMigen)
- [PyRTL](https://github.com/UCSBarchlab/PyRTL) - Python-based RTL design and simulation
- [Bluespec](https://github.com/B-Lang-org/bsc) - High-level HDL with formal verification support
- [Migen](https://github.com/m-labs/migen) - Embedded Python HDL for FPGA design

### VHDL
- [GHDL](https://github.com/ghdl/ghdl) - Open-source VHDL simulator
- [VUnit](https://github.com/VUnit/vunit) - Unit testing framework for VHDL

---

## Simulation & Verification

### Simulators
- [Verilator](https://github.com/verilator/verilator) - Fastest open-source SystemVerilog simulator (compiles to C++)
- [Icarus Verilog](https://github.com/steveicarus/iverilog) - Verilog simulation and synthesis
- [GHDL](https://github.com/ghdl/ghdl) - VHDL simulator with good performance
- [Xsim (Free)](https://www.xilinx.com/) - Xilinx's free simulator
- [Questa (Free Edition)](https://eda.sw.siemens.com/en-US/ic/questa/) - Commercial-grade simulator with free starter edition

### Waveform Viewers
- [GTKWave](http://gtkwave.sourceforge.net/) - Fast, lightweight waveform viewer
- [Surfer](https://gitlab.com/surfer-project/surfer) - Modern waveform viewer with advanced features
- [WaveTrace](https://github.com/Waveform-Analytics/wavetrace) - Web-based waveform viewer
- [Gtkwave+](https://www.npmjs.com/package/gtkwave-js) - GTKWave JavaScript bindings

### Verification Tools
- [cocotb](https://github.com/cocotb/cocotb) - Python-based verification framework (mature & widely used)
- [PyUVM](https://github.com/pyuvm/pyuvm) - UVM methodology in Python
- [SVUnit](https://github.com/tudortimi/svunit) - Unit testing framework for SystemVerilog
- [riscv-dv](https://github.com/chipsalliance/riscv-dv) - RISC-V randomized test generator
- [Formal Verification with SymbiYosys](https://github.com/YosysHQ/sby) - Formal verification automaton tool
- [VerilatedSim](https://github.com/steveicarus/iverilog) - Co-simulation framework

---

## Synthesis Tools

- [Yosys](https://github.com/YosysHQ/yosys) - Open-source synthesis suite with Verilog/Chisel support
- [ABC](https://github.com/berkeley-abc/abc) - Sequential logic synthesis and verification
- [LSOracle](https://github.com/lnis-uofu/LSOracle) - Modular logic synthesis framework
- [nextpnr](https://github.com/YosysHQ/nextpnr) - FPGA place and route tool

---

## Physical Design

### Place & Route
- [OpenROAD](https://github.com/The-OpenROAD-Project/OpenROAD) - Complete RTL-to-GDSII placement and routing
- [Innovus/Genus](https://www.cadence.com/) - Commercial tools (free education licenses)
- [Graywolf](https://github.com/rubund/graywolf) - Classic open-source placement tool

### Static Timing Analysis
- [OpenSTA](https://github.com/The-OpenROAD-Project/OpenSTA) - Static timing analyzer
- [OpenTimer](https://github.com/OpenTimer/OpenTimer) - High-performance timing analysis

### DRC/LVS
- [Magic DRC](http://opencircuitdesign.com/magic/) - Design rule checking and correction
- [Netgen](http://opencircuitdesign.com/netgen/) - Netlist comparison and LVS
- [KLayout DRC](https://www.klayout.de/) - Full DRC and LVS capabilities
- [PyDRC](https://github.com/chipsalliance/dffram) - Python-based DRC framework

### Parasitic Extraction
- [Magic Extract](http://opencircuitdesign.com/magic/) - RC parasitic extraction from layouts
- [FasterCap](https://www.fastfieldsolvers.com/fastercap.htm) - Capacitance extraction tool
- [FastHenry](https://www.fastfieldsolvers.com/fasthenry.htm) - Inductance extraction

---

## Power Analysis & Optimization

- [OpenSTA Power Analysis](https://github.com/The-OpenROAD-Project/OpenSTA) - Integrated power reporting in STA
- [PowerKit](https://github.com/chipsalliance/Cores-SweRVolf) - Power analysis toolkit
- [DynamicIV](https://github.com/google/skywater-pdk) - Dynamic power characterization
- [Perf Estimation Tools](https://github.com/The-OpenROAD-Project/OpenROAD) - Integrated performance & power analysis
- [Low Power Design Flows](https://github.com/pulp-platform) - Ultra-low-power design methodologies

---

## Test & Debug

### Test Generation & Verification
- [OpenTest](https://github.com/chipsalliance/riscv-dv) - VLSI test pattern generation
- [RISC-V Tests](https://github.com/riscv/riscv-compliance) - Standard compliance test suites
- [Debugging Frameworks](https://github.com/pulp-platform/pulp) - Integrated debugging infrastructure

### JTAG & Debug Interfaces
- [OpenOCD](https://openocd.org/) - Open On-Chip Debugger for JTAG/SWD
- [SVD Tools](https://github.com/posborne/cmsis-svd) - System View Description tooling

---

## AI/ML for Chip Design

### ML-Based Tools & Frameworks
- [https://github.com/google/gnn-simulator](https://github.com/google/gnn-simulator) - ML accelerator design frameworks
- [Ax/BoTorch](https://github.com/facebook/Ax) - Hyperparameter optimization for EDA tools
- [RouteNet](https://github.com/THUHPC/RouteNet) - ML-based routing prediction
- [DREAMPlace](https://github.com/limbo018/DREAMPlace) - GPU-accelerated placement with deep learning
- [XGBoost for EDA](https://github.com/dmlc/xgboost) - Tree-based learning for timing prediction

### Applications of AI/ML
- Placement optimization and prediction
- Routing congestion forecasting
- Timing closure acceleration
- Power optimization
- Design space exploration

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
- [RISC-V Cores](https://github.com/riscv/riscv-cores-list) - Comprehensive list of RISC-V implementations
- [PicoRV32](https://github.com/YosysHQ/picorv32) - Minimal 32-bit RISC-V core
- [VexRiscv](https://github.com/SpinalHDL/VexRiscv) - Configurable FPGA-friendly RISC-V core
- [Rocket Chip](https://github.com/chipsalliance/rocket-chip) - Parametric RISC-V processor generator
- [BOOM](https://github.com/riscv-boom/riscv-boom) - Out-of-order superscalar RISC-V core
- [OpenPiton](https://github.com/PrincetonUniversity/openpiton) - Scalable open-source manycore platform
- [OpenSPARC](https://www.oracle.com/servers/technologies/opensparc-overview.html) - SPARC processor from Oracle

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

### Comprehensive VLSI Courses
- [Coursera - VLSI CAD](https://www.coursera.org/specializations/vlsi-chip-design) - Complete CAD flow specialization
- [NPTEL - VLSI Design](https://nptel.ac.in/courses/117106030) - Free Indian Institute course
- [VSD - Physical Design](https://www.vlsisystemdesign.com/advanced-physical-design-using-openlane-sky130/) - Advanced physical design with OpenLane

### Specialized Topics
- [edX - Hardware Security](https://www.edx.org/learn/computer-science/university-of-maryland-college-park-hardware-security) - Security-focused chip design
- [Udemy - VLSI Courses](https://www.udemy.com/topic/vlsi/) - Various beginner to advanced topics

---

## YouTube Channels

- [Robert Feranec](https://www.youtube.com/user/matarofe) - PCB design, schematic, and layout tutorials
- [Phil's Lab](https://www.youtube.com/c/PhilsLab) - Practical electronics and embedded systems
- [Zero to ASIC](https://www.youtube.com/c/ZeroToASIC) - Complete ASIC design from concept to tapeout
- [Digital Design & Computer Architecture](https://www.youtube.com/c/SarahHarrisLectures) - Fundamental design principles
- [Neso Academy](https://www.youtube.com/c/nesoacademy) - Digital electronics and logic design
- [The OpenROAD Project](https://www.youtube.com/@the_openroad_project) - Open-source EDA tools and flows

---

## Blogs & Websites

- [ZipCPU](http://zipcpu.com/) - FPGA and digital design blog
- [Ken Shirriff's Blog](http://www.righto.com/) - Reverse engineering and chip analysis
- [SemiWiki](https://semiwiki.com/) - Semiconductor industry news and analysis
- [VLSI Expert](https://vlsi.expert/) - VLSI tutorials, tips, and interview preparation

---

## Communities

### Forums & Discussion
- [r/FPGA](https://www.reddit.com/r/FPGA/) - FPGA enthusiasts subreddit
- [r/ECE](https://www.reddit.com/r/ECE/) - Electrical and computer engineering subreddit
- [EEVblog Forum](https://www.eevblog.com/forum/) - Active electronics enthusiast community
- [VLSI Discord](https://discord.gg/vlsi) - Real-time VLSI community chat
- [Hacker News](https://news.ycombinator.com/) - Tech community (many VLSI discussions)

### Organizations & Collaboratives
- [FOSSi Foundation](https://www.fossi-foundation.org/) - Free and Open Source Silicon foundation
- [CHIPS Alliance](https://chipsalliance.org/) - Open-source hardware collaboration (Google, Qualcomm, etc.)
- [OpenHW Group](https://www.openhwgroup.org/) - Open-source processor ecosystem
- [Linux Foundation](https://www.linuxfoundation.org/) - Hardware initiatives and support

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

### Tapeout & Educational Programs
- [Google/efabless Open MPW Shuttle](https://efabless.com/open_shuttle_program) - Free shuttle program for open-source chips
- [TinyTapeout](https://tinytapeout.com/) - Educational ASIC program bundling many small designs
- [Zero to ASIC Course](https://zerotoasiccourse.com/) - Comprehensive course with guaranteed tapeout
- [CIC - Carleton IC](https://www.cic.gc.ca/) - Canadian free shuttle program

### Notable Open-Source Chips
- [OpenTitan](https://opentitan.org/) - Open-source secure microcontroller (Google)
- [Libre-SOC](https://libre-soc.org/) - Fully open RISC-V System-on-Chip
- [BlackParrot](https://github.com/black-parrot/black-parrot) - Linux-capable multicore RISC-V processor
- [PULP](https://github.com/pulp-platform/pulp) - Ultra-low-power parallel processor platform
- [OpenC910](https://github.com/alibaba/XiangShan) - Open-source RISC-V processor core

---

## Contributing

Contributions welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)
