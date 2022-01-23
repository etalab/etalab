---
title: Shower Presentations with R Markdown
author: https://github.com/mangothecat/rmdshower
output:
  rmdshower::shower_presentation:
    self_contained: false
    katex: true
    ratio: 16x10
---

# Shower Presentations with R Markdown

### Shower Presentations with R Markdown { .white }

![](../../../../../../diaporamas/slides-afd\_files/rmdshower/examples/scifi.jpg)

Get it from GitHub: https://github.com/mangothecat/rmdshower.

### R Markdown

This is an R Markdown presentation. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see [http://rmarkdown.rstudio.com](http://rmarkdown.rstudio.com).

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document.

### Shower

These slides use a template from the [shower](https://github.com/shower/shower) presentation system. Notable features:

1. Works in all modern browsers
2. Presentation fully keyboard accessible
3. Multiple themes available
4. Printable to PDF

Shower \['ʃəuə] noun. A person or thing that shows.

### Slide with Plain Text

Let me see your identification. You don't need to see his identification. We don't need to see his identification. These are not the droids your looking for. These are not the droids we're looking for. He can go about his business. You can go about your business.

Move along. Move along. Move along.

### Two column layout

What is it? Your fathers lightsaber. This is the weapon of a Jedi Knight. Not as clumsy or as random as a blaster. An elegant weapon for a more civilized time. For over a thousand generations the Jedi Knights were the guardians of peace and justice in the Old Republic. Before the dark times, before the Empire. How did my father die? A young Jedi named Darth Vader, who was a pupil of mine until he turned to evil, helped the Empire hunt down and destroy the Jedi Knights.

### Two column layout, text and image

How did I get into this mess? I really don't know how. We seem to be made to suffer. It's our lot in life. I've got to rest before I fall apart. My joints are almost frozen. What a desolate place this is. Where are you going? ![](../../../../../../diaporamas/slides-afd\_files/rmdshower/examples/sw.jpg)

### Two column layout, image and text

![](../../../../../../diaporamas/slides-afd\_files/rmdshower/examples/sw.jpg) How did I get into this mess? I really don't know how. We seem to be made to suffer. It's our lot in life. I've got to rest before I fall apart. My joints are almost frozen. What a desolate place this is. Where are you going?

### Two column layout, independent columns

How did I get into this mess? I really don't know how. We seem to be made to suffer.

It's our lot in life. I've got to rest before I fall apart.

### Lists

1. Simple lists are marked with bullets
2. Ordered lists begin with a number
3. You can even nest lists one inside another
   * Or mix their types
   * But do not go too far
   * Otherwise audience will be bored
4. Look, seven rows exactly!

### Formulas

Formulas are rendered by KaTeX, https://github.com/Khan/KaTeX

It supports both inline: (y = x / 2) and displayed formulas:

\[ x\_{1,2} = \frac{- b \pm \sqrt{b^2 - 4ac}}{2a} ]

### Slide with quote

> The bad news is that when ever you learn a new skill you're going to suck. It's going to be frustrating. The good news is that is typical and happens to everyone and it is only temporary. You can't go from knowing nothing to becoming an expert without going through a period of great frustration and great suckiness.

\*\*Hadley Wickham﻿ \*\*

### Slide with R Code and Output

```
summary(cars)
```

### Tables

|                   |  mpg | cyl |  disp |  hp |
| :---------------: | :--: | :-: | :---: | :-: |
|     Mazda RX4     |  21  |  6  |  160  | 110 |
|   Mazda RX4 Wag   |  21  |  6  |  160  | 110 |
|     Datsun 710    | 22.8 |  4  |  108  |  93 |
|   Hornet 4 Drive  | 21.4 |  6  |  258  | 110 |
| Hornet Sportabout | 18.7 |  8  | 360.0 | 175 |
|      Valiant      | 18.1 |  6  | 225.0 | 105 |
|     Duster 360    | 14.3 |  8  | 360.0 | 245 |

### Pictures { .white }

![](../../../../../../diaporamas/slides-afd\_files/rmdshower/examples/scifi.jpg)

And text on top of them.

## Title slide

### Lists item by item

> 1. Lets you reveal list items one by one
> 2. To keep some key points
> 3. In secret from audience
> 4. But it will work only once
> 5. Nobody wants to see the same joke twice

### Slide with Plot

```
par(mar = c(5, 4, 1, 2) + 0.1)
pairs(iris[1:4], pch = 21,
      bg = c("red", "green3", "blue")[unclass(iris$Species)])
```

## Full Page Plots

### { .fullpage }

\`\`\`{r, echo=FALSE, dev='svg'} par(mar = c(5, 4, 1, 2) + 0.1) pairs(iris\[1:4], pch = 21, bg = c("red", "green3", "blue")\[unclass(iris$Species)]) \`\`\`

### More information

#### About R markdown: http://rmarkdown.rstudio.com

#### About shower: https://github.com/shower/shower

#### Example shower presentation: http://shwr.me/
