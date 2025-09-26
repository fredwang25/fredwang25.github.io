---
layout: default
title: Home
---

<style>
  .hero { display: grid; grid-template-columns: 160px 1fr; gap: 1.25rem; align-items: center; }
  .hero img { width:160px; height:160px; object-fit:cover; border-radius:50%; }
  @media (max-width: 560px) {
    .hero { grid-template-columns: 1fr; justify-items: center; text-align:center; }
  }
  .section { margin: 2rem 0; }
  .meta { opacity: .85; }
  .list-compact li { margin-bottom: .5rem; }
</style>

<!-- HERO (image + name + contacts) -->
<header class="hero section">
  <img src="{{ '/assets/img/me.jpg' | relative_url }}" alt="Photo of Your Name" />
  <div>
    <h1 style="margin:0;">Your Name</h1>
    <p class="meta" style="margin:.25rem 0 0;">
      Your Title · Your Affiliation<br/>
      you@example.com · City, Country
    </p>
  </div>
</header>

<!-- BIO -->
<section class="section">
  <h2>Bio</h2>
  <p>
    This is a short placeholder bio. Write 2–3 sentences about your work, interests,
    and what you’re currently focused on.
  </p>
</section>

<!-- NEWS (hardcoded placeholders; newest first) -->
<section class="section">
  <h2>News</h2>
  <ul class="list-compact">
    <li><strong>2025-09-20</strong> — Placeholder news item about something recent.</li>
    <li><strong>2025-08-05</strong> — Another placeholder update.</li>
    <li><strong>2025-06-15</strong> — Yet another placeholder note.</li>
  </ul>
</section>

<!-- PAPERS (placeholders; no links) -->
<section class="section">
  <h2>Papers</h2>
  <ul class="list-compact">
    <li>
      <strong>Paper Title One</strong><br/>
      Author A, Author B, Your Name. <em>Venue Name</em>, 2025.
    </li>
    <li>
      <strong>Paper Title Two</strong><br/>
      Your Name, Author C. <em>Venue Name</em>, 2024.
    </li>
    <li>
      <strong>Paper Title Three</strong><br/>
      Author D, Your Name, Author E. <em>Venue Name</em>, 2023.
    </li>
  </ul>
</section>
