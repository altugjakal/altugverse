---
layout: default
title: About
---


<div class="about-wrapper">

  <header class="about-header">
    <h1>Mehmet Altuğ Jakal</h1>
  </header>

  <section class="about-bio">
    <p>
      I build search systems.
    </p>
  </section>

  <section class="about-section">
    <h2>Projects</h2>
    <div class="project-list">

      <div class="project-item">
        <div class="project-meta">
          <span class="project-name">janNet / corNet Search Suite</span>
          <span class="project-status">indev</span>
        </div>
        <p>A hybrid search engine combining VSP, dense retrieval, and MaxSim late interaction reranking with PageRank scoring. Crawler, indexer, and retrieval pipeline included.</p>
      </div>

    

    </div>
  </section>


</div>

<style>
.about-wrapper {
  max-width: 680px;
  margin: 0 auto;
  padding: 3rem 1.5rem;
}

.about-header {
  margin-bottom: 2.5rem;
  border-bottom: 1px solid currentColor;
  padding-bottom: 1.5rem;
  opacity: 0.9;
}

.about-header h1 {
  font-size: 2.2rem;
  margin: 0 0 0.4rem;
  letter-spacing: -0.02em;
}

.tagline {
  margin: 0;
  opacity: 0.6;
  font-style: italic;
}

.about-bio {
  margin-bottom: 3rem;
  line-height: 1.75;
}

.about-bio p + p {
  margin-top: 1rem;
}

.about-section {
  margin-bottom: 3rem;
}

.about-section h2 {
  font-size: 0.75rem;
  text-transform: uppercase;
  letter-spacing: 0.12em;
  opacity: 0.5;
  margin-bottom: 1.5rem;
}

.project-list {
  display: flex;
  flex-direction: column;
  gap: 1.75rem;
}

.project-item {
  padding-left: 1rem;
  border-left: 2px solid currentColor;
}

.project-meta {
  display: flex;
  align-items: baseline;
  gap: 0.75rem;
  margin-bottom: 0.4rem;
}

.project-name {
  font-weight: 600;
  font-size: 1rem;
}

.project-status {
  font-size: 0.7rem;
  text-transform: uppercase;
  letter-spacing: 0.1em;
  opacity: 0.45;
}

.interest-list {
  list-style: none;
  padding: 0;
  margin: 0;
  display: flex;
  flex-direction: column;
  gap: 0.85rem;
  line-height: 1.6;
}

.interest-list li::before {
  content: "— ";
  opacity: 0.4;
}
</style>
