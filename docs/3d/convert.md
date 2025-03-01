---
layout: default
---

[Startseite fylr Community](/) &gt; [3D-Visualisierung](/3d/) &gt; 3D-Konvertierungen

# 3D-Konvertierungen

## Linksammlung
 * [GigaMesh Software Framework](https://gigamesh.eu) kann hoch-aufgelöste PLYs und OBJs als glTF ab der Version 2401015 exportieren.<br />
   Kolorierung (Farbe pro Vertex) und Texturemapping mit mehreren Texturfile wird unterstützt.<br />
   Texturen können in GigaMesh reduziert werden (Menü "Edit" ab Version 240221)<br />
   Der Export der Normalen pro Vertex kann beim Export abgewählt werden und spart ca. 25% an Speicherplatz und ist für Messdaten empfohlen.<br />
   Die Konvertierung kann in der Konsole mit `gigamesh-togltf` automatisert werden.<br style="line-height: 120%;"/>
   GigaMesh bietet zu dem die Möglichkeit technische Metadaten zu exportieren. Dafür gibt es den Menüpunkt _Export Meta-Data_ in _File_ für die Formate XML, JSON-LD, TTL (Turtle, RDF) und HTML. Der Metadatenexport kann auf der Konsole mit `gigamesh-info` automatisert werden. Ebenso die Bereinigung (cf. [Tutorial Video No. 1 bei YouTube](https://www.youtube.com/@GigaMeshTutorials/videos)) der Geometrie mit `gigamesh-clean`.<br style="line-height: 120%;"/>
 * 3D → gltf/glb, 3D → 2D: [Skripte von 3D-DFG-Viewer-Projekt](https://github.com/thedworak/dfg_3dviewer/tree/main/scripts)
 * Nachträgliche Draco-Komprimierung von gltf/glb: `npx gltf-pipeline -i original.glb -d --draco.compressionLevel 10 -o compressed.glb`
 * obj → gltf/glb: [obj2gltf](https://github.com/CesiumGS/obj2gltf). Erlaubt auch das Vertauschen von Achsen über `--input-up-axis` bzw. `--outputUpAxis`. Allerdings sind damit offenbar nicht alle Kombinationen möglich, da hier jeweils nur die Werte X, Y und Z, jedoch nicht -X, -Y oder -Z erlaubt sind.
 * ply → Nexus: [nxsbuild, nxscompress](https://github.com/cnr-isti-vclab/nexus/tree/master)
