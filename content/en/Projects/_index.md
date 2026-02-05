---
title: Experience / Projects
linkTitle: Experience / Projects
url: "/projects/"
type: docs
description: >
  Below is the collection of work I have done that has deepened my learning and understanding of engineering.
menu: {main: {weight: 50}}
cascade:
  - type: "docs"
---

<style>
.exp-proj-layout {
  display: flex;
  gap: 3rem;
}
.exp-proj-left {
  flex: 0 0 220px;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  padding-top: 2rem;
}
.exp-proj-left h2 {
  font-size: 1.2rem;
  margin-bottom: 1rem;
  color: #63b3ed;
}
.exp-proj-left .exp-proj-list {
  margin-bottom: 2.5rem;
}
.exp-proj-left a {
  display: block;
  margin-bottom: 1.2rem;
  color: #fff;
  text-decoration: none;
  font-size: 1rem;
  padding: 0.5rem 0.8rem;
  border-radius: 0.5rem;
  transition: background 0.2s;
}
.exp-proj-left a:hover {
  background: #2d3748;
}
.exp-proj-center {
  flex: 1;
  display: flex;
  flex-direction: column;
  align-items: center;
  padding-top: 2rem;
}
.exp-proj-preview {
  width: 80%;
  max-width: 600px;
  height: 220px;
  background: rgba(44, 62, 80, 0.2);
  border: 2px dashed #4a5568;
  border-radius: 1rem;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 1.3rem;
  color: #4a5568;
  margin-bottom: 2rem;
}
.exp-proj-links {
  display: flex;
  gap: 2rem;
  justify-content: center;
  margin-bottom: 2.5rem;
}
.exp-proj-link {
  flex: 1;
  background: #2d3748;
  border: 2px solid #4a5568;
  border-radius: 1rem;
  padding: 2rem;
  text-align: center;
  color: #fff;
  font-size: 1.1rem;
  text-decoration: none;
  transition: box-shadow 0.2s;
}
.exp-proj-link:hover {
  box-shadow: 0 4px 16px rgba(44,62,80,0.2);
}
.exp-proj-divider {
  width: 100%;
  border-top: 2px solid #4a5568;
  margin: 3rem 0;
}

