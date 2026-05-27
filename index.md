---
layout: default
title: Home
---

<section class="hero">
  <div class="hero-copy">
    <p class="eyebrow">Engineering portfolio</p>
    <h1>Yi Dong</h1>
    <p class="lead">MEng Electronic and Information Engineering student at Imperial College London.</p>
    <p class="hero-note">I build practical FPGA, embedded Linux, and hardware/software integration prototypes, with a focus on real system bring-up, debugging, and end-to-end implementation.</p>

    <div class="button-row">
      <a class="button primary" href="https://github.com/dydx404">GitHub</a>
      <a class="button" href="{{ '/projects/' | relative_url }}">Projects</a>
      <a class="button" href="{{ '/cv/' | relative_url }}">CV</a>
      <a class="button" href="mailto:yd1723@ic.ac.uk">Email</a>
    </div>
  </div>

  <figure class="profile-card">
    <img src="{{ '/assets/img/head.jpg' | relative_url }}" alt="Portrait of Yi Dong">
    <figcaption>FPGA / Embedded Linux / SoC systems</figcaption>
  </figure>
</section>

<section class="section">
  <div class="section-heading">
    <p class="section-label">About</p>
    <h2>Practical Systems Builder</h2>
  </div>
  <div class="section-body prose">
    <p>I am an Imperial College London EIE student interested in FPGA-based system integration, embedded Linux, digital design, computer architecture, and sensor/device prototyping.</p>
    <p>My strongest work is in connecting hardware and software into working systems: camera capture, DMA data movement, PYNQ/Zynq PS-PL integration, Linux/Python runtime control, UDP communication, RTL prototyping, and iterative debugging on real hardware.</p>
  </div>
</section>

<section class="section">
  <div class="section-heading">
    <p class="section-label">Timeline</p>
    <h2>Education and Current Work</h2>
  </div>
  <div class="timeline">
    <article class="timeline-item">
      <span class="timeline-date">2024 -- 2028</span>
      <div>
        <h3>Imperial College London</h3>
        <p>MEng Electronic and Information Engineering. Relevant areas include digital electronics, computer architecture, embedded systems, signals and systems, communications, control systems, and engineering mathematics.</p>
      </div>
    </article>
    <article class="timeline-item">
      <span class="timeline-date">May 2026 -- Present</span>
      <div>
        <h3>EE_Acceleration / Electromagnetic FDTD FPGA Accelerator</h3>
        <p>Exploring SystemVerilog fixed-point datapaths, BRAM-backed field storage, CORDIC source generation, Vivado/XSim verification, and renderer integration for an FDTD acceleration project.</p>
      </div>
    </article>
    <article class="timeline-item">
      <span class="timeline-date">Feb 2026 -- Mar 2026</span>
      <div>
        <h3>FPGA Wand / PYNQ-Z1 Vision System</h3>
        <p>Built a PYNQ-Z1 vision prototype integrating OpenCV camera capture, AXI DMA transfer, FPGA-side centroid extraction, MMIO readback, Linux/Python runtime control, and UDP point streaming.</p>
      </div>
    </article>
    <article class="timeline-item">
      <span class="timeline-date">2025 -- Present</span>
      <div>
        <h3>Systems and Embedded Exploration</h3>
        <p>Worked on a simplified RV32I pipelined CPU, Linux Mini-Shell, UDP socket chat prototype, ESP32 automation experiments, and ECG acquisition/display prototypes.</p>
      </div>
    </article>
  </div>
</section>

<section class="section">
  <div class="section-heading">
    <p class="section-label">Projects</p>
    <h2>Featured Engineering Work</h2>
  </div>
  <div class="project-grid">
    <article class="project-card">
      <img src="{{ '/assets/img/FPGA_WANd.jpg' | relative_url }}" alt="FPGA Wand project preview">
      <div class="project-card-body">
        <h3>FPGA Wand / PYNQ-Z1 Vision System</h3>
        <p>End-to-end FPGA and Linux vision prototype using OpenCV, AXI DMA, custom RTL centroid logic, MMIO readback, and UDP communication.</p>
        <div class="tag-list compact">
          <span>PYNQ-Z1</span>
          <span>Zynq-7000</span>
          <span>AXI DMA</span>
          <span>OpenCV</span>
          <span>UDP</span>
        </div>
      </div>
    </article>
    <article class="project-card">
      <img src="{{ '/assets/img/fpga-project-placeholder.jpg' | relative_url }}" alt="FDTD FPGA project preview">
      <div class="project-card-body">
        <h3>EE_Acceleration / FDTD FPGA Accelerator</h3>
        <p>Current SystemVerilog exploration of fixed-point FDTD solver datapaths, BRAM field storage, CORDIC source generation, and Vivado timing/implementation flow.</p>
        <div class="tag-list compact">
          <span>SystemVerilog</span>
          <span>Q3.13</span>
          <span>BRAM</span>
          <span>CORDIC</span>
          <span>Vivado</span>
        </div>
      </div>
    </article>
    <article class="project-card">
      <img src="{{ '/assets/img/embedded-project-placeholder.jpg' | relative_url }}" alt="Systems programming project preview">
      <div class="project-card-body">
        <h3>Linux and Embedded Systems Projects</h3>
        <p>Mini-Shell, UDP socket chat, ESP32 automation experiments, and ECG prototyping, focused on practical systems programming and device-level debugging.</p>
        <div class="tag-list compact">
          <span>C/C++</span>
          <span>Linux</span>
          <span>ESP32</span>
          <span>UDP sockets</span>
        </div>
      </div>
    </article>
  </div>
</section>

<section class="section two-column">
  <div>
    <p class="section-label">Technical Focus</p>
    <h2>Engineering Areas</h2>
  </div>
  <div class="tag-list">
    <span>SystemVerilog</span>
    <span>Verilog</span>
    <span>C/C++</span>
    <span>Python</span>
    <span>Linux</span>
    <span>Bash</span>
    <span>PYNQ-Z1</span>
    <span>Zynq-7000</span>
    <span>PS/PL integration</span>
    <span>AXI DMA</span>
    <span>AXI4-Stream/Lite basics</span>
    <span>OpenCV</span>
    <span>UDP sockets</span>
    <span>ESP32</span>
    <span>Verilator</span>
    <span>Vivado/XSim</span>
    <span>waveform debugging</span>
  </div>
</section>

<section class="section callout">
  <p class="section-label">Current Goal</p>
  <h2>Seeking FPGA, embedded Linux, SoC, and systems engineering internships.</h2>
  <p>I am especially interested in internship work involving FPGA system bring-up, embedded runtime integration, RTL prototyping, Linux-based device interaction, and practical hardware/software debugging.</p>
</section>
