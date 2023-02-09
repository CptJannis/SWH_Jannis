---
title: "Additive Fertigung"
date: 2023-02-07
tags: []
---

Gegenteilig zur `subtraktiven Fertigung`
Bei der `additiven Fertigung` wird Material hinzugefügt, um ein Werkstück aufzubauen oder zu erweitern. 

Ein Beispiel hierfür, wäre die Verwendung einer Heißklebepistole, Löten oder Schweisen.
Im Lab haben wir uns aber hauptsächlich mit den verscheidenen Arten des 3D-Drucks beschäftigt.

Die erste der fünf Fertigungsmethoden war das **Fused Deposition Modeling (FDM)**. 
![FDM Drucker](Ultimaker-Origina.jpg)
https://ultimaker.com/de/3d-printers/ultimaker-original-plus

Bei diesem Vorgang werden verschiedenste Arten von Plastik geschmolzen und über eine Nozzle zu einem dünner Faden geformt. Diese Fäden werden geschichtet, um das gewünschte Objekt aufzubauen.
Die verschiedenen Arten von Plastik, wie **PLA**, **ABS**, **NYLON** oder **TPU** haben unterschiedliche Werkseigenschaften, wie Flexibilität, Stabilität, dass sie gut mit Witterung umgehen können, oder dass sie nicht leicht entflammbar sind. Auch bei dem Druckvorgang weisen die Werkstoffe Unterschiede bei der Drucktemperatur, Beheizung der Platte oder bei der Aussonderung giftiger Dämpfe auf.

Um ein Werkstück zu fertigen müssen wir dem Drucker einen Auftrag geben. Dieser Auftrag beinhält ein Mesh-Modell, welches wir aus einem selbst erstelltem 3D Modell erzeugen können. Ein 3D Modell kann mithilfe der Fusion 360 Software von Autodesk erstellt werden.
Für die jeweiligen Drucker wird nochmals weitere Software benötigt. Will man auf einen der beiden Ultimaker drucken, braucht man für beide Drucker die Cura Anwendung, um die Objekte zu slicen und drucken zu können.

Die vier weiteren Arten des 3D-Drucks, **Stereolithography (SLA)**, **Digital Light Processing (DLP)**, **Selective Laser Sintering (SLS) / (DLMS)** und **Selective-Powder-Deposition (SPD)**  sind für die Arbeit im Lab nicht sonderlich von Bedeutung, da wir diese nicht zur Verfügung haben.

Während des Druckvorganges können eine Reihe von Fehlern am Produkt als auch beim Drucker auftreten. So zum Beispiel bei Überhängen bei denen das gedruckte Material nicht schnell genug kühlt, und nach unten abfällt.

![Überhang](badoverhangs.jpg)
https://www.oeg3d.at/index.php/troubleshooting.html

Bridging ist ein weiteres Problem, welches bei komplexeren Fertigungen auftreten kann. Wenn zwischen zwei Pukten eine Ferbindung geschaffen werden soll, auf dieser Strecke in der Luft druckt weden, wodurch es zu Durchhängern kommen kann. Dieser Fehler kann bis zu einem gewissen Abstand mit den Richtigen Einstellungen beheben werden.

![Bridging](poor-bridging.jpg)
https://the3dprinterbee.com/de/bridging-3d-drucken-winkel-uberhange/

Ein weiteres mögliches Problem ist Stringing. Hierbei bleiben Zwischen benachbarten Objekten Fäden zurück. Ursachen hierfür könnte eine zu hohe Drucktemperatur, oder ein nicht richtig eingestellter Filamentrückzug sein.

![Stringing](stringing.jpg)
https://www.ab3d.at/3d-druck-erste-hilfe-faden-am-druckobjekt/

Dies waren natürlich nicht alle Fehler, aber schonmal ein kleiner Überblick, über das was alles schief laufen kann.