/* NEW: Individual item cards */
.exp-proj-item {
  width: 100%;
  max-width: 800px;
  margin-bottom: 3rem;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.item-header {
  width: 100%;
  text-align: left;
  margin-bottom: 1rem;
  padding-left: 1rem;
  border-left: 4px solid #63b3ed;
}

.item-content {
  display: flex;
  gap: 2rem;
  width: 110%;
  align-items: flex-start;
}

/* UPDATED: Smaller image container */
.item-preview {
  flex: 0 0 250px; /* Reduced from 250px */
  height: 180px; /* Reduced from 180px */
  background: rgba(44, 62, 80, 0.2);
  border: 2px solid #4a5568;
  border-radius: 1rem;
  display: flex;
  align-items: center;
  justify-content: center;
  overflow: hidden; /* Keeps images contained */
}

/* NEW: Ensure images fit properly */
.item-preview img {
  width: 100%;
  height: 100%;
  object-fit: cover; /* Crops image to fill container */
  object-position: center;
}

.item-details {
  flex: 1;
  padding: 1rem 0;
}

.item-details h3 {
  margin-top: 0;
  color: #fff;
  font-size: 1.3rem;
}

.item-details p {
  color: #cbd5e0;
  line-height: 1.6;
}

.item-link {
  display: inline-block;
  margin-top: 1rem;
  padding: 0.75rem 1.5rem;
  background: #2d3748;
  border: 1px solid #4a5568;
  border-radius: 0.5rem;
  color: #63b3ed;
  text-decoration: none;
  font-weight: bold;
  transition: all 0.2s;
}

.item-link:hover {
  background: #4a5568;
  transform: translateY(-2px);
}

</style>

<div class="exp-proj-layout">
  <div class="exp-proj-center">
    <h2 class="item-header">Experience</h2>
    <!-- Rainmaker Technology -->
    <div class="exp-proj-item">
      <div class="item-content">
        <img src="/images/rainmaker_cover.jpeg" class="item-preview" alt="Rainmaker Technology UAV System">
        <div class="item-details">
          <h3>Rainmaker Technology – Systems Engineering Intern</h3>
          <p>Designed compressor impellers for UAV aerosol dispersion systems deployed on 120+ drones. Created aerospace-grade technical drawings with GD&T and managed manufacturing coordination.</p>
          <a href="/Rainmaker/" class="item-link">View Details →</a> 
        </div>
      </div>
    </div>
    <!-- Purdue Hybrid Rocket Team -->
    <div class="exp-proj-item">
      <div class="item-content">
        <img src="/static/images/Hybrids.jpeg" class="item-preview" alt="Purdue Hybrid Rocket Team">
        <div class="item-details">
          <h3>Purdue Hybrid Rocket Team – Propulsion Engineer</h3>
          <p>Designed and manufactured aluminum rocket components targeting 50,000 ft altitude. Developed fuel grain decay simulations and presented at PDR/CDR reviews with aerospace engineers.</p>
          <a href="/projects/fusion-of-permutation-defects/purdue-hybrids/" class="item-link">View Details →</a>
        </div>
      </div>
    </div>
    <!-- Portland Van -->
    <div class="exp-proj-item">
      <div class="item-content">
        <img src="/images/portland-van-preview.jpeg" class="item-preview" alt="Portland Van Sprinter Racks">
        <div class="item-details">
          <h3>Portland Van – Sprinter Racks Manufacturer</h3>
          <p>Helped maintain a small business manufacturing aluminum tube racks for Sprinter vans. Managed sawing, welding, and powder coating processes, and facilitated vendor connections for laser cutting. Successfully sold the company for $50,000 including inventory, brand, and website assets.</p>
          <a href="/Portland%20Van/" class="item-link">View Details →</a>
        </div>
      </div>
    </div>
    <div class="exp-proj-divider"></div>
    <h2 class="item-header">Projects</h2>
    <!-- Purdue SLICE -->
    <div class="exp-proj-item">
      <div class="item-content">
        <img src="/images/418_box.png" class="item-preview" alt="Purdue SLICE Zero-G Experiment">
        <div class="item-details">
          <h3>Purdue SLICE – Zero-G Fluid Experiment</h3>
          <p>Engineered CAD system for human-tended zero-gravity flight experiment with Virgin Galactic. Automated 300mL flow-through system using Arduino control and performed FEA on composite structures.</p>
          <a href="/projects/website/purdue-slice/" class="item-link">View Details →</a>
        </div>
      </div>
    </div>
    <!-- Senior Design -->
    <div class="exp-proj-item">
      <div class="item-content">
        <img src="/images/451_CAD.jpeg" class="item-preview" alt="Senior Design Fixed-Wing UAV">
        <div class="item-details">
          <h3>Senior Design – Fixed-Wing UAV</h3>
          <p>Co-led CAD design of remotely piloted aircraft optimized for structural integrity and manufacturability. Performed wing loading, shear/bending, and aerodynamic analysis for flight.</p>
          <a href="/projects/website/senior-design/" class="item-link">View Details →</a>
        </div>
      </div>
    </div>
    <!-- Golf Cart -->
    <div class="exp-proj-item">
      <div class="item-content">
        <img src="/images/Golfcart_motor.jpeg" class="item-preview" alt="Remote-Controlled Golf Cart">
        <div class="item-details">
          <h3>Remote-Controlled Golf Cart</h3>
          <p>Designed and built a remote-controlled golf cart using C++ with Arduino, motor drivers, nRF24L01 radio, and motion tracking sensors. Combined hardware and software development in a collaborative project.</p>
          <a href="/projects/website/golf-cart/" class="item-link">View Details →</a>
        </div>
      </div>
    </div>
  </div>
</div>
