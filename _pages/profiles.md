---
layout: page
permalink: /people/
title: People
description: ""
hide_title: true
nav: true
nav_order: 4
_styles: |
  .people-intro {
    margin-bottom: 2rem;
  }

  .people-intro p {
    color: var(--global-text-color-light);
    max-width: 72ch;
    margin: 0;
    line-height: 1.6;
  }

  .people-section {
    margin-bottom: 2.75rem;
  }

  .people-section + .people-section {
    margin-top: 2.25rem;
  }

  .people-section__header {
    margin-bottom: 1rem;
  }

  .people-section__heading {
    margin: 0;
    font-size: 1.55rem;
    line-height: 1.35;
  }

  .people-section__subtitle {
    margin: 0.2rem 0 0;
    color: var(--global-text-color-light);
  }

  .people-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(240px, 1fr));
    gap: 1rem;
    align-items: stretch;
  }

  .person-card {
    display: flex;
    flex-direction: column;
    gap: 0.65rem;
  }

  .person-card__photo {
    width: 100%;
    aspect-ratio: 1 / 1;
    object-fit: cover;
    border-radius: 10px;
    border: 1px solid var(--global-divider-color);
  }

  .person-card__content {
    display: flex;
    flex-direction: column;
    gap: 0.45rem;
  }

  .person-card__links {
    margin-top: auto;
    padding-top: 0.3rem;
    display: flex;
    flex-wrap: wrap;
    gap: 0.75rem;
  }
---

<section class="people-section" id="faculty-director">
  <header class="people-section__header">
    <h2 class="people-section__heading">Faculty Director</h2>
  </header>
  <div class="people-grid">
    <article class="person-card">
      <img class="person-card__photo" src="{{ '/assets/img/ldr/amin-saberi.jpg' | relative_url }}" alt="Amin Saberi" loading="lazy" />
      <div class="person-card__content">
        <h3 class="person-card__name">Amin Saberi</h3>
        <p class="person-card__role">Professor, Management Science &amp; Engineering</p>
        <p class="person-card__links">
          <a href="https://stanford.edu/~saberi/" rel="noopener">Homepage</a>
          <a href="{% link _pages/people/amin-saberi.md %}">Profile</a>
        </p>
      </div>
    </article>
  </div>
</section>

<section class="people-section" id="affiliated-faculty">
  <header class="people-section__header">
    <h2 class="people-section__heading">Affiliated Faculty</h2>
  </header>

  <div class="people-grid">
    <article class="person-card">
      <img class="person-card__photo" src="{{ '/assets/img/ldr/azalia-mirhosseini.jpg' | relative_url }}" alt="Azalia Mirhosseini" loading="lazy" />
      <div class="person-card__content">
        <h3 class="person-card__name">Azalia Mirhosseini</h3>
        <p class="person-card__role">Assistant Professor, Computer Science</p>
        <p class="person-card__links">
          <a href="https://azaliamirhoseini.com" rel="noopener">Homepage</a>
          <a href="{% link _pages/people/azalia-mirhosseini.md %}">Profile</a>
        </p>
      </div>
    </article>

    <article class="person-card">
      <img class="person-card__photo" src="{{ '/assets/img/ldr/ellen-vitercik.jpeg' | relative_url }}" alt="Ellen Vitercik" loading="lazy" />
      <div class="person-card__content">
        <h3 class="person-card__name">Ellen Vitercik</h3>
        <p class="person-card__role">Assistant Professor, Stanford University</p>
        <p class="person-card__links">
          <a href="https://vitercik.github.io" rel="noopener">Homepage</a>
          <a href="{% link _pages/people/ellen-vitercik.md %}">Profile</a>
        </p>
      </div>
    </article>

    <article class="person-card">
      <img class="person-card__photo" src="{{ '/assets/img/ldr/diyi-yang.jpg' | relative_url }}" alt="Diyi Yang" loading="lazy" />
      <div class="person-card__content">
        <h3 class="person-card__name">Diyi Yang</h3>
        <p class="person-card__role">Assistant Professor, Computer Science</p>
        <p class="person-card__links">
          <a href="https://cs.stanford.edu/~diyiy/" rel="noopener">Homepage</a>
          <a href="{% link _pages/people/diyi-yang.md %}">Profile</a>
        </p>
      </div>
    </article>

  </div>
