# Awesome Web Performance

A list of Web Performance Optimization techniques, tools and resources.

## Table of Contents

- [Articles](#articles)
- [Talks / Videos](#talks--videos)
- [Case Studies](#case-studies)
- [Blogs](#blogs)
- [Courses](#courses)
- [Books](#books)
- [Converences](#converences)
- [Tools](#tools)
  - [Analyzers](#analyzers)
  - [Bundle Analyzers](#bundle-analyzers)
  - [Benhcmarking / Load Testing](#benhcmarking--load-testing)
  - [Image Optimization](#image-optimization)
  - [Tracers](#tracers)
- [Specs](#specs)
- [Stats](#stats)
- [Other Awesome Lists](#other-awesome-lists)

## Articles

- 2015
  - [Rendering Performance – Web Fundamentals](https://developers.google.com/web/fundamentals/performance/rendering) — Browser Rendering, Browser Layout.
- 2016
  - [The Right Way to Bundle Your Assets for Faster Sites Over HTTP2](https://medium.com/@asyncmax/the-right-way-to-bundle-your-assets-for-faster-sites-over-http-2-437c37efe3ff) — Bundling, Network, HTTP, HTTP2.
- 2020
  - [Maximally optimizing image loading for the web](https://www.industrialempathy.com/posts/image-optimizations/) — Images, Lazy Loading, HTML.
- 2022
  - [Prerender pages in Chrome for instant page navigations](https://developer.chrome.com/blog/prerender-pages/) — Chrome, Page Load, Prerender, Prefetch.
- 2023
  - [The truth about CSS selector performance](https://blogs.windows.com/msedgedev/2023/01/17/the-truth-about-css-selector-performance/) — CSS, Microsoft, Selector, DOM.
  - [Using :is() in complex selectors selects more than you might initially think](https://www.bram.us/2023/01/17/using-is-in-complex-selectors-selects-more-than-you-might-initially-think/) — CSS, Selectors.

## Talks / Videos

- 2018
  - [Архитектура и производительность фронтенда](https://www.youtube.com/watch?v=pIQo6yCicQk) — Architecure, SSR, Island Architecture, Yandex (Russian Only).
- 2019
  - [Anatomy of the browser 101 (Chrome University 2019)](https://www.youtube.com/watch?v=PzzNuCk-e0Y) — Chrome, Chrome University, Browser Internals.
  - [Anatomy of the browser 201 (Chrome University 2019)](https://www.youtube.com/watch?v=u7berRU9Qys) — Chrome, Chrome University, Browser Internals.
  - [Life of a navigation (Chrome University 2019)](https://www.youtube.com/watch?v=OFIvyc1y1ws) — Chrome, Chrome University, Browser Internals.
- 2022
  - [CSS runtime performance | Nolan Lawson](https://www.youtube.com/watch?v=nWcexTnvIKI) — CSS, Browser Rendering.
  - [Progressively loading images](https://www.youtube.com/watch?v=-7k3H2GxE5E) – HTTP203 Show, Images, Progressive Images.

## Case Studies

- 2021
  - [RFC Update theme shape](https://github.com/microsoft/fluentui/blob/master/rfcs/react-components/convergence/theme-shape.md) — CSS, CSS Variables, CSS Variables Performance, Microsoft.

## Blogs

- [https://calendar.perfplanet.com/](https://calendar.perfplanet.com/)
- [https://web.dev/tags/performance/](https://web.dev/tags/performance/)
- [https://v8.dev/](https://v8.dev/)

## Courses

TBD

## Books

TBD

## Converences

- [https://twitter.com/perfnowconf](https://twitter.com/perfnowconf)

## Tools

### Analyzers

- [Lighthouse](https://github.com/GoogleChrome/lighthouse) — Automated auditing, performance metrics, and best practices for the web.
- [PageSpeed Insights](https://pagespeed.web.dev/) — Lighthouse as a Service.

### Bundle Analyzers

- [source-map-explorer](https://github.com/danvk/source-map-explorer) — Analyze and debug space usage through source maps.
- [BundlePhobia](https://bundlephobia.com/) — Find the cost of adding a npm package to your bundle.
- [Webpack Bundle Analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) — Webpack plugin and CLI utility that represents bundle content as convenient interactive zoomable treemap.
- [Whybundled](https://github.com/d4rkr00t/whybundled) — Answers the question – Why the hell is this module in a bundle?
- [Statoscope](https://github.com/statoscope/statoscope) — Statoscope is a toolkit to analyze and validate webpack bundle.

### Benhcmarking / Load Testing

- [Yandex Tank](https://github.com/yandex/yandex-tank) — Load and performance benchmark tool.
- [JSBen.ch](https://jsben.ch/) — Online JavaScript benchmarking tool.
- [Perf.link](perf.link) — Benchmarking tool for JavaScript.

### Image Optimization

- [Squoosh](https://squoosh.app/) — Image compression app.
- [Squoosh CLI](https://www.npmjs.com/package/@squoosh/cli) — Squoosh CLI is an experimental way to run all the codecs you know from the Squoosh web app on your command line using WebAssembly.
- [ImageOptim CLI](https://github.com/JamieMason/ImageOptim-CLI) — Make optimisation of images part of your automated build process.
- [ImageOptim](https://imageoptim.com/mac) — ImageOptim optimizes images without losing quality or any metadata.
- [SVGO](https://github.com/svg/svgo) — Node.js tool for optimizing SVG files.

### Tracers

- [Indicium: V8 runtime tracer tool](https://v8.dev/blog/system-analyzer) — V8, Browser Internals, Tracer.
- [Trace Cafe](https://trace.cafe/) — View and shore Chrome DevTools traces.

## Specs

- [Web Performance Working Group](https://www.w3.org/webperf/) — The mission of the Web Performance Working Group is to provide methods to measure aspects of application performance of user agent features and APIs.

## Stats

- [HTTPArchive](http://httparchive.org/index.php) — HTTP Archive periodically crawls the top sites on the web and record detailed information about fetched resources, used web platform APIs and features, and execution traces of each page. And then crunches and analyze this data to identify trends.

## Other Awesome Lists

- [https://github.com/davidsonfellipe/awesome-wpo](https://github.com/davidsonfellipe/awesome-wpo) (last updated 3 years ago).
