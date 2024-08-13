# Compare Class A

## What is It ?
This repository is the source code of a QGIS Plugin.

## How to Use ?
This plugin can be downloaded on QGIS Plugin menu. Then run it.
Select described inputs and press "Ok"

## What it does ?
This plugin answer the following need: 
What is the distance error between two data set of points, representing a line, with differents sampling distances, 
different begining and end.

## Inputs
- Point geometry Vector Layer as a reference
  - QGIS Expression to get the Z value
  - Select the Z value unit
- Point geometry Vector Layer as a result to compare
  - QGIS Expression to get the Z value
  - Select the Z value unit

If the layer reference CRS is not in meter, it will be projected on EPSG:3857.
The layer result will be projected on the layer reference CRS if they are differents.

## Outputs
- Display of a graph showing histogram of error formated to follow Class A Regulation system.
