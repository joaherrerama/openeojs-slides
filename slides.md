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
image: "./assets/agenda.png?raw=true"
---

# Motivation

* EO data popularity is increasing due to its relevance in the Environmental sector 
* Client side for EO processes has few options (Geotiffjs, Geoblaze).
* Current infrastructure for web GIS splits the performance between client side and  server-side (must).
* Realistically, what are the limitation when it comes to Eo data processing in a bowser environment

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

### Platforms 
* EO data processing in Web GIS platform or infrastructure relies on the serves side. 
* There were not much bibliography regarding processes of EO data in browser using web tech.
* In SME (Small Medium Enterprise ) web browser tech was applied enhancing the portability of the platform


:: right ::

<div class="text-2xl text-primary dark:text-primary pb-2 pt-4">
    <span class="">
      ------------------------------
      <light-icon icon="hexagon" />
    </span>
</div>

### Libraries:

* Turf.js (Client-side)
* WPS (Web Processing Service)
* python-bridge (Python in Browser)

---
title: EO processes in the Browser
level: 2
layout: two-cols
---
<div class="text-2xl text-primary dark:text-primary pb-2 pt-4">
    <span class="">
      <light-icon icon="eye" />
      EO processes in the Browser
    </span>
</div>

* Google Earth Engine (GEE), Sentinel Hub, Open Data Cube (ODC), System for Earth Observation Data Access, Processing and Analysis for Land Monitoring (SEPAL, openEO, JEODPP, and pipsCloud.

* None of the platform uses browser processing as an approach. Most processes are done in server side.

* Geoblaze is a library that allows developers to perform EO data processes in vanilla Javascript. This library is based on geotiffjs.

* Geotiffjs allow users to handle Geotiff images up to certain capacity and extend.

:: right ::

  <a class="text-2xl text-bold absolute pt-1 right-75" href="#page-top">geotiff<span class="text-primary">.</span>js</a>

  <div class="absolute pt-4 right-14">
      <img src="/assets/openeo-logo.svg" class="m-10 h-10" />
  </div>

  <div class="absolute pt-25 right-37">
      <img src="https://earthobservations.org/images/articles/201911_earth_engines.png" class="m-6 h-6" />
  </div>

  <div class="absolute pt-10 right-5">
      <img src="http://geoblaze.io/assets/img/logo.svg" class="m-30 h-30" />
  </div>

  <div class="absolute pt-55 right-55">
      <img src="https://static.wixstatic.com/media/8959d6_98a1d74703d946ecab030b32f53db883~mv2.png/v1/fill/w_536,h_136,al_c,lg_1,q_85,enc_auto/f9d4ea_7a2d1d0c69ad4da0a2f48b69bc481612_.png" class="m-10 h-10" />
  </div>

  <div class="absolute pt-60 right-5">
      <img src="https://www.sentinel-hub.com/img/logo.svg" class="m-15 h-15" />
  </div>

  <div class="absolute pt-90 right-55">
      <img src="https://docs.sepal.io/en/latest/_static/sepal.png" class="m-10 h-10" />
  </div>
  
---
layout: center
class: text-center
---

# Design - Workflow

---
layout: center
class: text-center
---

# Preliminary Results

---
hideInToc: true
level: 2
layout: two-cols
---
<div class="text-2xl text-primary dark:text-primary pb-2 pt-4">
    <span class="">
      <light-icon icon="eye" />
      Implementation
    </span>
</div>

### Classes

* Band

```ts
export class OERasterBand {
  constructor(BufferArray, label) {
    this.BufferArray = BufferArray;
    this.label = label;
  }

  valitadorOEBand() {
    return true;
  }
}
```
:: right ::

* Raster

```ts
export default class OERaster {
  constructor(geotiff = null, source = null, extraProperties = {}) {
    this.geotiff = geotiff;
    this.source = source;
    this.extraProperties = extraProperties;
  }

  valitadorOERaster() {
    return true;
  }
}
```

* Rastercube

```ts
export class OERastercube {
  constructor(rasters, tdimension = new Date()) {
    this.rasters = rasters;
    this.tdimension = tdimension;
  }
}
```
---
hideInToc: true
level: 2 
---

### Functions 
* __Load__ - read an image in local or remote location and parse it to OEDatacube
* __ndvi__ - Calculates the NDVI given __red__ and __nir__ bands
* __Statistics__:
  * _Max_ - Find the maximun value in an TypedArray
  * _Min_ - Find the minimun value in an TypedArray
  * _Median_ - Find the median value in an TypedArray
  * _Mode_ - Find the mode value in an TypedArray
  * _Mean_ - Find the mean value in an TypedArray

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
hideInToc: true
level: 2 
---

<div class="text-2xl text-primary dark:text-primary pb-2 pt-4">
    <span class="">
      <light-icon icon="bug" />
      Challenges
    </span>
</div>

* Large images and formats
* Data structure and typedarrays
* Geotiff.js - library allows users to read file and write new objects but the input object can not be modified.
* Multidimensional array requiered high complexity of abstraction

---
layout: center
class: text-center
---

# What comes next?

---
hideInToc: true
level: 2 
---

<div class="text-2xl text-primary dark:text-primary pb-2 pt-4">
    <span class="">
      <light-icon icon="bug" />
      Challenges
    </span>
</div>

* apply and reduce methods on Rastercubes
* Process Graph implementation
* Change to an Array approach on how to handle EO data - avoid Geotiff object (from geotiff.js)
* Create user cases to run perfomance testing 
* Optimize processes to achieve the best performance as possible