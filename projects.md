---
layout: default
title: Projects
permalink: /projects/
---

<header class="page-header">
  <p class="eyebrow">Engineering portfolio</p>
  <h1>Projects</h1>
  <p>Selected FPGA, embedded Linux, systems programming, and device-prototyping projects. These are written conservatively to reflect real implementation and debugging work rather than inflated project claims.</p>
</header>

<section class="project-list">
  <article class="project-entry">
    <img src="{{ '/assets/img/FPGA_WANd.jpg' | relative_url }}" alt="FPGA Wand project preview">
    <div class="project-entry-body">
      <div class="project-entry-header">
        <h2>FPGA Wand / PYNQ-Z1 Vision System</h2>
        <a href="https://github.com/dydx404/fpga_wand">GitHub</a>
      </div>
      <p><strong>Feb 2026 -- Mar 2026.</strong> Built a PYNQ-Z1 vision prototype integrating OpenCV camera capture, PS-side preprocessing, AXI DMA transfer, FPGA-side centroid extraction, MMIO result readback, and UDP point streaming.</p>
      <ul>
        <li>Implemented a simple AXI4-Stream RTL module for thresholded-frame centroid accumulation and exposed sum, count, frame_id, and valid status through AXI-Lite/MMIO.</li>
        <li>Integrated the Linux/Python runtime with PYNQ overlays, DMA buffer allocation, frame freshness checks, threshold tuning, and stroke packetization.</li>
        <li>Debugged camera initialization, DMA transfer behavior, overlay/HWH mismatches, duplicate frames, and noise-sensitive thresholds during hardware bring-up.</li>
      </ul>
      <div class="tag-list compact">
        <span>PYNQ-Z1</span>
        <span>Zynq-7000</span>
        <span>Verilog</span>
        <span>AXI DMA</span>
        <span>AXI4-Stream</span>
        <span>MMIO</span>
        <span>OpenCV</span>
        <span>UDP</span>
      </div>
    </div>
  </article>

  <article class="project-entry">
    <img src="{{ '/assets/img/fpga-project-placeholder.jpg' | relative_url }}" alt="EE Acceleration FDTD FPGA project preview">
    <div class="project-entry-body">
      <div class="project-entry-header">
        <h2>EE_Acceleration / Electromagnetic FDTD FPGA Accelerator</h2>
        <a href="https://github.com/TahaMunir2/ElectroMagnetic-FPGA-3D-Renderer">GitHub</a>
      </div>
      <p><strong>May 2026 -- Present.</strong> Current FPGA implementation exploration for an FDTD electromagnetic simulation project, focused on fixed-point datapaths, BRAM-backed field storage, and SystemVerilog module integration.</p>
      <ul>
        <li>Implemented Q3.13 RTL blocks for field update logic, CORDIC-based source generation, top-level control, and early solver/renderer interface wiring.</li>
        <li>Built Python-assisted verification using Icarus Verilog, Verilator, Yosys, and Vivado/XSim while iterating a small 1D solver prototype.</li>
        <li>Ran Vivado implementation for the 1D top at 100 MHz and recorded WNS/resource results while extending toward 2D solver and render-buffer integration.</li>
      </ul>
      <div class="tag-list compact">
        <span>SystemVerilog</span>
        <span>Vivado/XSim</span>
        <span>Q3.13 fixed point</span>
        <span>BRAM</span>
        <span>CORDIC</span>
        <span>FDTD</span>
      </div>
    </div>
  </article>

  <article class="project-entry">
    <img src="{{ '/assets/img/fpga-project-placeholder.jpg' | relative_url }}" alt="RV32I CPU project preview">
    <div class="project-entry-body">
      <div class="project-entry-header">
        <h2>RV32I Pipelined CPU with Cache</h2>
        <a href="https://github.com/dydx404/EIE-Risc-V-CPU">GitHub</a>
      </div>
      <p><strong>Nov 2025 -- Dec 2025.</strong> Implemented and tested a simplified RV32I pipelined CPU in SystemVerilog, using the project to build practical understanding of datapaths, hazards, memory interaction, and ISA-visible correctness.</p>
      <ul>
        <li>Integrated forwarding paths, load-use hazard handling, stall/flush control, writeback selection, byte-addressable memory, and an experimental cache/refill path.</li>
        <li>Used Verilator/GoogleTest, directed RV32I assembly/reference programs, VCD waveforms, and text traces to debug pipeline behavior and writeback results.</li>
      </ul>
      <div class="tag-list compact">
        <span>SystemVerilog</span>
        <span>RV32I</span>
        <span>five-stage pipeline</span>
        <span>cache</span>
        <span>Verilator</span>
        <span>waveforms</span>
      </div>
    </div>
  </article>

  <article class="project-entry">
    <img src="{{ '/assets/img/embedded-project-placeholder.jpg' | relative_url }}" alt="Mini-Shell project preview">
    <div class="project-entry-body">
      <div class="project-entry-header">
        <h2>Mini-Shell / Linux Systems Programming</h2>
        <a href="https://github.com/dydx404/Mini-Shell">GitHub</a>
      </div>
      <p><strong>Nov 2025.</strong> Implemented a simplified Linux shell with command parsing, fork/exec, cd, pipes, and I/O redirection to strengthen understanding of the Unix process model.</p>
      <ul>
        <li>Debugged child-process reaping, file-descriptor handling, nested command parsing, and a small raw-mode line editor with tab completion.</li>
      </ul>
      <div class="tag-list compact">
        <span>C</span>
        <span>Linux</span>
        <span>fork/exec</span>
        <span>pipes</span>
        <span>I/O redirection</span>
      </div>
    </div>
  </article>

  <article class="project-entry">
    <img src="{{ '/assets/img/embedded-project-placeholder.jpg' | relative_url }}" alt="UDP multithreaded chat project preview">
    <div class="project-entry-body">
      <div class="project-entry-header">
        <h2>UDP Multithreaded Chat / Network Programming Exploration</h2>
        <a href="https://github.com/dydx404/udp-multithreaded-chat">GitHub</a>
      </div>
      <p>Built a UDP socket communication prototype to explore client/server message flow, send/receive thread separation, and basic network-program error handling.</p>
      <div class="tag-list compact">
        <span>UDP sockets</span>
        <span>client/server</span>
        <span>threading concepts</span>
        <span>network debugging</span>
      </div>
    </div>
  </article>

  <article class="project-entry">
    <img src="{{ '/assets/img/embedded-project-placeholder.jpg' | relative_url }}" alt="Smart Balcony embedded exploration preview">
    <div class="project-entry-body">
      <div class="project-entry-header">
        <h2>Smart Balcony Embedded Exploration</h2>
        <span>Personal exploration</span>
      </div>
      <p>Explored ESP32-based automation prototypes with sensors and simple actuators, gaining hands-on practice with GPIO/PWM control, peripheral integration, sensor acquisition, and device debugging.</p>
      <div class="tag-list compact">
        <span>ESP32</span>
        <span>sensors</span>
        <span>motors</span>
        <span>GPIO/PWM</span>
        <span>embedded debugging</span>
      </div>
    </div>
  </article>

  <article class="project-entry">
    <img src="{{ '/assets/img/ecg-project-placeholder.jpg' | relative_url }}" alt="ECG monitor project preview">
    <div class="project-entry-body">
      <div class="project-entry-header">
        <h2>ECG Monitor with ESP8266, AD8232, and OLED</h2>
        <span>Prototype</span>
      </div>
      <p>Prototyped an embedded ECG monitor using an AD8232 front end, ESP8266 control logic, and OLED display output, with basic waveform/BPM display and exploration of R-wave detection ideas.</p>
      <div class="tag-list compact">
        <span>ESP8266</span>
        <span>AD8232</span>
        <span>OLED</span>
        <span>ECG acquisition</span>
        <span>signal processing</span>
      </div>
    </div>
  </article>
</section>
