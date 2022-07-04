---
theme: light-icons
title: OpenEojs
favicon: >-
  https://master-geoinformatics.com/wp-content/uploads/2020/12/cropped-cropped-icon-32x32-1-180x180.png
layout: intro
hideInToc: true
image: >-
  https://images.unsplash.com/photo-1460186136353-977e9d6085a1?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1920&q=1080
---
<div class="absolute pt-1 right-1">
      <img src="/assets/openeo-logo.svg" class="m-7 h-7" />
  </div>
  <div class="absolute pt-1 right-20">
      <img src="https://master-geoinformatics.com/wp-content/uploads/2020/01/20-05-12_logo_ifgi_redesing.png" class="m-7 h-7" />
  </div>

  <div class="absolute pt-6 left-12">
    <span @click="next" class="p-1 rounded flex justify-center items-center">
      Supervision: <br>
      Prof. Dr. Edzer Pebesma - M.Sc Matthias Mohr
    </span>
  </div>

  <div class="absolute pt-20 left-12">
    <span @click="next" class="p-1 rounded flex justify-center items-center">
      Presenter: Jorge Herrera
    </span>
  </div>

  <div class="mb-4 absolute bottom-4 left-12">
    <div class="text-5xl text-orange text-opacity-60" style="font-weight:600;" >
      OpenEO JavaScript's library
    </div> 
    <span class="text-2xl text-white text-opacity-80" style="font-weight:500;" >
      A proposal for OpenEO processes in the browser
    </span>
  </div>


---
layout: dynamic-image
hideInToc: true
image: 'https://images.unsplash.com/photo-1579158949974-bfa5b5f171e1?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=3580&q=80'
---

  <div class="text-primary dark:text-primary pb-2 pt-4">
    <span class="">
      <light-icon icon="click" />
      AGENDA
    </span>
  </div>

  <Toc listClass="!list-disc" maxDepth="2" />

---
layout: center
class: text-center
title: Introduction
---

# Introduction

What is comming?

---
layout: dynamic-image
title: Motivation
level: 2
image: "https://github.com/joaherrerama/openeojs-slides/blob/main/assets/agenda.png?raw=true"
---

# Motivation

* EO data is one of the most powerful sources for Environmental monitoring and climate change science 
* The management of this data requires high computational power and high-skilled professional.
* Current infrastructure of processes for web GIS split the performance between client side and  server-side
* User-defined processes are relevant when it comes to customized workflows. Users with ownership in its products and simplification of methods - Tech Reliability

---
title: Aim & Research Questions
level: 2
layout: center
---
<div class="text-4xl text-primary dark:text-primary pb-2 pt-4">
    <span class="">
      <light-icon icon="target" />
      AIM
    </span>
</div>

<div class="text-black dark:text-white" style="padding:30px;">
    <span class="">
      This research aims to present a prototype of a Javascript library to perform EO processes based on OpenEO processes logic.
    </span>
</div>

<div class="text-4xl text-primary dark:text-primary pb-2 pt-4">
    <span class="">
      <light-icon icon="message-circle" />
      Research Questions
    </span>
</div>

<div class="text-black dark:text-white" style="padding:30px;">
  <ul>
    <li>To what extent are EO processes currently supported by JavaScript?</li>
    <li> How efficient is the execution of EO processes in a browser environment vs server environment? </li>
    <li> What are the advantages and limitations of implementation of the library? </li>
  </ul>
</div>


---
layout: center
class: text-center
---

# Literature Review
What has been done? Why has been relevant?

---
title: GIS in the Browser
level: 2
layout: two-cols
---
<div class="text-2xl text-primary dark:text-primary pb-2 pt-4">
    <span class="">
      <light-icon icon="hexagon" />
      GIS in the Browser
    </span>
</div>

<div class="text-black dark:text-white" style="padding:30px;">
  
</div>
---
title: EO processes in the Browser
level: 2
---
<div class="text-2xl text-primary dark:text-primary pb-2 pt-4">
    <span class="">
      <light-icon icon="eye" />
      EO processes in the Browser
    </span>
</div>
---
layout: center
class: text-center
---

# Materias and Methods

---
title: Nodejs and Javascript
level: 2
layout: two-cols
---

# NodeJS

::right::

# Javascript 
---
title: OpenEo Processes
level: 2
---

# OpenEO Processes

---
layout: center
class: text-center
---

# Preliminary Results

---
hideInToc: true
level: 2
---
<div class="text-2xl text-primary dark:text-primary pb-2 pt-4">
    <span class="">
      <light-icon icon="eye" />
      Implementation
    </span>
</div>

---
hideInToc: true
level: 2
layout: iframe
url: https://openeo.cloud/
---

---
layout: center
class: text-center
---

# Challenges

---
layout: center
class: text-center
---

# Timeline
