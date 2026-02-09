---
layout: page
---

<style>
  /* 1. Import Xanh Mono + Lora for body text */
  @import url('https://fonts.googleapis.com/css2?family=Xanh+Mono:ital@0;1&family=Lora:ital,wght@0,400;0,700;1,400&display=swap');

  /* Apply the new background color to the entire site */
  html, body {
    background-color: #edf4f8; /* Your light blue color */
    margin: 0;
    padding: 0;
    min-height: 100%;
  }

  /* Ensure the main container doesn't have a white background */
  .wrapper, .page-content {
    background-color: transparent !important;
  }

  /* 2. Apply Xahn Mono to Headings */
  h1, h2, h3 {
    font-family: 'Xanh Mono', monospace; /* Fixed font name */
    font-weight: 400;
    letter-spacing: 0.5px;
  }

  /* Sticky Menu */
  .sticky-menu {
    position: sticky;
    top: 0;
    background-color: #edf4f8;
    padding: 15px 0;
    text-align: center;
    width: 100%;
    z-index: 1000;
    box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    margin-bottom: 40px;
  }

  .sticky-menu a {
    font-family: 'Xanh Mono', monospace;
    color: #444;
    text-decoration: none;
    font-weight: 400;      
    letter-spacing: 1.5px; 
    margin: 0 25px;
    font-size: 1rem;
    transition: 0.2s;
    padding: 5px 10px;
    border-radius: 3px;
  }

  .sticky-menu a:hover {
    text-decoration: underline;
    color: #000;
    background-color: rgba(255,255,255,0.2);
  }

  /* Body text font */
  body {
    font-family: 'Xanh Mono', monospace; 
    line-height: 1.6;
  }

  /* Sections spacing */
  section {
    margin-bottom: 60px;
    padding-bottom: 40px;
    border-bottom: 1px solid rgba(0,0,0,0.1);
  }

  section:last-of-type {
    border-bottom: none;
  }

  /* Remove horizontal rules (they were the --- lines) */
  hr {
    display: none;
  }

  /* Entry styling */
  .entry {
    margin-bottom: 30px;
    padding-left: 20px;
    position: relative;
  }

  .entry:before {
    content: "";
    position: absolute;
    left: 0;
    top: 0;
    bottom: 0;
    width: 2px;
    background-color: #444;
  }

  .date {
    display: block;
    font-size: 0.85rem;
    color: #666;
    margin-bottom: 5px;
    font-family: 'Xanh Mono', monospace;
    letter-spacing: 0.5px;
  }

  /* Skills horizontal layout */
  .skills-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 40px;
    margin-top: 20px;
  }

  .skills-grid > div {
    background-color: rgba(255,255,255,0.3);
    padding: 25px;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.05);
  }

  .skills-grid p {
    margin-top: 0;
    margin-bottom: 15px;
    font-weight: bold;
  }

  .skills-grid ul {
    margin: 0;
    padding-left: 20px;
  }

  .skills-grid li {
    margin-bottom: 8px;
  }

  /* Section titles */
  h2 {
    color: #333;
    margin-bottom: 25px;
    padding-bottom: 10px;
    border-bottom: 2px solid #444;
    display: inline-block;
  }

  /* Footer Styling */
.footer {
  margin-top: 60px;
  padding: 30px 0;
  text-align: center;
  border-top: 1px solid rgba(0,0,0,0.1);
  background-color: rgba(255,255,255,0.2);
}

.social-links {
  display: flex;
  justify-content: center;
  gap: 30px;
  margin-top: 15px;
}

.social-link {
  display: flex;
  align-items: center;
  gap: 10px;
  color: #444;
  text-decoration: none;
  font-family: 'Xanh Mono', monospace;
  font-size: 0.95rem;
  transition: all 0.2s ease;
  padding: 10px 20px;
  border-radius: 4px;
}

.social-link:hover {
  background-color: rgba(255,255,255,0.3);
  color: #000;
  transform: translateY(-2px);
}

/* Fixed icon size */
.social-icon {
  width: 18px;  /* Reduced from 20px */
  height: 18px; /* Reduced from 20px */
  fill: currentColor;
}

