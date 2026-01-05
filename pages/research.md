---
layout: default
title: Research Theme
permalink: /research/
---
<style>
.research-theme {
  display: flex;
  gap: 2rem; /* space between text and image */
  margin-bottom: 4rem; /* space between themes */
}

.theme-text {
  flex: 1; /* text column smaller */
}

.theme-image {
  flex: 1; /* image column larger */
}

.theme-image img {
  width: 100%;
  height: auto;
  object-fit: cover;
  border-radius: 0.5rem; /* optional for a soft look */
}

/* Responsive: stack columns on small screens */
@media (max-width: 768px) {
  .research-theme {
    flex-direction: column;
  }
  .theme-text,
  .theme-image {
    flex: none;
    width: 100%;
  }
}

.related-papers {
  font-size: 0.9rem;
  margin-top: 1rem;
}

.related-papers ul {
  padding-left: 1.2rem;
  margin: 0.3rem 0 0 0;
}

.related-papers li {
  margin-bottom: 0.3rem;
}

.spacer1 {
  height: 0.2rem;
}

.spacer2 {
  height: 3rem;
}

.theme-divider {
  border-top: 1px solid rgba(255, 255, 255, 0.7);
  margin: 3rem 0;
}

</style>

<div class="research-list">

<div class="research-theme">
  
  <div class="theme-text">
    <h3>Fluid-Structure Interactions</h3>
    <div class="spacer1"></div>
    <p>
      Particles moving in a fluid, driven either externally or internally, generate flows that mediate inter-particle interactions. In the limit of negligible inertia, this system presents a classical N-body problem with long-ranged hydrodynamic interactions. The interplay between the geometry of individual particles, the suspension microstructure, and the surrounding flow produces rich dynamical patterns. We study this collective behavior at both the level of individual particles and long wavelengths, using tools from fluid dynamics and non-equilibrium statistical mechanics.
    </p>
    <p class="related-papers">
      <strong>Related Publications:</strong><br>
    <!--  <ul>
        <li><a href="/papers/paper1">Paper Title 1</a></li>
        <li><a href="/papers/paper2">Paper Title 2</a></li>
      </ul> -->
     • R. Chajwa, N. Menon, S. Ramaswamy. Phys. Rev. Lett. <b>122</b>, 224501 (2019).
     <a href="https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.122.224501">doi:10.1103/PhysRevLett.122.224501</a><br>
     • R. Chajwa, N. Menon, S. Ramaswamy, R. Govindarajan. Phys. Rev. X <b>10</b>, 041016 (2020).
     <a href="https://journals.aps.org/prx/abstract/10.1103/PhysRevX.10.041016">doi:10.1103/PhysRevX.10.041016</a><br>
     • H. Joshi, R. Chajwa, S. Ramaswamy, N. Menon, R. Govindarajan (2025). Journal of Fluid Mechanics <b>1017</b>:A1 (2025).
     <a href="https://doi.org/10.1017/jfm.2025.10467">doi:10.1017/jfm.2025.10467</a><br>
    </p>
  </div>
   
   <div class="theme-image">
    <div class="spacer2"></div>
    <img src="/assets/images/research/sedimentation.png" alt="Marine Snow">
  </div>

<div class="theme-divider"></div>
</div>

<div class="research-theme">

   <div class="theme-text">
   <h3>Biological & Active Matter </h3>
    <p>
    <div class="spacer1"></div>
      Living systems both challenge and inspire physical and mechanistic understanding — from flocks of birds to the dynamics of slime molds. They dramatically expand the behavior space of inanimate matter, exhibiting far-from-equilibrium structures as well as features such as adaptation, learning, and computation. Capturing the essential building blocks of these dynamics holds promise for a fundamental understanding of living systems and for guiding the engineering of materials that can move, self-organize, adapt, learn, and compute. Through the lens of physics, we study biological and self-driven matter with the goal of identifying these essential ingredients and understanding how they give rise to the emergent properties found in nature.
    </p>

   <p class="related-papers">
     <strong>Related Publications:</strong><br>
     • L.P. Dadhichi, J. Kethapelli, R. Chajwa, A. Maitra, S. Ramaswamy. Phys. Rev. E <b>101</b>, 052601 (2020). <a href="https://journals.aps.org/pre/abstract/10.1103/PhysRevE.101.052601">doi:10.1103/PhysRevE.101.052601</a><br>
     • A.G. Larson*, R. Chajwa*, H. Li, M. Prakash. Current Biology Volume <b>34</b>, Issue 22, 5149 - 5163.e3 (2024). <a href="https://doi.org/10.1016/j.cub.2024.09.046">doi:10.1016/j.cub.2024.09.046</a><br>
     • R. Chajwa, Rajarshi, R. Govindarajan, S. Ramaswamy (2024). <a href="https://arxiv.org/abs/2310.01829">arXiv:2310.01829</a> [cond-mat.soft]
    </p>
  </div>

  <div class="theme-image">
    <div class="spacer2"></div>
    <img src="/assets/images/research/caustics.jpg" alt="Marine Snow">
   </div>

</div>


<div class="research-theme">
<div class="theme-text">
    <h3>Ocean Carbon Cycle</h3>
    <p>
    <div class="spacer1"></div>
      The oceans constitute the largest active reservoir of carbon on Earth, sequestering carbon from the surface to the deep ocean and sediments through a continual flux of biotic aggregates known as marine snow. This transport process, termed the biological carbon pump, spans microscopic mechanisms such as motility, self-assembly, and fluid–structure interactions, as well as gravity- and flow-driven transport across kilometer scales. We study this inherently multiscale problem — from single plankton to large-scale carbon flux — with the goal of building a bottom-up, predictive framework for ocean-based carbon sequestration. By investigating these mechanisms directly in ocean environments aboard research vessels see ([Expedition](/expedition/)), we ensure a strongly observation-driven approach.
    </p>

    <p class="related-papers">
      <strong>Related Publications:</strong><br>
     • R. Chajwa, E. Flaum, K.D. Bidle, B. Van Mooy, M. Prakash. Science <b>386</b>, eadl5767 (2024).
     <a href="https://doi.org/10.1126/science.adl5767">doi:10.1126/science.adl5767</a><br>
     • A.G. Larson*, R. Chajwa*, H. Li, M. Prakash. Current Biology Volume <b>34</b>, Issue 22, 5149 - 5163.e3 (2024). <a href="https://doi.org/10.1016/j.cub.2024.09.046">doi:10.1016/j.cub.2024.09.046</a>
    </p>
  </div>
   
   <div class="theme-image">
    <img src="/assets/images/research/Biological_Pump.png" alt="Marine Snow">
  </div>

</div>

<div class="research-theme">

   <div class="theme-text">
   <h3>Physics-Inspired Interpretability </h3>
    <p>
    <div class="spacer1"></div>
      A mechanistic understanding of how neural networks develop coarse concepts and internal representations is essential for ensuring AI safety and steerability, and remains an open problem. Neural networks serve as abstract model organisms for studying the physics of learning and computation, providing a platform to probe how distributed interactions give rise to representation, memory, and adaptive behavior. This challenge closely parallels questions in biological physics, and by drawing on tools from soft matter physics, we aim to uncover the underlying organizing principles.
    </p>
  </div>

</div>

</div>
