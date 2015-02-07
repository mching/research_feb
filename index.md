---
title       : Pediatrics Research Group
subtitle    : 10 February 2015
author      : Michael Ching, MD, MPH, FAAP
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Goals of Research Group

1. Increase productivity of researchers in department
2. Provide opportunities for new/current department members to perform research
3. Develop knowledge base of research resources at Tripler

--- .class #id 

## Publication Productivity

Survey of department in late 2014

PubMed "Tripler Pediatrics" (2013-)
Google Scholar "Tripler Pediatrics" (2013-)

[Link to Publication Bibliography](publications.html)

---

## Breakdown of Research Type

![plot of chunk unnamed-chunk-1](assets/fig/unnamed-chunk-1-1.png) 

---

## Participation by Residents


```r
ggplot(data=dat, aes(x=type, fill = resident)) + 
    geom_bar(stat="bin") + xlab("Publication Type")
```

![plot of chunk unnamed-chunk-2](assets/fig/unnamed-chunk-2-1.png) 

---

## Divisions Involved in Research


```r
ggplot(data=dat, aes(x=division)) + 
    geom_bar(fill="#FF9999", stat="bin") + xlab("Publication Type")
```

![plot of chunk unnamed-chunk-3](assets/fig/unnamed-chunk-3-1.png) 

---

## Posters/Presentations

