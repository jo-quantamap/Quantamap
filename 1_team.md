---
layout: page
title: Who we are
description: Get to know the QuantaMAP team
image: 
nav-menu: true
---

# Meet the QuantaMap team

|![Johannes Jobst (CEO)](/assets/images/Johannes-Jobst.png){: width="150" }| ![Kaveh Lahabi](/assets/images/Kaveh-Lahabi.png){: width="150" }| ![Milan P Allan](/assets/images/Milan-Allan.png){: width="150" }| ![Jimi de Haan](/assets/images/Jimi-de-Haan.png){: width="150" }|
|:-:|:-:|:-:|:-:|
|**Johannes Jobst (CEO)**| **Kaveh Lahabi** | **Milan P Allan** | **Jimi de Haan**|

---
# YAML front matter
images:
  - path: /assets/images/Johannes-Jobst.png
    column: 1
    text: Some text 1
  - path: /assets/images/Johannes-Jobst.png
    column: 2
    text: Some text 2
  - path: /assets/images/Johannes-Jobst.png
    column: 3
    text: Some text 3
---
<ul>
  {% for image in page.images %}
    <li class="col-{{ image.column }}" style="background-image: url({{ image.path }})">
      <p>{{ image.text }}</p>
    </li>
  {% endfor %}
</ul>

We are a team of four founders and two interns, and we are motivated to solve hard problems that do not have solutions yet. We believe that our technology will have a major impact on the quantum industry, and will also have applications in different fields in science and emerging technology. We are committed to diversity and work to build an inclusive environment where everyone can thrive.

# Our mission and our technology

At Quantamap, we are developing cutting-edge tools for metrology and defect inspection for quantum chips and other quantum hardware.

We concluded that one of the major road-blocks of quantum computing is that when chips do not work as well as they should (they often don’t), there is no way to find out which component failed, and how to improve the production processes. 

We believe that our novel microscope, based on SQUID-on-tip, can solve the diagnostics challenge and help enable the quantum revolution.



