---
layout: page
title: REFORM
permalink: /reform/
description: Weekly reading group on ML foundations and scalable reasoning systems.
nav: true
nav_order: 3
_styles: |
  .reform-hero {
    margin-bottom: 1.8rem;
    padding: 1.4rem;
    border-radius: 1rem;
    background: linear-gradient(130deg, rgba(0, 123, 255, 0.09), rgba(124, 58, 237, 0.09));
    border: 1px solid var(--global-divider-color);
  }

  .reform-hero p {
    margin: 0;
    line-height: 1.6;
  }

  .reform-hero ul {
    margin: 0.75rem 0 1rem 0;
    padding-left: 1.4rem;
  }

  .reform-hero li {
    margin-bottom: 0.35rem;
    line-height: 1.5;
  }

  .reform-actions {
    display: flex;
    gap: 0.75rem;
    flex-wrap: wrap;
    margin: 1.2rem 0 1.5rem 0;
  }

  .reform-actions a {
    display: inline-block;
    border: 1px solid var(--global-theme-color);
    border-radius: 999px;
    padding: 0.45rem 1rem;
    text-decoration: none;
    color: var(--global-theme-color);
    font-size: 0.92rem;
    transition: all 160ms ease;
  }

  .reform-actions a:hover {
    color: var(--global-bg-color);
    background-color: var(--global-theme-color);
  }

  .reform-meta {
    display: grid;
    gap: 0.45rem;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    margin-bottom: 1.6rem;
  }

  .reform-meta a {
    color: var(--global-theme-color);
  }

  .reform-people {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(240px, 1fr));
    gap: 1rem;
  }

  .reform-person-card {
    border: 1px solid var(--global-divider-color);
    border-radius: 12px;
    padding: 0.95rem 1rem;
    background: var(--global-card-bg-color);
    display: flex;
    flex-direction: column;
    gap: 0.45rem;
    min-height: 100%;
  }

  .reform-person-name {
    margin: 0;
    font-size: 1.1rem;
    line-height: 1.35;
  }

  .reform-person-role {
    margin: 0;
    color: var(--global-text-color-light);
    font-size: 0.9rem;
  }

  .reform-person-bio {
    margin: 0;
    color: var(--global-text-color);
    line-height: 1.45;
    font-size: 0.92rem;
  }

  .reform-person-links {
    margin-top: auto;
    padding-top: 0.2rem;
    display: flex;
    flex-wrap: wrap;
    gap: 0.75rem;
    font-size: 0.9rem;
  }

  .reform-person-links a {
    color: var(--global-theme-color);
    text-decoration: none;
  }

  .reform-person-links a:hover {
    text-decoration: underline;
  }

  .reform-section {
    margin-top: 2rem;
  }
---

<div class="reform-hero">
  <p>
    <strong>Rethinking Foundations of Real-world ML.</strong> The last few years have seen rapid
    developments in the deployment and adoption of ML systems. And yet, we lack a cohesive
    understanding of how these systems work, and the principles and laws (if any!) that govern
    their behavior. To this end, the goal of this reading group is to explore the intersection
    of cutting-edge experiments and corresponding explanations, with the goal of answering:
  </p>
  <ul>
    <li>How might we devise theoretical models that not only explain unexpected phenomena, but also predict new phenomena that we can verify experimentally?</li>
    <li>What are the right questions to ask, and phenomena to explain—at what level of abstraction should we be aiming to explain them?</li>
    <li>How can tools from statistics, CS theory, and operations research inform a better understanding of machine learning algorithms and systems?</li>
  </ul>
  <p>
    We meet every Thursday at 5:00 PM in CoDa W101.
  </p>
</div>

<div class="reform-actions">
  <a href="{% link _pages/reform-schedule.md %}">Upcoming &amp; past sessions</a>
  <a href="https://forms.gle/Pdz9AQ7mWVDMBJwm7">Sign up as a discussant</a>
  <a href="mailto:reform-ml-list@stanford.edu">Mailing list</a>
</div>

<div class="reform-meta">
  <div>
    <strong>Contact points</strong>
    <ul>
      <li>anaymehrotra1 [at] gmail [dot] com</li>
      <li>saberi [at] stanford [dot] edu</li>
      <li>gvelegkas [at] google [dot] com</li>
    </ul>
  </div>
  <div>
    <strong>Format</strong>
    <ul>
      <li>One deep-dive session each week</li>
      <li>20–30 minute discussant presentation</li>
      <li>Open discussion and open problems</li>
    </ul>
  </div>
  <div>
    <strong>Focus areas</strong>
    <ul>
      <li>Language model scaling and training dynamics</li>
      <li>Post-training and self-improvement</li>
      <li>Evaluation, reliability, and reasoning behavior</li>
    </ul>
  </div>
</div>

{% if site.data.reform_people and site.data.reform_people.size > 0 %}
<section class="reform-section">
  <h2 id="people">People involved</h2>

  <div class="reform-people">
    {% for person in site.data.reform_people %}
    <article class="reform-person-card">
      <h3 class="reform-person-name">{{ person.name }}</h3>
      <p class="reform-person-role">{{ person.role }}</p>
      <p class="reform-person-bio">{{ person.bio }}</p>
      <div class="reform-person-links">
        {% if person.email %}
        <a href="mailto:{{ person.email }}">Email</a>
        {% endif %}
        {% if person.website %}
        <a href="{{ person.website }}" rel="noopener" target="_blank">Webpage</a>
        {% endif %}
      </div>
    </article>
    {% endfor %}
  </div>
</section>
{% endif %}
