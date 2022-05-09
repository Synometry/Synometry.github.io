# **Tile Set Generation Demonstration**

Project Web Page: [synometry.github.io/TileGenDemo/](https://synometry.github.io/TileGenDemo/)

## Introduction

This repository is a demonstration of tile set creation using QGIS. Tile sets are groups of images that allow a web mapping service to quickly display map layers or features without having to render that information on the fly, typically resource-intensive operations. In this repository I have included four tilesets (detailed below) that demonstrate the efficacy of this strategy. All four are geographic representations of Seattle. I showcase these tilesets in [this](synometry.github.io/TileGenDemo/) web page.

---

## Tileset 1: Alternate Basemap
### 12-15 Zoom

The map represented by this tileset is simply a deviation from MapBox's normal map. I uploaded an image of mine to MapBox Cartogram and tweaked the colors and other aspects to produce what I thought was a decent-on-the-eyes basemap.

![tileset 1: basemap](assets\screenshots\tileset1ss.jpeg)

---

## Tileset 2: Thematic Map
### 10-14 Zoom

The feature class represented by this tileset is an overlay of census blocks with a max advertised download speed of 35 Megabits-per-second (Mb should not be confused with MB). The tiles of this layer are png's to allow for overlaying on a basemap.

![tileset 2: thematic](assets\screenshots\tileset2ss.jpeg)

---

## Tileset 3: Thematic Map & Basemap
### 10-14 Zoom

The map represented by this tileset is the combination of the two previous tilesets.

![tileset 3: thematic](assets\screenshots\tileset3ss.jpeg)

---

## Tileset 4: NDVI Raster Map (Satellite Analysis to Estimate Vegetation)
### 7-13 Zoom

The raster map represented by this tileset is an interpretation of various wavelengths of light detected by the USGS's LandSat 8 satellite array. These wavelength "bands" are then used to calculate NDVI values, which I use to estimate the density of vegetation. I express this classification by the color ramp of this map's base layer.

![tileset 4: thematic](assets\screenshots\tileset4ss.jpeg)