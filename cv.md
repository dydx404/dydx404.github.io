---
layout: default
title: FPGA / Embedded Linux / SoC Portfolio
description: "Imperial EIE student building FPGA, embedded Linux, and SoC prototypes across hardware/software boundaries."
permalink: /cv/
---

<header class="page-header cv-hero">
  <p class="eyebrow">Engineering portfolio</p>
  <h1>FPGA / Embedded Linux / SoC Portfolio</h1>
  <p class="lead">Imperial EIE student building FPGA, embedded Linux, and SoC prototypes across hardware/software boundaries.</p>
  <p>I focus on practical system bring-up, Linux/Python runtime integration, PS/PL communication, FPGA offloading, socket programming, and debugging real hardware/software interactions.</p>

  <div class="button-row">
    <a class="button primary" href="{{ '/assets/resume/yi-dong-fpga-soc-resume.pdf' | relative_url }}" download>Download FPGA / SoC Resume</a>
    <a class="button" href="{{ '/assets/resume/yi-dong-embedded-linux-resume.pdf' | relative_url }}" download>Download Embedded / Linux Resume</a>
    <a class="button" href="https://github.com/dydx404">GitHub</a>
    <a class="button" href="mailto:yd1723@ic.ac.uk">Email</a>
  </div>
</header>

<section class="cv-section">
  <h2>Current Internship Direction</h2>
  <p>Seeking FPGA, embedded Linux, SoC, RTL/digital design, MCU/device integration, and hardware/software co-design internships. I am strongest in hands-on implementation, system integration, hardware bring-up, and iterative debugging across software and hardware boundaries.</p>
</section>

<section class="cv-section">
  <h2>Technical Skills</h2>
  <div class="skill-grid">
    <div>
      <h3>FPGA / Digital Design</h3>
      <p>SystemVerilog, Verilog, FSMs, RTL datapaths, pipelined CPU basics, AXI4-Stream/Lite basics, AXI DMA usage, BRAM/FIFO basics, Vivado</p>
    </div>
    <div>
      <h3>Embedded / Linux</h3>
      <p>C/C++, Python, Bash, Linux, OpenCV, UDP sockets, device bring-up, runtime integration, PYNQ-Z1, Zynq-7000, ESP32</p>
    </div>
    <div>
      <h3>Verification / Debugging</h3>
      <p>Verilator, Icarus Verilog, Vivado/XSim, waveform debugging, directed tests, Python reference models, Git</p>
    </div>
    <div>
      <h3>Systems Programming</h3>
      <p>Unix process model basics, fork/exec, pipes, I/O redirection, socket programming, threading concepts, Makefile basics</p>
    </div>
  </div>
</section>

<section class="cv-section">
  <h2>Selected Projects</h2>
  <div class="portfolio-grid">
    <article class="portfolio-card">
      <div class="portfolio-card-header">
        <div>
          <h3>FPGA Wand / PYNQ-Z1 Vision System</h3>
          <p class="card-meta">Feb 2026 -- Mar 2026</p>
        </div>
        <div class="project-links">
          <a href="https://github.com/dydx404/fpga_wand">GitHub</a>
          <a href="https://github.com/dydx404/fpga_wand#readme">README</a>
        </div>
      </div>
      <p class="tech-line">PYNQ-Z1, Zynq-7000, Verilog, AXI DMA, AXI4-Stream, MMIO, OpenCV, Linux/Python, UDP</p>
      <ul class="compact-list">
        <li>Built a PYNQ-Z1 vision prototype integrating OpenCV camera capture, PS-side preprocessing, AXI DMA transfer, FPGA-side centroid extraction, MMIO readback, and UDP point streaming.</li>
        <li>Implemented a simple AXI4-Stream RTL module for thresholded-frame centroid accumulation and exposed compact results through AXI-Lite/MMIO.</li>
        <li>Debugged camera initialization, DMA transfer behavior, overlay/HWH mismatches, repeated frames, and threshold noise during real hardware bring-up.</li>
      </ul>
    </article>

    <article class="portfolio-card">
      <div class="portfolio-card-header">
        <div>
          <h3>EE_Acceleration / Electromagnetic FDTD FPGA Accelerator</h3>
          <p class="card-meta">May 2026 -- Present</p>
        </div>
        <div class="project-links">
          <a href="https://github.com/TahaMunir2/ElectroMagnetic-FPGA-3D-Renderer">GitHub</a>
          <a href="https://github.com/TahaMunir2/ElectroMagnetic-FPGA-3D-Renderer#readme">README</a>
        </div>
      </div>
      <p class="tech-line">SystemVerilog, Vivado/XSim, Q3.13 fixed point, BRAM, CORDIC, Python reference model, FDTD</p>
      <ul class="compact-list">
        <li>Exploring fixed-point FPGA implementation for FDTD simulation, focusing on datapath construction, BRAM-backed field storage, and module integration.</li>
        <li>Implemented Q3.13 RTL blocks for field updates, CORDIC-based source generation, top-level control, and early solver/renderer interface wiring.</li>
        <li>Used Python-assisted verification with Verilator/XSim and checked Vivado implementation behavior for a small 100 MHz solver prototype.</li>
      </ul>
    </article>

    <article class="portfolio-card">
      <div class="portfolio-card-header">
        <div>
          <h3>RV32I Pipelined CPU with Cache</h3>
          <p class="card-meta">Nov 2025 -- Dec 2025</p>
        </div>
        <div class="project-links">
          <a href="https://github.com/dydx404/EIE-Risc-V-CPU">GitHub</a>
          <a href="https://github.com/dydx404/EIE-Risc-V-CPU#readme">README</a>
        </div>
      </div>
      <p class="tech-line">SystemVerilog, RV32I, five-stage pipeline, forwarding, hazards, cache/refill path, Verilator</p>
      <ul class="compact-list">
        <li>Implemented and tested a simplified RV32I pipelined CPU to understand datapaths, control flow, hazards, memory interaction, and ISA-visible behavior.</li>
        <li>Integrated forwarding paths, load-use hazard handling, stall/flush control, writeback selection, byte-addressable memory, and experimental cache/refill paths.</li>
        <li>Used Verilator/GoogleTest, directed assembly, VCD waveforms, and text traces to debug pipeline stalls, branch flushes, and writeback results.</li>
      </ul>
    </article>

    <article class="portfolio-card">
      <div class="portfolio-card-header">
        <div>
          <h3>Mini-Shell / Linux Systems Programming</h3>
          <p class="card-meta">Nov 2025</p>
        </div>
        <div class="project-links">
          <a href="https://github.com/dydx404/Mini-Shell">GitHub</a>
          <a href="https://github.com/dydx404/Mini-Shell#readme">README</a>
        </div>
      </div>
      <p class="tech-line">C, Linux, fork/exec, pipes, I/O redirection, command parsing</p>
      <ul class="compact-list">
        <li>Implemented a simplified Linux shell supporting command parsing, fork/exec, cd, pipes, and I/O redirection.</li>
        <li>Debugged child-process reaping, file-descriptor handling, nested parsing, and a small raw-mode line editor with tab completion.</li>
      </ul>
    </article>
  </div>
