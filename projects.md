---
layout: default
title: Projects
permalink: /projects/
---

<!-- Duplicate a project-entry block to add more projects. Replace placeholder images when ready. -->

<header class="page-header">
  <p class="eyebrow">Engineering portfolio</p>
  <h1>Projects</h1>
  <p>[Short overview of your project work here. Keep it concise and engineering-focused.]</p>
</header>

<section class="project-list">
  <article class="project-entry">
    <img src="{{ '/assets/img/fpga-project-placeholder.jpg' | relative_url }}" alt="FPGA project placeholder">
    <div class="project-entry-body">
      <div class="project-entry-header">
        <h2>FPGA Wand System</h2>
        <a href="https://github.com/dydx404/fpga_wand">GitHub</a>
      </div>
      <p>[Short summary placeholder. Describe the system goal, hardware platform, and what you personally implemented.]</p>
      <p><strong>Engineering focus:</strong> [PS-PL co-design, streaming architecture, DMA data movement, timing, real-time image processing.]</p>
      <div class="tag-list compact">
        <span>PYNQ-Z1</span>
        <span>Zynq-7000</span>
        <span>AXI DMA</span>
        <span>AXI-Stream</span>
        <span>OpenCV</span>
        <span>UDP</span>
      </div>
    </div>
  </article>

  <article class="project-entry">
    <img src="{{ '/assets/img/embedded-project-placeholder.jpg' | relative_url }}" alt="Embedded systems project placeholder">
    <div class="project-entry-body">
      <div class="project-entry-header">
        <h2>ESP32 Smart Balcony / IoT System</h2>
        <a href="#">GitHub placeholder</a>
      </div>
      <p>[Short summary placeholder. Describe the sensing goal, node architecture, communication method, and power constraints.]</p>
      <p><strong>Engineering focus:</strong> [Low-power embedded sensing, telemetry, sensor integration, display interface.]</p>
      <div class="tag-list compact">
        <span>ESP32</span>
        <span>Battery Nodes</span>
        <span>Soil Moisture</span>
        <span>Telemetry</span>
        <span>OLED / E-ink</span>
      </div>
    </div>
  </article>

  <article class="project-entry">
    <img src="{{ '/assets/img/ecg-project-placeholder.jpg' | relative_url }}" alt="ECG project placeholder">
    <div class="project-entry-body">
      <div class="project-entry-header">
        <h2>ECG Monitor</h2>
        <a href="#">GitHub placeholder</a>
      </div>
      <p>[Short summary placeholder. Describe the acquisition circuit, embedded display, signal-processing method, and current status.]</p>
      <p><strong>Engineering focus:</strong> [Real-time acquisition, waveform rendering, R-wave detection, BPM estimation.]</p>
      <div class="tag-list compact">
        <span>AD8232</span>
        <span>ESP32 / ESP8266</span>
        <span>OLED</span>
        <span>Pan-Tompkins</span>
        <span>BPM</span>
      </div>
    </div>
  </article>
</section>
