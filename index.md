---
layout: default
title: Lynn Nguyen
permalink: /
---

<div class="vh-100 d-flex flex-column align-items-center justify-content-center text-center px-4" style="background-color: #ffffff; color: #1d1d1f;">

  <img src="{{ '/assets/img/logo.png' | relative_url }}" alt="Hello Lynn Logo" class="img-fluid d-md-none" style="max-height: 300px;">
  <div class="max-width-800 mb-5">
      
    <h1> Hey I'm Lynn :) </h1><br>
    I design software for the public and make systems easy to use.<br>
    It's a little quiet here but I'll be back with a refresh!<br><br>
    Reach me at <a href="mailto:mail@hellolynn.com">mail@hellolynn.com.</a><br><br>
    UX • UI
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
    animation: cleanEntrance 4s cubic-bezier(0.15, 1, 0.3, 1) forwards;
    animation-delay: var(--delay);
  }

.link-hover {
  transition: opacity 0.3s ease;
}

.link-hover:hover {
  opacity: 0.5;
}  
</style>