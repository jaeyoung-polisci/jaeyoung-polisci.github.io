---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---

<style>
/* ── Research page styles ───────────────────────────────────────── */
/* Edit values here once — they apply to every project card below.   */

.proj {
  width: 100%;
  box-sizing: border-box;
  border: 1px solid rgba(128, 128, 128, 0.25);
  border-radius: 10px;
  padding: 22px 24px;
  margin-bottom: 22px;
  background: rgba(128, 128, 128, 0.04);
}

/* The dissertation gets a stronger left accent so it reads as the
   centerpiece. Change the accent color in one place here. */
.proj--feature {
  border-left: 4px solid #2a6db0;
}

.proj h3 {
  margin: 0 0 6px;
  line-height: 1.4;
  font-size: 1.18rem;
}

.proj .authors {
  margin: 0 0 8px;
  font-size: 0.92rem;
  opacity: 0.75;
}

/* One-sentence takeaway, always visible */
.proj .lede {
  margin: 0 0 10px;
  font-size: 0.97rem;
  line-height: 1.6;
}

/* Methods / data line */
.proj .methods {
  margin: 0 0 12px;
  font-size: 0.82rem;
  letter-spacing: 0.01em;
  opacity: 0.65;
}

/* Optional figure inside a card */
.proj figure {
  margin: 4px 0 14px;
}
.proj figure img {
  width: 100%;
  max-width: 560px;
  border-radius: 6px;
  border: 1px solid rgba(128, 128, 128, 0.2);
}
.proj figcaption {
  margin-top: 6px;
  font-size: 0.82rem;
  opacity: 0.7;
}

/* Status tags + links sit on one row */
.proj-meta {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  gap: 8px;
  margin-bottom: 12px;
}

.tag {
  font-size: 0.78rem;
  font-weight: 600;
  letter-spacing: 0.02em;
  padding: 3px 11px;
  border-radius: 6px;
  white-space: nowrap;
}

