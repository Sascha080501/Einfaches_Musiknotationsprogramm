# Musiknotationsprogramm (Web-App)

## Überblick

Dieses Projekt ist ein browserbasiertes Musiknotationsprogramm zur einfachen Erstellung und Wiedergabe von Noten. Es wurde im Rahmen einer Masterarbeit mithilfe von KI erstellt und dient der Demonstration KI-gestützten programmierens von Musiknotationsprogrammen.

## Funktionen

Das Programm bietet folgende Kernfunktionen:

* Notation von ganzen, halben, Viertel- und Achtelnoten
* Unterstützung von Pausen in entsprechenden Notenwerten
* Darstellung und Wiedergabe von **Halbton- und Vierteltonschritten
* Visuelle Darstellung im klassischen Notensystem
* Audiowiedergabe der notierten Sequenz direkt im Browser
* Intuitive Benutzeroberfläche ohne Installation oder externe Abhängigkeiten

## Technische Umsetzung

Die Anwendung wurde vollständig als **Single-Page-Webanwendung** umgesetzt und besteht ausschließlich aus clientseitigen Technologien:

* **HTML5** zur Strukturierung der Benutzeroberfläche und des Notensystems
* **CSS3** für ein modernes, responsives Design
* **JavaScript (Vanilla JS)** für die gesamte Logik, Interaktion und Notationsverarbeitung
* Nutzung der **Web Audio API** zur Klangerzeugung und Wiedergabe, inklusive mikrotonaler Anpassungen (Vierteltöne)

Die Notenpositionierung erfolgt programmatisch durch Berechnung der vertikalen Lage im Notensystem, basierend auf Tonhöhe und Notenwert. Die Audioausgabe wird synthetisch erzeugt, wodurch keine externen Sounddateien benötigt werden.

## Nutzung

Die Anwendung kann direkt im Browser geöffnet werden:

👉 https://sascha080501.github.io/Einfaches_Musiknotationsprogramm/

Es ist keine Installation erforderlich.

## Hinweis

Dieses Projekt wurde komplett unter Einsatz von KI-gestützten Entwicklungshilfen erstellt.
