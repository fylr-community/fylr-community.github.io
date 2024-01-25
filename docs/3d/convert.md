---
layout: default
---

[Startseite fylr Community](/) &gt; [3D-Visualisierung](/3d/) &gt; 3D-Konvertierungen

# 3D-Konvertierungen

## Linksammlung
 * [GigaMesh Software Framework](https://gigamesh.eu) export von hoch-aufgelösten PLYs und OBJs als glTF ab der Version 2401015.<br />
   Kolorierung (Farbe pro Vertex) und Texturemapping mit einem Texturfile wird unterstützt.<br />
   Der Export der Normalen pro Vertex kann beim Export abgewählt werden und spart ca. 25% an Speicherplatz und ist für Messdaten empfohlen.<br />
   GigaMesh bietet zu dem die Möglichkeit technische Metadaten zu exportieren. Dafür gibt es einen Menüpunkt in _File_. Der Export kann auf der Konsole mit `gigamesh-info` automatisert werden. Ebenso die Bereinigung (cf. [Tutorial Video No. 1 bei YouTube](https://www.youtube.com/@GigaMeshTutorials/videos)) der Geometrie mit `gigamesh-clean`.
 * 3D → gltf/dlb, 3D → 2D: [Skripte von 3D-DFG-Viewer-Projekt](https://github.com/thedworak/dfg_3dviewer/tree/main/scripts)
 * Nachträgliche Draco-Komprimierung von gltf/glb: `npx gltf-pipeline -i original.glb -d --draco.compressionLevel 10 -o compressed.glb`