</section>

<section class="cv-section">
  <h2>Additional Systems Projects</h2>
  <div class="portfolio-grid compact-cards">
    <article class="portfolio-card">
      <div class="portfolio-card-header">
        <div>
          <h3>UDP Multithreaded Chat</h3>
          <p class="card-meta">Network programming exploration</p>
        </div>
        <div class="project-links">
          <a href="https://github.com/dydx404/udp-multithreaded-chat">GitHub</a>
          <a href="https://github.com/dydx404/udp-multithreaded-chat#readme">README</a>
        </div>
      </div>
      <p class="tech-line">UDP sockets, client/server message flow, threading concepts</p>
      <ul class="compact-list">
        <li>Built a UDP socket communication prototype to explore client/server messaging, send/receive thread separation, and network-program error handling.</li>
      </ul>
    </article>

    <article class="portfolio-card">
      <div class="portfolio-card-header">
        <div>
          <h3>Smart Balcony / Embedded Exploration</h3>
          <p class="card-meta">Personal exploration</p>
        </div>
      </div>
      <p class="tech-line">ESP32, sensors, motors, GPIO/PWM, peripheral integration</p>
      <ul class="compact-list">
        <li>Explored ESP32 automation prototypes with sensors and simple actuators, gaining hands-on practice with GPIO/PWM control, sensor acquisition, and device debugging.</li>
      </ul>
    </article>

    <article class="portfolio-card">
      <div class="portfolio-card-header">
        <div>
          <h3>ECG Prototype with ESP8266, AD8232, and OLED</h3>
          <p class="card-meta">Embedded sensing prototype</p>
        </div>
      </div>
      <p class="tech-line">ESP8266, AD8232, OLED, ECG acquisition, waveform display</p>
      <ul class="compact-list">
        <li>Prototyped an embedded ECG acquisition/display system and explored basic waveform/BPM display plus R-wave detection ideas.</li>
      </ul>
    </article>
  </div>
</section>

<section class="cv-section">
  <h2>Education</h2>
  <div class="cv-item">
    <div class="cv-date">2024 -- 2028</div>
    <div>
      <h3>Imperial College London</h3>
      <p>MEng Electronic and Information Engineering. Relevant coursework includes Digital Electronics, Computer Architecture, Signals and Systems, Communications, Control Systems, Embedded Systems, Mathematics for Engineers, and Software Systems.</p>
    </div>
  </div>
</section>

<section class="cv-section">
  <h2>Contact</h2>
  <div class="contact-mini-grid">
    <a href="mailto:yd1723@ic.ac.uk">yd1723@ic.ac.uk</a>
    <a href="https://github.com/dydx404">github.com/dydx404</a>
    <span>London, UK</span>
  </div>
</section>
