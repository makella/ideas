This is the main example from my blog on [Creating a smooth color legend with an SVG gradient](http://www.visualcinnamon.com/2016/05/smooth-color-legend-d3-svg-gradient.html). The color legend below is just a simple rectangle filled with an SVG gradient. But in for this particular data it works well, because you are mostly interested in trends, to get a general sense of then numbers. Therefore, it is not imperative to be able to read the exact value that each color represents. And in those cases, when you work with a quantitative color scale, I prefer to use smooth color legends.

This visual is based on a similar dataset that I used for [my Traffic Accidents project](http://www.visualcinnamon.com/portfolio/traffic-accidents), but with data from 2014 instead of 2013. 
Looking at the data from a different angle than I did in my previous project, I now made a simple heatmap (based on [Miles McCrocklin's Heatmap block](http://blockbuilder.org/milroc/7014412)) showing the number of traffic accidents that occur on each given hour throughout the week. 
No surprise to see the numbers jump up during the morning and evening rush hours (but the evenings are worse than the mornings).

You can other SVG legend gradient examples here:

- [Hexagon map of a Self-Organizing Map](http://bl.ocks.org/nbremer/5cd07f2cb4ad202a9facfbd5d2bc842e)
- [Weather radial of Boston](http://bl.ocks.org/nbremer/a43dbd5690ccd5ac4c6cc392415140e7)
