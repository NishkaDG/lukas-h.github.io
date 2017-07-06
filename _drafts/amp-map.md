---
title: Geojson auf einer Karte darstellen mit AMP
date: 2017-07-02 21:39:00 Z
gists: true
layout: post
---

## Einführung

http://leafletjs.com/examples/geojson/

## Gist
Man kann einfach einen Gist mit einer GeoJson-Datei bei Github erstellen, so wie [das](https://gist.github.com/lukas-h/2a0df5216644e4507d0d784e39db5630). Gists kann man dann mit dem AMP-Modul `amp-gist` einbinden.

## der schwierigere Weg: amp-iframe & leaflet.js
### 1. `amp-iframe`-Komponente laden
[hier](https://ampbyexample.com/components/amp-iframe/) beschrieben.  
### 2. Die folgende Datei in den iframe laden:  

<script src="https://gist.github.com/lukas-h/4bdee7df84f3ddddcb50d415ed00133b.js"></script>

Wenn man die Datei nicht selbst auf seinen Server packen möchte, kann man sie von hier aus einbinden: *lukas-h.github.io/assets/map.html*

3. Parameter angeben
Damit etwas auf der Karte angezeigt werden kann, muss man mehrere Parameter spezifizieren.  

map.html?src=http://stolpersteine-heilbronn.de/stolpersteine.geojson&lat=49.13&long=9.21&zoom=12