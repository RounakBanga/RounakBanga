<div align="center">

<h1>&lt; Rounak Banga /&gt;</h1>

<p><b>CMOS Design · Computer Architecture · Systems</b></p>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=RounakBanga&layout=compact&theme=nightowl&hide_border=true"/>

</div>

---

```
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