</section>

<section class="people-section" id="postdocs-research-scientists">
  <header class="people-section__header">
    <h2 class="people-section__heading">Postdocs &amp; Research Scientists</h2>
  </header>

  <div class="people-grid">
    <article class="person-card">
      <img class="person-card__photo" src="{{ '/assets/img/ldr/anay-mehrotra.jpg' | relative_url }}" alt="Anay Mehrotra" loading="lazy" />
      <div class="person-card__content">
        <h3 class="person-card__name">Anay Mehrotra</h3>
        <p class="person-card__role">Postdoctoral Fellow</p>
        <p class="person-card__links">
          <a href="https://anaymehrotra.com" rel="noopener">Homepage</a>
          <a href="{% link _pages/people/anay-mehrotra.md %}">Profile</a>
        </p>
      </div>
    </article>

    <article class="person-card">
      <img class="person-card__photo" src="{{ '/assets/img/ldr/xizhitan.jpeg' | relative_url }}" alt="Xizhi Tan" loading="lazy" />
      <div class="person-card__content">
        <h3 class="person-card__name">Xizhi Tan</h3>
        <p class="person-card__role">Postdoctoral Fellow</p>
        <p class="person-card__links">
          <a href="https://xizhitan.github.io" rel="noopener">Homepage</a>
          <a href="{% link _pages/people/xizhi-tan.md %}">Profile</a>
        </p>
      </div>
    </article>

    <article class="person-card">
      <img class="person-card__photo" src="{{ '/assets/img/ldr/grigoris-velegkas.jpg' | relative_url }}" alt="Grigoris Velegkas" loading="lazy" />
      <div class="person-card__content">
        <h3 class="person-card__name">Grigoris Velegkas</h3>
        <p class="person-card__role">Research Scientist, Google Research</p>
        <p class="person-card__links">
          <a href="https://gvelegkas.github.io" rel="noopener">Homepage</a>
          <a href="{% link _pages/people/grigoris-velegkas.md %}">Profile</a>
        </p>
      </div>
    </article>

  </div>
</section>

