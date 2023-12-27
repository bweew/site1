+++
draft = false
date = '2023-12-26 18:56:32'
title = "how to vectorize"
description = "converting jpg to scalable vectors using potrace in the terminal or even better, this web app"
slug = "raster-to-svg"
tags = ["vectorize", "terminal"]
+++

# potrace
its a terminal app that takes bmp as input and exports eps
```
potrace bird.bmp -o bird.eps
``` 

im sure your can use imagemagick and convert out to svg.
I didn't mess around too much with this though because the image still needed a bit more tweaking to get right and i found this webapp that this guy made that is a way easier to deal with.

{{< youtube id="kcvfyQh6J-0" title="SVGcode: A PWA to convert raster images to SVG vector graphics" >}}

[link to the webapp svgcode](https://svgco.de/)
