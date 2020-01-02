---
layout: page
title:
order: 1
---
<!-- Indexpage-->
# SWT-Praktikum 2019/20 Gruppe nw19a - Simulation von Poi-Figuren
<br>
<br>

<center><img src="{{site.url}}{{ site.baseurl}}/public/Muster2.jpg"></center>

# Beschreibung der Aufgabenstellung
Ein Poi ist ein Kleingerät, bestehend aus einem Gewicht (Head), der an einer Schnur hängend in Rotation versetzt wird, um durch seine Flugbahn Figuren zu beschreiben. Im einfachsten Fall sind diese Figuren Rotationen auf einer Kreisbahn, also Figuren der Form (x(t),y(t)) = (r*cos(t), r*sin(t)). Es sind aber auch komplexere Figuren der Form (x(t),y(t)) = (r*cos(t)+q*cos(a*t), r*sin(t)+q*sin(a*t)), sogenannte Flowers, üblich.
Im Rahmen des SWT-Praktikums sollen mathematischen Grundlagen erarbeitet werden, die es beim Poispiel erlauben nicht nur diese eingeschränkten geometrischen Muster zu spielen, sondern auch beliebige 2-dimensionale Figuren zu erzeugen, welche als geschossene Linienzüge in der Ebene beschrieben werden können.
Ziel ist es dabei eine beliebige geometrische Figur in die dazu passende Arm- und Handbewegung des Poi-Spielers zu übersetzen.
Für eine Applikation mit einem solchen Fundament als Basis ist es erstrebenswert, dass diese die Eingabe einer gewünschten Figur per Touchscreen oder Bild-Upload ermöglicht und dann die benötigten Bewegungen simuliert.
# Ziel:
Aufgabe des Teams ist es, ein solches mathematisches Modell zu entwickeln und eine Simulationsumgebung zu implementieren, welche nach Möglichkeit auch physikalische Aspekte wie Gravitation und Luftwiderstand berücksichtigt. Die Umsetzung einer solchen Simulationsanwendung soll in Form einer (mobilen und/oder Web-) Applikation erfolgen.

# Lernziele:

* Kennenlernen und Weiterentwicklung von mathematischen Konzepte für durch Rotationen beschriebene 2-dimensionale Figuren, insbesondere der komplexen Fourier Analyse
* Anwendung von Methoden zur Bildeingabe und Bildverarbeitung
* Einarbeitung in ein geeignetes Framework zur graphischen Ein- und    Ausgabe auf mobilen Geräten bzw. im Browser
* Implementierung einer Applikation

<center><img src="{{site.url}}{{ site.baseurl}}/public/Poi2.JPG"></center>
