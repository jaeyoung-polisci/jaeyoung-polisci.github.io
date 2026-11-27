---
layout: single
title: "Teaching"
permalink: /teaching/
author_profile: true
excerpt: "Teaching experience of Jaeyoung Lee at the University of Illinois Urbana-Champaign."
read_time: false
show_date: false
---

<style>
/* ── Teaching page styles ───────────────────────────────────────── */
/* Edit values here once — they apply to every course card below.    */

.course {
  border: 1px solid rgba(128, 128, 128, 0.25);
  border-radius: 10px;
  padding: 18px 22px;
  margin-bottom: 16px;
  background: rgba(128, 128, 128, 0.04);
}

/* Title row: course name on the left, term on the right */
.course-head {
  display: flex;
  align-items: baseline;
  justify-content: space-between;
  gap: 12px;
  flex-wrap: wrap;
}
.course-head h3 {
  margin: 0;
  font-size: 1.12rem;
  line-height: 1.4;
}
.course-term {
  font-size: 0.85rem;
  opacity: 0.6;
  white-space: nowrap;
}

/* Badges (rating + excellence) */
.course-badges {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin: 11px 0 12px;
}
.badge {
  font-size: 0.78rem;
  font-weight: 600;
  padding: 3px 11px;
  border-radius: 6px;
  white-space: nowrap;
}
.badge--rating  { background: rgba(15, 110, 86, 0.15);  color: #0f6e56; }
.badge--pending { background: rgba(128, 128, 128, 0.18); color: inherit; opacity: 0.85; }
.badge--excellent { background: rgba(42, 109, 176, 0.15); color: #2a6db0; }

/* Resource links */
.course-links {
  display: flex;
  flex-wrap: wrap;
  gap: 16px;
  font-size: 0.9rem;
}
.course-links a {
  text-decoration: none;
  border-bottom: 1px solid transparent;
}
.course-links a:hover { border-bottom-color: currentColor; }

.teaching-note {
  font-size: 0.85rem;
  opacity: 0.6;
  margin-top: 18px;
  line-height: 1.6;
}

/* Award card (large photo with caption below) */
.award {
  max-width: 460px;
  border: 1px solid rgba(128, 128, 128, 0.25);
  border-radius: 10px;
  overflow: hidden;
  background: rgba(128, 128, 128, 0.04);
  margin-bottom: 28px;
}
.award-photo {
  position: relative;
  display: block;
  cursor: zoom-in;
  border-bottom: none !important;
}
.award-photo img {
  display: block;
  width: 100%;
  aspect-ratio: 1.55 / 1;
  object-fit: cover;
  object-position: center 50%;
}
.award-photo span {
  position: absolute;
  right: 10px;
  top: 10px;
  font-size: 0.7rem;
  color: #fff;
  background: rgba(0, 0, 0, 0.55);
  padding: 2px 9px;
  border-radius: 10px;
}

/* Full-size photo overlay */
.photo-overlay {
  display: none;
  position: fixed;
  inset: 0;
  z-index: 9999;
  background: rgba(0, 0, 0, 0.85);
  align-items: center;
  justify-content: center;
  padding: 24px;
  cursor: zoom-out;
}
.photo-overlay.open { display: flex; }
.photo-overlay img {
  max-width: 100%;
  max-height: 100%;
  border-radius: 6px;
  box-shadow: 0 10px 40px rgba(0, 0, 0, 0.5);
}
.award-text {
  padding: 14px 20px 16px;
}
.award .award-label {
  font-size: 0.75rem;
  font-weight: 400;
  letter-spacing: 0.04em;
  color: #3b5b92;
  margin: 0 0 4px;
}
.award .award-text h3 {
  margin: 0;
  font-size: 1.02rem;
  font-weight: 500;
  line-height: 1.45;
}
</style>

## Teaching Award

<div class="award" markdown="0">
  <a class="award-photo" href="{{ '/images/teaching_award_2025_full.jpg' | relative_url }}" id="award-photo">
    <img src="{{ '/images/teaching_award_2025_card.jpg' | relative_url }}" alt="Jaeyoung Lee receiving the A. Belden Fields Award at the 2025 Political Science Awards Banquet">
    <span>View photo</span>
  </a>
  <div class="award-text">
    <p class="award-label">2025 &middot; Department of Political Science, UIUC</p>
    <h3>A. Belden Fields Award for Excellence in Undergraduate Teaching as a Teaching Assistant</h3>
  </div>
</div>

<div class="photo-overlay" id="photo-overlay" markdown="0">
  <img src="{{ '/images/teaching_award_2025_full.jpg' | relative_url }}" alt="Jaeyoung Lee receiving the A. Belden Fields Award at the 2025 Political Science Awards Banquet">
</div>

<script>
(function () {
  var link = document.getElementById('award-photo');
  var overlay = document.getElementById('photo-overlay');
  if (!link || !overlay) { return; }
  link.addEventListener('click', function (e) { e.preventDefault(); overlay.className = 'photo-overlay open'; });
  overlay.addEventListener('click', function () { overlay.className = 'photo-overlay'; });
  document.addEventListener('keydown', function (e) { if (e.key === 'Escape') { overlay.className = 'photo-overlay'; } });
})();
</script>

## Teaching Assistant, University of Illinois Urbana-Champaign

<div class="course" markdown="0">
  <div class="course-head">
    <h3>PS280 &middot; Introduction to International Relations</h3>
    <span class="course-term">Spring 2026</span>
  </div>
  <div class="course-badges">
    <span class="badge badge--pending">Evaluations 4.53 / 5.0</span>
  </div>
  <div class="course-links">
    <a href="/files/ps280_slides.pdf">Sample materials</a>
    <a href="/files/ps280_evaluation.pdf">Full report</a>
  </div>
</div>

<div class="course" markdown="0">
  <div class="course-head">
    <h3>PS272 &middot; Women and Politics</h3>
    <span class="course-term">Fall 2025</span>
  </div>
  <div class="course-badges">
    <span class="badge badge--rating">Evaluation 4.78 / 5.0</span>
  </div>
  <div class="course-links">
    <a href="/files/ps272_slides.pdf">Sample materials</a>
    <a href="/files/ps272_evaluation.pdf">Full report</a>
  </div>
</div>

<div class="course" markdown="0">
  <div class="course-head">
    <h3>PS282 &middot; Governing Globalization</h3>
    <span class="course-term">Spring 2024, Fall 2022</span>
  </div>
  <div class="course-badges">
    <span class="badge badge--rating">Evaluation 4.88 / 5.0</span>
    <span class="badge badge--excellent">Ranked as Excellent</span>
  </div>
  <div class="course-links">
    <a href="/files/ps282_slides.pdf">Sample materials</a>
    <a href="/files/ps282_evaluation.pdf">Full report</a>
  </div>
</div>

<div class="course" markdown="0">
  <div class="course-head">
    <h3>PS270 &middot; Introduction to Political Theory</h3>
    <span class="course-term">Spring 2023</span>
  </div>
  <div class="course-badges">
    <span class="badge badge--rating">Evaluation 4.6 / 5.0</span>
    <span class="badge badge--excellent">Ranked as Excellent</span>
  </div>
  <div class="course-links">
    <a href="/files/ps270_slides.pdf">Sample materials</a>
    <a href="/files/ps270_evaluation.pdf">Full report</a>
  </div>
</div>

<p class="teaching-note">Courses badged &ldquo;Ranked as Excellent&rdquo; were listed in the university-wide Teachers Ranked as Excellent by Their Students (top 10%).</p>