<section class="people-section" id="graduate-students">
  <header class="people-section__header">
    <h2 class="people-section__heading">Graduate Students</h2>
  </header>

  <div class="people-grid">
    <article class="person-card">
      <img class="person-card__photo" src="{{ '/assets/img/ldr/emil-dp-wp.jpg' | relative_url }}" alt="Emil Biju" loading="lazy" />
      <div class="person-card__content">
        <h3 class="person-card__name">Emil Biju</h3>
        <p class="person-card__role">Graduate Student</p>
        <p class="person-card__links">
          <a href="https://emilbiju.github.io" rel="noopener">Homepage</a>
          <a href="{% link _pages/people/emil-biju.md %}">Profile</a>
        </p>
      </div>
    </article>

    <article class="person-card">
      <img class="person-card__photo" src="{{ '/assets/img/ldr/david-castro-pena.jpg' | relative_url }}" alt="David Castro-Peña" loading="lazy" />
      <div class="person-card__content">
        <h3 class="person-card__name">David Castro-Peña</h3>
        <p class="person-card__role">Graduate Student</p>
        <p class="person-card__links">
          <a href="https://davidcastropena.github.io" rel="noopener">Homepage</a>
          <a href="{% link _pages/people/david-castro-pena.md %}">Profile</a>
        </p>
      </div>
    </article>

    <article class="person-card">
      <img class="person-card__photo" src="{{ '/assets/img/ldr/abhinav-chinta.jpg' | relative_url }}" alt="Abhinav Chinta" loading="lazy" />
      <div class="person-card__content">
        <h3 class="person-card__name">Abhinav Chinta</h3>
        <p class="person-card__role">Graduate Student</p>
        <p class="person-card__links">
          <a href="https://abhinavchinta.com" rel="noopener">Homepage</a>
          <a href="{% link _pages/people/abhinav-chinta.md %}">Profile</a>
        </p>
      </div>
    </article>

    <article class="person-card">
      <img class="person-card__photo" src="{{ '/assets/img/ldr/winnie-chow.jpg' | relative_url }}" alt="Winnie Chow" loading="lazy" />
      <div class="person-card__content">
        <h3 class="person-card__name">Winnie Chow</h3>
        <p class="person-card__role">Graduate Student</p>
        <p class="person-card__links">
          <a href="https://www.linkedin.com/in/winniechow0617/" rel="noopener">Homepage</a>
          <a href="{% link _pages/people/winnie-chow.md %}">Profile</a>
        </p>
      </div>
    </article>

    <article class="person-card">
      <img class="person-card__photo" src="{{ '/assets/img/ldr/kent-hippler.png' | relative_url }}" alt="Kent Hippler" loading="lazy" />
      <div class="person-card__content">
        <h3 class="person-card__name">Kent Hippler</h3>
        <p class="person-card__role">Graduate Student</p>
        <p class="person-card__links">
          <a href="https://www.linkedin.com/in/jkenthippler/" rel="noopener">Homepage</a>
          <a href="{% link _pages/people/kent-hippler.md %}">Profile</a>
        </p>
      </div>
    </article>

    <article class="person-card">
      <img class="person-card__photo" src="{{ '/assets/img/ldr/zhemin-huang.jpg' | relative_url }}" alt="Zhemin Huang" loading="lazy" />
      <div class="person-card__content">
        <h3 class="person-card__name">Zhemin Huang</h3>
        <p class="person-card__role">Graduate Student</p>
        <p class="person-card__links">
          <a href="https://www.linkedin.com/in/xav-huang/" rel="noopener">Homepage</a>
          <a href="{% link _pages/people/zhemin-huang.md %}">Profile</a>
        </p>
      </div>
    </article>

    <article class="person-card">
      <img class="person-card__photo" src="{{ '/assets/img/ldr/senem.png' | relative_url }}" alt="Senem Işık" loading="lazy" />
      <div class="person-card__content">
        <h3 class="person-card__name">Senem Işık</h3>
        <p class="person-card__role">Graduate Student</p>
        <p class="person-card__links">
          <a href="https://sites.google.com/view/senem-ashak" rel="noopener">Homepage</a>
          <a href="{% link _pages/people/senem-ashak.md %}">Profile</a>
        </p>
      </div>
    </article>

    <article class="person-card">
      <img class="person-card__photo" src="{{ '/assets/img/ldr/sneha-jayaganthan.jpg' | relative_url }}" alt="Sneha Jayaganthan" loading="lazy" />
      <div class="person-card__content">
        <h3 class="person-card__name">Sneha Jayaganthan</h3>
        <p class="person-card__role">Graduate Student</p>
        <p class="person-card__links">
          <a href="https://www.linkedin.com/in/sneha-jayaganthan-a492601a9/" rel="noopener">Homepage</a>
          <a href="{% link _pages/people/sneha-jayaganthan.md %}">Profile</a>
        </p>
      </div>
    </article>

    <article class="person-card">
      <img class="person-card__photo" src="{{ '/assets/img/ldr/meijin-li.png' | relative_url }}" alt="Meijin Li" loading="lazy" />
      <div class="person-card__content">
        <h3 class="person-card__name">Meijin Li</h3>
        <p class="person-card__role">Graduate Student</p>
        <p class="person-card__links">
          <a href="https://www.linkedin.com/in/limeijin/" rel="noopener">Homepage</a>
          <a href="{% link _pages/people/meijin-li.md %}">Profile</a>
        </p>
      </div>
    </article>

    <article class="person-card">
      <img class="person-card__photo" src="{{ '/assets/img/ldr/shayan-talaei.jpg' | relative_url }}" alt="Shayan Talaei" loading="lazy" />
      <div class="person-card__content">
        <h3 class="person-card__name">Shayan Talaei</h3>
        <p class="person-card__role">Graduate Student</p>
        <p class="person-card__links">
          <a href="https://shayantalaei.com" rel="noopener">Homepage</a>
          <a href="{% link _pages/people/shayan-talaei.md %}">Profile</a>
        </p>
      </div>
    </article>

  </div>
</section>
