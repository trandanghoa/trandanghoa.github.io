---
permalink: /cv/
title: "Curriculum Vitae"
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

* **Ph.D. in Computer Science**, University of Lorraine, France, 2017
* **M.S. in Computer Science**, Kumoh National Institute of Technology, Republic of Korea, 2012
* **B.S. in Electronic and Electrical Engineering**, Hanoi University of Science and Technology, Viet Nam, 2010

## Professional Experience

* **2017–Present: Research Professor**
  * Department of IT Convergence Engineering
  * Kumoh National Institute of Technology (KIT), Gumi, Republic of Korea

## Research Interests

* Internet of Things (IoT)
* Edge and Fog Computing
* Distributed Artificial Intelligence and Federated Learning
* 5G and 6G Communication Networks
* Digital Twin-enabled Intelligent Computing
* Quantum Machine Learning and Optimization
* Intelligent Resource Allocation and Task Offloading

## Professional Membership

* IEEE Senior Member

## Books

* *Industrial Sensors and Controls in Communication Networks*, Springer, 2019.
* *Cooperative and Distributed Intelligent Computation in Fog Computing: Concepts, Architectures, and Frameworks*, Springer, 2023.

## Research Projects

* **Digital Twins-empowered Distributed AI Framework for Edge Computing**, 2023–2026.
* **Distributed Intelligent Fog Computing Architecture for IoT-Enabled Physical Internet Hubs**, 2020–2023.

## Publications

<ul>
{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

## Talks and Presentations

<ul>
{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}
</ul>

## Teaching

<ul>
{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>
