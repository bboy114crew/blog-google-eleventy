---
title: CSS Inline
description: CSS Explained 101.
date: 2019-12-20
draft: false
category: CSS
tags: Note
layout: layouts/post.njk
---

### Keep in mind
 If you inline a large amount of CSS, it delays the transmission of the rest of the HTML document. If everything is prioritized then nothing is. Inlining also has some downsides in that it prevents the browser from caching the CSS for reuse on subsequent page loads, so it's best to use it sparingly.

## Reference:
[Extract critical CSS](https://web.dev/extract-critical-css/) <br/>
[Render Blocking CSS](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/render-blocking-css) <br/>
[The approach is less performant than CSS classes](https://esbench.com/bench/5908f78199634800a0347e94) <br/>
