---
layout: default
title: Undergraduate Research — Spring 2026
permalink: /undergraduate-research/spring-2026/
---

[← Back to Research](/research.html)

# Undergraduate Research in Physics — Spring 2026

This page highlights undergraduate research completed during Spring 2026 at SUNY New Paltz and presented at the APS Global Physics Summit in Denver, Colorado.

<div class="project-entry">
  <div class="project-copy">
    <h2>Band Gap Prediction in h-BN Using mBJ Data and Physically Informed Descriptors</h2>
    <h3>Michael Buccino and Kendra Scheele</h3>
    <p class="project-affiliation">Department of Physics and Astronomy, SUNY New Paltz</p>

    <p>
      This project combines density functional theory and machine learning to predict the band gap of monolayer hexagonal boron nitride (h-BN). Standard PAW-DFT reproduces the optimized lattice constant well but underestimates the band gap. A random-forest model trained on mBJ reference data and physically informed composition descriptors improves the prediction while avoiding the computational cost of higher-level band-gap corrections.
    </p>

    <p>
      Using 246 monolayer materials, the model achieved a mean absolute error of 0.336 eV and an R<sup>2</sup> score of 0.938. For held-out monolayer h-BN, the predicted mBJ band gap was 6.049 eV, close to the 5.917 eV reference value.
    </p>

    <div class="project-links">
      <a href="/assets/posters/LLM_DFT_Poster.pdf"
         style="display:inline-block; padding:10px 14px; border-radius:10px; text-decoration:none;
                background:#003E7E; color:white; font-weight:700;">
        Poster (PDF)
      </a>
    </div>
  </div>

  <a href="/assets/posters/LLM_DFT_Poster.pdf"
     aria-label="Open the Spring 2026 h-BN band-gap prediction poster PDF"
     style="display:block; text-decoration:none; border-radius:16px; overflow:hidden; border:1px solid rgba(255,255,255,0.16); box-shadow:0 12px 28px rgba(0,0,0,0.24);">
    <div style="background:#06477f; color:white; padding:28px 24px 22px; text-align:center; border-bottom:4px solid #f58220;">
      <div style="font-size:1.65rem; line-height:1.15; font-weight:800;">Band Gap Prediction in h-BN</div>
      <div style="font-size:1.08rem; line-height:1.3; font-weight:700; margin-top:6px;">Using mBJ Data and Physically Informed Descriptors</div>
      <div style="font-size:0.95rem; margin-top:12px; opacity:0.92;">Michael Buccino · Kendra Scheele · Greis J. Kim-Reyes</div>
    </div>
    <div style="background:#f6f7f8; color:#20252b; padding:20px; display:grid; grid-template-columns:repeat(auto-fit,minmax(150px,1fr)); gap:12px;">
      <div style="background:white; border-radius:10px; padding:14px; border-top:5px solid #06477f;">
        <strong>DFT foundation</strong><br>
        <span style="font-size:0.92rem;">Optimized h-BN lattice constant and calculated PAW-DFT band structure.</span>
      </div>
      <div style="background:white; border-radius:10px; padding:14px; border-top:5px solid #f58220;">
        <strong>ML correction</strong><br>
        <span style="font-size:0.92rem;">Random-forest prediction trained on mBJ data and physical descriptors.</span>
      </div>
      <div style="background:white; border-radius:10px; padding:14px; border-top:5px solid #555;">
        <strong>Key result</strong><br>
        <span style="font-size:0.92rem;">6.049 eV predicted versus 5.917 eV mBJ reference.</span>
      </div>
    </div>
    <div style="background:#06477f; color:white; padding:11px 18px; font-size:0.92rem; text-align:center;">
      APS Global Physics Summit · Denver, Colorado · March 2026
    </div>
  </a>
</div>

## Project highlights

- Standard PAW-DFT band gap for monolayer h-BN: approximately 4.6 eV.
- Optimized lattice constant: approximately 4.7 Bohr (2.49 Å), close to the accepted value.
- Machine-learning dataset: 246 monolayer materials with mBJ band-gap references.
- Model performance: MAE = 0.336 eV and R<sup>2</sup> = 0.938.
- Held-out h-BN prediction: 6.049 eV compared with the 5.917 eV mBJ reference.
- Presented at the APS Global Physics Summit, Denver, Colorado, March 2026.

## Acknowledgments

This work was supported by the Academic Year Undergraduate Research Experience (AYURE) program at SUNY New Paltz and by the Research, Scholarship, and Creative Activities Office through the Student Opportunity Grant.

[← Back to Research](/research.html)
