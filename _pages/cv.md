---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **Ph.D in Microelectronics**, National Institute of Microelectronics of Sevilla and University of Seville, 2021 -- Jan 2026
  * Design, implementation and verification of mixed-signal algorithms for neural implantable technologies.
  * Implementation end-to-end from requirements, architecture, proof of concept (Python, C/C++), implementation on VHDL/Verilog, to validation and verification on FPGA and RTL analysis. Used Cadence (Genus and Virtuoso) and Xilinx (Vivado and Vitis) for analog and digital design and verifications.
  * Published 2 journal paper in Advanced Science and Plos One. 4 Conference papers in ICECS, ISCAS, and EMBC.
  * Research stay at Next Generation Neural Interfaces (NGNI) Laboratory at Imperial College of London under the supervision of Timothy Constandinou.

* **MSc in Mechatronics, Electronics and Embedded systems specialization**, University of Glasgow, 2019-2020
  * **Relevant Coursework:** Real time embedded systems programming (C++), Digital Signal Processing (DSP), Control and Systems engineering.

* **International Scholarship (GPA: 4.00 / 4.00)**, Incheon National University, Feb 2018 - Jul 2018
  * **Relevant Coursework:** Brain engineering, nanomaterials bioengineering.

* **Bachelor of Science in Biomedical engineering (GPA: 3.23 / 4.00)**, University of Malaga, 2013-2018
  * **Relevant Coursework:** Electronic Design, Data Structures and Algorithms (Java/C++), Digital Signal Processing (Matlab/Python), Biomaterials, Bioimplants, Bioinstrumentation.

Work experience
======
* **Feb 2021 -- Present: Signal Processing Engineer**, Analog Devices Inc., Valencia, Spain
  * Development of signal processing algorithms and architectures for diagnosis of pathologies in ECG signals for on-device ambulatory monitoring devices.
  * Conceptualization, design, development, and integration of algorithms on ECG medical devices on-device for low-power critical applications. Implementation of signal conditioning and curation steps for machine learning algorithms on high-performance cloud computing.
  * Analysis of product requirements and specifications in compliance with IEC/ISO medical device regulations and standards for FDA submissions. Compliance with IEC60601 and ISO9001.
  * Implementation of software best practices and tests for CI/CD using Jenkins, GitLab, and pytest. Planning and development of different product validation and verification tests.
  * Implementation of high-performance algorithms for embedded microcontrollers using ARM Cortex-M4, Cortex-M7, and Cortex-M33.

* **Nov 2024 -- Dec 2024: Visiting Researcher**, Imperial College London, London, U.K.
  * Design, synthesis, RTL analysis, and verification of algorithm IPs in Cadence Virtuoso, Genus, and Xilinx Vivado, Vitis.
  * Collaborated on the design of neural interfaces and implantable systems.

* **Sep 2020 -- Feb 2021: R&D Engineer**, Spanish National Centre of Microelectronics, Seville, Spain
  * Conducted research tasks for the HERMES FET-PROACT European project, designing and testing ICs for brain bioimplantable devices.
  * Designed digital signal processing architectures (Python/C++) for microelectrode array used for intracortical EEG using DSP processors and FPGAs.
  * Mixed-signal IC design in VHDL and Verilog. Full system implementation from DMA I/O routines, algorithm implementation, RTL analysis and laboratory testing.
  * Designed circuits specific to neural interfaces and implantable systems.
  * Digital design flow and top-level system integration for FPGAs. Used Zynq 7020 SoC for FPGA Verilog code verification and functional test preparation.

* **Jan 2020 -- Sep 2020: Research Assistant**, Polytechnic University of Madrid, Madrid, Spain
  * Management of European project proposal documentation and design of electronic schematics. Managed specific work packages of >1M€ projects.
  * Developed IoT and WoT architectures on STM32 Cortex-M4 and Raspberry Pi.

* **Apr 2019 -- Jan 2020: Research Scholar**, Microelectronics Laboratory (MeLab), University of Glasgow, Glasgow, United Kingdom
  * Designed and fabricated a bioelectronic brain implantable device for treating epilepsy for the FET-Proact HERMES European project.
  * Published two conference papers (ICECS 2019 and ISCAS 2021) and one journal paper (Advanced Science).
  * Designed RF electromagnetic wireless power transfer systems using HFSS and EAGLE.
  * Fabricated flexible and stretchable circuits on DuPont Pyralux AP8535R using automatic PCB printing with Voltera machine.

Relevant projects
======
* **Design and fabrication of a portable ElectroCardioGraph (ECG) controlled by Arduino and signal processing for heartbeat detection** | *Kicad, Eagle, C++, Python, PCB fabrication*
  * Developed an implemented a platform to record ECG signals with an AD8231 analog front end.
  * I carried out the whole design, from conceptualization, PCB design, firmware development, algorithm implementation and fabrication.
  * [Project Link](https://ggche.github.io/portfolio/portfolio-1/)

* **Design and Fabrication of a modular bioimplantable device for the treatment of epilepsy based on optoelectronics techniques.** | *PCB design, C++, Python*
  * Design, simulation, fabrication and validation of a biocompatible brain implantable device using wireless power transmission techniques through RF techniques, simulation run in HFSSS and COMSOL, and fabrication over a flexible PCB substrate and using optoelectronic techniques. This work was published in 2 conference papers at IEEE and 1 journal paper.
  * [Publication Link](https://ieeexplore.ieee.org/abstract/document/8964995)

* **Conferences**
  * Galeote Checa, G. & Pimentel Naranjo, V. (2016). Quantum Dots. *PIE15-110*. Jornadas PIE 15-110: Enseñanza Multidisciplinar de la Biotecnología y de las Ciencias Ómicas a Biólogos e Ingenieros.Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>


