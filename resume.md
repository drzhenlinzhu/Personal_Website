---
share-title: CV | Zhenlin Zhu
layout: page
title: CV
subtitle: Data science, machine learning and research experience
permalink: /resume/
---

{% assign cv = '/assets/pdf/Zhenlin_Zhu_Resume_DS.pdf' | relative_url %}

<div class="zz-cv-actions">
  <a class="btn zz-btn zz-btn-primary" href="{{ cv }}" download><i class="fas fa-download" aria-hidden="true"></i> Download PDF</a>
  <a class="btn zz-btn" href="{{ cv }}" target="_blank" rel="noopener"><i class="fas fa-external-link-alt" aria-hidden="true"></i> Open in new tab</a>
</div>

<object class="zz-pdf" data="{{ cv }}#view=FitH" type="application/pdf" aria-label="Zhenlin Zhu's CV (PDF)">
  <p>Your browser can't display the PDF here. <a href="{{ cv }}">Open the CV</a> instead.</p>
</object>

<p class="zz-pdf-fallback">
  PDFs don't preview well on phones. Tap <a href="{{ cv }}">Download PDF</a> above to view the full CV.
</p>
