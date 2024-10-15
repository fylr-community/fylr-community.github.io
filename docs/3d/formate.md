---
layout: default
---

[Startseite fylr Community](/) &gt; [3D-Visualisierung](/3d/) &gt; 3D-Formate

# 3D-Formate

## obj
Archiv-Format, dass aus mehreren Datein besteht (Texturen werden z.B. als gesonderte Dateien abgelegt). Zwar wird das Format für die Langzeitarchivierung geeignet, aktuell ist die Verarbeitung der Dateien z.B. für ein Viewer noch nicht gelöst.

## ply

## Nexus
Der große Vorteil des Nexus-Formats (.nxs bzw. komprimiert als .nxz) ist es, dass verschiedene "Auflösungen" in einer Datei vorgehalten werden können. Entsprechende Viewer (z.B. 3DHOP) sind in der Lage, nur die Ausschnitte (und die Auflösungen), die sie gerade benötigen, aus der Datei zu lesen.

## glTF/glb
Format scheint sich aktuell als defacto-Standard in der Community durchzusetzen.

Das glTF-Format besteht i.d.R. aus einer zentralen Datei mit der Endung gltf im JSON-Format aus der dann ggf. auf weitere Dateien verweist/verlinkt. Die gltf-Dateien können in eine Binärdatei (zugehörige Dateiendung: glb) überführt werden. Bei beiden Varianten ist es möglich, die Informationen aus den verlinkten Dateien direkt in die Datei selbst einzubinden (embedded Variante).

Informationen rund um glTF finden sich im zugehörigen [GitHUB-Repository](https://github.com/KhronosGroup/glTF). Dort gibt es auch eine [Übersichtsposter](https://www.khronos.org/files/gltf20-reference-guide.pdf)

Das glTF-Format kann über [Extensions (siehe glTF Extension Registry)](https://github.com/KhronosGroup/glTF/blob/main/extensions/README.md) erweitert werden.

# Verwandte Formate

## RTI (Reflectance Transformation Imaging)

### Allgemein/Formatbeschreibung

Leider insgesamt sehr wenig bzw. nur veraltete Dokumentation zu diesen Formaten zu finden :-(

Vorgänger-Format: PTM (Polynomial texture mapping):
 * https://www.loc.gov/preservation/digital/formats/fdd/fdd000487.shtml
 * https://en.wikipedia.org/wiki/Polynomial_texture_mapping
 * https://cceh.github.io/rti/intro.html

Formatbeschreibung:
 * https://www.loc.gov/preservation/digital/formats/fdd/fdd000486.shtml

Für die Visualisierung über den JS-basierten Viewer sind die Dateien in das [Relight Format](https://vcg.isti.cnr.it/relight/#format) (Ordner mit JSON-Datei (in früheren Versionen: XML) + 2D-Bilder) umgewandelt werden.

### Software/Viewer

 * Ältere Konvertiersoftware und Viewer (nicht mehr supported): [https://vcg.isti.cnr.it/rti/webviewer.php](https://vcg.isti.cnr.it/rti/webviewer.php)
 * Neuere Konvertiersoftware und Viewer (letzterer nicht mehr supported, Nachfolger: OpenLIME): [https://vcg.isti.cnr.it/relight](https://vcg.isti.cnr.it/relight)
 * Viewer: [OpenLIME](https://github.com/cnr-isti-vclab/openlime)

