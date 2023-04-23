# Awesome Web Performance

A list of Web Performance Optimization techniques, tools and resources.

## Table of Contents

<!-- toc -->

- [Table of Contents](#table-of-contents)
- [Articles](#articles)
- [Talks / Videos](#talks--videos)
- [Case Studies](#case-studies)
- [Podcasts](#podcasts)
- [Blogs](#blogs)
- [Social Media](#social-media)
- [Courses](#courses)
- [Books](#books)
- [Conferences](#conferences)
- [Tools](#tools)
  - [Analyzers](#analyzers)
  - [Bundle Analyzers](#bundle-analyzers)
  - [Benhcmarking / Load Testing](#benhcmarking--load-testing)
  - [Image Optimization](#image-optimization)
  - [Tracers](#tracers)
- [Web Vitals](#web-vitals)
- [Specs](#specs)
- [Stats](#stats)
- [Other Awesome Lists](#other-awesome-lists)

<!-- tocstop -->

## Articles

- 2015
  - [Rendering Performance – Web Fundamentals](https://developers.google.com/web/fundamentals/performance/rendering) — Browser Rendering, Browser Layout.
- 2016
  - [The Right Way to Bundle Your Assets for Faster Sites Over HTTP2](https://medium.com/@asyncmax/the-right-way-to-bundle-your-assets-for-faster-sites-over-http-2-437c37efe3ff) — Bundling, Network, HTTP, HTTP2.
- 2020
  - [Maximally optimizing image loading for the web](https://www.industrialempathy.com/posts/image-optimizations/) — Images, Lazy Loading, HTML.
- 2021
  - [Overview of the RenderingNG architecture](https://developer.chrome.com/articles/renderingng-architecture/) — Chrome, RenderingNG, Browser Internals.
- 2022
  - [Prerender pages in Chrome for instant page navigations](https://developer.chrome.com/blog/prerender-pages/) — Chrome, Page Load, Prerender, Prefetch.
- 2023
  - [The truth about CSS selector performance](https://blogs.windows.com/msedgedev/2023/01/17/the-truth-about-css-selector-performance/) — CSS, Microsoft, Selector, DOM.
  - [Using :is() in complex selectors selects more than you might initially think](https://www.bram.us/2023/01/17/using-is-in-complex-selectors-selects-more-than-you-might-initially-think/) — CSS, Selectors.

## Talks / Videos

- 2018
  - [Архитектура и производительность фронтенда](https://www.youtube.com/watch?v=pIQo6yCicQk) — Architecure, SSR, Island Architecture, Yandex (Russian Only).
- 2019
  - [Anatomy of the browser 101 (Chrome University 2019)](https://www.youtube.com/watch?v=PzzNuCk-e0Y) — Chrome, Chrome University, Browser Internals. Architecture of Chrome, including the process model, layering of components, and the directory structure.
  - [Anatomy of the browser 201 (Chrome University 2019)](https://www.youtube.com/watch?v=u7berRU9Qys) — Chrome, Chrome University, Browser Internals. Here we explore the major objects and common patterns in the Chromium codebase.
  - [Life of a navigation (Chrome University 2019)](https://www.youtube.com/watch?v=OFIvyc1y1ws) — Chrome, Chrome University, Browser Internals. Alex’s talk describes the steps taken in Chrome to navigate from one web page to another. It covers the various parts, processes, and steps taken in making it happen.
- 2020
  - [Life of a Pixel](https://www.youtube.com/watch?v=K2QHdgAKP-s) — Chrome, Blink, Browser Internals, Browser Rendering. A tour of the internals of Chromium's rendering architecture, tracing the steps in the pipeline from web content to display pixels. Concretizes high-level concepts with pointers to important classes and data structures in the codebase.
  - [Life of a Script](https://www.youtube.com/watch?v=veYjbF1rt5o) — Chrome, V8, Blink, Browser Internals, JavaScript. The design of V8 and current ongoing work, garbage collection and how V8 fits into Blink and Chrome, and how WebAssembly fits into that picture.
- 2021
  - [From 'Fully Loaded' to Core Web Vitals: Understanding the Evolution of Performance Metrics](https://www.youtube.com/watch?v=zcvsk3LstJo) — WebVitals, RUM, Performance Metrics. In this talk, Patrick and Tim explore how we got to this point, the metrics we’ve loved along the way, and how the new core web vital metrics are seeking to provide some stability to the picture. They get into the weeds about how each metric is reported, what they’re good at, and a few shortcomings and gotcha’s to be aware of.
- 2022
  - [CSS runtime performance | Nolan Lawson](https://www.youtube.com/watch?v=nWcexTnvIKI) — CSS, Browser Rendering. On the client side, we pay a lot of attention to JavaScript performance. But relatively little time is spent on CSS, even though style and layout calculation can impact runtime performance as well. In this talk, I'd like to demystify some aspects of CSS runtime performance, exploring what parts the browser has already optimized, and what we as web developers can do to speed up styling.
  - [Progressively loading images](https://www.youtube.com/watch?v=-7k3H2GxE5E) – HTTP203 Show, Images, Progressive Images.In this episode, Jake (that's him on the left) and Surma (that's the other one) chat about how the different image formats load, and what you can do to make them feel faster.
- 2023
  - [Intro to Runtime Performance in the Chrome DevTools Performance Panel with Annie Sullivan](https://www.youtube.com/watch?v=3_5DKEx72qk) — Chrome, Chrome Dev Tools, Performance Profiling, Begginer Level. Annie Sullivan, Software Engineer on Google's Chrome Web Platform Team, is digging into runtime performance in the Chrome DevTools Performance Panel.

## Case Studies

- 2021
  - [RFC Update theme shape](https://github.com/microsoft/fluentui/blob/master/rfcs/react-components/convergence/theme-shape.md) — CSS, CSS Variables, CSS Variables Performance, Microsoft.

## Podcasts

- 2023
  - [JS Party: Web development's lost decade](https://changelog.com/jsparty/263)

## Blogs

- [https://calendar.perfplanet.com/](https://calendar.perfplanet.com/)
- [https://web.dev/tags/performance/](https://web.dev/tags/performance/)
- [https://developer.chrome.com/tags/performance/](https://developer.chrome.com/tags/performance/)
- [https://v8.dev/](https://v8.dev/)
- [https://csswizardry.com/](https://csswizardry.com/)
- [Infrequently Noted](https://infrequently.org/)

## Social Media

- [Addy Osmani](https://twitter.com/addyosmani)
- [Alex Russell](https://twitter.com/slightlylate)
- [Dan Shappir ](https://twitter.com/DanShappir)
- [Harry Roberts](https://twitter.com/csswizardry)
- [Ivan Akulov](https://twitter.com/iamakulov)
- [Patrick Meenan](https://twitter.com/patmeenan)
- [Stoyan Stefanov](https://twitter.com/stoyanstefanov)
- [Tim Kadlec](https://twitter.com/tkadlec)
- [Yoav Weiss](https://twitter.com/yoavweiss)

## Courses

TBD

## Books

TBD

## Conferences

- [https://twitter.com/perfnowconf](https://twitter.com/perfnowconf)

## Tools

### Analyzers

- [Lighthouse](https://github.com/GoogleChrome/lighthouse) — Automated auditing, performance metrics, and best practices for the web.
- [PageSpeed Insights](https://pagespeed.web.dev/) — Lighthouse as a Service.
- [WebPageTest.org](https://www.webpagetest.org/) — Web Performance and Optimization Test.

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
- [Trace Cafe](https://trace.cafe/) — View and share Chrome DevTools traces.

## Web Vitals

- [Web Vitals Changelog](https://chromium.googlesource.com/chromium/src/+/master/docs/speed/metrics_changelog/README.md) — Changelog for Web Vitals Metrics.

## Specs

- [Web Performance Working Group](https://www.w3.org/webperf/) — The mission of the Web Performance Working Group is to provide methods to measure aspects of application performance of user agent features and APIs.

## Stats

- [HTTPArchive](http://httparchive.org/index.php) — HTTP Archive periodically crawls the top sites on the web and record detailed information about fetched resources, used web platform APIs and features, and execution traces of each page. And then crunches and analyze this data to identify trends.
- [WPO Stats](https://wpostats.com/) — Case studies and experiments demonstrating the impact of web performance optimization (WPO) on user experience and business metrics.

## Other Awesome Lists

- [https://github.com/davidsonfellipe/awesome-wpo](https://github.com/davidsonfellipe/awesome-wpo) (last updated 3 years ago).
