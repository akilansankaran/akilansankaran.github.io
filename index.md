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

  <p class="hero-bio">I think about the intersection of computation and theory with the applied sciences, spanning materials, chemistry, physics, and biology. Currently working on machine-learned exchange-correlation functionals and neural-network potentials at the <a href="https://mir.g.harvard.edu/">Kozinsky Lab</a>. I'm also pursuing economics and political philosophy through <a href="https://www.charlesrivereconomicslabs.org/">Charles River Economics Labs</a> and Harvard's <a href="https://iop.harvard.edu/">Institute of Politics</a>. Outside the lab, I <a href="https://www.youtube.com/channel/UC3BUUIJfTgrYauJq0PTKlng">perform piano</a> and run long-distance.</p>

  <div class="hero-anim">
    <svg viewBox="0 0 400 320" class="c-svg" xmlns="http://www.w3.org/2000/svg" aria-label="Research topics">

      <!-- Static outer hexagon frame -->
      <line class="c-ring-line" x1="200" y1="45"  x2="300" y2="103"/>
      <line class="c-ring-line" x1="300" y1="103" x2="300" y2="218"/>
      <line class="c-ring-line" x1="300" y1="218" x2="200" y2="275"/>
      <line class="c-ring-line" x1="200" y1="275" x2="100" y2="218"/>
      <line class="c-ring-line" x1="100" y1="218" x2="100" y2="103"/>
      <line class="c-ring-line" x1="100" y1="103" x2="200" y2="45"/>

      <!-- Spokes — JS updates x2/y2 to follow animated icons -->
      <line id="spoke-0" class="c-spoke" x1="200" y1="160" x2="200" y2="45"  style="animation-delay:0s"/>
      <line id="spoke-1" class="c-spoke" x1="200" y1="160" x2="300" y2="103" style="animation-delay:0.47s"/>
      <line id="spoke-2" class="c-spoke" x1="200" y1="160" x2="300" y2="218" style="animation-delay:0.93s;animation-direction:reverse"/>
      <line id="spoke-3" class="c-spoke" x1="200" y1="160" x2="200" y2="275" style="animation-delay:1.4s"/>
      <line id="spoke-4" class="c-spoke" x1="200" y1="160" x2="100" y2="218" style="animation-delay:1.87s;animation-direction:reverse"/>
      <line id="spoke-5" class="c-spoke" x1="200" y1="160" x2="100" y2="103" style="animation-delay:2.33s"/>

      <!-- Center dot -->
      <circle class="c-center" cx="200" cy="160" r="3.5"/>

      <!-- Icons — all drawn at local (0,0); JS animates the translate -->

      <!-- NODE: Number Theory  /nt -->
      <g id="ig-nt" transform="translate(200,45)">
        <a href="/nt" class="c-node">
          <circle class="c-node-bg" cx="0" cy="0" r="22"/>
          <text class="c-icon" x="0" y="1">τ</text>
          <text class="c-label" x="0" y="33" text-anchor="middle">Number Theory</text>
        </a>
      </g>

      <!-- NODE: ML for Materials  /mir -->
      <g id="ig-mir" transform="translate(300,103)">
        <a href="/mir" class="c-node">
          <circle class="c-node-bg" cx="0" cy="0" r="22"/>
          <polygon class="c-icon-path c-hex-spin"
            points="0,-9 7.8,-4.5 7.8,4.5 0,9 -7.8,4.5 -7.8,-4.5"/>
          <text class="c-label" x="0" y="33" text-anchor="middle">ML · Materials</text>
        </a>
      </g>

      <!-- NODE: Carrier Recombination  /recombination -->
      <g id="ig-rec" transform="translate(300,218)">
        <a href="/recombination" class="c-node">
          <circle class="c-node-bg" cx="0" cy="0" r="22"/>
          <circle class="c-icon-hole" cx="0" cy="0" r="11"/>
          <circle class="c-icon-dot" cx="0" cy="-11" r="3">
            <animateTransform attributeName="transform" type="rotate"
              from="0 0 0" to="360 0 0" dur="2.2s" repeatCount="indefinite"/>
          </circle>
          <text class="c-label" x="0" y="33" text-anchor="middle">Recombination</text>
        </a>
      </g>

      <!-- NODE: PFAS  /pfas -->
      <g id="ig-pfas" transform="translate(200,275)">
        <a href="/pfas" class="c-node">
          <circle class="c-node-bg" cx="0" cy="0" r="22"/>
          <circle class="c-icon-dot"  cx="0"  cy="0"  r="2.8"/>
          <circle class="c-icon-dot"  cx="-8" cy="-8" r="1.8"/>
          <circle class="c-icon-dot"  cx="8"  cy="-8" r="1.8"/>
          <circle class="c-icon-dot"  cx="0"  cy="9"  r="1.8"/>
          <line   class="c-icon-bond" x1="0" y1="0" x2="-8" y2="-8"/>
          <line   class="c-icon-bond" x1="0" y1="0" x2="8"  y2="-8"/>
          <line   class="c-icon-bond" x1="0" y1="0" x2="0"  y2="9"/>
          <text class="c-label" x="0" y="33" text-anchor="middle">PFAS</text>
        </a>
      </g>

      <!-- NODE: Drosophila  /flylab -->
      <g id="ig-fly" transform="translate(100,218)">
        <a href="/flylab" class="c-node">
          <circle class="c-node-bg" cx="0" cy="0" r="22"/>
          <ellipse class="c-icon-wing" cx="-12" cy="-7" rx="9" ry="4.5"
            transform="rotate(-35 -12 -7)"/>
          <ellipse class="c-icon-wing" cx="12" cy="-7" rx="9" ry="4.5"
            transform="rotate(35 12 -7)"/>
          <ellipse class="c-icon-dot" cx="0" cy="4" rx="2.5" ry="5.5"/>
          <circle  class="c-icon-dot" cx="0" cy="-7" r="3"/>
          <text class="c-label" x="0" y="33" text-anchor="middle">Drosophila</text>
        </a>
      </g>

      <!-- NODE: Droplet Hydrodynamics  /hydrodynamics -->
      <g id="ig-hydro" transform="translate(100,103)">
        <a href="/hydrodynamics" class="c-node">
          <circle class="c-node-bg" cx="0" cy="0" r="22"/>
          <path class="c-icon-drop"
            d="M0,-10 C8,-2 8,7 0,11 C-8,7 -8,-2 0,-10 Z"/>
          <text class="c-label" x="0" y="33" text-anchor="middle">Hydrodynamics</text>
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

