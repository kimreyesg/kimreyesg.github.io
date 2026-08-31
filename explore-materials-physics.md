---
layout: default
title: Explore Materials Physics
permalink: /explore-materials-physics.html
---

<span class="eyebrow">Learning resource</span>
# Explore Materials Physics

<p class="lead">
A small collection of explanations and examples that connect computational methods with the broader story of materials science.
</p>

## Data-driven methods

<div class="explore-grid">
  <div class="card collapsed">
    <h3>Density Functional Theory</h3>
    <p>First-principles methods allow us to simulate electronic behavior by solving for the electronic structure self-consistently.</p>
    <div class="more-text" style="display:none;">
      <p>The iterative process solves the Kohn-Sham equations and updates the charge density until self-consistency is achieved.</p>
<pre>
Initial charge density ρ(r)
        ↓
Effective potential Veff(r)
        ↓
Solve Kohn-Sham equations
        ↓
New charge density ρ(r)
        ↓
Total energy and convergence
</pre>
    </div>
    <a href="#" class="read-more">Read more...</a>
  </div>

  <div class="card collapsed">
    <h3>Machine Learning in Materials Discovery</h3>
    <p>Machine-learning models can help search large chemical spaces and identify promising materials more efficiently.</p>
    <div class="more-text" style="display:none;">
      <p>This figure illustrates a typical machine-learning pipeline in materials science.</p>
      <img src="https://github.com/user-attachments/assets/7935c27f-8f9d-4550-ab91-7d908dcdce87"
           alt="Machine-learning workflow for materials science">
    </div>
    <a href="#" class="read-more">Read more...</a>
  </div>
</div>

## Discoveries in unexpected places

<div class="explore-grid">
  <div class="card collapsed">
    <h3>Saccharin</h3>
    <p>A laboratory accident and an unwashed hand helped reveal the first artificial sweetener.</p>
    <div class="more-text" style="display:none;">
      <p>Saccharin was discovered in 1879 when Constantin Fahlberg noticed a sweet taste on his fingers after working with coal-tar derivatives. The accidental observation eventually led to a widely used sugar substitute.</p>
    </div>
    <a href="#" class="read-more">Read more...</a>
  </div>

  <div class="card collapsed">
    <h3>Stainless steel</h3>
    <p>A discarded alloy sample that resisted rust revealed a new class of corrosion-resistant steel.</p>
    <div class="more-text" style="display:none;">
      <p>Harry Brearley was experimenting with steel alloys when he noticed that one chromium-rich sample had not rusted. That observation helped lead to stainless steel.</p>
    </div>
    <a href="#" class="read-more">Read more...</a>
  </div>

  <div class="card collapsed">
    <h3>Teflon</h3>
    <p>A gas cylinder unexpectedly produced a slippery white solid instead of the expected refrigerant gas.</p>
    <div class="more-text" style="display:none;">
      <p>In 1938, Roy Plunkett found that tetrafluoroethylene had polymerized inside a cylinder, producing the material later known as Teflon.</p>
    </div>
    <a href="#" class="read-more">Read more...</a>
  </div>

  <div class="card collapsed">
    <h3>Vulcanized rubber</h3>
    <p>Heat transformed a rubber-sulfur mixture into a more durable and elastic material.</p>
    <div class="more-text" style="display:none;">
      <p>Charles Goodyear's experiments with rubber and sulfur helped establish vulcanization, which dramatically improved rubber's durability and temperature stability.</p>
    </div>
    <a href="#" class="read-more">Read more...</a>
  </div>
</div>

## Physics research feed

<a class="twitter-timeline"
   data-height="520"
   data-theme="light"
   href="https://twitter.com/PhysRevX">
  Tweets by Phys. Rev. X
</a>
<script defer src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<script>
  document.addEventListener('DOMContentLoaded', function() {
    document.querySelectorAll('.read-more').forEach(function(link) {
      link.addEventListener('click', function(e) {
        e.preventDefault();
        const card = link.closest('.card');
        const moreText = card.querySelector('.more-text');
        if (moreText.style.display === 'none') {
          moreText.style.display = 'block';
          link.textContent = 'Read less...';
        } else {
          moreText.style.display = 'none';
          link.textContent = 'Read more...';
        }
      });
    });
  });
</script>
