---
theme: light-icons
layout: intro
image: 'https://images.unsplash.com/photo-1460186136353-977e9d6085a1?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1920&q=1080'
---
  <div class="mb-4 absolute top-4 right-12">
      <img src="/assets/openeo-logo.svg" class="m-10 h-10" />
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
image: 'https://images.unsplash.com/photo-1579158949974-bfa5b5f171e1?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=3580&q=80'
equal: true
left: false
---
  <layout-tag layout-name="dynamic-image" />

  <div class="text-primary dark:text-primary pb-2 pt-4">
    <span class="">
      <light-icon icon="click" />
      Outline
    </span>
  </div>
<!-- 
---
layout: dynamic-image 
image: 'https://source.unsplash.com/collection/VBNb52J8Trk/1920x1080'
equal: false
left: false
---
  <layout-tag layout-name="dynamic-image" />

  <div class="text-black dark:text-white text-opacity-60 dark:text-opacity-60 pt-2 font-sm">
    <span class="text-sm">
      Image at Right
    </span>
  </div>
  <div class="text-primary dark:text-primary pb-2 pt-4">
    <span class="">
      Theme Configuration <light-icon icon="settings"/>
    </span>
  </div>

---
layout: dynamic-image 
image: 'https://source.unsplash.com/collection/94734566/1920x1080'
equal: false
left: true
---
  <layout-tag layout-name="dynamic-image" />

  <div class="text-black dark:text-white text-opacity-60 dark:text-opacity-60 pt-2 font-sm">
      <span class="text-sm">
        Image at Left
      </span>
  </div>
  <div class="text-primary dark:text-primary pb-2 pt-2">
    <span class="">
      Theme Configuration <light-icon icon="adjustments-horizontal"/>
    </span>
  </div>
---
layout: dynamic-image 
image: 'https://source.unsplash.com/collection/94734566/1920x1080'
equal: true
left: false
---
  <layout-tag layout-name="dynamic-image" />

  <div class="text-black dark:text-white text-opacity-60 dark:text-opacity-60 pt-2 font-sm">
      <span class="text-sm">
        Equal Width
      </span>
  </div>
  <div class="text-primary dark:text-primary pb-2 pt-2">
    <span class="">
      Theme Configuration <light-icon icon="adjustments"/>
    </span>
  </div>

```ts
layout: dynamic-image //Layout Name
image: 'https://source.unsplash.com/collection/94734566/1920x1080'
equal: true
left: false
```




---
layout: dynamic-image 
image: 'https://source.unsplash.com/collection/94734566/1920x1080'
upperImage: 'https://source.unsplash.com/collection/94734566/1920x1080'
equal: true
left: false
---
  <layout-tag layout-name="dynamic-image" />

  <div class="text-black dark:text-white text-opacity-60 dark:text-opacity-60 pt-2 font-sm">
      <span class="text-sm">
        Floating image
      </span>
  </div>
  <div class="text-primary dark:text-primary pb-2 pt-2">
    <span class="">
      Theme Configuration <light-icon icon="settings"/>
    </span>
  </div>

```ts
layout: dynamic-image //Layout Name
image: 'https://source.unsplash.com/collection/94734566/1920x1080'
upperImage: 'https://source.unsplash.com/collection/94734566/1920x1080'
equal: true
left: false
```




---
layout: center-image
image: '/static/light-icons-screenshot.png'
---
  <layout-tag layout-name="center-image" />

  <div class="mb-4">
    <span class="text-3xl text-primary dark:text-primary" style="font-weight:500;" >Designed for Innovative Projects <light-icon icon="wand" /></span>
  </div>




---
layout: dynamic-image
image: 'https://source.unsplash.com/collection/94734566/1920x1080'
equal: false
left: false
---
  <layout-tag layout-name="dynamic-image" />

  <div class="text-primary dark:text-primary ">
    <span class="text-xl" style="font-weight: 600;">
      Simplified Syntax
      <light-icon icon="code" />
    </span>
  </div>
  
  <div class="flex items-end justify-between pb-2 pt-5">
    <div class="">
      <i class="light-icon-brand-facebook" style="font-size:24px;" ></i>
    </div>
    <span class="text-xs opacity-60">
      Universal
    </span>
  </div>

  ```ts
  // Universal
  <i class="light-icon-brand-facebook"></i> 
  ```

  <div class="flex items-end justify-between pb-2 pt-5">
    <div class="">
      <light-icon icon="brand-facebook" size="24px" />
    </div>
    <span class="text-xs opacity-60">
      Inbuilt in theme
    </span>
  </div>

  ```ts
  // Inbuilt component in theme
  <light-icon icon="brand-facebook" size="24px" />
  ```


  <div class="flex items-end justify-between pb-2 pt-5">
    <div class="">
      <icon-box>
        <light-icon icon="brand-twitter" size="24px" />
      </icon-box>
    </div>
    <span class="text-xs opacity-60 ">
      Inbuilt in theme
    </span>
  </div>

  ```ts
  // Inbuilt wrapper-component in theme
  <icon-box>
    <light-icon icon="brand-twitter" size="24px" />
  </icon-box>
  ```
---
layout: image-left
image: '/static/light-icons-illustration.svg'
equal: true
---
  <layout-tag layout-name="image-left" />

  <div class="">
    <h1 class="text-primary dark:text-primary" >Handcrafted Icons...</h1>
  </div>
  <div class="leading-snug text-black dark:text-white text-opacity-60 dark:text-opacity-60">
    Your imagination has no boundaries and so does our handpicked collection of premium & light-weighted icons. 
    <br/><br/>
    Explore and choose icons from the vast landscape of Light-Icons. <light-icon icon="brand-telegram" />
  </div>

---
layout: center-image
---
  <layout-tag layout-name="center-image" />

  <div class="mb-0">
    <span class="text-3xl text-primary dark:text-primary" style="font-weight:600;text-transform: uppercase;" >Explore More</span>
  </div>
  <div class="mb-0">
    <a href="https://icons.lightvue.org/" target="_blank" class="">Documentation</a> |
    <a href="https://github.com/lightvue/light-icons" target="_blank" class="">Contribution</a>
  </div>

  <style>
    a {
      margin: 10px;
    }

    a:hover{
      opacity:0.7;
    }
  </style> -->
