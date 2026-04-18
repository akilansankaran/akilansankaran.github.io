---
layout: default
title: Home
---

<div class="hero">

  <h1 class="hero-name">Akilan Sankaran</h1>
  <p class="hero-tagline">Harvard</p>

  <div class="get-in-touch">
    <p class="git-email">akilansankaran [at] college [dot] harvard [dot] edu</p>
  </div>

  <p class="hero-bio">I think about the intersection of <b>computation and theory</b> with the <b>applied physical sciences</b>, spanning materials, chemistry, physics, and biology. Currently working on machine-learned exchange-correlation functionals and neural-network potentials at the <a href="https://mir.g.harvard.edu/">Kozinsky Lab</a>. I'm also pursuing economics and political philosophy through <a href="https://www.charlesrivereconomicslabs.org/">Charles River Economics Labs</a> and Harvard's <a href="https://iop.harvard.edu/">Institute of Politics</a>. Outside the lab, I <a href="https://www.youtube.com/channel/UC3BUUIJfTgrYauJq0PTKlng">perform piano</a> and run long-distance.</p>

  <div class="hero-anim">
    <svg viewBox="0 0 400 320" class="c-svg" xmlns="http://www.w3.org/2000/svg" aria-label="Research topics">

      <!-- Static outer hexagon frame (does not rotate) -->
      <line class="c-ring-line" x1="200" y1="45"  x2="300" y2="103"/>
      <line class="c-ring-line" x1="300" y1="103" x2="300" y2="218"/>
      <line class="c-ring-line" x1="300" y1="218" x2="200" y2="275"/>
      <line class="c-ring-line" x1="200" y1="275" x2="100" y2="218"/>
      <line class="c-ring-line" x1="100" y1="218" x2="100" y2="103"/>
      <line class="c-ring-line" x1="100" y1="103" x2="200" y2="45"/>

      <!-- Rotating constellation group: spokes + center + all nodes -->
      <g class="c-constellation">

        <!-- Spokes from center to each vertex -->
        <line class="c-spoke" x1="200" y1="160" x2="200" y2="45"  style="animation-delay:0s"/>
        <line class="c-spoke" x1="200" y1="160" x2="300" y2="103" style="animation-delay:0.47s"/>
        <line class="c-spoke" x1="200" y1="160" x2="300" y2="218" style="animation-delay:0.93s;animation-direction:reverse"/>
        <line class="c-spoke" x1="200" y1="160" x2="200" y2="275" style="animation-delay:1.4s"/>
        <line class="c-spoke" x1="200" y1="160" x2="100" y2="218" style="animation-delay:1.87s;animation-direction:reverse"/>
        <line class="c-spoke" x1="200" y1="160" x2="100" y2="103" style="animation-delay:2.33s"/>

        <!-- Center dot -->
        <circle class="c-center" cx="200" cy="160" r="3.5"/>

        <!-- NODE: Number Theory -->
        <g transform="translate(200,45)">
          <g class="c-icon-content">
            <a href="/nt" class="c-node">
              <circle class="c-node-bg" cx="0" cy="0" r="22"/>
              <text class="c-icon" x="0" y="1">τ</text>
            </a>
          </g>
        </g>

        <!-- NODE: ML for Materials -->
        <g transform="translate(300,103)">
          <g class="c-icon-content">
            <a href="/mir" class="c-node">
              <circle class="c-node-bg" cx="0" cy="0" r="22"/>
              <polygon class="c-icon-path c-hex-spin"
                points="0,-9 7.8,-4.5 7.8,4.5 0,9 -7.8,4.5 -7.8,-4.5"/>
            </a>
          </g>
        </g>

        <!-- NODE: Carrier Recombination -->
        <g transform="translate(300,218)">
          <g class="c-icon-content">
            <a href="/recombination" class="c-node">
              <circle class="c-node-bg" cx="0" cy="0" r="22"/>
              <circle class="c-icon-hole" cx="0" cy="0" r="11"/>
              <circle class="c-icon-dot" cx="0" cy="-11" r="3">
                <animateTransform attributeName="transform" type="rotate"
                  from="0 0 0" to="360 0 0" dur="2.2s" repeatCount="indefinite"/>
              </circle>
            </a>
          </g>
        </g>

        <!-- NODE: PFAS -->
        <g transform="translate(200,275)">
          <g class="c-icon-content">
            <a href="/pfas" class="c-node">
              <circle class="c-node-bg" cx="0" cy="0" r="22"/>
              <circle class="c-atom-c"  cx="0"  cy="0"  r="2.8"/>
              <circle class="c-atom-f"  cx="-8" cy="-8" r="1.8"/>
              <circle class="c-atom-f"  cx="8"  cy="-8" r="1.8"/>
              <circle class="c-atom-f"  cx="0"  cy="9"  r="1.8"/>
              <line   class="c-bond-cf" x1="0" y1="0" x2="-8" y2="-8"/>
              <line   class="c-bond-cf" x1="0" y1="0" x2="8"  y2="-8"/>
              <line   class="c-bond-cf" x1="0" y1="0" x2="0"  y2="9"/>
            </a>
          </g>
        </g>

        <!-- NODE: Drosophila -->
        <g transform="translate(100,218)">
          <g class="c-icon-content">
            <a href="/flylab" class="c-node">
              <circle class="c-node-bg" cx="0" cy="0" r="22"/>
              <ellipse class="c-icon-wing" cx="-12" cy="-7" rx="9" ry="4.5"
                transform="rotate(-35 -12 -7)"/>
              <ellipse class="c-icon-wing" cx="12" cy="-7" rx="9" ry="4.5"
                transform="rotate(35 12 -7)"/>
              <ellipse class="c-icon-dot" cx="0" cy="4" rx="2.5" ry="5.5"/>
              <circle  class="c-icon-dot" cx="0" cy="-7" r="3"/>
            </a>
          </g>
        </g>

        <!-- NODE: Droplet Hydrodynamics -->
        <g transform="translate(100,103)">
          <g class="c-icon-content">
            <a href="/hydrodynamics" class="c-node">
              <circle class="c-node-bg" cx="0" cy="0" r="22"/>
              <path class="c-icon-drop"
                d="M0,-12 C10,-2 10,9 0,13 C-10,9 -10,-2 0,-12 Z"/>
            </a>
          </g>
        </g>

      </g><!-- end .c-constellation -->

    </svg>
  </div>

  <div class="hero-links">
    <a href="/research" class="btn-primary">Research</a>
    <a href="/coursework" class="btn-secondary">Background</a>
    <a href="mailto:akilansankaran@college.harvard.edu" class="btn-secondary">Email</a>
    <a href="https://linkedin.com/in/akilan-sankaran/" class="btn-secondary" target="_blank" rel="noopener noreferrer">LinkedIn</a>
  </div>

</div>
