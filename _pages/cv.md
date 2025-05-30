---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---



{% include base_path %}

<div style="text-align: center; padding: 20px;">
  <p>If your browser do not support embedded PDFs, you can download or view my CV here:</p>
  <a href="{{ base_path }}/files/cv.pdf" target="_blank" class="btn btn--primary">
    Download or View CV (PDF)
  </a>
</div>

<hr>

<div class="pdf-embed-container" style="text-align: center; padding: 20px;">
  <object 
    data="{{ base_path }}/files/cv.pdf#toolbar=0" 
    type="application/pdf" 
    width="100%" 
    height="600px"
    style="display: block; margin: 0 auto; border: 1px solid #ddd;"
  >
    <p>Your browser doesn't support embedded PDFs. Please use the download link above.</p>
  </object>
</div>

<style>
  /* Basic responsive styling for the embed container */
  .pdf-embed-container object {
    max-width: 800px; /* Optional: Sets a max width for large screens */
  }

  /* You can add more media queries if you want to hide the embed on very small screens */
  @media (max-width: 768px) {
    /* Hide the embedded PDF on smaller screens as it's often not supported or has poor UX */
    .pdf-embed-container {
      display: none; 
    }
  }
</style>

<!-- Education
======
* PhD in Bioinformatics 
* M.S. in Jekyll, GitHub University, 2014
* B.S. in GitHub, GitHub University, 2012

Work experience
======
* Spring 2024: Academic Pages Collaborator
  * GitHub University
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users

* Fall 2015: Research Assistant
  * GitHub University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

* Summer 2015: Research Assistant
  * GitHub University
  * Duties included: Tagging issues
  * Supervisor: Professor Git
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams -->

