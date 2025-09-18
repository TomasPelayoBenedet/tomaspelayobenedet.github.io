---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Computer Science, University of Zaragoza, 2024-Present
  * Research focus: AI applications in cybersecurity
* M.S. in Research in Cybersecurity, University of León, 2022-2023
  * Thesis: Detection of Algorithmically Generated Domains (AGDs)
* B.S. in Computer Science, University of Zaragoza, 2018-2022
  * Graduated with honors in Artificial Intelligence

Work experience
======
* May 2024-Present: Ph.D. Researcher
  * University of Zaragoza, Zaragoza, Spain
  * Novel research on detection of algorithmically generated domains using LLMs
  * Designed and benchmarked deep learning architectures for AGD detection

* April 2025-July 2025: Visiting Researcher
  * Ruhr University Bochum, Bochum, Germany
  * Exploring novel applications of LLMs for binary decompilation via intermediate representations

* May 2023-May 2024: Cybersecurity Engineer
  * Teltronic, Zaragoza, Spain
  * Led cybersecurity strategy and compliance for LTE (4G) product line
  * Implemented risk mitigation policies aligned with industry standards

* October 2022-April 2023: Cybersecurity Intern
  * Teltronic, Zaragoza, Spain
  * Conducted vulnerability assessments and risk analysis for telecommunications systems
  
Skills
======
* Programming
  * Python, C/C++, Java, Rust, Go
  * JavaScript, SQL, R, Bash, Assembly
* Machine Learning
  * Deep Learning, NLP, Large Language Models (LLMs)
  * TensorFlow, PyTorch
* Cybersecurity
  * Vulnerability Assessment, Risk Analysis
  * Incident Response, Malware Detection
* Tools & Technologies
  * Git, Docker, Linux, LaTeX
  * Wireshark, Nmap, Burp Suite, SIEM platforms, Binary Ninja
* Languages
  * Spanish (Native)
  * English (B2+)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% if post.category == "publications" or post.category == "conferences" %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}</ul>

Posters
======
  <ul>{% for post in site.publications reversed %}
    {% if post.category == "posters" %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Awards, Grants & Honors
======
* "Ayudas para la cofinanciación de Contratos Puente de Investigación del I3A" (2025)

Certifications & Additional Studies
======
* University Expert in Cyber Incident Management and Response – University of Zaragoza (2025)
* Containment and Forensics Expert after a Cyber Incident – INCIBE & EICYC (2023)
* B2 Cambridge English: First (FCE) – Cambridge University (2023)
* Elementary and Professional Music Studies – Conservatorio Profesional de Música de Zaragoza (CPMZ) (2011-2022)
  
Leadership and Activities
======
* Principal Bassoon at City Council Band of Zaragoza (2024-Present)
* First Team Rower at Os'Nabaters Rowing Club — Men's Eight (8+) (2024-Present)