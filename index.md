---
title       : Milk Price Comparison
subtitle    : 
author      : 
job         : 
framework   : revealjs        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : default      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Milk Price Comparison

A Shiny App to compare farm gate and retail prices of milk, from different countries!

--- .class #id 

## What is shown

- User has the choice between visualizing farm gate or retail price for one
  litre of milk, in Canadian dollars, across time
- According to visualization, you have the choice between various countries, by
  default Canada
- Graph is shown after making choices and submitting the job

---

## Origin of the data

- USA: USDA-NASS and USDA AMS
- Canada: Québec dairy producers and Statistics Canada
- Europe: DG Agri and Eurostat
- New Zealand: CLAL.it

---

## Harmonization

- Each country has its way of reporting economic information:
  - USA: $/cwt for farm gate price; $ for a gallon or half a gallon for retail
    price
  - CAN: $/hl for farm gate price; $ for a litre for retail price
  - Europe: euros/100 kg for farm gate price; euros per litre for retail price
  - New Zealand: dollars per 100 kg for farm gate price
- So all measures were harmonized as Canadian dollars per litre
- Also, exchange rate on the first day of the year was used to convert between
the currencies and Canadian dollars

---

## Where to find it?

[https://dhaine.shinyapps.io/milkPrice/](https://dhaine.shinyapps.io/milkPrice/)




