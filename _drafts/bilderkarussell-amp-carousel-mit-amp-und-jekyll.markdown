---
title: Bilderkarussell (amp-carousel) mit AMP und Jekyll
date: 2017-06-12 22:42:00 Z
categories:
- amp
- jekyll
- html
---

In meinem Blog habe ich schon beschrieben, [wie man eine Seite mit Jekyll und AMP baut](http://himsel.me/06-04-2017-Accelerated-Mobile-Pages.html). Wie man einfache Bildergalerien für AMP erstellt, beschreibe ich hier.

Für mein Beispiel benutze ich die [vorgefertigte AMP-Komponente `amp-carousel`](https://ampbyexample.com/components/amp-carousel/). 

Als erstes muss man die Komponente in den HTML-Kopf (Achtung: muss zwingend im `<head>` sein) hinzufügen:
<script src="https://gist.github.com/lukas-h/ab21ad318ed71107046ea8478d8ddcdf.js"></script>

<script src="https://gist.github.com/lukas-h/bb49c4d4b2ba5c6e480115c246b24a64.js"></script>

Dieser Quellcode muss einfach in das Layout `post` eingefügt werden.