.tag--jmp     { background: rgba(42, 109, 176, 0.15); color: #2a6db0; }
.tag--review  { background: rgba(15, 110, 86, 0.15);  color: #0f6e56; }
.tag--working { background: rgba(133, 79, 11, 0.15);  color: #854f0b; }
.tag--rr      { background: rgba(83, 74, 183, 0.15);  color: #534ab7; }
.tag--prep    { background: rgba(128, 128, 128, 0.18); color: inherit; opacity: 0.85; }

/* Links render as small outlined buttons */
.proj-links {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin-left: auto;
  font-size: 0.8rem;
}

.proj-links a {
  text-decoration: none;
  padding: 2px 10px;
  border: 1px solid rgba(42, 109, 176, 0.45);
  border-radius: 6px;
  color: #2a6db0;
  white-space: nowrap;
}
.proj-links a:hover {
  background: rgba(42, 109, 176, 0.1);
}

/* Abstract toggle */
.proj details { margin-top: 4px; }
.proj summary {
  cursor: pointer;
  font-weight: 600;
  font-size: 0.9rem;
  opacity: 0.85;
  list-style: none;
}
.proj summary::-webkit-details-marker { display: none; }
.proj summary::before {
  content: "▸";
  display: inline-block;
  margin-right: 6px;
  transition: transform 0.15s ease;
}
.proj details[open] summary::before { transform: rotate(90deg); }
.proj details p {
  margin-top: 10px;
  font-size: 0.95rem;
  line-height: 1.65;
  opacity: 0.92;
}
</style>

## Dissertation Project

<div class="proj proj--feature" markdown="0">
  <div class="proj-meta">
    <span class="tag tag--jmp">Job Market Paper</span>
    <span class="tag tag--prep">In Progress</span>
    <span class="proj-links">
      <a href="/data/">Data</a>
      <!-- Add links as they become available, e.g.: -->
      <!-- <a href="/files/jmp_draft.pdf">Draft</a> -->
      <!-- <a href="https://osf.io/xxxxx">Pre-registration</a> -->
    </span>
  </div>
  <h3>Strategic Publicity Management in Foreign Aid: When and Why Do Governments Publicize or Conceal Aid Projects?</h3>
  <p class="lede">How aid-receiving governments decide whether to name donors, obscure them, claim credit for aid-funded projects, or stay silent about them.</p>
  <p class="methods">Cross-national press release data · Interviews · Conjoint experiment</p>

  <!-- Figure: copy an image path from _pages/data.md, then remove this comment wrapper.
  <figure>
    <img src="/images/YOUR_FIGURE.png" alt="Donor visibility in government press releases over time">
    <figcaption>Donor visibility in Philippine government press releases declines over time. <a href="/data/">More figures</a></figcaption>
  </figure>
  -->

  <details>
    <summary>Abstract</summary>
    <p>
      This project examines how aid-receiving governments strategically manage the publicity of foreign aid projects in their public communications. I conceptualize publicity as four distinct communication strategies: full disclosure, in which governments explicitly identify the foreign donor; partial disclosure, in which they publicize aid-funded projects while referring only vaguely to external funders as &ldquo;development partners&rdquo;; credit stealing, in which they present externally financed development outcomes as government achievements; and non-publicity, in which they omit aid projects from public communication altogether. I argue that governments choose among these strategies depending on donor identity, project characteristics, and domestic political incentives. The project builds an original cross-national dataset linking foreign aid project records to government press releases across multiple aid-receiving countries, supplemented by interviews and an original conjoint experiment. By distinguishing whether governments name donors, obscure donor involvement, claim credit for externally financed projects, or remain silent about them, the project explains when foreign aid becomes politically visible and when donor involvement is hidden from public view.
    </p>
  </details>
</div>

## Other Projects

<div class="proj" markdown="0">
  <div class="proj-meta">
    <span class="tag tag--working">Working Paper</span>
    <span class="proj-links">
      <!-- <a href="/files/donors_draft.pdf">Draft</a> -->
    </span>
  </div>
  <h3>What To Do If Donors Do Not Deliver: Recipient Responses to Poor Implementation of Foreign Aid Projects</h3>
  <p class="authors">with Matthew S. Winters</p>
  <p class="lede">After poor World Bank performance, recipient governments approve fewer new projects and take longer to make loans effective.</p>
  <p class="methods">World Bank project evaluation data, 1995–2020</p>
  <details>
    <summary>Abstract</summary>
    <p>
      This paper examines whether aid-receiving governments can hold foreign aid donors accountable for poor project implementation. We argue that recipients may respond to unreliable donors by reducing future engagement, even in a policy area often understood as donor-driven. Using World Bank project evaluation data from 1995 to 2020, we find that poor World Bank performance is followed by fewer new project approvals, especially among IBRD borrowers and in Investment Project Financing, as well as delays between project approval and loan effectiveness.
    </p>
  </details>
</div>

<div class="proj" markdown="0">
  <div class="proj-meta">
    <span class="tag tag--prep">In Progress</span>
    <span class="proj-links">
    </span>
  </div>
  <h3>When Foreign Aid Wins Hearts and Minds: Sociotropic vs. Pocketbook Effects</h3>
  <p class="lede">Does aid improve attitudes toward donors because people benefit personally, or because they see it helping their country?</p>
  <details>
    <summary>Abstract</summary>
    <p>
      This project examines whether foreign aid improves public attitudes toward donor countries through direct personal benefits or broader perceptions of national development. While existing research suggests that foreign aid can help donors win hearts and minds, less is known about whose attitudes change and why. I distinguish between pocketbook effects, in which individuals become more favorable toward donors because they personally benefit from aid, and sociotropic effects, in which individuals respond positively because they perceive aid as benefiting their country as a whole.
    </p>
  </details>
</div>
