---
title: "Pixel +1 dans Illustrator"
date: "2019-10-21T10:12:00-05:00"
tags: [Illustrator, pixel, plan de travail, bogue]
toc: true
---

![capture](../images/1nfograph3/illustrator-artboard-pixel.png)

Vous est-il déjà arrivé d'exporter un plan de travail Illustrator en PNG pour réaliser que les dimensions étaient de 1 pixel de plus?
Oui, c'est bien un bogue, mais l'explication et la solution sont simples :

{{< blockquote author="[Logos by Nick](https://logosbynick.com/illustrator-exports-1-pixel-more/)" >}}
**Why Illustrator Adds That Extra Pixel**

After doing a little digging around, I discovered (thanks to [Pixel & Bracket](https://www.youtube.com/watch?v=kBgVyXYwDoI) on YouTube) that it’s because of the position of the artboard on the canvas as it relates to the X and Y axis.

Whenever the artboard is positioned in a location that includes a decimal value, Illustrator rounds up to the nearest pixel, meaning your exported document ends up being 1 pixel larger than the actual artboard on each dimension.

{{< /blockquote >}}
