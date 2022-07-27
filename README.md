<a href="https://juncture-digital.org"><img src="https://juncture-digital.org/images/ve-button.png"></a>

<param ve-config 
       title="CLACS Summer 2022 Workshop"
       author="Ann Hanlon"
       banner="https://iiif.juncture-digital.org/banner/?url=https://upload.wikimedia.org/wikipedia/commons/f/f7/Citadelle_Laferri%C3%A8re%2C_Haiti%2C_1920_-_49810176056.jpg"
       layout="vertical">

<!-- Entities discussed throughout the essay are typically defined before the essay text and
     are thus available in all text.  Entity identifiers (QIDs) can be found in either
     Wikipedia or Wikidata (https://www.wikidata.org)> -->
<param ve-entity eid="Q185372"> <!-- Girl with a Pearl Earring painting -->
<param ve-entity eid="Q41264"> <!-- Johannes Vermeer -->
<param ve-entity eid="Q221092"> <!-- Mauritshuis -->
<param ve-entity eid="Q36600"> <!-- The Hague -->

# Sample visual essay

This is a sample visual essay demonstrating a few key features of a visual essay.  Complete [Documentation](https://juncture-digital.org/docs) and helpful [examples](https://juncture-digital.org/examples) are available on the [Juncture site](https://juncture-digital.org).
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">

# Basic usage

## Image

_Republic of Cuba Military Intelligence Map, 1934 _ Explanation of the map.[^1]
<param ve-image 
       label="Republic of Cuba Military Intelligence Map, 1934" 
       description="map showing relief, etc" 
       license="copyright" 
       url="https://annhanlon.github.io/images/agdm_1459_medium.jpg">
       
## Central Park in Havana, Cuba

From the Smithsonian Institution collections
<param ve-image fit="contain"
       manifest="https://ids.si.edu/ids/manifest/NMAH-AHB2012q03608">


## Map

The work has been in the collection of the Mauritshuis in The Hague since 1902 and has been the subject of various literary treatments. In 2006, the Dutch public selected it as the most beautiful painting in the Netherlands.
<param ve-map center="Q36600" zoom="11" prefer-geojson>

## Multiple viewers

Multiple viewers may be defined for a single paragraph of text.  The first viewer defined is displayed as the default viewer.  Others are selectable using icons displayed in the top right margin of the paragraph.
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">
<param ve-map center="Q36600" zoom="11">

# References

[^1]: [Wikimedia Commons: Citadelle Laferrière, Haiti, 1920](https://commons.wikimedia.org/wiki/File:Citadelle_Laferri%C3%A8re,_Haiti,_1920_-_49810176056.jpg)
