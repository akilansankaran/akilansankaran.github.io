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

      <!-- Radial tiling lines: fixed arc-length positions, deform with shape but don't orbit -->
      <line id="morph-ray-0"  class="c-ray" x1="200" y1="160" x2="200" y2="45"/>
      <line id="morph-ray-1"  class="c-ray" x1="200" y1="160" x2="200" y2="45"/>
      <line id="morph-ray-2"  class="c-ray" x1="200" y1="160" x2="200" y2="45"/>
      <line id="morph-ray-3"  class="c-ray" x1="200" y1="160" x2="200" y2="45"/>
      <line id="morph-ray-4"  class="c-ray" x1="200" y1="160" x2="200" y2="45"/>
      <line id="morph-ray-5"  class="c-ray" x1="200" y1="160" x2="200" y2="45"/>
      <line id="morph-ray-6"  class="c-ray" x1="200" y1="160" x2="200" y2="45"/>
      <line id="morph-ray-7"  class="c-ray" x1="200" y1="160" x2="200" y2="45"/>
      <line id="morph-ray-8"  class="c-ray" x1="200" y1="160" x2="200" y2="45"/>
      <line id="morph-ray-9"  class="c-ray" x1="200" y1="160" x2="200" y2="45"/>
      <line id="morph-ray-10" class="c-ray" x1="200" y1="160" x2="200" y2="45"/>
      <line id="morph-ray-11" class="c-ray" x1="200" y1="160" x2="200" y2="45"/>
      <line id="morph-ray-12" class="c-ray" x1="200" y1="160" x2="200" y2="45"/>
      <line id="morph-ray-13" class="c-ray" x1="200" y1="160" x2="200" y2="45"/>
      <line id="morph-ray-14" class="c-ray" x1="200" y1="160" x2="200" y2="45"/>
      <line id="morph-ray-15" class="c-ray" x1="200" y1="160" x2="200" y2="45"/>
      <line id="morph-ray-16" class="c-ray" x1="200" y1="160" x2="200" y2="45"/>
      <line id="morph-ray-17" class="c-ray" x1="200" y1="160" x2="200" y2="45"/>

      <!-- Morphing shape outline — JS updates the points attribute each frame -->
      <polygon id="morph-outline" class="c-ring-poly" points=""/>

      <!-- Spokes from center to each icon — JS updates x2/y2 -->
      <line id="morph-spoke-0" class="c-spoke" x1="200" y1="160" x2="200" y2="45"  style="animation-delay:0s"/>
      <line id="morph-spoke-1" class="c-spoke" x1="200" y1="160" x2="300" y2="103" style="animation-delay:0.47s"/>
      <line id="morph-spoke-2" class="c-spoke" x1="200" y1="160" x2="300" y2="218" style="animation-delay:0.93s"/>
      <line id="morph-spoke-3" class="c-spoke" x1="200" y1="160" x2="200" y2="275" style="animation-delay:1.4s"/>
      <line id="morph-spoke-4" class="c-spoke" x1="200" y1="160" x2="100" y2="218" style="animation-delay:1.87s"/>
      <line id="morph-spoke-5" class="c-spoke" x1="200" y1="160" x2="100" y2="103" style="animation-delay:2.33s"/>

      <!-- Center dot -->
      <circle class="c-center" cx="200" cy="160" r="3.5"/>

      <!-- Icon nodes — JS sets transform="translate(x,y)" each frame -->

      <!-- NODE 0: Number Theory -->
      <g id="morph-node-0" transform="translate(200,45)">
        <a href="/nt" class="c-node">
          <circle class="c-node-bg" cx="0" cy="0" r="22"/>
          <text class="c-icon" x="0" y="1">τ</text>
        </a>
      </g>

      <!-- NODE 1: ML · Materials -->
      <g id="morph-node-1" transform="translate(300,103)">
        <a href="/mir" class="c-node">
          <circle class="c-node-bg" cx="0" cy="0" r="22"/>
          <polygon class="c-icon-path c-hex-spin"
            points="0,-9 7.8,-4.5 7.8,4.5 0,9 -7.8,4.5 -7.8,-4.5"/>
        </a>
      </g>

      <!-- NODE 2: Carrier Recombination -->
      <g id="morph-node-2" transform="translate(300,218)">
        <a href="/recombination" class="c-node">
          <circle class="c-node-bg" cx="0" cy="0" r="22"/>
          <circle class="c-icon-hole" cx="0" cy="0" r="11"/>
          <circle class="c-icon-dot" cx="0" cy="-11" r="3">
            <animateTransform attributeName="transform" type="rotate"
              from="0 0 0" to="360 0 0" dur="2.2s" repeatCount="indefinite"/>
          </circle>
        </a>
      </g>

      <!-- NODE 3: PFAS -->
      <g id="morph-node-3" transform="translate(200,275)">
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

      <!-- NODE 4: Drosophila -->
      <g id="morph-node-4" transform="translate(100,218)">
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

      <!-- NODE 5: Hydrodynamics -->
      <g id="morph-node-5" transform="translate(100,103)">
        <a href="/hydrodynamics" class="c-node">
          <circle class="c-node-bg" cx="0" cy="0" r="22"/>
          <path class="c-icon-drop"
            d="M0,-12 C10,-2 10,9 0,13 C-10,9 -10,-2 0,-12 Z"/>
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
  'use strict';

  var CX = 200, CY = 160, R = 115;
  var N = 120;   // number of outline sample points (higher = smoother circle)
  var ICONS = 6;

  /* ── Shape samplers ─────────────────────────────────────────────────────
     Each function takes t ∈ [0,1] and returns [x, y].
     All shapes are parameterised by arc-length starting at the "top"
     (highest point) and going clockwise, so morphing aligns naturally.
  ───────────────────────────────────────────────────────────────────────── */

  function circlePoint(t) {
    var a = 2 * Math.PI * t - Math.PI / 2;
    return [CX + R * Math.cos(a), CY + R * Math.sin(a)];
  }

  /* Regular n-gon with circumradius R, top vertex at angle -π/2, clockwise.
     All sides equal → parameter is proportional to arc-length. */
  function regPolyPoint(n, t) {
    t = ((t % 1) + 1) % 1;
    var side = Math.floor(t * n);
    var u    = t * n - side;
    var a0   = -Math.PI / 2 + 2 * Math.PI * side / n;
    var a1   = -Math.PI / 2 + 2 * Math.PI * (side + 1) / n;
    var x0 = CX + R * Math.cos(a0), y0 = CY + R * Math.sin(a0);
    var x1 = CX + R * Math.cos(a1), y1 = CY + R * Math.sin(a1);
    return [x0 + u * (x1 - x0), y0 + u * (y1 - y0)];
  }

  /* 2:1 rectangle (width=2R, height=R) centred at (CX,CY).
     Perimeter = 2(2R+R) = 6R, same as the hexagon, so shapes feel similar.
     Parameterised starting at the mid-point of the top edge, clockwise. */
  function rectPoint(t) {
    t = ((t % 1) + 1) % 1;
    var hw = R, hh = R / 2;          // half-width R, half-height R/2
    /* Each segment: [x0, y0, x1, y1, length] */
    var segs = [
      [CX,    CY-hh, CX+hw, CY-hh, hw  ],   /* top-centre  → top-right   */
      [CX+hw, CY-hh, CX+hw, CY+hh, 2*hh],   /* top-right   → bot-right   */
      [CX+hw, CY+hh, CX-hw, CY+hh, 2*hw],   /* bot-right   → bot-left    */
      [CX-hw, CY+hh, CX-hw, CY-hh, 2*hh],   /* bot-left    → top-left    */
      [CX-hw, CY-hh, CX,    CY-hh, hw  ]    /* top-left    → top-centre  */
    ];
    var s = t * 6 * R;
    for (var i = 0; i < segs.length; i++) {
      var seg = segs[i], len = seg[4];
      if (s <= len + 1e-9) {
        var u = Math.min(s / len, 1);
        return [seg[0] + u * (seg[2] - seg[0]),
                seg[1] + u * (seg[3] - seg[1])];
      }
      s -= len;
    }
    return [CX, CY - hh];
  }

  /* ──────────────── */
  var SHAPES = [
    function (t) { return regPolyPoint(6, t); },   /* hexagon   */
    function (t) { return circlePoint(t);     },   /* circle    */
    function (t) { return regPolyPoint(3, t); },   /* triangle  */
    function (t) { return rectPoint(t);       },   /* rectangle */
    function (t) { return regPolyPoint(4, t); }    /* diamond   */
  ];

  /* ── Sampling: pre-compute N evenly-spaced points for a shape fn ──────── */
  function sampleShape(fn) {
    var pts = [];
    for (var i = 0; i < N; i++) pts.push(fn(i / N));
    return pts;
  }

  /* ── DOM references ───────────────────────────────────────────────────── */
  var NUM_RAYS = 18;
  var outline = document.getElementById('morph-outline');
  var rays    = [];
  for (var i = 0; i < NUM_RAYS; i++) {
    rays.push(document.getElementById('morph-ray-' + i));
  }
  var spokes  = [], nodes = [];
  for (var i = 0; i < ICONS; i++) {
    spokes.push(document.getElementById('morph-spoke-' + i));
    nodes.push(document.getElementById('morph-node-'  + i));
  }

  /* ── Animation state ─────────────────────────────────────────────────── */
  var curIdx  = 0,  nxtIdx = 1;
  var sampCur = sampleShape(SHAPES[0]);
  var sampNxt = sampleShape(SHAPES[1]);

  /* progress 0 → fully curShape, 1 → fully nxtShape */
  var progress    = 0;
  var holding     = true;   /* true = pausing on curShape before transitioning */
  var holdElapsed = 0;

  var HOLD_MS  = 5000;   /* ms to pause on each shape */
  var TRANS_MS = 5600;   /* ms for each shape-to-shape morph */
  var ORBIT_MS = 50000;  /* ms for one full orbit of the icons */

  var iconOffset = 0;    /* continuously increasing fractional position */
  var lastTs     = null;

  function easeInOut(t) {
    /* cubic ease-in-out */
    return t < 0.5 ? 4 * t * t * t : 1 - Math.pow(-2 * t + 2, 3) / 2;
  }

  /* Return interpolated [x, y] on the morphed shape.
     t  — fractional position along perimeter [0,1]
     p  — morph progress (0 = curShape, 1 = nxtShape) */
  function morphPoint(t, p) {
    t = ((t % 1) + 1) % 1;
    var f  = t * N;
    var lo = Math.floor(f) % N;
    var hi = (lo + 1) % N;
    var u  = f - Math.floor(f);

    var ax = sampCur[lo][0] + u * (sampCur[hi][0] - sampCur[lo][0]);
    var ay = sampCur[lo][1] + u * (sampCur[hi][1] - sampCur[lo][1]);
    var bx = sampNxt[lo][0] + u * (sampNxt[hi][0] - sampNxt[lo][0]);
    var by = sampNxt[lo][1] + u * (sampNxt[hi][1] - sampNxt[lo][1]);

    return [ax + p * (bx - ax), ay + p * (by - ay)];
  }

  /* ── Main loop ───────────────────────────────────────────────────────── */
  function tick(ts) {
    if (!lastTs) lastTs = ts;
    var dt = Math.min(ts - lastTs, 100); /* cap to avoid large jumps on resume */
    lastTs = ts;

    /* Continuously orbit the icons */
    iconOffset = (iconOffset + dt / ORBIT_MS) % 1;

    /* State machine: hold → transition → hold → … */
    if (holding) {
      holdElapsed += dt;
      if (holdElapsed >= HOLD_MS) {
        holdElapsed = 0;
        holding     = false;
        progress    = 0;
      }
    } else {
      progress += dt / TRANS_MS;
      if (progress >= 1) {
        /* Snap to next shape and start holding */
        curIdx      = nxtIdx;
        nxtIdx      = (nxtIdx + 1) % SHAPES.length;
        sampCur     = sampNxt;
        sampNxt     = sampleShape(SHAPES[nxtIdx]);
        progress    = 0;
        holding     = true;
        holdElapsed = 0;
      }
    }

    var p = holding ? 0 : easeInOut(progress);

    /* Rebuild outline polygon */
    var pts = [];
    for (var i = 0; i < N; i++) {
      var pt = morphPoint(i / N, p);
      pts.push(pt[0].toFixed(1) + ',' + pt[1].toFixed(1));
    }
    outline.setAttribute('points', pts.join(' '));

    /* Update radial tiling lines — rotate with icons via iconOffset */
    for (var r = 0; r < NUM_RAYS; r++) {
      var rpos = morphPoint((iconOffset + r / NUM_RAYS) % 1, p);
      if (rays[r]) { rays[r].setAttribute('x2', rpos[0].toFixed(1)); rays[r].setAttribute('y2', rpos[1].toFixed(1)); }
    }

    /* Reposition each icon node and its spoke */
    for (var k = 0; k < ICONS; k++) {
      var t   = (iconOffset + k / ICONS) % 1;
      var pos = morphPoint(t, p);
      var tx  = pos[0].toFixed(1), ty = pos[1].toFixed(1);
      if (nodes[k])  nodes[k].setAttribute('transform', 'translate(' + tx + ',' + ty + ')');
      if (spokes[k]) { spokes[k].setAttribute('x2', tx); spokes[k].setAttribute('y2', ty); }
    }

    requestAnimationFrame(tick);
  }

  requestAnimationFrame(tick);
}());
</script>
