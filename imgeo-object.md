---
permalink: /imgeo-object
sort: 1
---

# IMGeo-object

**Definitie**

De gemeenschappelijke eigenschappen van een grootschalig topografisch object, al
dan niet uit de basisregistratie.

```mermaid
classDiagram
   IMGeo_object <|-- Wegdeel
   IMGeo_object <|-- Ondersteunend wegdeel
   IMGeo_object <|-- Spoor
   IMGeo_object <|-- Onbegroeid terreindeel
   IMGeo_object <|-- Begroeidterreindeel
   IMGeo_object <|-- Waterdeel
   IMGeo_object <|-- OndersteunendWaterdeel
   IMGeo_object <|-- Pand
   IMGeo_object <|-- OverigeConstructie
   IMGeo_object <|-- OverigBouwwerk
   IMGeo_object <|-- Overbruggingsdeel
   IMGeo_object <|-- Tunneldeel
   IMGeo_object <|-- Kunstwerkdeel
   IMGeo_object <|-- Scheiding
   IMGeo_object <|-- FunctioneelGebied
   IMGeo_object <|-- GebouwInstallatie
   IMGeo_object <|-- Inrichtingselement
   IMGeo_object <|-- Bak
   IMGeo_object <|-- Bord
   IMGeo_object <|-- Installatie
   IMGeo_object <|-- Kast
   IMGeo_object <|-- Mast
   IMGeo_object <|-- Paal
   IMGeo_object <|-- Put
   IMGeo_object <|-- Sensor
   IMGeo_object <|-- Straatmeubilair
   IMGeo_object <|-- Waterinrichtingselement
   IMGeo_object <|-- Weginrichtingselement
   IMGeo_object <|-- VegetatieObject
   IMGeo_object <|-- OpenbareRuimteLabel
   IMGeo_object <|-- Registratief gebied
   IMGeo_object <|-- Buurt
   IMGeo_object <|-- OpenbareRuimte
   IMGeo_object <|-- Stadsdeel
   IMGeo_object <|-- Waterschap
   IMGeo_object <|-- Wijk
'''
