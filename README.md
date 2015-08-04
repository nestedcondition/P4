## Website Performance Optimization portfolio project

The challenge was to optimize this (https://github.com/udacity/frontend-nanodegree-mobile-portfolio) online portfolio for speed! Challenge accepted. In particular, I optimized the critical rendering path and made this page render as quickly as possible by applying the techniques I picked up in the [Critical Rendering Path course](https://www.udacity.com/course/ud884).

# Optimizations
- replace document.querySelector with faster document.getElementById and document.getElementsByClassName
- moved reusable calculations outside of loops
- combined multiple loops where possible
- decreased size of images to maximum display size
- loaded css inline

# How to run this application?

1. Download the project assets ( https://github.com/nestedcondition/P4 ).
2. In your browser, open index.html at the root level of the project folder.
