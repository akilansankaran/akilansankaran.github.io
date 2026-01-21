---
layout: default
title: Music
---
* * *

# Music

<div class="content-container" markdown="1">
I am incredibly passionate about Classical music. Some of my recent pianistic repertoire has included Chopin's Fourth Ballade and Polonaise-Fantaisie.
</div>

<div class="content-container">
  <div class="repertoire-box" onclick="toggleRepertoire(this)">
    <div class="repertoire-header">Baroque Repertoire</div>
    <div class="repertoire-content">
      <ul>
        <li>Mazurka TEST</li>
        <li>Mazurka TEST</li>
        <li>Mazurka TEST</li>
      </ul>
    </div>
  </div>

  <div class="repertoire-box" onclick="toggleRepertoire(this)">
    <div class="repertoire-header">Classical Repertoire</div>
    <div class="repertoire-content">
      <ul>
        <li>Mazurka TEST</li>
        <li>Mazurka TEST</li>
        <li>Mazurka TEST</li>
      </ul>
    </div>
  </div>

  <div class="repertoire-box" onclick="toggleRepertoire(this)">
    <div class="repertoire-header">Romantic Repertoire</div>
    <div class="repertoire-content">
      <ul>
        <li>Mazurka TEST</li>
        <li>Mazurka TEST</li>
        <li>Mazurka TEST</li>
      </ul>
    </div>
  </div>

  <div class="repertoire-box" onclick="toggleRepertoire(this)">
    <div class="repertoire-header">Contemporary Repertoire</div>
    <div class="repertoire-content">
      <ul>
        <li>Mazurka TEST</li>
        <li>Mazurka TEST</li>
        <li>Mazurka TEST</li>
      </ul>
    </div>
  </div>
</div>

<script>
function toggleRepertoire(box) {
  box.classList.toggle('expanded');
}
</script>