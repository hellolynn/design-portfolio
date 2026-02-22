---
layout: default
title:
permalink: /
---

<div class="vh-100 d-flex flex-column align-items-center justify-content-center text-center px-4" style="background-color: #ffffff; color: #1d1d1f;">

  <img src="{{ '/assets/img/logo.png' | relative_url }}" alt="Hello Lynn Logo" class="img-fluid d-md-none" style="max-height: 300px;">
  <div class="max-width-800">
    <h1 class="display-3 fw-bold animate-clean mb-3" style="--delay: 0.2s; letter-spacing: -0.02em;">
      Hello, I'm <span class="tilted-highlight">Lynn</span>
    </h1>
    <p class="fs-2 animate-clean mb-3" style="--delay: 0.8s; font-weight: 400; color: #1d1d1f;">
      Design Lead based on Vancouver Island, Canada.
    </p>
    <div class="animate-clean" style="--delay: 1.4s;">
      <p class="fs-5 text-secondary mx-auto mb-5" style="max-width: 700px; line-height: 1.8;">
        Driven by passion for improving public service through thoughtful and intentional design.
      </p>
      <a href="/about" class="text-dark fw-medium text-decoration-none border-bottom border-dark pb-1 link-hover">About me →</a>
    </div>
  </div>

</div>

<style>
  /* Clean & Calm: No blur, 1.2s duration, soft easing */
  @keyframes cleanEntrance {
    0% { 
      opacity: 0; 
      transform: translateY(15px); 
    }
    100% { 
      opacity: 1; 
      transform: translateY(0); 
    }
  }

  .animate-clean {
    opacity: 0;
    animation: cleanEntrance 1.2s cubic-bezier(0.15, 1, 0.3, 1) forwards;
    animation-delay: var(--delay);
  }

.link-hover {
  transition: opacity 0.3s ease;
}

.link-hover:hover {
  opacity: 0.5;
}  
</style>