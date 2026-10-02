---
permalink: /
title: ""
author_profile: false
redirect_from: 
  - /about/
  - /about.html
---

<style>
  /* Home page only: no left sidebar; text on the left, large photo + icons on the right */
  #main .page {
    float: none !important;
    width: 100% !important;
    margin: 0 !important;
    padding-left: 0 !important;
    padding-right: 0 !important;
  }
  .home-intro { display: grid; grid-template-columns: minmax(0, 1fr) 280px; gap: 4em; align-items: start; }
  /* Original headshot file is shown untouched; the browser just frames it as a
     4:5 rectangle by trimming a little from each side (no re-encoding). */
  .home-photo { width: 100%; aspect-ratio: 4 / 5; object-fit: cover; object-position: center; display: block; border-radius: 2px; margin-top: 0.4em; }
  .home-links { display: flex; justify-content: center; gap: 1.4em; margin-top: 1em; font-size: 1.35em; }
  .home-links a { color: #494e51; text-decoration: none; }
  .home-links a:hover { color: #000; }
  html[data-theme="dark"] .home-links a { color: #c9cdd1; }
  html[data-theme="dark"] .home-links a:hover { color: #fff; }
  html[data-theme="dark"] .home-photo { opacity: 1; }
  @media (max-width: 900px) {
    .home-intro { grid-template-columns: 1fr; gap: 1.5em; }
    .home-side { max-width: 280px; margin: 0.5em auto 0; }
  }
</style>

<div class="home-intro">
<div class="home-text" markdown="1">

<h2 style="border-bottom: none; margin-top: 0;">Welcome!</h2>

I am a PhD student in [political science](https://polisci.la.psu.edu/people/duan-songtao/) and [social data analytics](https://soda.la.psu.edu/) at the Pennsylvania State University. Prior to Penn State, I was a consultant and research assistant at the [Center for Global Development](https://www.cgdev.org/) in Washington D.C. I was also a graduate fellow at the [Reppy Institute for Peace and Conflict Studies](https://einaudi.cornell.edu/programs/reppy-institute-peace-and-conflict-studies) and the [Emerging Market Program](https://emergingmarkets.dyson.cornell.edu/smart/smart-2022-23/) at Cornell University.

My research interests focus on political economy of development, specifically foreign aid, civil wars and conflicts, and multilateral development organizations.  My work has been supported by the Vice Provost and Dean's Scholarship, the Miller-LaVigne Distinguished Graduate Fellowship, the Paterno Graduate Fellowship, Mario Einaudi Center for International Studies, and Cornell Brooks School of Public Policy.  

For inquiries, please reach out to me at [sduan@psu.edu](mailto:sduan@psu.edu), or connect with me on Bluesky [@sduan.bsky.social](https://bsky.app/profile/sduan.bsky.social).

</div>
<div class="home-side">
  <img class="home-photo" src="/images/Duan_headshot.jpg" alt="Songtao Duan">
  <div class="home-links">
    <a href="mailto:sduan@psu.edu" aria-label="Email" title="Email"><i class="fas fa-envelope" aria-hidden="true"></i></a>
    <a href="https://orcid.org/0009-0009-9833-3711" aria-label="ORCID" title="ORCID"><i class="ai ai-orcid" aria-hidden="true"></i></a>
    <a href="https://bsky.app/profile/sduan.bsky.social" aria-label="Bluesky" title="Bluesky"><i class="fab fa-bluesky" aria-hidden="true"></i></a>
    <a href="https://twitter.com/duan_songtao" aria-label="Twitter" title="Twitter"><i class="fab fa-twitter" aria-hidden="true"></i></a>
  </div>
</div>
</div>
