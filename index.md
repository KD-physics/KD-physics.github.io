---
title: "Kenneth Desmond, Ph.D. | Random Close Packing (RCP) & Soft Matter Physics"
description: "Independent researcher | Research and software by Kenneth Desmond, Ph.D. Featuring rcpgenerator for high-density sphere packing, acoustic sensing, and soft-matter simulation toolkits."
keywords: ["random close packing", "dense packing", 'python', jammed state","particle simulator","acoustic sensing","wave propagation","soft matter","deep learning"]
---

<style>
  .profile-header {
    display: flex;
    align-items: flex-start;
    gap: 2rem;
    margin-bottom: 2rem;
  }
  .left-column {
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  .left-column img {
    width: 180px;
    height: 180px;
    object-fit: cover;
    border-radius: 50%;
  }
  .contact-links {
    display: flex;
    flex-direction: column;
    align-items: flex-start;       /* left-align everything */
    gap: 0.25rem;                  /* smaller gap between items */
    font-size: 0.9rem;
    margin-top: 0.25rem;           /* reduce top margin */
  }
  .contact-links p {
    margin: 0;                     /* remove default paragraph margins */
    line-height: 1.2;              /* tighten line spacing */
  }
  .contact-links a {
    margin-top: 0.25rem;           /* small space before links */
    text-decoration: none;
    color: #0366d6;
  }
  .contact-links a:hover {
    text-decoration: underline;
  }

  /* ── Sticky nav bar ──────────────────────────────────────────── */
  html { scroll-padding-top: 52px; }
  .site-nav {
    position: sticky;
    top: 0;
    z-index: 900;
    background: #fff;
    border-bottom: 1px solid #e1e4e8;
    box-shadow: 0 1px 3px rgba(0,0,0,0.08);
    display: flex;
    align-items: center;
    flex-wrap: wrap;
    padding: 0 0.4rem;
    min-height: 42px;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
    font-size: 0.82rem;
    margin-bottom: 1rem;
  }
  .site-nav .nav-name {
    font-weight: 700;
    color: #24292e;
    padding: 0 0.7rem 0 0.2rem;
    border-right: 1px solid #d0d7de;
    margin-right: 0.3rem;
    line-height: 42px;
    flex-shrink: 0;
  }
  .site-nav a {
    color: #586069;
    text-decoration: none;
    padding: 0 0.55rem;
    line-height: 42px;
    white-space: nowrap;
    transition: color 0.15s;
  }
  .site-nav a:hover {
    color: #0366d6;
    text-decoration: none;
  }
  @media (max-width: 580px) {
    .site-nav .nav-name { display: none; }
    .site-nav a { padding: 0 0.32rem; font-size: 0.74rem; }
  }
</style>


<script>
  // Hide the default site title if needed
  document.querySelector('header > a')?.style.setProperty('display','none');
</script>

<nav class="site-nav">
  <span class="nav-name">Kenneth Desmond</span>
  <a href="#about">About</a>
  <a href="#code">Code</a>
  <a href="#research">Research</a>
  <a href="#prior-research">Prior Work</a>
  <a href="#publications">Publications</a>
  <a href="#education">Education</a>
  <a href="#connect">Connect</a>
</nav>

<span id="about"></span>

<div class="profile-header">
  <!-- Left column: photo + contact info -->
  <div class="left-column">
    <img src="images/me.png" alt="Kenneth Desmond" />
    <div class="contact-links">
      <p><strong>Physicist & Researcher</strong></p>
      <p>Former ExxonMobil Research Scientist</p>
      <p>Post Doc, UCSB</p>
      <p>PhD, Emory University</p>
      <p>BSc, Rochester Institute of Technology</p>
      <a href="https://www.linkedin.com/in/kenneth-desmond-7461257/">🔗 LinkedIn</a>
      <a href="https://scholar.google.com/citations?user=KqSFejcAAAAJ&hl=en">🎓 Google Scholar</a>
    </div>
  </div>

  <!-- Right column: welcome & about -->
  <div>
    <h2>👋 Welcome</h2>
    <p>
      I’m an independent researcher pursuing research in soft matter physics and acoustic sensing.
    </p>
    <ul>
      <li>Particle-size distribution effects in RCP</li>
      <li>Acoustic-based navigation & sensing (“BatBot”)</li>
      <li>Deformable-particle models for soft-matter simulations</li>
    </ul>
    <p>Feel free to explore my code or reach out via GitHub issues!</p>
  </div>
</div>


---

<span id="code"></span>

## Current Code & Repositories Available

### Generating Dense Spherical Packings 
🔗 [GitHub ↗ Random Close Packing Generator - Code for densely packing particles](https://github.com/KD-physics/RCPGenerator) | [Link to Mathworks File Exchange ↗](https://www.mathworks.com/matlabcentral/fileexchange/181165-random-close-packing-generator-in-arbitrary-dimensions) | 🔗 [Python Implementation Guide ↗](https://kd-physics.github.io/notes/packing-spheres-python.html) | 🔗 [Run in Colab ↗](https://colab.research.google.com/github/KD-physics/RCPGenerator/blob/main/getting_started.ipynb) - Python, C++, and MATLAB code for generating dense random packings of polydisperse particles in arbitrary dimensions with periodic or hard boundaries. Boundaries may be flat or curved (e.g., spherical), allowing many types of packing geometries. The code can generate packings such as spheres packed in a box, disks packed in a 2D box or circle, and 3D spheres packed in rectangular boxes, spheres, or cylinders. The framework generalizes naturally to higher dimensions and has been tested for sphere packings up to seven dimensions.

### Simulating Squishy 2D Particles with Stiff Perimeters
🔗 [GitHub ↗ Squishy Particle Simulator](https://github.com/KD-physics/Squishy-Particle-Simulator) 

---

<span id="research"></span>

## Current Research

### N-Dimensional Random Close Packing Generator  
🔗 [GitHub ↗](https://github.com/KD-physics/RCPGenerator)   
A fast, flexible toolkit (C++, MATLAB, Python) for generating **random close packings**, **dense packings**, and **jammed states** of spheres in 2–N dimensions.  

| ![Ex1](images/example1.png) | ![Ex2](images/example2.png) | ![Ex3](images/example3.png) | ![Ex4](images/example4.png) |
|:---------------------------:|:---------------------------:|:---------------------------:|:---------------------------:|
| 2D Confined Packing | Dense packing confined within circular container                  | Cylindrically confined packing with upper and lower hard boundaries.                   | Spherically confined packing.                  |


### Squishy Particle Simulator  
🔗 [GitHub ↗](https://github.com/KD-physics/Squishy-Particle-Simulator) 
A MATLAB-based 2D deformable-polygon model for “squishy” particles. Includes core engine, example scripts, and GIFs showcasing deformation and flow.  

| ![Ex1](images/Gravity.gif) | ![Ex2](images/HexCouette_Soft.gif) | ![Ex3](images/SimpleShearMedium.gif) |
|:---------------------------:|:---------------------------:|:---------------------------:|
| Deformable ellipses falling under gravity | Fun couette geometry  | Simple shear                  | 


---

<span id="prior-research"></span>

## Prior Research


<style>
#prt{margin:1.5rem 0 2rem;font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Helvetica,Arial,sans-serif}
#prt .prt-nav{display:flex;flex-wrap:wrap;border-bottom:2px solid #e1e4e8;margin-bottom:0;gap:0}
#prt .prt-btn{background:none;border:none;padding:.55rem 1.15rem;cursor:pointer;font-size:.875rem;font-weight:600;color:#586069;border-bottom:3px solid transparent;margin-bottom:-2px;transition:color .15s,border-color .15s;white-space:nowrap}
#prt .prt-btn:hover{color:#0366d6}
#prt .prt-btn.prt-on{color:#0366d6;border-bottom-color:#0366d6}
#prt .prt-bar-wrap{height:2px;background:#e1e4e8;margin-bottom:1.25rem}
#prt .prt-bar{height:2px;background:#0366d6;width:0%;transition:width .1s linear}
#prt .prt-panel{display:none}
#prt .prt-panel.prt-on{display:block}
#prt .prt-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(210px,1fr));gap:1rem}
#prt .prt-card{border:1px solid #e1e4e8;border-radius:6px;overflow:hidden;display:flex;flex-direction:column;background:#fff;transition:box-shadow .15s}
#prt .prt-card:hover{box-shadow:0 4px 14px rgba(0,0,0,.11)}
#prt .prt-img{height:130px;overflow:hidden;background:#f6f8fa;flex-shrink:0}
#prt .prt-img img{width:100%;height:100%;object-fit:cover;display:block}
#prt .prt-noimg{height:130px;background:linear-gradient(135deg,#f0f3f7,#dce3eb);display:flex;align-items:center;justify-content:center;font-size:2.4rem}
#prt .prt-body{padding:.7rem .8rem;flex:1;display:flex;flex-direction:column}
#prt .prt-title{font-weight:600;font-size:.84rem;color:#24292e;margin:0 0 .35rem;line-height:1.4}
#prt .prt-desc{font-size:.78rem;color:#586069;line-height:1.52;flex:1;margin:0 0 .55rem}
#prt .prt-link{font-size:.8rem;color:#0366d6;text-decoration:none;font-weight:500}
#prt .prt-link:hover{text-decoration:underline}
</style>

<div id="prt">

<div class="prt-nav">
  <button class="prt-btn prt-on" data-i="0">Emulsions</button>
  <button class="prt-btn" data-i="1">Granular Matter</button>
  <button class="prt-btn" data-i="2">Packing</button>
  <button class="prt-btn" data-i="3">Colloidal Dynamics</button>
  <button class="prt-btn" data-i="4">Wave Mechanics</button>
  <button class="prt-btn" data-i="5">Adhesion</button>
</div>
<div class="prt-bar-wrap"><div class="prt-bar" id="prt-bar"></div></div>

<!-- TAB 0: JAMMING -->
<div class="prt-panel prt-on" id="prt-p0">
<div class="prt-grid">

<div class="prt-card">
  <div class="prt-img"><img src="projects/images/forces-chain-image.png" alt="Force chain network in a 2D jammed emulsion"/></div>
  <div class="prt-body">
    <p class="prt-title">Forces Between Quasi-2D Emulsion Droplets Near Jamming</p>
    <p class="prt-desc">Contact forces extracted from droplet shape deformation reveal critical scaling of pressure and coordination number near the jamming transition, confirming the spatial randomness of force chain networks.</p>
    <a class="prt-link" href="projects/forces-between-2d-droplets.html">Details →</a>
  </div>
</div>

<div class="prt-card">
  <div class="prt-img"><img src="projects/images/force-network-hopper.gif" alt="Evolving force chain network in a flowing dense emulsion"/></div>
  <div class="prt-body">
    <p class="prt-title">Stress Redistribution in Flowing Dense Emulsions</p>
    <p class="prt-desc">T1 rearrangement events in a flowing quasi-2D emulsion redistribute stress in a quadrupolar pattern, directly linking local particle rearrangements to macroscopic soft glassy flow behavior.</p>
    <a class="prt-link" href="projects/stress-propagation-2d-emulsion.html">Details →</a>
  </div>
</div>

</div>
</div>

<!-- TAB 1: GRANULAR MATTER -->
<div class="prt-panel" id="prt-p1">
<div class="prt-grid">

<div class="prt-card">
  <div class="prt-img"><img src="projects/images/FlowField.gif" alt="PIV flow field of granular intrusion"/></div>
  <div class="prt-body">
    <p class="prt-title">Penetration of an Object into Granular Media</p>
    <p class="prt-desc">MRI imaging combined with PIV reveals the 3D velocity field of granular material flowing around a penetrating intruder, making internal flow structure visible for the first time.</p>
    <a class="prt-link" href="projects/granular-flow.html">Details →</a>
  </div>
</div>

<div class="prt-card">
  <div class="prt-img"><img src="projects/images/nails.jpg" alt="Pile of acrylic rods suspended by entanglement"/></div>
  <div class="prt-body">
    <p class="prt-title">Jamming of Three-Dimensional Prolate Granular Materials</p>
    <p class="prt-desc">High-aspect-ratio acrylic rods (aspect ratio &gt;35) form self-supporting, wall-free piles through particle entanglement alone, demonstrating a shape-driven jamming transition.</p>
    <a class="prt-link" href="projects/jamming-of-rods.html">Details →</a>
  </div>
</div>

<div class="prt-card">
  <div class="prt-img"><img src="projects/images/granular-rheology-apparatus.png" alt="Rotating drum apparatus with oscillatory secondary forcing"/></div>
  <div class="prt-body">
    <p class="prt-title">Rheology of Fluidized Granular Matter</p>
    <p class="prt-desc">Secondary oscillatory forcing applied to a rotating drum of fluidized glass beads reveals non-Newtonian rheology that is well described by the GDR-Midi model at low forcing but breaks down when forcing becomes faster than the material's viscous relaxation time.</p>
    <a class="prt-link" href="projects/granular-rheology.html">Details →</a>
  </div>
</div>

</div>
</div>

<!-- TAB 2: PACKING -->
<div class="prt-panel" id="prt-p2">
<div class="prt-grid">

<div class="prt-card">
  <div class="prt-img"><img src="projects/images/rcpalgorithmmov2.gif" alt="Animation of RCP algorithm evolving"/></div>
  <div class="prt-body">
    <p class="prt-title">Random Close Packing Algorithm</p>
    <p class="prt-desc">An iterative swell–contract–minimize particle packing algorithm generates random close packings of 2D hard disks and 3D hard spheres. The animation shows a packing evolving from a random start to a jammed configuration.</p>
    <a class="prt-link" href="projects/rcp-algorithm.html">Details →</a>
  </div>
</div>

<div class="prt-card">
  <div class="prt-img"><img src="projects/images/CircleRCP.png" alt="RCP in a circular container showing wall layering"/></div>
  <div class="prt-body">
    <p class="prt-title">Random Close Packing in Confined Geometries</p>
    <p class="prt-desc">Hard-wall boundaries alter packing structure near container walls. An extended algorithm generates confined RCPs and quantifies the wall-induced layering effect on local packing fraction.</p>
    <a class="prt-link" href="projects/confined-rcp.html">Details →</a>
  </div>
</div>

<div class="prt-card">
  <div class="prt-img"><img src="projects/images/2dRCP.png" alt="2D random close packing of binary disks"/></div>
  <div class="prt-body">
    <p class="prt-title">Influence of Particle Size Distribution on RCP</p>
    <p class="prt-desc">Large-scale packing simulations map how size-distribution shape (width, skewness) affects the achievable hard-sphere packing fraction, yielding quantitative scaling laws for polydisperse granular and colloidal systems.</p>
    <a class="prt-link" href="projects/rcp-polydispersity.html">Details →</a>
  </div>
</div>

<div class="prt-card">
  <div class="prt-img"><img src="projects/images/EllipsoidalPacking.gif" alt="Animation of randomly packed ellipsoids"/></div>
  <div class="prt-body">
    <p class="prt-title">Ellipsoidal Packing</p>
    <p class="prt-desc">Dense random packings of ellipsoidal particles exceed the ~64% hard-sphere packing fraction limit. Aspect ratio and polydispersity effects on packing fraction and structure were systematically characterized.</p>
    <a class="prt-link" href="projects/ellipsoidal-packing.html">Details →</a>
  </div>
</div>

</div>
</div>

<!-- TAB 3: COLLOIDAL DYNAMICS -->
<div class="prt-panel" id="prt-p3">
<div class="prt-grid">

<div class="prt-card">
  <div class="prt-img"><img src="projects/images/ellipsoids2.gif" alt="Synthesized ellipsoids diffusing in solution"/></div>
  <div class="prt-body">
    <p class="prt-title">Ellipsoidal Diffusion Microrheology</p>
    <p class="prt-desc">Measuring both translational and rotational Brownian fluctuations of ellipsoidal tracers simultaneously determines the viscoelastic modulus without requiring precise knowledge of particle dimensions.</p>
    <a class="prt-link" href="projects/ellipsoidal-diffusion.html">Details →</a>
  </div>
</div>

<div class="prt-card">
  <img class="prt-img" src="projects/images/dh_frame19c0028_e.png" alt="Mobile colloidal particles near glass transition">
  <div class="prt-body">
    <p class="prt-title">Spatial and Temporal Dynamical Heterogeneities Approaching the Binary Colloidal Glass Transition</p>
    <p class="prt-desc">Near the colloidal glass transition, mobile particles (red) cluster into large cooperative regions while most of the sample is arrested (blue). The four-point susceptibility &#967;&#8324; quantifies this growing spatial and temporal heterogeneity.</p>
    <a class="prt-link" href="projects/four-point-colloids.html">Details →</a>
  </div>
</div>

</div>
</div>

<!-- TAB 4: WAVE MECHANICS -->
<div class="prt-panel" id="prt-p4">
<div class="prt-grid">

<div class="prt-card">
  <div class="prt-img"><img src="KrauklisWaves/images/Setup.JPG" alt="Experimental setup for Krauklis wave measurement"/></div>
  <div class="prt-body">
    <p class="prt-title">Wave Propagation in Fractures</p>
    <p class="prt-desc">Generating and monitoring acoustic Krauklis waves in synthetic fractures to probe fracture geometry and fluid content — with applications to geophysical monitoring.</p>
    <a class="prt-link" href="KrauklisWaves/">Details →</a>
  </div>
</div>

</div>
</div>

<!-- TAB 5: ADHESION -->
<div class="prt-panel" id="prt-p5">
<div class="prt-grid">

<div class="prt-card">
  <div class="prt-img"><img src="projects/images/mussel-experiment.gif" alt="Mussel plaque being pulled to detachment"/></div>
  <div class="prt-body">
    <p class="prt-title">Dynamics of Mussel Plaque Detachment</p>
    <p class="prt-desc">Plastic yielding of the mussel plaque and mushroom-shaped holdfast geometry together provide a 100–1000× enhancement in bond strength over chemistry alone, revealed by a custom dual-imaging load frame.</p>
    <a class="prt-link" href="projects/mussel-plaque-detachment.html">Details →</a>
  </div>
</div>

</div>
</div>

<script>
(function(){
  var CYCLE = 5000, TICK = 60;
  var btns   = document.querySelectorAll('#prt .prt-btn');
  var panels = document.querySelectorAll('#prt .prt-panel');
  var bar    = document.getElementById('prt-bar');
  var box    = document.getElementById('prt');
  var cur = 0, elapsed = 0, paused = false;

  function show(i) {
    btns.forEach(function(b,j){ b.classList.toggle('prt-on', j===i); });
    panels.forEach(function(p,j){ p.classList.toggle('prt-on', j===i); });
    cur = i; elapsed = 0;
    if(bar) bar.style.width = '0%';
  }

  btns.forEach(function(b, i){
    b.addEventListener('click', function(){ show(i); });
  });

  box.addEventListener('mouseenter', function(){ paused = true; });
  box.addEventListener('mouseleave', function(){ paused = false; });

  setInterval(function(){
    if(paused) return;
    elapsed += TICK;
    if(bar) bar.style.width = Math.min(100, elapsed / CYCLE * 100) + '%';
    if(elapsed >= CYCLE) show((cur + 1) % btns.length);
  }, TICK);
}());
</script>

</div>





---

<span id="publications"></span>

## 📚 Publications & Patents

### Publications

| #  | Title                                                                                                                                                             | Year |
| -- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- | :--: |
| 14 | [**Clogging and avalanches in quasi-2D emulsion hopper flow**](https://doi.org/10.1103/PhysRevE.105.014603)<br>*X. Hong, K.W. Desmond, D. Chen, E.R. Weeks.* Phys. Rev. E 105(1), 014603 | 2022 |
| 13 | [**Encoded injection of microbubbles to improve flow velocity measurements using cross-correlation technique**](https://doi.org/10.1088/1361-6501/abe96b)<br>*K.W. Desmond, G.L. Hunter.* Meas. Sci. Technol. 32(8), 085302 | 2021 |
| 12 | [**3D generalized finite element method for wave propagation in fluid-filled fractures**](https://doi.org/10.1016/j.cma.2021.114136)<br>*N. Shauer, K.W. Desmond, P.A. Gordon, F. Liu, C.A. Duarte.* CMAME 386, 114136 | 2021 |
| 11 | [**Sensitivity of coda wave interferometry to fluid migration through rock**](https://doi.org/10.1121/1.5091697)<br>*K.W. Desmond, J.J. Valenza.* J. Acoust. Soc. Am. 145(2), 1100–1104 | 2019 |
| 10 | [**Experimental observation of local rearrangements in dense quasi-2D emulsion flow**](https://doi.org/10.1103/PhysRevE.91.062306)<br>*D. Chen, K.W. Desmond, E.R. Weeks.* Phys. Rev. E 91(6), 062306 | 2015 |
| 9  | [**Dynamics of mussel plaque detachment**](https://doi.org/10.1039/C5SM01072A)<br>*K.W. Desmond, N.A. Zacchia, J.H. Waite, M.T. Valentine.* Soft Matter 11(34), 6832–6839 | 2015 |
| 8  | [**Measurement of stress redistribution in flowing emulsions**](https://doi.org/10.1103/PhysRevLett.115.098302)<br>*K.W. Desmond, E.R. Weeks.* Phys. Rev. Lett. 115(9), 098302 | 2015 |
| 7  | [**Influence of particle size distribution on random close packing of spheres**](https://doi.org/10.1103/PhysRevE.90.022204)<br>*K.W. Desmond, E.R. Weeks.* Phys. Rev. E 90(2), 022204 | 2014 |
| 6  | [**Rheology of fluidized granular matter**](https://doi.org/10.1103/PhysRevE.88.032202)<br>*K.W. Desmond, U. Villa, M. Newey, W. Losert.* Phys. Rev. E 88(3), 032202 | 2013 |
| 5  | [**Experimental study of forces between quasi-2D emulsion droplets near jamming**](https://doi.org/10.1039/C3SM27287G)<br>*K.W. Desmond, P.J. Young, D. Chen, E.R. Weeks.* Soft Matter 9(12), 3424–3436 | 2013 |
| 4  | [**Stress fluctuations in 2D hopper flow**](https://doi.org/10.1039/C2SM26023A)<br>*D. Chen, K.W. Desmond, E.R. Weeks.* Soft Matter 8(40), 10486–10492 | 2012 |
| 3  | [**Dynamical heterogeneities near colloidal glass transition**](https://doi.org/10.1039/C0SM00756K)<br>*T. Narumi, S.V. Franklin, K.W. Desmond, M. Tokuyama, E.R. Weeks.* Soft Matter 7(4), 1472–1482 | 2011 |
| 2  | [**Random close packing in confined geometries**](https://doi.org/10.1103/PhysRevE.80.051305)<br>*K.W. Desmond, E.R. Weeks.* Phys. Rev. E 80(5), 051305 | 2009 |
| 1  | [**Jamming of three-dimensional prolate granular materials**](https://doi.org/10.1103/PhysRevE.73.031306)<br>*K. Desmond, S.V. Franklin.* Phys. Rev. E 73(3), 031306 | 2006 |

### Patents

| # | Title                                                                                                                                                                                      | Year |
| - | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | :--: |
| 5 | **Systems and methods for measuring cluster efficiency using broadband tube waves**<br>*B.D. Wheelock, P.A. Gordon, L. Song, K.W. Desmond, Y. Zhang.* US Pat. 12,130,399                   | 2024 |
| 4 | **Estimates of flow velocity with controlled spatio-temporal variations in contrast media properties**<br>*K.W. Desmond, G.L. Hunter.* US Pat. 11,573,108                                  | 2023 |
| 3 | **Method and system for performing wireless ultrasonic communications along tubular members**<br>*T.F. Kinn, X. Yi, S.W. Clawson, M.M. Disko, K.W. Desmond, J.H. Moss.* US Pat. 11,203,927 | 2021 |
| 2 | **Estimating flow velocity in pipes by correlating multi-frequency signals**<br>*K.W. Desmond, G.L. Hunter.* US Pat. App. 16/190,734                                                       | 2019 |
| 1 | **Electrode materials with mixed particle sizes**<br>*Z.C. Tim Holme, K. Desmond, W\.A. Hermann, J. Han.* US Pat. 20,150,357,644                                                           | 2015 |


<span id="education"></span>

## 🎓 Education

| Degree              | Institution                             |   Year  | Advisor                                                                  |
| ------------------- | --------------------------------------- | :-----: | ------------------------------------------------------------------------ |
| PhD Physics         | Emory University                        |   2012  | [Eric R. Weeks](https://faculty.college.emory.edu/sites/weeks/)          |
| BSc (Physics)       | Rochester Institute of Technology       |   2006  | [Scott V. Franklin](https://www.rit.edu/directory/svfsps-scott-franklin) |
| Postdoctoral Fellow | University of California, Santa Barbara | 2012–14 | [Megan J. Valentine](https://valentine.me.ucsb.edu/)                     |

**Google Scholar profile:**  

🔗 [Google Scholar](https://scholar.google.com/citations?user=KqSFejcAAAAJ&hl=en) 

<span id="connect"></span>

## 🏷 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kenneth-desmond-7461257/)

<hr>

<div style="font-size:0.85rem; color:#666; margin-top:2rem">
<h3>Site Index</h3>

<ul>
<li><a href="/projects/forces-between-2d-droplets.html">Forces Between Quasi-2D Emulsion Droplets Near Jamming</a></li>
<li><a href="/projects/stress-propagation-2d-emulsion.html">Stress Redistribution in Flowing Dense Emulsions</a></li>
<li><a href="/projects/granular-flow.html">Penetration of an Object into Granular Media</a></li>
<li><a href="/projects/jamming-of-rods.html">Jamming of Three-Dimensional Prolate Granular Materials</a></li>
<li><a href="/projects/granular-rheology.html">Rheology of Fluidized Granular Matter</a></li>
<li><a href="/projects/rcp-algorithm.html">Random Close Packing Algorithm</a></li>
<li><a href="/projects/confined-rcp.html">Random Close Packing in Confined Geometries</a></li>
<li><a href="/projects/rcp-polydispersity.html">Influence of Particle Size Distribution on RCP</a></li>
<li><a href="/projects/ellipsoidal-packing.html">Ellipsoidal Packing</a></li>
<li><a href="/projects/ellipsoidal-diffusion.html">Ellipsoidal Diffusion Microrheology</a></li>
<li><a href="/projects/four-point-colloids.html">Dynamical Heterogeneities in Colloidal Glass</a></li>
<li><a href="/KrauklisWaves/">Wave Propagation in Fractures</a></li>
<li><a href="/projects/mussel-plaque-detachment.html">Dynamics of Mussel Plaque Detachment</a></li>
</ul>

</div>

*Last updated: 2026-03-17*  




