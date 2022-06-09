- 👋 Hi, I’m @fernandoleuvenamsterdam
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
fernandoleuvenamsterdam/fernandoleuvenamsterdam is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<a href="https://juncture-digital.org"><img src="https://juncture-digital.org/images/ve-button.png"></a>

<param ve-config 
       title="Peyotl enters the scene "
       author="JSTOR Labs team"
       banner="https://commons.wikimedia.org/wiki/File:Lophophora_williamsii_(5673485954).jpg"
       layout="vertical">

<!-- Entities discussed throughout the essay are typically defined before the essay text and
     are thus available in all text.  Entity identifiers (QIDs) can be found in either
     Wikipedia or Wikidata (https://www.wikidata.org)> -->
<param ve-entity eid="Q185372"> <!-- Girl with a Pearl Earring painting -->
<param ve-entity eid="Q41264"> <!-- Johannes Vermeer -->
<param ve-entity eid="Q221092"> <!-- Mauritshuis -->
<param ve-entity eid="Q36600"> <!-- The Hague -->

# Sample visual essay

This is a sample visual essay demonstrating a few key features of a Visual Essay. Additional [Documentation](https://github.com/JSTOR-Labs/juncture/wiki) and [examples](https://jstor-labs.github.io/juncture-examples) are available for reference.
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">

# Basic usage

## Image

Equating  hallucinations with (dark) magic was the beginning of the prohibitive approach applied to these substances during the Colonial period. In his multi-volume ethnographic project, La Historia General de las Cosas de Nueva España / The Universal History of the Things of New Spain, Bernardino de Sahagún wrote on the subject: “Its leaves are slender, cord-like, small. Its name is ololiuhqui. It makes one besotted; it deranges one, troubles one, maddens one, makes one possessed. He who eats it, who drinks it, sees many things which greatly terrify him. He is really frightened [by the] poisonous serpent which he sees for that reason. He who hates people causes on to swallow it in drink [and] food to madden him.”  Ololiuhqui  has been identified as Christmas vine / Morning Glory (Ipomoea corymbosa / Turbina corymbosa, Granziera, 2001).  Images of the plant ornamenting Sahagún’s unique book are among the first sites of visual mediation of psychoactive precursors from the Americas [^1].
<param ve-image 
       label="Peyotl" 
       description="painting by Johannes Vermeer" 
       license="By Leonora Enking. Public domain" 
       url="https://commons.wikimedia.org/wiki/File:Lophophora_williamsii_(4876527737).jpg"
       

## Map

<!DOCTYPE html>
<html>
<head>
    <title>Leaflet GeoJSON Example</title>
    <meta charset="utf-8" />
    <link rel="stylesheet" href="http://cdn.leafletjs.com/leaflet-0.7.1/leaflet.css" />
    <style type="text/css">
        .leaflet-container{background-color:#c5e8ff;}
    </style>
</head>

<body>
    <div id="map" style="width: 600px; height: 400px"></div>

    <script src="http://code.jquery.com/jquery-1.10.2.min.js"></script>
    <script src="http://cdn.leafletjs.com/leaflet-0.7.1/leaflet.js"></script>
    <script>
        var myGeoJSONPath = 'path/to/mymap.geo.json';
        var myCustomStyle = {
            stroke: false,
            fill: true,
            fillColor: '#fff',
            fillOpacity: 1
        }
        $.getJSON(myGeoJSONPath,function(data){
            var map = L.map('map').setView([39.74739, -105], 4);

            L.geoJson(data, {
                clickable: false,
                style: myCustomStyle
            }).addTo(map);
        })
    </script>
</body>
</html>


## Multiple viewers

Multiple viewers may be defined for a single paragraph of text.  The first viewer defined is displayed as the default viewer.  
Others are selectable using icons displayed in the top right margin of the paragraph.
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">
<param ve-map center="Q36600" zoom="11">

# References

[^1]: Drawing of ololiuhqui, appears first in  La Historia General de las Cosas de Nueva España, Folio 129, Book X1, Volume 7. 
Courtesy of World Digital Library.

