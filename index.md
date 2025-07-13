---
layout: default
title: Computational Materials Science
---

<nav>
  <a href="/">Home</a> |
  <a href="/teaching.html">Teaching</a> |
  <a href="/research.html">Research</a> |
  <a href="/about.html">About</a> |
  <a href="/contact.html">Contact</a> |
</nav>

# Computational Materials Science


<div class="grid">


<div class="card collapsed">
  <h2 style="font-size: 28px;">The Journey of Materials</h2>
  <p>
    The study and design of materials form the backbone of modern technology.
     An incredible journey of research, meticulous attention to detail, and hard work has transformed technology into what we have today. However, many of these discoveries originate from intriguing and unexpected sources.
    </p>
</div>


<h2 style="font-size: 28px;">💡 Discoveries in Unexpected Places</h2>


<div class="card collapsed">
  <h2>🍬🍭 Saccharin: Bad Lab Practices</h2>
  <p>
    Saccharin, the first artificial sweetener, was discovered in 1879 when Constantin Fahlberg noticed a sweet taste on his fingers 
  </p>
  <div class="more-text" style="display: none;">
    <p>
      after working with coal tar derivatives. An improper lab practice—forgetting to wash his hands—led to a revolutionary sugar substitute. It quickly became a popular low-calorie sweetener worldwide, despite some early controversies over safety.
    </p>
  </div>
  <a href="#" class="read-more">Read more...</a>
</div>

<div class="card collapsed">
  <h2>🖇️👩🏻‍🏭 Stainless Steel: Rusty Experiments</h2>
  <p>
    Harry Brearley was experimenting with steel alloys for erosion-resistant gun barrels.
  </p>
  <div class="more-text" style="display: none;">
    <p>
      By chance, he created steel with about 12% chromium—and noticed a discarded sample hadn’t rusted. His accidental observation gave birth to stainless steel, transforming modern society by revolutionizing kitchenware, construction, and medical devices.
    </p>
  </div>
  <a href="#" class="read-more">Read more...</a>
</div>

<div class="card collapsed">
  <h2>🧪🍳 Teflon: Frozen Gases Surprise</h2>
  <p>
    In 1938, Roy Plunkett at DuPont was researching refrigerants when he opened a gas cylinder and found a slippery white powder inside instead of gas.
  </p>
  <div class="more-text" style="display: none;">
    <p>
      That powder turned out to be Teflon—a material now famous for nonstick cookware and countless industrial uses, thanks to its chemical resistance and low friction properties.
    </p>
  </div>
  <a href="#" class="read-more">Read more...</a>
</div>

<div class="card collapsed">
  <h2>🔋🛞 Vulcanized Rubber: Spilled Sulfur</h2>
  <p>
    Charles Goodyear accidentally dropped a rubber-sulfur mixture onto a hot stove in 1839.
  </p>
  <div class="more-text" style="display: none;">
    <p>
      Instead of melting, the rubber became durable and elastic—creating vulcanized rubber, essential for tires, seals, and countless products we rely on today. This discovery revolutionized transportation and manufacturing industries.
    </p>
  </div>
  <a href="#" class="read-more">Read more...</a>
</div>

<h2 style="font-size: 28px;"> 💻 Data-Driven Methods</h2>


<div class="card collapsed">
  <h2>🔄 Density Functional Theory</h2>
  <p>
    First-principle methods enable us to simulate electronic behavior, optical response by looping the Hamiltonian of the many-body system through the charge density.
  </p>

  <div class="more-text" style="display: none;">
    <p>
      The iterative process solves the Kohn-Sham equations and updates the charge density until self-consistency is achieved.
    </p>
    <pre><code>
Initial Charge Density ρ(r)
     |
     v
Compute Effective Potential Veff(r)
     |
     v
Solve Kohn-Sham Equations
     |
     v
Update ρ(r), Etot
     |
     v
Converged?
  /       \
 No        Yes
 |           |
 v           v
Loop      Output Data
    </code></pre>
  </div>

  <a href="#" class="read-more">Read more...</a>
</div>



<div class="card collapsed">
  <h2>🧠 Machine Learning in Materials Discovery</h2>
  <p>
    Even more recently, Machine Learning techniques have transformed the landscape of materials search by predicting many prototype materials capable of optimizing and launching a new way to find new materials.
  </p>
  <div class="more-text" style="display: none;">
    <p>
      Machine learning models help explore huge chemical spaces, identify promising materials faster, and reduce the cost of experiments. This figure illustrates a typical ML pipeline in materials science.
    </p>
    <img 
      src="https://github.com/user-attachments/assets/e8a101c3-7a58-4f2c-82f2-b00df0cc5375"
      alt="Machine Learning Diagram"
      style="max-width: 100%; border-radius: 8px;">
  </div>
  <a href="#" class="read-more">Read more...</a>
</div>



<a class="twitter-timeline"
   data-height="600"
   data-theme="dark"
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


