---
title: "Teaching"
date: 2023-04-25T18:46:47+08:00
draft: false
tags:
- Teaching
tags_weight: 4
---

------
#### [Integrated Intelligent Systems](https://ai.uni-bremen.de/teaching/le-iis-ws22)
\
This course consist of ten modules that together provide an overview of the methods required to build a cognition-enabled robot agent. The appended picture shows an overview of the modules. Each module consists of several video lectures and an exercise. Some modules contain additional learning materials.

<div style="text-align:center;">
  <a href="https://iris.informatik.uni-bremen.de/teacher/images/control_system.png" target="blank">
    <img width="100%" src="https://iris.informatik.uni-bremen.de/teacher/images/control_system.png" />
  </a>
</div>

<script>
  var BINDER_URL="https://binder.intel4coro.de/v2/gh/yxzhan/moodle_jupyter.git/main?urlpath=%2Flab%2Ftree%2F1%2F"
  var popupWindows = {}
  function openBinderHub(file) {
    if (!popupWindows[file] || popupWindows[file].closed) {
      popupWindows[file] = window.open(BINDER_URL + file, file, "popup=1,width=1280,height=720,resizable=no");
    } else {
      popupWindows[file].focus();
    }
  }
  function openSlide(url) {
    window.open(url, 'slide', "popup=1,width=1280,height=720,resizable=no");
  }
</script>

***Module 1: Introduction***

<a href="JavaScript:openSlide('https://seafile.zfn.uni-bremen.de/f/62b6c0cf547b410280c1/')">Slide 1</a> ---
<a href="JavaScript:openBinderHub('00-Intro_Setup.ipynb')">Assignment 1</a>

***Module 2: Robots and Their Envirsonments***

<a href="JavaScript:openSlide('https://seafile.zfn.uni-bremen.de/f/62b6c0cf547b410280c1/')">Slide 2</a> ---
<a href="JavaScript:openBinderHub('01-Lesson_01_Lisp_Introduction.ipynb')">Assignment2</a>
<!--more-->

Module 3: Sensors and Sensor Data

<a href="JavaScript:openBinderHub('02-Lesson_02_CRAM_Basics.ipynb')">Assignment3</a>


Module 4: Perception

<a href="JavaScript:openBinderHub('03-Lesson_03_Pick_n_Place.ipynb')">Assignment4</a>

Module 5: Probabilistic State Estimation

Module 6: Action Execution

Module 7: Planning and Execution

Module 8: Knowledge Representation and Reasoning (KRR)

Module 9: Learning-Enabled Robots

Module 10: Cognitive Architectures