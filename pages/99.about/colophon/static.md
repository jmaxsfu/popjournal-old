---
title: 'Colophon & Credits'
subtitle: 'How Pop! is Made'
date: 30-10-2020
---

*Pop!* is ultimately intended to be a printed journal – but we have an entirely digital-first workflow. Here's how the Pop! web version is made.

Content comes to *Pop!* typically as Word files, because of course. Once peer review and copyediting are complete, we convert all content to [markdown](https://en.wikipedia.org/wiki/Markdown), using the excellent [Pandoc](https://pandoc.org) conversion tool.

The *Pop!* website uses the [Grav](https://getgrav.org) flat-file CMS, hosted at the fabulous [Reclaim Hosting](https://reclaimhosting.com). Grav makes websites out of markdown content, YAML metadata, and twig templates; an entire Grav site is just a collection of text files, which makes development, migration, and backup properly straightforward.  *Pop!* makes use of Grav plugs: [Img Captions](https://github.com/olevik/grav-plugin-imgcaptions), [Bigfoot](https://github.com/CPPL/grav-bigfootjs), and [Breadcrumbs](https://github.com/getgrav/grav-plugin-breadcrumbs/blob/master/README.md). Thanks to their authors!

As each issue is finalized, we push the local development version of the site up to [Github](https://github.com/jmaxsfu/popjournal). The Pop! website is sync'ed with the Github repository via [Trilby Media's](https://trilby.media/) GitSync plugin for Grav.

The type is *Tzimmes*, by Michał Jarociński and *Motiva Sans*, by Rodrigo Saiani.

## *Pop!* is very appreciative of the support of:

- [Ellen Michelle](https://ellenmichelle.com), for copy- and production editing support;
- [Paul Hibbitts](http://www.hibbittsdesign.org/), for help building in Grav;
- [Mark Jordan](https://www.lib.sfu.ca/users/mark-jordan), for assistance with DOIs.


