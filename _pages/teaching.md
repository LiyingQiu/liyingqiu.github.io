---
layout: page
permalink: /teaching/
title: Teaching
nav: true
nav_order: 3
---

<style>
  .teaching-page {
    max-width: 950px;
    margin: 0 auto;
  }

  .teaching-intro {
    margin-bottom: 2rem;
    font-size: 1.05rem;
    line-height: 1.65;
    color: var(--global-text-color);
  }

  .teaching-section {
    margin-bottom: 2.4rem;
    padding: 1.7rem 1.9rem;
    border: 1px solid var(--global-divider-color);
    border-radius: 14px;
    background: var(--global-card-bg-color);
  }

  .teaching-role {
    margin-bottom: 1.35rem;
    font-size: 1.45rem;
    font-weight: 700;
    color: var(--global-theme-color);
  }

  .course-list {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 1.1rem 1.25rem;
  }

  .course-list.single-course {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }

  .course-list.single-course .course-item {
    max-width: none;
  }

  .course-item {
    padding: 1.1rem 1.25rem;
    border: 1px solid var(--global-divider-color);
    border-radius: 8px;
    background: var(--global-bg-color);
    box-sizing: border-box;
  }

  .course-title {
    font-weight: 700;
    font-size: 1.02rem;
    line-height: 1.4;
    margin-bottom: 0.35rem;
  }

  .course-level {
    font-style: italic;
    color: var(--global-text-color-light);
    font-size: 0.95rem;
    line-height: 1.4;
  }

  @media (max-width: 700px) {
    .teaching-section {
      padding: 1.35rem 1.25rem;
    }

    .course-list,
    .course-list.single-course {
      grid-template-columns: 1fr;
    }
  }
</style>

<div class="teaching-page">

<p class="teaching-intro">
My teaching experience spans MBA, MSBA, undergraduate, and PhD courses, with a focus on quantitative methods, data analytics, digital marketing, artificial intelligence, and empirical research in business.
</p>

<section class="teaching-section">
  <h2 class="teaching-role">Instructor</h2>

  <div class="course-list single-course">
    <div class="course-item">
      <div class="course-title">Math Skills Workshop</div>
      <div class="course-level">MBA</div>
    </div>
  </div>
</section>

<section class="teaching-section">
  <h2 class="teaching-role">Teaching Assistant</h2>

  <div class="course-list">
    <div class="course-item">
      <div class="course-title">Data Exploration and Visualization</div>
      <div class="course-level">MBA, Undergraduate</div>
    </div>

    <div class="course-item">
      <div class="course-title">Digital Marketing and Social Media Strategy</div>
      <div class="course-level">MBA, MSBA, Undergraduate</div>
    </div>

    <div class="course-item">
      <div class="course-title">Modern Data Management</div>
      <div class="course-level">MBA</div>
    </div>

    <div class="course-item">
      <div class="course-title">Economics of AI in Business Research</div>
      <div class="course-level">PhD</div>
    </div>
  </div>
</section>

<section class="teaching-section">
  <h2 class="teaching-role">Guest Lecturer</h2>

  <div class="course-list">
    <div class="course-item">
      <div class="course-title">Digital Marketing and Social Media Strategy</div>
      <div class="course-level">Undergraduate</div>
    </div>

    <div class="course-item">
      <div class="course-title">Structural Models &amp; Quantitative Methods</div>
      <div class="course-level">PhD</div>
    </div>
  </div>
</section>

</div>
