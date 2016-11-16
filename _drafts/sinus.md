---
layout: post
title:  "Sinus + Audio"
date:   2016-11-13 22:00:00 +0200
---

Um den Zusammenhang zwischen dem Sinus und Schwingungen darzustellen, kann man einfach mithilfe von ein paar Zeilen Quellcode
und einer Sinusfunktion Töne wiedergeben. Man kann mit verschiedenen Veränderungen der Funktion andere Effekte hervorrufen.
- `a * sin(x)` - Streckung in y-Richtung um Faktor `|a|`, Veränderung der Lautstärke.  
- `sin(b * x)` - Streckung in x-Richtung um Faktor `|1/b|`, Veränderung der Frequenz (Tonhöhe).  
- `sin(c + x)` - Verschiebung in x-Richtung um `(-c)`, kein hörbarer Unterschied.
- `sin(x) + d` - muss ich ausprobieren
# MUSS ICH AUSPROBIEREN !!!

Bei folgendem Programm ist zu beachten, dass ein beliebiger mathematischer Ausdruck eingegeben werden kann, solange er der vorgeschriebenen Syntax entspricht.
Um einen wachsenden x-Wert zu bekommen, ist eine Variable `x` vordefiniert, die in der Eingabe verwendet werden kann.
Ein weiterer wichtiger Hinweis ist, dass Töne erst ab Frequenzen > 20Hz wahrgenommen werden können. Im Klartext entspricht das einer Streckung in x-Richtung mit einem Faktor von mindestens 20. Bsp: `f(x) = sin(20 * x)`

# VERLINKUNG ZUM PROGRAMM