/* Copyright text */
.copyright {
  margin-top: 20px;
  font-size: 0.85rem;
  color: #666;
  font-family: 'Xanh Mono', monospace;
}

</style>

<!-- Sticky Navigation Menu -->
<nav class="sticky-menu">
  <a href="#education">Education</a>
  <a href="#research">Research</a>
  <a href="#skills">Skills</a>
</nav>

<section id="education">
  <h2>Education</h2>
  <p><em>Since my undergraduate studies, I have pursued an interdisciplinary academic path focused on research. I have developed solid skills in scientific communication, literature review, and hands-on experience in collaborative and autonomous work.</em></p>

  <div class="entry">
    <span class="date">09/2023 - 06/2025</span>
    <p><strong>Master of Biosciences and Modelling of Complex Systems</strong><br>
    <small>École Normale Supérieure de Lyon, France</small><br>
    Modules: Machine Learning, Modelling for Biology, Complex Networks, Genomics, Biophysics.</p>
  </div>

  <div class="entry">
    <span class="date">09/2022 - 06/2023</span>
    <p><strong>Bachelor of Biosciences</strong><br>
    <small>École Normale Supérieure de Lyon, France</small><br>
    Modules: Programming, Biostatistics, Immunology. Includes 8-week practical in biochemistry.</p>
  </div>

  <div class="entry">
    <span class="date">09/2019 - 06/2022</span>
    <p><strong>Bachelor in Experimental Sciences</strong><br>
    <small>Université Paris Sciences et Lettres (PSL), France</small><br>
    Passed with high honours. Focus on Biology, Informatics, and Physics.</p>
  </div>
</section>

<section id="research">
  <h2>Research Experience</h2>

  <div class="entry">
    <span class="date">09/2025 – Today</span>
    <p><strong>Deciphering Mechanisms of Tumor Maintenance in Oral Epithelium</strong><br>
    <em>CRCL, France | Supervised by Elsa Guillot & Arnaud Bonnaffoux</em><br>
    Building a digital twin using an agent-based framework (**PhysiCell**). Performing sensibility analysis to study homeostasis and tumor maintenance.</p>
  </div>

  <div class="entry">
    <span class="date">01/2025 – 06/2025</span>
    <p><strong>Modelling the Extracellular Matrix in Three Dimensions</strong><br>
    <em>Barcelona Supercomputing Center, Spain | Supervised by Marco Ruscone</em><br>
    Extended **PhysiMeSS** for 3D simulations. Developed mechanics in **C++**, tested on **MareNostrum5**, and built data pipelines in **Python/Bash**.</p>
  </div>

  <div class="entry">
    <span class="date">02/2024 – 06/2024</span>
    <p><strong>Dynamics of Hematopoeisis in Health and Disease</strong><br>
    <em>MacSys, University of Melbourne | Supervised by Michael Stumpf</em><br>
    Developed an agent-based model in **Julia** to simulate cell population dynamics.</p>
  </div>

  <div class="entry">
    <span class="date">04/2023 – 07/2023</span>
    <p><strong>Simulation of Recombination Hotspots Evolution</strong><br>
    <em>LBBE, Université Lyon 1, France | Supervised by Laurent Duret</em><br>
    Built a pipeline to simulate genomes in **SliM**, analyzed Linkage Disequilibrium with **LDhelmet**, and gBGC in **R**.</p>
  </div>
</section>

<section id="skills">
  <h2>Skills</h2>
  <div class="skills-grid">
    <div>
      <p><strong>Programming</strong></p>
      <ul>
        <li>Proficient: Python, Julia</li>
        <li>Intermediate: C++, R, Bash, LaTeX</li>
        <li>Basics: SliM/Eidos</li>
      </ul>
    </div>
    <div>
      <p><strong>Tools & Methods</strong></p>
      <ul>
        <li>Git & CPU clusters</li>
        <li>PhysiCell, PyVista, ParaView</li>
        <li>Data Pipelines (Python/R)</li>
      </ul>
    </div>
    <div>
      <p><strong>Languages</strong></p>
      <ul>
        <li>French & English (Fluent)</li>
        <li>German & Spanish (Notions)</li>
      </ul>
    </div>
  </div>
</section>

