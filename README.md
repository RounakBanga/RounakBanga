<h1 align="center">&lt; Rounak Banga /&gt;</h1>

<p align="center"><b>CMOS Design · Computer Architecture · Systems</b></p>

<p align="center">
  <img src="https://github-readme-stats.shion.dev/api/top-langs/?username=RounakBanga&layout=compact&theme=nightowl&hide_border=true&bg_color=00000000"/>
</p>

---

```c
/* =====================  profile.config  ===================== */

build {
  project: "RISC CPU (Verilog)";

  modules: {
    ALU:             COMPLETE,
    ProgramCounter:  COMPLETE,
    Datapath:        IN_PROGRESS
  };

  simulation: "Vivado";
}

/* ------------------------------------------------------------ */

analog {
  tools: ["Cadence Virtuoso", "LTSpice", "KiCad"];

  focus: [
    "CMOS logic (AND / OR / XOR)",
    "inverter characteristics",
    "DC + transient analysis"
  ];
}

/* ------------------------------------------------------------ */

embedded {
  target: "LPC1768";

  drivers: [
    GPIO, ADC, UART,
    SPI, PWM, Displays
  ];
}

/* ------------------------------------------------------------ */

architecture {
  reference: "Patterson & Hennessy";

  topics: [
    "datapath design",
    "control flow",
    "RISC pipeline fundamentals"
  ];
}

/* ------------------------------------------------------------ */

signals {
  SIH_rank: "14 / 641";
}

/* ------------------------------------------------------------ */

toolchain = [
  Verilog, Vivado,
  Cadence, LTSpice, KiCad,
  C++, Python, MATLAB
];

direction {
  focus: ["Analog Design", "VLSI"];
  goal:  "useful, real-world electronics";
}

/* ============================================================ */
```
