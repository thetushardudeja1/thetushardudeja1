# Tushar Dudeja

**Semiconductor device & compact modelling · reliability · device-to-circuit design**
B.Tech. Electronics Engineering (VLSI Design), Vellore Institute of Technology (VIT), India · expected 2028

[![Email](https://img.shields.io/badge/Email-tushar.dudeja09%40gmail.com-D14836?logo=gmail&logoColor=white)](mailto:tushar.dudeja09@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-tushardudeja-0A66C2?logo=linkedin&logoColor=white)](https://linkedin.com/in/tushardudeja)

🏆 **Top-3 Winner, IEEE Electron Devices Society TCAD Hackathon 2026 (international)** · US$1,000 award + travel grant to IEEE EDTM 2027, Fukuoka

---

### What I work on

I take one device all the way from physics to circuits. Most of my work is on the
**CFET** (complementary FET, an nFET stacked on a pFET): how its tiers heat, age and vary
in TCAD, how to capture that in compact models, and how circuit designers can turn the
asymmetry between the tiers into useful function, from neuromorphic neurons to quantum
devices. Alongside that I build hardware, EDA and ML tools for reliability and power.

---

### 📄 Publications

- **Geometry-Aware Grad-CAM Localization for Wafer Map Defects**, *Scientific Reports*, 2026 ·
  [doi:10.1038/s41598-026-52885-x](https://doi.org/10.1038/s41598-026-52885-x) · [code](https://github.com/thetushardudeja1/wafer_xai_framework)
- **Explainable Power Estimation for HLS-Stage FPGA Designs**, *IEEE Access*, 2026 ·
  [doi:10.1109/ACCESS.2026.3716018](https://doi.org/10.1109/ACCESS.2026.3716018)

### 📝 Under review at IEEE

| Work | Venue | Repository |
|---|---|---|
| Correlation-aware high-sigma SRAM reliability of junctionless GAA nanowires | IEEE TDMR | [jl-gaa-nanowire-tdmr](https://github.com/thetushardudeja1/jl-gaa-nanowire-tdmr) |
| Multi-tier CFET electrothermal reliability and NBTI/PBTI aging | IEEE JXCDC | [cfet-multitier-reliability-tcad](https://github.com/thetushardudeja1/cfet-multitier-reliability-tcad) |
| Register-level composition of HLS transformation power | IEEE TCAD | [hls-register-level-power](https://github.com/thetushardudeja1/hls-register-level-power) |
| Approximation placement in FIP/FFIP matrix-multiply accelerators | IEEE TCAS-I | [ffip-approximation-placement](https://github.com/thetushardudeja1/ffip-approximation-placement) |

---

### 🔬 Research projects

**Devices & TCAD**
| Project | Highlight |
|---|---|
| [cfet-multitier-reliability-tcad](https://github.com/thetushardudeja1/cfet-multitier-reliability-tcad) | 4-tier CFET in Sentaurus: tier-resolved self-heating and NBTI/PBTI aging; top-tier pFET ages 4.8–6.3× faster |
| [jl-gaa-nanowire-tdmr](https://github.com/thetushardudeja1/jl-gaa-nanowire-tdmr) | TCAD variability → BSIM-CMG (1.1–1.3 % RMS) → 6σ SRAM: wire correlation shifts Vmin by up to 157 mV |
| [imec-quantum-dot-qtcad-sim](https://github.com/thetushardudeja1/imec-quantum-dot-qtcad-sim) | QTCAD model of imec's quantum-dot array, then a stacked-tier dot with ~52× less barrier disturbance |
| [2d-tmd-cfet-thermal](https://github.com/thetushardudeja1/2d-tmd-cfet-thermal) | QuantumATK phonon transport: MoS₂/WSe₂ thermal-boundary-conductance ratio 1.13–1.16 |
| [AlGaN-GaN-HEMT-TCAD](https://github.com/thetushardudeja1/AlGaN-GaN-HEMT-TCAD) | TCAD replica of a fabricated AlGaN/GaN HEMT on Si with a superlattice buffer |

**Circuits, test & architecture**
| Project | Highlight |
|---|---|
| [neuromorphic-circuit-testing](https://github.com/thetushardudeja1/neuromorphic-circuit-testing) | 110k simulated spiking neurons, 46 defects: spike tests miss 11.4 %, supply-current readouts catch them all |
| [cfet-neural-amplifier](https://github.com/thetushardudeja1/cfet-neural-amplifier) | All-CFET neural recording chain: 41.6 dB, 4.34 µVrms, 42 nW amplifier; 38/38 bursts detected |
| [ffip-approximation-placement](https://github.com/thetushardudeja1/ffip-approximation-placement) | 28 nm FD-SOI: FIP saves 14.2 % area / 18.8 % power; pre-adder approximation collapses ResNet-20 to 10 % |
| [hls-register-level-power](https://github.com/thetushardudeja1/hls-register-level-power) | 19,113 HLS designs, 700k register power records; composition beats power change (0.935 vs 0.575) |

**ML & reinforcement learning**
| Project | Highlight |
|---|---|
| [Beamrider](https://github.com/thetushardudeja1/Beamrider) | 1-v-1 beyond-visual-range air-combat RL agent (JSBSim 6-DOF, PPO) |
| [mems-differentiable-pullin](https://github.com/thetushardudeja1/mems-differentiable-pullin) | Dataset-free inverse design of electrostatic MEMS through the pull-in bifurcation |

---

### 🧰 Tools

**TCAD & atomistic:** Synopsys Sentaurus (SDE, SDevice, SVisual), Silvaco Victory, QuantumATK, QTCAD
**Circuits & compact models:** BSIM-CMG extraction, PrimeSim HSPICE (high-sigma Monte Carlo), ngspice, Cadence Virtuoso / Spectre
**Digital & EDA:** SystemVerilog, Cadence Xcelium / Genus / Innovus / Conformal, Siemens Catapult HLS, OpenROAD
**Programming & ML:** Python, PyTorch, scikit-learn, C/C++, MATLAB, TCL, Linux / HPC

### 🎓 Certifications

| Certificate | Issuer | Date | Verify |
|---|---|---|---|
| Unsupervised Learning, Recommenders, Reinforcement Learning | DeepLearning.AI (Coursera) | Jul 2025 | [credential](https://www.coursera.org/account/accomplishments/verify/HVE5R5SOUBZN) |

### 💼 Experience

**Research Intern, Reinforcement Learning**, DRDO, Institute for Systems Studies and Analyses (ISSA), Ministry of Defence · May–Jun 2026

---

📫 Open to research collaborations and internships in device modelling, reliability and circuit design: **tushar.dudeja09@gmail.com**
