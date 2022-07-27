<a href="https://juncture-digital.org"><img src="https://juncture-digital.org/images/ve-button.png"></a>

<param ve-config 
       title="CLACS Summer 2022 Workshop"
       author="Ann Hanlon"
       banner="https://iiif.juncture-digital.org/banner/?url=https://upload.wikimedia.org/wikipedia/commons/f/f7/Citadelle_Laferri%C3%A8re%2C_Haiti%2C_1920_-_49810176056.jpg"
       layout="vertical">

<!-- Entities discussed throughout the essay are typically defined before the essay text and
     are thus available in all text.  Entity identifiers (QIDs) can be found in either
     Wikipedia or Wikidata (https://www.wikidata.org)> -->
<param ve-entity eid="Q206194"> <!-- Citadelle Laferrière -->


# Introduction

This is a sample visual essay to demonstrate how to use Juncture for the CLACS 2022 Summer Workshop. The banner image features Haiti's Citadelle Laferrière, photographed from an airplane in 1920[^1]. The first image featured in this essay is also an image of Citadelle Laferrière, from 1935.
<param ve-image 
       manifest="https://collections.lib.uwm.edu//digital/iiif-info/agsnorth/2574/manifest.json">

# Basic usage

## Image

_Republic of Cuba Military Intelligence Map, 1934 _ Explanation of the map.
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
