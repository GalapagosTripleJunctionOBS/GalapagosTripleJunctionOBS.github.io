---
layout: default
title: Galapagos Triple Junction OBS Deployment
---

<style>
  header {
    background-color: #0077be !important;
    background-image: linear-gradient(120deg, #003973, #0077be, #00c6ff) !important;
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    height: 250px;
    color: white;
    display: flex;
    flex-direction: column;
    justify-content: center;
    padding: 2em;
    text-shadow: 1px 1px 5px #000;
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
.About        { background-color: #117a8b; }
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


<div class="dropdown About">
  <div class="dropdown-button">About ▼</div>
  <div class="dropdown-content">
    <a href="/About/Rationale">Scientific Rationale</a>
    <a href="/About/Contact">Contact Us</a>
  </div>
</div>

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
      <a href="/news/DeparturefromSanDiego">Sucessful Departure from San Diego!</a>
     <a href="/news/VoyageDetails">Voyage Details</a>
    </div>
  </div>

  <div class="dropdown deployment">
    <div class="dropdown-button">Deployment Blog ▼</div>
    <div class="dropdown-content">
      <a href="/deployment/MeetTheScienceParty">Meet the Science Team!</a>

     
    </div>
  </div>

  <div class="dropdown retrieval">
    <div class="dropdown-button">Retrieval Blog ▼</div>
    <div class="dropdown-content">
      <!--
      <a href="/retrieval/day1">Day 1</a>
      <a href="/retrieval/day2">Day 2</a>
      <a href="/retrieval/day3">Day 3</a>
      -->
    </div>
  </div>

  <a href="/publications" class="link-button publications">
    Publications
  </a>

</div>

<br>

<b>This is the website/blog for the Galapagos Triple Junction ocean-bottom seismometer (OBS) Deployment, a massive deployment of 45 OBSs in the Pacific Ocean. </b> The goal of this ambitious seismic experiment is to provide the most robust and detailed images of the upper mantle beneath a ridge-ridge triple junction, thereby illuminating the origin of mantle upwellings and the internal structures in oceanic plates. This page contains links to blog posts and more information about the experiment. [Contact us](https://galapagostriplejunctionobs.github.io/About/Contact) if you have any questions!

<div style="margin-top: 2em;">
  <p><strong>Share this page:</strong></p>
  <a href="https://twitter.com/intent/tweet?url={{ page.url | absolute_url }}&text={{ page.title | uri_escape }}" target="_blank" style="margin-right: 10px;">
    <img src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/twitter.svg" alt="Twitter" width="24" height="24">
  </a>
  <a href="https://www.facebook.com/sharer/sharer.php?u={{ page.url | absolute_url }}" target="_blank" style="margin-right: 10px;">
    <img src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/facebook.svg" alt="Facebook" width="24" height="24">
  </a>
  <a href="https://www.linkedin.com/shareArticle?mini=true&url={{ page.url | absolute_url }}&title={{ page.title | uri_escape }}" target="_blank">
    <img src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/linkedin.svg" alt="LinkedIn" width="24" height="24">
  </a>
</div>
