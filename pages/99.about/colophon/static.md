---
title: 'Colophon & Credits'
subtitle: 'How Pop! is Made'
date: 31-10-2019
---

*Pop!* is first and foremost a printed journal. More about that in a few weeks, when we solidify the production process. In the meantime, here's how the Pop! web version is made.

Content comes to *Pop!* typically as Word files. Once peer review and copyediting are complete, we convert all content to [markdown](https://en.wikipedia.org/wiki/Markdown), using the excellent [Pandoc](https://pandoc.org) conversion tool.

The *Pop!* website uses the [Grav](https://getgrav.org) flat-file CMS, hosted at the fabulous [Reclaim Hosting](https://reclaimhosting.com). Grav makes websites out of markdown content and twig templates; an entire Grav site is just a collection of text files, which makes development, migration, and backup really easily.

As each issue is finalized, we push the local development version of the site up to [Github](https://github.com/jmaxsfu/popjournal). The Pop! website is sync'ed with the Github repository via Paul Hibbits' GitSync plugin for Grav.

## *Pop!* is very appreciative of the support of:

- [Ellen Michelle](https://ellenmichelle.com), for copy- and production-editing support;
- [Paul Hibbitts](http://www.hibbittsdesign.org/), for help building in Grav;
- [Kevin Stranack](https://pkp.sfu.ca/about/people), for assistance with publishing and DOIs.


