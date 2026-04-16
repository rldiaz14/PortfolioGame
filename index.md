---
layout: default
title: "Home"
---


<!-- HERO -->
<section id="hero">
  <div class="hero-glow"></div>
  <div class="hero-glow2"></div>
  <div class="hero-tag">Game Developer & AI Engineer</div>
  <h1 class="hero-name">
    Ramon L.
    <span class="highlight">Diaz<span class="cursor"></span></span>
  </h1>
  <div class="hero-role">Building worlds · Training agents · Exploring realities</div>
  <p class="hero-desc">
    CS graduate from Drexel University. I build games that push boundaries — from
    procedurally generated worlds to AI-driven agents. Interested in AR/VR, deep
    reinforcement learning, and the intersection of play and intelligence.
  </p>
  <div class="hero-cta">
   <a href="#projects" class="hero-btn-primary">View Projects</a>
   <a href="#contact" class="hero-btn-secondary">Get in Touch</a>
  </div>
</section>





<!-- ABOUT -->
<section id="about" class="container py-5 mt-5">
  <h2 class="mb-4">About</h2>
  <div class="row g-4 align-items-center">
    <div class="col-md-4 text-center">
      <div class="image-placeholder">
        <p>Photo</p>
      </div>
    </div>
    <div class="col-md-8">
      <p>I'm <strong>Ramon L. Diaz</strong>, a game developer and AI engineer based in Pennsylvania.</p>
      <p>M.S. in Artificial Intelligence and Machine Learning from <strong>Drexel University</strong>. B.S. in Game Development from <strong>SNHU</strong>.</p>
      <p>I build at the crossroads of games and AI - focused on <strong>reinforcement learning</strong>, <strong>computer vision</strong>, and <strong>AR/VR</strong>.</p>
      <p>Research work lives on my <a href="https://rldiaz14.github.io/rldiaz.github.io">academic site</a>.</p>
    </div>
  </div>
</section>

<!-- SKILLS -->
<section id="skills" class="container py-5">
  <h2 class="mb-4">Skills</h2>
  <div class="row g-4">
    <div class="col-sm-6 col-lg-3">
      <div class="skill-cluster p-3 h-100">
        <h5>Game Engines</h5>
        <ul class="mt-2">
          <li>Unity (C#)</li>
          <li>Unreal Engine 5 (C++ / Blueprints)</li>
          <li>Godot</li>
          <li>AR Foundation / XR Toolkit</li>
        </ul>
      </div>
    </div>
    <div class="col-sm-6 col-lg-3">
      <div class="skill-cluster p-3 h-100">
        <h5>AI / ML</h5>
        <ul class="mt-2">
          <li>Deep Reinforcement Learning</li>
          <li>Computer Vision (OpenCV, YOLO)</li>
          <li>PyTorch / TensorFlow</li>
          <li>ML-Agents (Unity)</li>
        </ul>
      </div>
    </div>
    <div class="col-sm-6 col-lg-3">
      <div class="skill-cluster p-3 h-100">
        <h5>Languages</h5>
        <ul class="mt-2">
          <li>Python</li>
          <li>C# / C++</li>
          <li>JavaScript / HTML / CSS</li>
          <li>GLSL (shaders)</li>
        </ul>
      </div>
    </div>
    <div class="col-sm-6 col-lg-3">
      <div class="skill-cluster p-3 h-100">
        <h5>Research and Tools</h5>
        <ul class="mt-2">
          <li>Procedural Content Generation</li>
          <li>Digital Twin modeling</li>
          <li>Git / GitHub</li>
          <li>Blender (3D assets)</li>
        </ul>
      </div>
    </div>
  </div>
</section>

<!-- PROJECTS -->
<section id="projects" class="section container">
  <div class="section-header">
    <span class="section-num">01</span>
    <h2 class="section-title">Projects</h2>
    <div class="section-line"></div>
  </div>

  <div class="projects-grid">

    <div class="project-card fade-in">
      <span class="project-num">01</span>
      <div class="project-tag-row">
        <span class="ptag ptag-cyan">AR/VR</span>
        <span class="ptag ptag-gray">Unity</span>
      </div>
      <h3>Project 1</h3>
      <p>Project description goes here.</p>
      <div class="project-links link-cyan">
        <a href="{{ '/portfolio/project-1/' | prepend: site.baseurl }}" class="project-link">View Project</a>
      </div>
    </div>

    <div class="project-card accent2 fade-in">
      <span class="project-num">02</span>
      <div class="project-tag-row">
        <span class="ptag ptag-purple">Deep RL</span>
        <span class="ptag ptag-gray">Python</span>
      </div>
      <h3>Project 2</h3>
      <p>Project description goes here.</p>
      <div class="project-links link-purple">
        <a href="{{ '/portfolio/project-2/' | prepend: site.baseurl }}" class="project-link purple">View Project</a>
      </div>
    </div>

    <div class="project-card accent3 fade-in">
      <span class="project-num">03</span>
      <div class="project-tag-row">
        <span class="ptag ptag-orange">PCG</span>
        <span class="ptag ptag-gray">Unreal</span>
      </div>
      <h3>Project 3</h3>
      <p>Project description goes here.</p>
      <div class="project-links orange">
        <a href="{{ '/portfolio/project-3/' | prepend: site.baseurl }}" class="project-link orange">View Project</a>
      </div>
    </div>

  </div>
</section>

<!-- CONTACT -->
<section id="contact" class="container py-5 text-center">
  <h2 class="mb-3">Contact</h2>
  <p>Open to collaborating on game projects, discussing AI research, or just talking StarCraft strategy.</p>
  <div class="d-flex justify-content-center gap-4 my-4">
    <a href="mailto:rldiaz14.1@gmail.com">Email</a>
    <a href="https://github.com/rldiaz14" target="_blank">GitHub</a>
    <a href="https://www.linkedin.com/in/rldiaz14/" target="_blank">LinkedIn</a>
    <a href="https://orcid.org/0009-0007-4248-3935" target="_blank">ORCID</a>
  </div>
  <div class="academic-callout p-4 mx-auto">
    <p>Looking for research, publications, or CV?</p>
    <a href="https://rldiaz14.github.io/rldiaz.github.io" target="_blank">Visit Academic Site</a>
  </div>
</section>