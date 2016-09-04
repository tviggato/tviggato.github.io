---
title       : Drive Time Between European Cities
subtitle    : (Are we there yet??)
author      : Me!
job         : Coursera Student
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Problem

Visiting Europe, and don't know the distance between cities?

Or, what if you don't know how long the drive should take?

Visit my Shiny App!!!
https://tviggato.shinyapps.io/DataProducts/

--- .class #id 

## Let's look at a demo...

Want to drive from Athens to Cologne?

Let's say you think you will drive 100 kph (62 mph)




```r
citydist["Cologne",]
```

```
##         Distance (km) Driving Time (hours)
## Cologne          2762                27.62
```

But what if you get stuck in traffic, and only travel at 75 kph (47 mph)




```r
citydist["Cologne",]
```

```
##         Distance (km) Driving Time (hours)
## Cologne          2762             36.82667
```

Wouldn't all this be easier on a web app??
https://tviggato.shinyapps.io/DataProducts/

--- .class #id 

## Another example

Or, maybe you are in Munich and deciding between going to Milan or Paris, and will drive 85 kph




```r
citydist[c("Milan","Paris"),]
```

```
##       Distance (km) Driving Time (hours)
## Milan           331                 3.31
## Paris           821                 8.21
```

Wow, it's a good thing we ran the app, I didn't realize it was so far to Paris!

If you use the web app, you can see the distance to all the major European cities at once!
https://tviggato.shinyapps.io/DataProducts/

--- .class #id 

## Summary

It's AMAZING!!!

Make better informed decisions

Access to information, easier, faster!! 

TIME = MONEY!!!

https://tviggato.shinyapps.io/DataProducts/
