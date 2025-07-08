---
layout: default
title: Galapagos Triple Junction OBS Deployment
---

<style>
  header {
    background-color: #0077be !important;
    background-image: linear-gradient(120deg, #003973, #0077be, #00c6ff) !important;
  }
</style>



<style>
/* Grid layout: 3 columns, 2 rows */
.link-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 1em;
  margin-top: 2em;
}

/* Shared button styles */
.link-button,
.dropdown-button {
  font-size: 1.4em;
  color: white;
  padding: 1em;
  border-radius: 12px;
  text-align: center;
  text-decoration: none;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100px;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
  cursor: pointer;
}

/* Static links */
.link-button {
  display: flex;
}

/* Individual color overrides */
.about        { background-color: #117a8b; }
.experiment   { background-color: #1d91c0; }
.news         { background-color: #145a7a; }
.retrieval    { background-color: #2a5d9f; }
.deployment   { background-color: #3167b2; }
.publications { background-color: #635bb1; }

/* Dropdown wrapper */
.dropdown {
  position: relative;
  width: 100%;
}

/* Dropdown content styling */
.dropdown-content {
  display: none;
  position: absolute;
  top: 100%;
  left: 0;
  right: 0;
  background-color: white;
  border: 1px solid #ccc;
  border-radius: 8px;
  z-index: 1;
  padding: 0.5em 0;
}

.dropdown-content a {
  display: block;
  padding: 0.5em 1em;
  text-decoration: none;
  color: #155799;
}

.dropdown-content a:hover {
  background-color: #f0f0f0;
}

.dropdown:hover .dropdown-content {
  display: block;
}
</style>

<div class="link-grid">

  <!-- Row 1 -->
  <a href="/about" class="link-button about">
    About
  </a>

<div class="dropdown experiment">
  <div class="dropdown-button">Experiment ▼</div>
  <div class="dropdown-content">
    <a href="/experiment/team">Team</a>
    <a href="/experiment/study-region">Study Region</a>
  </div>
</div>

  <div class="dropdown news">
    <div class="dropdown-button">News ▼</div>
    <div class="dropdown-content">
      <a href="/news/announcement1">Announcement 1</a>
      <a href="/news/announcement2">Announcement 2</a>
      <a href="/news/announcement3">Announcement 3</a>
    </div>
  </div>

  <!-- Row 2 -->
  <div class="dropdown retrieval">
    <div class="dropdown-button">Retrieval Blog ▼</div>
    <div class="dropdown-content">
      <a href="/retrieval/day1">Day 1</a>
      <a href="/retrieval/day2">Day 2</a>
      <a href="/retrieval/day3">Day 3</a>
    </div>
  </div>

  <div class="dropdown deployment">
    <div class="dropdown-button">Deployment Blog ▼</div>
    <div class="dropdown-content">
      <a href="/deployment/day1">Day 1</a>
      <a href="/deployment/day2">Day 2</a>
      <a href="/deployment/day3">Day 3</a>
      <a href="/deployment/day4">Day 4</a>
      <a href="/deployment/day5">Day 5</a>
      <a href="/deployment/day6">Day 6</a>
     
    </div>
  </div>

  <a href="/publications" class="link-button publications">
    Publications
  </a>

</div>