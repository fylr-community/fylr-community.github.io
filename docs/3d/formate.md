---
layout: default
---

[Startseite fylr Community](/) &gt; [3D-Visualisierung](/3d/) &gt; 3D-Formate

# 3D-Formate

## obj
Archiv-Format, dass aus mehreren Datein besteht (Texturen werden z.B. als gesonderte Dateien abgelegt). Zwar wird das Format für die Langzeitarchivierung geeignet, aktuell ist die Verarbeitung der Dateien z.B. für ein Viewer noch nicht gelöst.

## ply

## Nexus

## glTF/glb
Format scheint sich aktuell als defacto-Standard in der Community durchzusetzen.

Das glTF-Format besteht i.d.R. aus einer zentralen Datei mit der Endung gltf im JSON-Format aus der dann ggf. auf weitere Dateien verweist/verlinkt. Die gltf-Dateien können in eine Binärdatei (zugehörige Dateiendung: glb) überführt werden. Bei beiden Varianten ist es möglich, die Informationen aus den verlinkten Dateien direkt in die Datei selbst einzubinden (embedded Variante).

Informationen rund um glTF finden sich im zugehörigen [GitHUB-Repository](https://github.com/KhronosGroup/glTF). Dort gibt es auch eine [Übersichtsposter](https://www.khronos.org/files/gltf20-reference-guide.pdf)

Das glTF-Format kann über [Extensions (siehe glTF Extension Registry)](https://github.com/KhronosGroup/glTF/blob/main/extensions/README.md) erweitert werden.

# Verwandte Formate

## RTI

### Allgemein/Formatbeschreibung

Eine offizielle Formatbeschreibung scheint es nicht zu geben.
Für die Visualisierung über den JS-basierten Viewer sind die Dateien in das [Relight Format](https://vcg.isti.cnr.it/relight/#format) (Ordner mit JSON-Datei + 2D-Bilder) umgewandelt werden.

### Software/Viewer

 * Ältere Konvertiersoftware und Viewer: [https://vcg.isti.cnr.it/rti/webviewer.php](https://vcg.isti.cnr.it/rti/webviewer.php)
 * Neuere Konvertiersoftware und Viewer: [https://vcg.isti.cnr.it/relight](https://vcg.isti.cnr.it/relight)

