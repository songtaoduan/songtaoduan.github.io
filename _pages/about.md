---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  /* Home page only: big rectangular photo on the right, text on the left */
  .home-intro { display: grid; grid-template-columns: minmax(0, 1fr) 260px; gap: 2.5em; align-items: start; }
  .home-photo { width: 100%; height: auto; display: block; border-radius: 2px; margin-top: 0.4em; }
  /* The big photo replaces the small round one in the sidebar on this page */
  .sidebar .author__avatar { display: none; }
  .sidebar .author__name { max-width: none !important; text-align: left !important; }
  html[data-theme="dark"] .home-photo { opacity: 1; }
  @media (max-width: 900px) {
    .home-intro { grid-template-columns: 1fr; }
    .home-photo { max-width: 260px; grid-row: 1; margin: 0 auto; }
  }
</style>

<div class="home-intro">
<div class="home-text" markdown="1">

<h2 style="border-bottom: none; margin-top: 0;">Welcome!</h2>

I am a PhD student in [political science](https://polisci.la.psu.edu/people/duan-songtao/) and [social data analytics](https://soda.la.psu.edu/) at the Pennsylvania State University. Prior to Penn State, I was a consultant and research assistant at the [Center for Global Development](https://www.cgdev.org/) in Washington D.C. I was also a graduate fellow at the [Reppy Institute for Peace and Conflict Studies](https://einaudi.cornell.edu/programs/reppy-institute-peace-and-conflict-studies) and the [Emerging Market Program](https://emergingmarkets.dyson.cornell.edu/smart/smart-2022-23/) at Cornell University.

My research interests focus on political economy of development, specifically foreign aid, civil wars and conflicts, and multilateral development organizations.  My work has been supported by the Vice Provost and Dean's Scholarship, the Miller-LaVigne Distinguished Graduate Fellowship, the Paterno Graduate Fellowship, Mario Einaudi Center for International Studies, and Cornell Brooks School of Public Policy.  

For inquiries, please reach out to me at [sduan@psu.edu](mailto:sduan@psu.edu), or connect with me on Bluesky [@sduan.bsky.social](https://bsky.app/profile/sduan.bsky.social).

</div>
<img class="home-photo" src="/images/headshot_rect.jpg" alt="Songtao Duan">
</div>