<script>
(function () {
  // Hexagon vertex positions (must match SVG)
  var V = [
    [200, 45],
    [300, 103],
    [300, 218],
    [200, 275],
    [100, 218],
    [100, 103]
  ];

  var IDS = ['ig-nt', 'ig-mir', 'ig-rec', 'ig-pfas', 'ig-fly', 'ig-hydro'];

  var nodes  = IDS.map(function(id) { return document.getElementById(id); });
  var spokes = [0,1,2,3,4,5].map(function(i) { return document.getElementById('spoke-' + i); });

  // assignment[i] = which vertex index icon i currently targets
  var assign = [0, 1, 2, 3, 4, 5];

  // Per-icon animation state
  var state = V.map(function(v) {
    return { x: v[0], y: v[1], sx: v[0], sy: v[1], tx: v[0], ty: v[1],
             t: 1, cpx: 0, cpy: 0 };
  });

  function ease(t) {
    return t < 0.5 ? 2*t*t : -1 + (4 - 2*t)*t;
  }

  function scheduleSwap() {
    // Pick two distinct icons and swap their target vertices
    var i = Math.floor(Math.random() * 6);
    var j;
    do { j = Math.floor(Math.random() * 6); } while (j === i);

    var vi = assign[i], vj = assign[j];
    assign[i] = vj;
    assign[j] = vi;

    // For each of the two moving icons, compute a quadratic bezier control point
    // that arcs perpendicular to the straight-line path
    [i, j].forEach(function(k, idx) {
      var s = state[k];
      var tx = V[assign[k]][0], ty = V[assign[k]][1];
      s.sx = s.x; s.sy = s.y;
      s.tx = tx;  s.ty = ty;
      s.t  = 0;

      // Perpendicular offset for the arc (alternating sides)
      var mx = (s.sx + tx) / 2, my = (s.sy + ty) / 2;
      var dx = tx - s.sx, dy = ty - s.sy;
      var len = Math.sqrt(dx*dx + dy*dy) || 1;
      var dir = idx === 0 ? 1 : -1;
      var arc = 60;
      s.cpx = mx + (-dy / len) * arc * dir;
      s.cpy = my + ( dx / len) * arc * dir;
    });
  }

  var lastSwap = null;
  var SWAP_MS  = 3800;   // how often to trigger a swap
  var ANIM_MS  = 2400;   // how long each arc takes

  function tick(ts) {
    if (lastSwap === null) lastSwap = ts;

    if (ts - lastSwap >= SWAP_MS) {
      scheduleSwap();
      lastSwap = ts;
    }

    for (var i = 0; i < 6; i++) {
      var s = state[i];
      if (s.t < 1) {
        s.t = Math.min(1, s.t + 16 / ANIM_MS);
        var et = ease(s.t);
        var mt = 1 - et;
        // Quadratic bezier: start -> control -> target
        s.x = mt*mt*s.sx + 2*mt*et*s.cpx + et*et*s.tx;
        s.y = mt*mt*s.sy + 2*mt*et*s.cpy + et*et*s.ty;
      }

      if (nodes[i])  nodes[i].setAttribute('transform', 'translate(' + s.x + ',' + s.y + ')');
      if (spokes[i]) { spokes[i].setAttribute('x2', s.x); spokes[i].setAttribute('y2', s.y); }
    }

    requestAnimationFrame(tick);
  }

  requestAnimationFrame(tick);
})();
</script>
