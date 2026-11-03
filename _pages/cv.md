---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<div class="pdf-container">
  <div class="pdf-actions">
    <a href="{{ base_path }}/files/webcv.pdf" class="btn btn--primary" target="_blank" rel="noopener">
      Open CV in a new tab
    </a>
    <a href="{{ base_path }}/files/webcv.pdf" class="btn btn--inverse" download>
      Download CV (PDF)
    </a>
  </div>

  <object
    class="pdf-viewer"
    data="{{ base_path }}/files/webcv.pdf#toolbar=1&navpanes=0"
    type="application/pdf"
    aria-label="CV PDF viewer">
    <div class="pdf-fallback">
      <p>Your browser doesn't support embedded PDFs. Open or download the CV instead.</p>
      <a href="{{ base_path }}/files/webcv.pdf" class="btn btn--primary" target="_blank" rel="noopener">
        Open CV
      </a>
    </div>
  </object>
</div>
