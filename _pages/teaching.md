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

/* Award heading + photo gallery */
.gallery {
  position: relative;
  border: 1px solid rgba(128, 128, 128, 0.25);
  border-radius: 10px;
  background: rgba(128, 128, 128, 0.04);
  margin-bottom: 28px;
  padding: 14px 0 10px;
}
.gallery-track {
  display: flex;
  overflow-x: auto;
  scroll-snap-type: x mandatory;
  scroll-behavior: smooth;
  scrollbar-width: none;
}
.gallery-track::-webkit-scrollbar { display: none; }
.gallery-slide {
  flex: 0 0 100%;
  scroll-snap-align: center;
  display: flex;
  flex-direction: column;
  align-items: center;
  cursor: zoom-in;
  border-bottom: none !important;
  text-decoration: none;
}
.gallery-slide img {
  display: block;
  height: 240px;
  width: auto;
  max-width: calc(100% - 96px);
  object-fit: contain;
  border-radius: 6px;
}
.gallery-slide .cap {
  margin-top: 10px;
  padding: 0 56px;
  max-width: 640px;
  text-align: center;
  font-size: 0.8rem;
  line-height: 1.5;
  color: #6b7280;
}
.gallery-slide .cap b {
  display: block;
  font-size: 0.92rem;
  font-weight: 500;
  color: #313131;
}
.gallery-btn {
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  width: 34px;
  height: 34px;
  border-radius: 50%;
  border: 1px solid rgba(128, 128, 128, 0.3);
  background: #fff;
  color: #333;
  font-size: 1.1rem;
  line-height: 1;
  cursor: pointer;
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 0;
}
.gallery-btn.prev { left: 12px; }
.gallery-btn.next { right: 12px; }
.gallery-dots {
  display: flex;
  justify-content: center;
  gap: 6px;
  margin-top: 8px;
}
.gallery-dots button {
  width: 7px;
  height: 7px;
  border-radius: 50%;
  border: 0;
  padding: 0;
  background: rgba(128, 128, 128, 0.35);
  cursor: pointer;
}
.gallery-dots button.on { background: #3b5b92; }

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
@media (max-width: 600px) {
  .gallery-slide img { height: 200px; max-width: calc(100% - 80px); }
}
</style>

## Teaching Award

<div class="gallery" id="award-gallery" markdown="0">
  <div class="gallery-track">
    <a class="gallery-slide" href="{{ '/images/teaching_award_2025_full.jpg' | relative_url }}">
      <img src="{{ '/images/teaching_award_2025_card.jpg' | relative_url }}" alt="Jaeyoung Lee receiving the A. Belden Fields Award at the 2025 Political Science Awards Banquet">
      <span class="cap"><b>A. Belden Fields Award for Excellence in Undergraduate Teaching as a Teaching Assistant</b>Department of Political Science, UIUC &middot; 2025 Awards Banquet</span>
    </a>
    <a class="gallery-slide" href="{{ '/images/student_card_1.jpg' | relative_url }}">
      <img src="{{ '/images/student_card_1.jpg' | relative_url }}" alt="Handwritten thank-you card from a student">
      <span class="cap"><b>A thank-you card from a student</b>PS280 Introduction to International Relations &middot; Spring 2026</span>
    </a>
  </div>
  <button type="button" class="gallery-btn prev" aria-label="Previous photo">&#8249;</button>
  <button type="button" class="gallery-btn next" aria-label="Next photo">&#8250;</button>
  <div class="gallery-dots"></div>
</div>

<div class="photo-overlay" id="photo-overlay" markdown="0">
  <img src="" alt="">
</div>

<script>
(function () {
  var g = document.getElementById('award-gallery');
  var overlay = document.getElementById('photo-overlay');
  if (!g || !overlay) { return; }
  var track = g.querySelector('.gallery-track');
  var slides = g.querySelectorAll('.gallery-slide');
  var prev = g.querySelector('.prev'), next = g.querySelector('.next');
  var dotsBox = g.querySelector('.gallery-dots');
  var big = overlay.querySelector('img');
  var cur = 0, open = -1;

  if (slides.length < 2) { prev.style.display = 'none'; next.style.display = 'none'; }

  Array.prototype.forEach.call(slides, function (s, i) {
    var d = document.createElement('button');
    d.type = 'button';
    d.setAttribute('aria-label', 'Photo ' + (i + 1));
    d.addEventListener('click', function () { go(i); });
    dotsBox.appendChild(d);
    s.addEventListener('click', function (e) { e.preventDefault(); show(i); });
  });
  var dots = dotsBox.querySelectorAll('button');

  function update() {
    Array.prototype.forEach.call(dots, function (d, i) { d.className = i === cur ? 'on' : ''; });
  }
  function go(i) {
    cur = (i + slides.length) % slides.length;
    track.scrollTo({ left: cur * track.clientWidth });
    update();
  }
  prev.addEventListener('click', function () { go(cur - 1); });
  next.addEventListener('click', function () { go(cur + 1); });
  track.addEventListener('scroll', function () {
    var i = Math.round(track.scrollLeft / track.clientWidth);
    if (i !== cur) { cur = i; update(); }
  });

  function show(i) {
    open = (i + slides.length) % slides.length;
    big.src = slides[open].getAttribute('href');
    big.alt = slides[open].querySelector('img').alt;
    overlay.className = 'photo-overlay open';
  }
  function hide() { overlay.className = 'photo-overlay'; open = -1; }
  overlay.addEventListener('click', hide);
  document.addEventListener('keydown', function (e) {
    if (open < 0) { return; }
    if (e.key === 'Escape') { hide(); }
    if (e.key === 'ArrowRight') { show(open + 1); }
    if (e.key === 'ArrowLeft') { show(open - 1); }
  });
  update();
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
