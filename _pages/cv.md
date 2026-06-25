---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

* **Ph.D. in Computer Science**, EPFL, 2018 - 2023
* **B.Sc.**, Moscow State University, 2014 - 2018

## Research Experience

* **Postdoctoral Researcher**, Max Planck Institute Security & Privacy Group
  * Research on applied cryptography and security

* **Research Intern**, a16z Crypto Research, June 2022 - December 2022
  * Research on zero-knowledge proof systems

* **Research Intern**, Chainlink Labs, June 2021 - September 2021
  * Research on secure multi-party computation

## Research Interests

* Zero-Knowledge Proof Systems
* Secure Multi-Party Computation
* Post-Quantum Cryptography

## Publications

{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}

## Awards

* EPFL Doctoral Excellence Scholarship

## Skills

* Applied Cryptography
* Zero-Knowledge Proofs
* Secure Multi-Party Computation
* Post-Quantum Cryptography
* Formal Verification
