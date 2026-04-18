---
layout: default
title: Home
---

<div class="hero">

  <div class="hero-anim">
    <svg viewBox="0 0 400 320" class="c-svg" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Research topics">

      <!-- Outer hexagon frame -->
      <line class="c-ring-line" x1="200" y1="45"  x2="300" y2="103"/>
      <line class="c-ring-line" x1="300" y1="103" x2="300" y2="218"/>
      <line class="c-ring-line" x1="300" y1="218" x2="200" y2="275"/>
      <line class="c-ring-line" x1="200" y1="275" x2="100" y2="218"/>
      <line class="c-ring-line" x1="100" y1="218" x2="100" y2="103"/>
      <line class="c-ring-line" x1="100" y1="103" x2="200" y2="45"/>

      <!-- Spokes — flowing dashes, each slightly offset -->
      <line class="c-spoke" x1="200" y1="160" x2="200" y2="45"  style="animation-delay:0s"/>
      <line class="c-spoke" x1="200" y1="160" x2="300" y2="103" style="animation-delay:0.47s"/>
      <line class="c-spoke" x1="200" y1="160" x2="300" y2="218" style="animation-delay:0.93s; animation-direction:reverse"/>
      <line class="c-spoke" x1="200" y1="160" x2="200" y2="275" style="animation-delay:1.4s"/>
      <line class="c-spoke" x1="200" y1="160" x2="100" y2="218" style="animation-delay:1.87s; animation-direction:reverse"/>
      <line class="c-spoke" x1="200" y1="160" x2="100" y2="103" style="animation-delay:2.33s"/>

      <!-- Center dot -->
      <circle class="c-center" cx="200" cy="160" r="3.5"/>

      <!-- NODE 1 · Number Theory — TOP -->
      <a href="/nt" class="c-node">
        <circle class="c-ripple"   cx="200" cy="45" r="21" style="animation-delay:0s"/>
        <circle class="c-node-bg"  cx="200" cy="45" r="21"/>
        <!-- ζ (zeta function) -->
        <text class="c-icon" x="200" y="45">ζ</text>
        <text class="c-label" x="200" y="16" text-anchor="middle">Number Theory</text>
      </a>

      <!-- NODE 2 · ML for Materials — TOP RIGHT -->
      <a href="/mir" class="c-node">
        <circle class="c-ripple"   cx="300" cy="103" r="21" style="animation-delay:0.5s"/>
        <circle class="c-node-bg"  cx="300" cy="103" r="21"/>
        <!-- Hexagonal lattice -->
        <polygon class="c-icon-path" points="300,96 306,99.5 306,106.5 300,110 294,106.5 294,99.5"/>
        <text class="c-label" x="328" y="107" text-anchor="start">ML · Materials</text>
      </a>

      <!-- NODE 3 · Carrier Recombination — BOTTOM RIGHT -->
      <a href="/recombination" class="c-node">
        <circle class="c-ripple"   cx="300" cy="218" r="21" style="animation-delay:1s"/>
        <circle class="c-node-bg"  cx="300" cy="218" r="21"/>
        <!-- Atom: two crossing elliptical orbits + nucleus -->
        <ellipse class="c-icon-path" cx="300" cy="218" rx="8.5" ry="3"/>
        <ellipse class="c-icon-path" cx="300" cy="218" rx="8.5" ry="3" transform="rotate(60 300 218)"/>
        <circle  class="c-icon-dot"  cx="300" cy="218" r="2"/>
        <text class="c-label" x="328" y="222" text-anchor="start">Recombination</text>
      </a>

      <!-- NODE 4 · PFAS — BOTTOM -->
      <a href="/pfas" class="c-node">
        <circle class="c-ripple"   cx="200" cy="275" r="21" style="animation-delay:1.5s"/>
        <circle class="c-node-bg"  cx="200" cy="275" r="21"/>
        <!-- CF₃ molecule: central C + 3 F atoms -->
        <circle class="c-icon-dot"  cx="200" cy="275" r="2.6"/>
        <circle class="c-icon-dot"  cx="193" cy="268" r="1.7"/>
        <circle class="c-icon-dot"  cx="207" cy="268" r="1.7"/>
        <circle class="c-icon-dot"  cx="200" cy="283" r="1.7"/>
        <line   class="c-icon-bond" x1="200" y1="275" x2="193" y2="268"/>
        <line   class="c-icon-bond" x1="200" y1="275" x2="207" y2="268"/>
        <line   class="c-icon-bond" x1="200" y1="275" x2="200" y2="283"/>
        <text class="c-label" x="200" y="304" text-anchor="middle">PFAS</text>
      </a>

      <!-- NODE 5 · Drosophila — BOTTOM LEFT -->
      <a href="/flylab" class="c-node">
        <circle class="c-ripple"   cx="100" cy="218" r="21" style="animation-delay:2s"/>
        <circle class="c-node-bg"  cx="100" cy="218" r="21"/>
        <!-- Fly: two wing ellipses + body -->
        <ellipse class="c-icon-path" cx="93"  cy="212" rx="6" ry="2.8" transform="rotate(-30 93 212)"/>
        <ellipse class="c-icon-path" cx="107" cy="212" rx="6" ry="2.8" transform="rotate(30 107 212)"/>
        <ellipse class="c-icon-dot"  cx="100" cy="218" rx="2" ry="4"/>
        <text class="c-label" x="72" y="222" text-anchor="end">Drosophila</text>
      </a>

      <!-- NODE 6 · Droplet Hydrodynamics — TOP LEFT -->
      <a href="/hydrodynamics" class="c-node">
        <circle class="c-ripple"   cx="100" cy="103" r="21" style="animation-delay:2.5s"/>
        <circle class="c-node-bg"  cx="100" cy="103" r="21"/>
        <!-- Teardrop (pointed top, round base) -->
        <path class="c-icon-drop" d="M100,95 C106,101 106,108 100,111 C94,108 94,101 100,95 Z"/>
        <text class="c-label" x="72" y="107" text-anchor="end">Hydrodynamics</text>
      </a>

    </svg>
  </div>

  <h1 class="hero-name">Akilan Sankaran</h1>
  <p class="hero-tagline">Harvard</p>
  <p class="hero-bio">I think about the intersection of computation and theory with the applied sciences, spanning materials, chemistry, physics, and biology. Currently working on machine-learned exchange-correlation functionals and neural-network potentials at the <a href="https://mir.g.harvard.edu/">Kozinsky Lab</a>. I'm also pursuing economics and political philosophy through <a href="https://www.charlesrivereconomicslabs.org/">Charles River Economics Labs</a> and Harvard's <a href="https://iop.harvard.edu/">Institute of Politics</a>. Outside the lab, I <a href="https://www.youtube.com/channel/UC3BUUIJfTgrYauJq0PTKlng">perform piano</a> and run long-distance.</p>
  <div class="hero-links">
    <a href="/research" class="btn-primary">Research</a>
    <a href="/coursework" class="btn-secondary">Background</a>
    <a href="mailto:akilansankaran@college.harvard.edu" class="btn-secondary">Email</a>
    <a href="https://linkedin.com/in/akilan-sankaran/" class="btn-secondary" target="_blank" rel="noopener noreferrer">LinkedIn</a>
  </div>

</div>

<div class="get-in-touch">
  <p class="git-label">Get in touch</p>
  <p class="git-email">akilansankaran [at] college [dot] harvard [dot] edu</p>
</div>
