---
layout: single
title: "[Apps]"
permalink: /apps/
author_profile: true
---

Apps I’ve built (or am currently building) for my courses to help students discover and apply linguistics.

<style>
.app-list {
  display: flex;
  flex-direction: column;
  gap: 18px;
  margin-top: 20px;
}

.app-card {
  display: grid;
  grid-template-columns: 80px minmax(0, 1fr);
  gap: 18px;
  align-items: start;
  padding: 16px;
  border: 1px solid rgba(255,255,255,0.05);
  border-radius: 8px;
}

.app-media img {
  width: 100%;
  height: auto;
  display: block;
  border-radius: 6px;
}

.app-content h3 {
  margin-top: 0;
  margin-bottom: 10px;
}

.app-content p {
  margin-top: 0;
  margin-bottom: 10px;
}

.app-link {
  margin-top: 6px;
}

@media (max-width: 700px) {
  .app-card {
    grid-template-columns: 1fr;
  }

  .app-media {
    max-width: 180px;
  }
}
</style>

<div class="app-list">

  <div class="app-card">
    <div class="app-media">
      <img src="/assets/images/gta_icon.png" alt="Guess the Accent logo or screenshot">
    </div>
    <div class="app-content">
      <h3>[1] Guess the Accent (completed)</h3>
      <p><strong>Guess the Accent</strong> is a listening game in which students hear recordings of speakers reading the same English passage and try to identify their accents. The recordings and reading passage come from the <a href="https://accent.gmu.edu/">Speech Accent Archive</a> (George Mason University), a great resource for exploring accent variation in English. Click the following link to open and play the game:<br>
      <a href="https://timurakishev.github.io/guess-the-accent/" target="_blank" rel="noopener noreferrer">https://timurakishev.github.io/guess-the-accent/</a></p>
    </div>
  </div>

  <div class="app-card">
    <div class="app-media">
      <img src="/assets/images/stb_icon.png" alt="Syntax Tree Builder logo or screenshot">
    </div>
    <div class="app-content">
      <h3>[2] Syntax Tree Builder (in development)</h3>
      <p>I've developed a web-based application for constructing syntax trees. While existing tools such as <a href="https://sourceforge.net/projects/treeform/">TreeForm</a> are useful, many have outdated interfaces and limited flexibility. My goal is to provide a modern, intuitive tool for teaching and practicing syntactic analysis. You can open Syntax Tree Builder here:<br>
      <a href="https://timurakishev.github.io/syntax-tree-builder-web/" target="_blank" rel="noopener noreferrer">https://timurakishev.github.io/syntax-tree-builder-web/</a></p>
    </div>
  </div>
