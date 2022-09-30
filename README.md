# Summary

This repository is focused on the visualization of cooperation and conflict among countries as source and target actors. 

The data are obtained via the [UTDEventData R package](https://github.com/KateHyoung/UTDEventData) (please refer to the "Data_Pull.Rmd" file for an example of how to interact with the UTDEventData R package to query event data). 

The igraph package in R is utilized to generate static images, while the pacman and magick packages are used to animate those images.

The "EventData.Rmd" file relies on the "EventData.json" file for the data, and the "igraphs_animated.gif" is the product of those two files.

For this example, the script in the "EventData.Rmd" file will create four igraphs for 2022 (January, February, March, and April) involving cooperation and conflict among the U.S., Ukraine, Turkey, Russia, India, Great Britain, Germany, and China. It will then produce a GIF so that the changes over time can be viewed in an animated format.

![image](https://github.com/eventdata/igraph/blob/a7440a100e66c953dd5a97255d3834562badf355/igraphs_animated.gif)
