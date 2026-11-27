---
layout: single
title: "Contact"
permalink: /contact/
author_profile: true
read_time: false
show_date: false
---

<style>
.contact-intro {
  font-size: 1.05rem;
  line-height: 1.75;
  margin: 0 0 28px;
}
.contact-block {
  border-top: 1px solid rgba(128, 128, 128, 0.25);
  border-bottom: 1px solid rgba(128, 128, 128, 0.25);
  padding: 20px 0;
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 16px;
  flex-wrap: wrap;
  margin-bottom: 28px;
}
.contact-label {
  font-size: 0.75rem;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  opacity: 0.55;
  margin: 0 0 4px;
}
.contact-email {
  font-size: 1.2rem;
  font-weight: 500;
  color: #3b5b92 !important;
  text-decoration: none;
  border-bottom: 1px solid currentColor !important;
}
.contact-actions { display: flex; gap: 8px; }
.contact-actions a,
.contact-actions button {
  font: inherit;
  font-size: 0.85rem;
  padding: 7px 14px;
  border-radius: 8px;
  border: 1px solid rgba(128, 128, 128, 0.4) !important;
  background: transparent;
  color: inherit !important;
  cursor: pointer;
  text-decoration: none;
}
.contact-actions a:hover,
.contact-actions button:hover { background: rgba(128, 128, 128, 0.08); }
</style>

<div class="contact-block" markdown="0">
  <div>
    <p class="contact-label">Email</p>
    <a class="contact-email" href="mailto:jl192@illinois.edu">jl192@illinois.edu</a>
  </div>
  <div class="contact-actions">
    <a href="mailto:jl192@illinois.edu?subject=Hello%20from%20your%20website">Send an email</a>
    <button type="button" id="copy-email">Copy address</button>
  </div>
</div>

<p class="contact-intro">If you came across my research and something caught your eye, whether it is the politics of foreign aid, how governments talk about the aid they receive, or an idea for a collaboration, please feel free to reach out.</p>

<p class="contact-intro">My fieldwork in the Philippines, interviewing government officials and donor representatives, was possible in large part because political scientists who work on the Philippines generously met with me when I reached out out of the blue, and guided me through every step. I would love to pay that kindness forward, so if you are preparing fieldwork of your own or simply have questions about it, those conversations are very welcome too. I would be delighted to set up a short call and chat!</p>

<script>
(function () {
  var btn = document.getElementById('copy-email');
  if (!btn) { return; }
  btn.addEventListener('click', function () {
    var done = function () {
      btn.textContent = 'Copied';
      setTimeout(function () { btn.textContent = 'Copy address'; }, 1600);
    };
    if (navigator.clipboard && navigator.clipboard.writeText) {
      navigator.clipboard.writeText('jl192@illinois.edu').then(done, function () {});
    }
  });
})();
</script>
