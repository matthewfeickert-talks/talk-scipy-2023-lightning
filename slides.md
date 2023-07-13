---
theme: seriph
background: false  # Need false to avoid default gradient
layout: cover
aspectRatio: '16/9'
class: text-center
highlighter: shiki
lineNumbers: false
info: |
  Lightning Talk at SciPy 2023
drawings:
  persist: false
favicon: 'https://images.squarespace-cdn.com/content/v1/63975e9df6661225421e79b4/e46a82c5-0bc8-40ef-9299-e866d2934ee2/favicon.ico?format=100w'
transition: fade-out
# transition: slide-left
# transition: false
selectable: true
download: true
title: Sustainability of Scientific Open Source Software
---

# **Sustainability of Scientific<br>Open Source Software**
<br>
Matthew Feickert

matthew.feickert@cern.ch

SciPy 2023 Lightning Talks

July 13th, 2023

<div class="abs-bl m-5 flex gap-2">
  <img src=/figures/logos/logo_institution.png style="width: 30%">
</div>

<div class="abs-br m-6 flex gap-2">
  <a href="https://github.com/matthewfeickert-talks/talk-scipy-2023-lightning" target="_blank" alt="GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)

TODO: How to add logos?
-->

---

# Sometimes you have things planned out
<br>

<div style="margin-left:150px">
<Tweet id="1548483936858152968" />
</div>

<!-- https://twitter.com/HEPfeickert/status/1548483936858152968?s=20 -->

---

# But then you get inspired

<div grid="~ cols-2 gap-4">
<div>
<Tweet id="1634267477772324867" />
</div>
<!--  -->
<div>
<Tweet id="1635063997585309698" />
</div>
</div>


<!-- https://twitter.com/HEPfeickert/status/1634267477772324867?s=20 -->
<!-- https://twitter.com/InessaPawson/status/1635063997585309698?s=20 -->


---
layout: center
---

# So we still need coffee

But let's go!

<video controls autoplay loop>
  <source src="/videos/JamesHoffman_ahh_coffee.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

---

# Rocket Ship To Mars 🚀

<div grid="~ cols-2 gap-4">
<div>

[![](https://opentechstrategies.com/archetypes-files/open-source-archetypes-v2-cover.png)](https://opentechstrategies.com/archetypes)

[Open Source Archetypes: A Framework For Purposeful Open Source](https://opentechstrategies.com/archetypes) --- Open Tech Strategies and Mozilla, 2019

</div>
<!--  -->
<div style="font-size: 22px">

<br>

* > Characterized by a small full-time core team that is wholly focused on a well-articulated and highly specific goal.
* Many projects start out in this archetype, but it is almost impossible to sustain
   - Not everyone can (or should!) be Daniel Stenberg (developing `curl` since before 1998)

</div>
</div>

---

# Small dev teams in science can be exciting but hard

<div grid="~ cols-2 gap-4">
<div>

<Tweet id="1634267482709008384" />

</div>
<!--  -->
<div>

<Tweet id="1634267487582801924" />

</div>
</div>

---

# Find and embrace developer communities

<div style="margin-left:150px">
<a href="https://scikit-hep.org/">
<img src="/public/figures/shells-hep.svg" style="width: 70%">
</a>
</div>

<div style="margin-left:325px">

[scikit-hep.org](https://scikit-hep.org/)

</div>

---

# Find and embrace developer communities

<div style="margin-left:100px">
<a href="https://scikit-hep.org/">
<img src="/public/figures/scientific-python.png" style="width: 90%">
</a>
</div>


<div style="margin-left:325px">

[scientific-python.org](https://scientific-python.org/)

</div>

---

# Go to the BoFs!

Don't listen to me, go to the Birds of a Feather sessions this week!

---
transition: slide-up

level: 2
---

# Navigation

Hover on the bottom-left corner to see the navigation's controls panel, [learn more](https://sli.dev/guide/navigation.html)

### Keyboard Shortcuts

|     |     |
| --- | --- |
| <kbd>right</kbd> / <kbd>space</kbd>| next animation or slide |
| <kbd>left</kbd>  / <kbd>shift</kbd><kbd>space</kbd> | previous animation or slide |
| <kbd>up</kbd> | previous slide |
| <kbd>down</kbd> | next slide |

<!-- https://sli.dev/guide/animations.html#click-animations -->
<img
  v-click
  class="absolute -bottom-9 -left-7 w-80 opacity-50"
  src="https://sli.dev/assets/arrow-bottom-left.svg"
/>
<p v-after class="absolute bottom-23 left-45 opacity-30 transform -rotate-10">Here!</p>

---
transition: fade-out
---

# What is Slidev?

Slidev is a slides maker and presenter designed for developers, consist of the following features

- 📝 **Text-based** - focus on the content with Markdown, and then style them later
- 🎨 **Themable** - theme can be shared and used with npm packages
- 🧑‍💻 **Developer Friendly** - code highlighting, live coding with autocompletion
- 🤹 **Interactive** - embedding Vue components to enhance your expressions
- 🎥 **Recording** - built-in recording and camera view
- 📤 **Portable** - export into PDF, PNGs, or even a hostable SPA
- 🛠 **Hackable** - anything possible on a webpage

<br>
<br>

Read more about [Why Slidev?](https://sli.dev/guide/why)

<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<!--
Here is another comment.
-->
