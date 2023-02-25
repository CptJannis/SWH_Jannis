---
title: "Serielle Kommunikation"
date: 2022-12-05
tags: ["Ha"]
---

Um einmal mit serieller Kommunikation gearbeitet zu haben, habe ich mir eine 8x8 Matrix mit LEDs ausgesucht.

![LED-Matrix](https://wolles-elektronikkiste.de/wp-content/uploads/2020/04/8x8x1_DotMatrix.jpg)
(https://wolles-elektronikkiste.de/wp-content/uploads/2020/04/8x8x1_DotMatrix.jpg)

Damit man beliebige LEDs ansteuern kann, muss jede Spalte betrachtet werden.
In dem Array v hab ich die Zustände der LEDs in einer Spalte abgespeichert. Eine 1 stet dafür, dass eine LED leuchtet und eine 0, dass sie aus ist. **B11000000**, soll die ersten zwei LEDs der Spalte zum Leuchten bringen. Mit dem Befehl **setRow**, kann nun jeder Reihe eine solchen Zustand übergeben werden(**lc** ist hierbei die 8x8 Matrix). Hierbei wird jedes der 8 Bits hintereinander in einem zeitlichen Abstand übergeben.
Mittels der **delay** Funktion können die Zustände der LEDs resetet werden. 

```C#
 byte v[8]={B11000000,B00110000,B00001100,B00000011};
    lc.setRow(0,0,v[0]);
    lc.setRow(0,1,v[1]);
    lc.setRow(0,2,v[2]);
    lc.setRow(0,3,v[3]);
    lc.setRow(0,4,v[3]);
    lc.setRow(0,5,v[2]);
    lc.setRow(0,6,v[1]);
    lc.setRow(0,7,v[0]);
    delay(delaytime);
```