---
layout: default
title: Home
---
<nav class="main-nav">
  <a href="/" class="active">Home</a>
  <a href="#about">About</a>
  <a href="#projects">Projects</a>
  <a href="#skills">Skills</a>
  <a href="#contact">Contact</a>
</nav>

<div class="hero">
  <div class="hero-content">
    <div class="hero-headshot">
      <img src="images/headshot.jpg" alt="Nidhi Khiantani">
    </div>

    <div class="hero-text">
      <h1>Nidhi Khiantani</h1>
      <p class="subtitle">Duke University '26 · University of Michigan MEng '27</p>
      <p>B.S. Computer Science & ECE + Theater Studies · MEng ECE, Autonomous Systems Concentration</p>
      <p class="coursework"><strong>Relevant Coursework:</strong> Digital Systems, IoT Systems, Electrical and Computer Engineering Fundamentals, Advanced Data Structures and Algorithms, Product Design, Computer Systems, Discrete Math</p>
      
      <div class="hero-buttons">
        <a href="resume.pdf" class="btn-primary" target="_blank">View My Resume</a>
      </div>
    </div>
    
    <div class="hero-image">
      <img src="images/cover_image.JPG" alt="Nidhi on wakeboard!">
    </div>
  </div>
</div>

<div id="about"></div>

## About Me

Hello! I recently graduated from Duke University with a B.S. in Computer Science (ECE focus) and Theater Studies, and I'm heading to the University of Michigan for a Master of Engineering in ECE with a concentration in Autonomous Systems. I'm looking for hardware engineering opportunities where I can design, test, and optimize real systems! I began my studies in Computer Science at Duke and quickly discovered I wanted to physically build as well as code. That led me to focus on embedded systems, sensor integration, and hardware design. I have designed and developed hardware products, including custom PCBs, microcontroller-based systems (ESP32), sensor arrays (IMU, FSRs), and FPGA development. I've also executed test plans, validated hardware performance under real-world conditions, and troubleshooted hardware issues.

<div id="projects"></div>

## Projects

<div class="project-grid">

<div class="project-card-grid">
  <a href="projects/wavguard">
    <img src="images/wavguard/final-product.jpg" alt="WavGuard Wakeboard" class="project-thumbnail">
  </a>
  <div class="project-card-content">
    <h3><a href="projects/wavguard">WavGuard</a></h3>
    <p>Wakeboard balance training system with FSR sensors, IMU, and real-time LED feedback.</p>
    <div class="project-tech">
      <span class="tech-tag">ESP32</span>
      <span class="tech-tag">PCB Design</span>
      <span class="tech-tag">FSR Sensors</span>
      <span class="tech-tag">IMU</span>
    </div>
  </div>
</div>

<div class="project-card-grid">
  <a href="projects/ice-cream-dispenser">
    <img src="images/ice-cream/full-setup.jpg" alt="Ice Cream Dispenser" class="project-thumbnail">
  </a>
  <div class="project-card-content">
    <h3><a href="projects/ice-cream-dispenser">Ice Cream Dispenser</a></h3>
    <p>Custom 32-bit RISC CPU in Verilog controlling automated topping dispenser via memory-mapped I/O.</p>
    <div class="project-tech">
      <span class="tech-tag">Verilog</span>
      <span class="tech-tag">FPGA</span>
      <span class="tech-tag">Assembly</span>
      <span class="tech-tag">PWM</span>
    </div>
  </div>
</div>

<div class="project-card-grid">
  <a href="projects/matchamatic">
    <img src="images/matchamatic/front.jpg" alt="Matchamatic" class="project-thumbnail">
  </a>
  <div class="project-card-content">
    <h3><a href="projects/matchamatic">Matchamatic</a></h3>
    <p>ESP32-powered automated matcha latte maker.</p>
    <div class="project-tech">
      <span class="tech-tag">ESP32</span>
      <span class="tech-tag">Motor Control</span>
      <span class="tech-tag">Web Server</span>
      <span class="tech-tag">Calibration</span>
    </div>
  </div>
</div>

<div class="project-card-grid">
  <a href="projects/CPSL">
    <img src="images/icaraus/platforms.jpg" alt="IcaRAus UGV and UAV" class="project-thumbnail">
  </a>
  <div class="project-card-content">
    <h3><a href="projects/CPSL">IcaRAus: Radar-Based Robot Navigation</a></h3>
    <p>Co-authored IEEE T-RO paper on GNN-enhanced radar point clouds for autonomous UGV and UAV navigation.</p>
    <div class="project-tech">
      <span class="tech-tag">ROS2</span>
      <span class="tech-tag">mmWave Radar</span>
      <span class="tech-tag">SLAM</span>
      <span class="tech-tag">Nav2</span>
    </div>
  </div>
</div>

<div class="project-card-grid">
  <a href="projects/autonomous-vehicle">
    <img src="images/autonomous-vehicle/robot-front.jpg" alt="Autonomous Robot" class="project-thumbnail">
  </a>
  <div class="project-card-content">
    <h3><a href="projects/autonomous-vehicle">Autonomous Navigation Robot</a></h3>
    <p>Ground-up robot build with LiDAR, RGB camera, and IMU.</p>
    <div class="project-tech">
      <span class="tech-tag">ROS</span>
      <span class="tech-tag">LiDAR</span>
      <span class="tech-tag">Computer Vision</span>
      <span class="tech-tag">Arduino</span>
    </div>
  </div>
</div>

<div class="project-card-grid">
  <a href="projects/dronewq">
    <img src="images/dronewq/results-dashboard.png" alt="DroneWQ" class="project-thumbnail">
  </a>
  <div class="project-card-content">
    <h3><a href="projects/dronewq">DroneWQ</a></h3>
    <p>Electron desktop app for water quality analysis from drone imagery.</p>
    <div class="project-tech">
      <span class="tech-tag">Python</span>
      <span class="tech-tag">Flask</span>
      <span class="tech-tag">Electron</span>
      <span class="tech-tag">GDAL</span>
    </div>
  </div>
</div>

</div>

<div id="skills"></div>

## Skills

**Hardware Design & Testing:** PCB Design (KiCad), FPGA Development (Vivado), Circuit Design, Oscilloscope, Logic Analyzer, Multimeter, Soldering, Hardware Debugging, Testing & Validation, Signal Processing

**Embedded Systems & Firmware:** Arduino, ESP32 (S2/S3), STM32, Raspberry Pi, Jetson AGX Xavier, Nexys A7 FPGA

**Protocols & Interfaces:** I²C, SPI, UART, PWM, Memory-Mapped I/O

**HDL & Programming:** Verilog, C/C++, Python (NumPy, Pandas, PyTorch), Java, MATLAB, MicroPython, Assembly (MIPS)

**Software & Development Tools:** Git, Linux, ROS2, Flask, Node.js, HTML/CSS, Google Cloud, Electron, Docker

**CAD & Design:** Figma, Onshape, KiCad, 3D Printing

**Robotics & Computer Vision:** LiDAR, RealSense RGB-D Camera, YOLO, Sensor Fusion, Dataset Creation

<div id="contact"></div>

## Contact

**Email:** nkhian@umich.edu  
**LinkedIn:** [linkedin.com/in/nidhi-khiantani](https://linkedin.com/in/nidhi-khiantani)

