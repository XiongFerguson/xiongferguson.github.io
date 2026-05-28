---
permalink: /
title: "Biography"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  .bio-visual {
    display: grid;
    grid-template-columns: minmax(0, 1.35fr) minmax(220px, 0.65fr);
    gap: 1.4rem;
    align-items: stretch;
    margin-bottom: 1.5rem;
  }

  .bio-intro,
  .bio-photo-panel,
  .bio-focus,
  .bio-area {
    border: 1px solid #e6e9ec;
    border-radius: 8px;
    background: #fff;
  }

  .bio-intro {
    padding: 1.25rem;
  }

  .bio-intro p {
    margin-bottom: 1rem;
  }

  .bio-intro p:last-child {
    margin-bottom: 0;
  }

  .bio-photo-panel {
    overflow: hidden;
    display: flex;
    flex-direction: column;
  }

  .bio-photo-panel img {
    width: 100%;
    aspect-ratio: 4 / 5;
    object-fit: cover;
  }

  .bio-photo-caption {
    padding: 0.85rem;
    font-size: 0.78rem;
    line-height: 1.45;
    color: #5f676d;
    background: #f8fafb;
  }

  .bio-focus {
    margin: 1.25rem 0;
    padding: 1rem 1.15rem;
    border-left: 4px solid #52adc8;
    background: #f6fbfd;
  }

  .bio-focus strong,
  .bio-section-title {
    display: block;
    margin-bottom: 0.45rem;
    color: #2f3a40;
    font-size: 0.95rem;
  }

  .bio-area-grid {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 0.8rem;
    margin: 1rem 0 1.5rem;
  }

  .bio-area {
    padding: 0.95rem;
  }

  .bio-area span {
    display: block;
    margin-bottom: 0.35rem;
    color: #3f7180;
    font-weight: 700;
  }

  .bio-area p {
    margin: 0;
    color: #5c646a;
    font-size: 0.86rem;
    line-height: 1.45;
  }

  @media (max-width: 760px) {
    .bio-visual,
    .bio-area-grid {
      grid-template-columns: 1fr;
    }

    .bio-photo-panel img {
      aspect-ratio: 16 / 10;
    }
  }
</style>

<div class="bio-visual">
  <div class="bio-intro">
    <p>I am J. Xiong, a Research Postgraduate within the thrust of Smart Manufacturing (SMMG) of the Systems Hub at <a href="https://www.hkust-gz.edu.cn/">The Hong Kong University of Science and Technology (Guangzhou)</a>. I am supervised by <a href="https://scholar.google.com/citations?user=3auvsZQAAAAJ&amp;hl=en">Dr. Guo Daqiang</a>.</p>
    <p>My research focuses on human-centric manufacturing, human-robot collaboration, human factors and ergonomics, and the human-centric adaptation of robotics.</p>
    <p>Please feel free to contact me by email for discussion, collaboration, or further information.</p>
  </div>

  <div class="bio-photo-panel">
    <img src="/images/HIMO_Personal%20Profile.JPG" alt="J. Xiong profile photo">
    <div class="bio-photo-caption">Research interests in human-centric manufacturing, adaptive robotics, and collaborative manufacturing systems.</div>
  </div>
</div>

<div class="bio-focus">
  <strong>Current Research Focus</strong>
  My current work focuses on monitoring and interpreting the physiological states of human operators, with the aim of supporting safer, more efficient, and more adaptive human-robot collaboration.
</div>

<strong class="bio-section-title">Research Areas</strong>
<div class="bio-area-grid">
  <div class="bio-area">
    <span>Human-Centric Manufacturing</span>
    <p>Designing manufacturing systems around human capability, safety, efficiency, and well-being.</p>
  </div>
  <div class="bio-area">
    <span>Human-Robot Collaboration</span>
    <p>Studying how operators and robots communicate, coordinate, and collaborate in shared tasks.</p>
  </div>
  <div class="bio-area">
    <span>Human Factors &amp; Ergonomics</span>
    <p>Understanding human workload, physiological state, and task experience in collaborative environments.</p>
  </div>
  <div class="bio-area">
    <span>Adaptive Robotics</span>
    <p>Enabling robotic systems to respond to human states and changing manufacturing contexts.</p>
  </div>
</div>
