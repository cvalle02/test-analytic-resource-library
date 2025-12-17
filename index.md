---
title: "HHEAR Analytic Resource Library"
layout: splash
permalink: /
excerpt: "A centralized, easy-to-navigate set of documentation for working with the HHEAR Data Repository."
<div style="display:flex; align-items:center; gap:2rem; padding:2.5rem 0; flex-wrap:wrap;">
  <img src="/assets/images/hhear-main-logo.png"
       alt="HHEAR logo"
       style="max-width:340px; width:100%; height:auto;">

  <div style="max-width:700px;">
    <h1 class="page__title">{{ page.title }}</h1>
    <div class="page__excerpt">
      {{ page.excerpt | markdownify }}
    </div>
  </div>
</div>


feature_row:
  - alt: "Getting started"
    title: "Getting Started"
    excerpt: "What the repository contains, how to access it, and core concepts."
    url: /getting-started/
    btn_label: "Open"
    btn_class: "btn--primary"
  - alt: "Annotations"
    title: "Data & Metadata Annotations"
    excerpt: "Important notes on study-specific data & metadata."
    url: /data-metadata/
    btn_label: "Open"
    btn_class: "btn--primary"
  - alt: "Training & Tutorials"
    title: "Tutorials"
    excerpt: "Short how-to-videos and step-by-step guides."
    url: /tutorials/
    btn_label: "Open"
    btn_class: "btn--primary"
feature_row2:
  - alt: "Code"
    title: "Data Cleaning and Analytic Code"
    excerpt: "Example programming code in R"
    url: /examples/
    btn_label: "Open"
    btn_class: "btn--primary"
  - alt: "Support"
    title: "Support"
    excerpt: "FAQ, troubleshooting, and how to request help."
    url: /support/
    btn_label: "Open"
    btn_class: "btn--primary"
---

{% include feature_row %}
{% include feature_row id="feature_row2" %}

## Quick links

- **Repository landing page:** [link here](https://hheardatacenter.mssm.edu)
- **Ontology:** [link here](https://bioportal.bioontology.org/ontologies/HHEAR)
- **HHEAR Publication Policy:** [link here](https://hheardatacenter.mssm.edu/Resource/Get)


## About this site

This site provides **documentation and training resources** for using the HHEAR Data Repository. It does **not** host any data.
