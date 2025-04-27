## Technische Details

* **HTML:** Struktur der Webseiten.
* **CSS:** Styling (hauptsächlich via Tailwind CSS, teilweise eigene Stile).
* **JavaScript:** Interaktive Logik, Berechnungen, DOM-Manipulation, SVG-Generierung, 3D-Rendering, Chart-Erstellung, CindyJS-Steuerung.
* **SVG:** Darstellung von 2D-Grafiken (Streichhölzer, Archimedes-Herleitung).
* **WebGL (via Three.js):** Für die 3D-Darstellung des Würfels.
* **Canvas API (via Chart.js & CindyJS):** Für die Diagramme und die CindyJS-Visualisierung.

## Abhängigkeiten (Gesamt)

Die Projekte nutzen die folgenden externen Bibliotheken, die meist über CDN eingebunden werden:

* [Tailwind CSS](https://tailwindcss.com/) (MIT Lizenz) - Wird in mehreren Projekten für das Styling verwendet.
* [MathJax](https://www.mathjax.org/) (Apache License 2.0) - Für die Darstellung von LaTeX-Formeln (Archimedes).
* [Inter Font](https://rsms.me/inter/) (SIL Open Font License 1.1) - Schriftart (Streichhölzer).
* [Three.js](https://threejs.org/) (MIT Lizenz) - Für die 3D-Visualisierung (Würfel).
* [Chart.js](https://www.chartjs.org/) (MIT Lizenz) - Für die Diagramme (Häufigkeiten).
* [CindyJS](https://cindyjs.org/) (Apache License 2.0) - Für die interaktive Geometrie-Visualisierung (Trigonometrie).
* [KaTeX](https://katex.org/) (MIT Lizenz) - Wird von CindyJS intern für Formelsatz verwendet.

## Lizenz

Der Code in diesem Repository steht unter der [MIT-Lizenz](LICENSE.md). Beachte die Lizenzen der verwendeten Drittanbieter-Bibliotheken (siehe Abhängigkeiten).
