---
layout: default
title: Home
---

<div class="hero">

  <h1 class="hero-name">Akilan Sankaran</h1>
  <p class="hero-tagline">Harvard</p>

  <div class="get-in-touch">
    <p class="git-label">Get in touch</p>
    <p class="git-email">akilansankaran [at] college [dot] harvard [dot] edu</p>
  </div>

  <p class="hero-bio">I think about the intersection of computation and theory with the applied sciences, spanning materials, chemistry, physics, and biology. Currently working on machine-learned exchange-correlation functionals and neural-network potentials at the <a href="https://mir.g.harvard.edu/">Kozinsky Lab</a>. I'm also pursuing economics and political philosophy through <a href="https://www.charlesrivereconomicslabs.org/">Charles River Economics Labs</a> and Harvard's <a href="https://iop.harvard.edu/">Institute of Politics</a>. Outside the lab, I <a href="https://www.youtube.com/channel/UC3BUUIJfTgrYauJq0PTKlng">perform piano</a> and run long-distance.</p>

  <div class="hero-anim">
    <svg viewBox="0 0 400 320" class="c-svg" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Research topics constellation">

      <!-- Static outer hexagon frame -->
      <line class="c-ring-line" x1="200" y1="45"  x2="300" y2="103"/>
      <line class="c-ring-line" x1="300" y1="103" x2="300" y2="218"/>
      <line class="c-ring-line" x1="300" y1="218" x2="200" y2="275"/>
      <line class="c-ring-line" x1="200" y1="275" x2="100" y2="218"/>
      <line class="c-ring-line" x1="100" y1="218" x2="100" y2="103"/>
      <line class="c-ring-line" x1="100" y1="103" x2="200" y2="45"/>

      <!-- Everything inside rotates slowly around center (200,160) -->
      <g class="c-constellation">

        <!-- Spokes — flowing dashes -->
        <line class="c-spoke" x1="200" y1="160" x2="200" y2="45"  style="animation-delay:0s"/>
        <line class="c-spoke" x1="200" y1="160" x2="300" y2="103" style="animation-delay:0.47s"/>
        <line class="c-spoke" x1="200" y1="160" x2="300" y2="218" style="animation-delay:0.93s;animation-direction:reverse"/>
        <line class="c-spoke" x1="200" y1="160" x2="200" y2="275" style="animation-delay:1.4s"/>
        <line class="c-spoke" x1="200" y1="160" x2="100" y2="218" style="animation-delay:1.87s;animation-direction:reverse"/>
        <line class="c-spoke" x1="200" y1="160" x2="100" y2="103" style="animation-delay:2.33s"/>

        <!-- Center dot -->
        <circle class="c-center" cx="200" cy="160" r="3.5"/>

        <!-- NODE 1 · Number Theory — τ (Ramanujan tau / abc quality) -->
        <a href="/nt" class="c-node">
          <circle class="c-node-bg" cx="200" cy="45" r="22"/>
          <text class="c-icon" x="200" y="45">τ</text>
        </a>

        <!-- NODE 2 · ML for Materials — spinning hexagonal lattice -->
        <a href="/mir" class="c-node">
          <circle class="c-node-bg" cx="300" cy="103" r="22"/>
          <polygon class="c-icon-path c-hex-spin"
            points="300,94 308,98.5 308,107.5 300,112 292,107.5 292,98.5"/>
        </a>

        <!-- NODE 3 · Carrier Recombination — electron orbiting a hole -->
        <a href="/recombination" class="c-node">
          <circle class="c-node-bg" cx="300" cy="218" r="22"/>
          <!-- Hole: dashed ring representing semiconductor vacancy -->
          <circle class="c-icon-hole" cx="300" cy="218" r="11"/>
          <!-- Electron: orbits the hole via SMIL -->
          <circle class="c-icon-dot" cx="300" cy="207" r="3">
            <animateTransform attributeName="transform" type="rotate"
              from="0 300 218" to="360 300 218"
              dur="2.2s" repeatCount="indefinite"/>
          </circle>
        </a>

        <!-- NODE 4 · PFAS — CF₃ molecule -->
        <a href="/pfas" class="c-node">
          <circle class="c-node-bg" cx="200" cy="275" r="22"/>
          <circle class="c-icon-dot"  cx="200" cy="275" r="2.8"/>
          <circle class="c-icon-dot"  cx="192" cy="267" r="1.8"/>
          <circle class="c-icon-dot"  cx="208" cy="267" r="1.8"/>
          <circle class="c-icon-dot"  cx="200" cy="284" r="1.8"/>
          <line   class="c-icon-bond" x1="200" y1="275" x2="192" y2="267"/>
          <line   class="c-icon-bond" x1="200" y1="275" x2="208" y2="267"/>
          <line   class="c-icon-bond" x1="200" y1="275" x2="200" y2="284"/>
        </a>

        <!-- NODE 5 · Drosophila — larger, clearer fly -->
        <a href="/flylab" class="c-node">
          <circle class="c-node-bg" cx="100" cy="218" r="22"/>
          <!-- Wings: semi-filled ellipses angled outward -->
          <ellipse class="c-icon-wing" cx="88"  cy="210" rx="9"   ry="4.5" transform="rotate(-35 88 210)"/>
          <ellipse class="c-icon-wing" cx="112" cy="210" rx="9"   ry="4.5" transform="rotate(35 112 210)"/>
          <!-- Thorax + abdomen -->
          <ellipse class="c-icon-dot"  cx="100" cy="221" rx="2.5" ry="5.5"/>
          <!-- Head -->
          <circle  class="c-icon-dot"  cx="100" cy="213" r="2.8"/>
        </a>

        <!-- NODE 6 · Droplet Hydrodynamics — teardrop -->
        <a href="/hydrodynamics" class="c-node">
          <circle class="c-node-bg" cx="100" cy="103" r="22"/>
          <path class="c-icon-drop" d="M100,93 C108,101 108,110 100,114 C92,110 92,101 100,93 Z"/>
        </a>

      </g>
    </svg>
  </div>

  <div class="hero-links">
    <a href="/research" class="btn-primary">Research</a>
    <a href="/coursework" class="btn-secondary">Background</a>
    <a href="mailto:akilansankaran@college.harvard.edu" class="btn-secondary">Email</a>
    <a href="https://linkedin.com/in/akilan-sankaran/" class="btn-secondary" target="_blank" rel="noopener noreferrer">LinkedIn</a>
  </div>

</div>
