---
layout: default
title: Home
description: We build civic tech projects to make Ottawa better for everyone.
---

<section id="mission" class="py-5">
  <div class="container">
    <h2 class="text-center mb-4">Our Mission</h2>
    <p class="lead text-center">
      Code for Ottawa unites technologists, designers, public servants, and engaged residents to create open-source tools that serve the people of {{ site.location | default: "Ottawa" }}.
      Our goal is to foster a more transparent, accessible, and responsive local government through civic tech.
    </p>
  </div>
</section>

<section id="projects" class="py-5 bg-light">
  <div class="container">
    <h2 class="text-center mb-5">Current Projects</h2>
    <div class="row g-4">
      <div class="col-md-4">
        <div class="card h-100 shadow-sm">
          <div class="card-body">
            <h5 class="card-title">OC Transpo Live</h5>
            <p class="card-text">Providing real-time data and visualizations to help residents better navigate public transit.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card h-100 shadow-sm">
          <div class="card-body">
            <h5 class="card-title">City Council Tracker</h5>
            <p class="card-text">A tool to monitor council meetings, voting records, and open data related to municipal governance.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card h-100 shadow-sm">
          <div class="card-body">
            <h5 class="card-title">Community Resource Map</h5>
            <p class="card-text">Connecting residents with shelters, food banks, and community programs throughout Ottawa.</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<section id="join" class="py-5">
  <div class="container text-center">
    <h2 class="mb-4">Join the Movement</h2>
    <p class="lead mb-4">
      Whether you’re a developer, a policy thinker, or just passionate about civic change — we’d love to have you involved in building a better {{ site.location | default: "Ottawa" }}.
    </p>
    <a href="#" class="btn btn-primary btn-lg">Join Our Discord</a>
  </div>
</section>
