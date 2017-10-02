---
author: Jesse Sadler
date: 2017-05-27T12:50:02-07:00
description: "A digital humanities project of an early modern merchant's correspondence network using GIS techniques with R"
draft: false
tags: 
title: "The Correspondence Network of Daniel van der Meulen, 1578–1591"
subtitle: 
---

<img src="/img/ggmap-light-2017-06-06.png" height="400" />

---

### Visualizations
* [Interactive leaflet map of the correspondence network](https://jessesadler.com/visualization/leaflet-map/)
* [Shiny version of the leaflet map that includes real-time filtering of dates](https://jessesadler.shinyapps.io/dvdm-correspondence/)

### Background to Daniel van der Meulen
Long-distance trade in the early modern period could not be conducted without correspondence networks and the exchange of letters. Merchants continued to travel in order to manage their affairs, but elite merchants like Daniel van der Meulen rarely if ever travelled with their own goods. Instead of escorting goods from place to place, merchants like Daniel organized and supervised the purchase, transportation, and sale of goods through correspondence with factors spread throughout the trade routes of Europe and beyond. This more sedentary system of exchange enabled the rapid growth of trade on an individual and European-wide basis, but it also necessitated that merchants create and maintain wide networks of competent and trustworthy correspondents willing and able to follow the directions of merchants who might be many hundreds of miles away.

Daniel van der Meulen, the fifth child and youngest son of Jan van der Meulen and Elizabeth Zeghers, was born in Antwerp in 1554. The Van der Meulens participated in regional trade from Antwerp, mainly with the fairs in Frankfurt and Strassbourg. The prospects of the Van der Meulens improved over the course of Daniel's childhood, especially after Daniel's mother took over management of the family's trading activities following the death of her husband around 1563. In the 1580s, Daniel and his older brother Andries both married into the mercantile elite of Antwerp, enabling the Van der Meulens to enter into international trade. Closely associated with the rebel side of the Dutch Revolt, the Van der Meulens left Antwerp in the fall of 1585. Daniel first spent six years in Bremen before relocating to the university city of Leiden in September 1591. By the time of Daniel's death from the plague in 1600, his trading activities had expanded well beyond the European continent to involve the western coast of Africa and even exploratory ventures to the Indies that predated the founding of the Dutch East Indies Company.

The large collection of approximately 6,600 letters that Daniel van der Meulen (1554–1600) received between 1578 and 1600 — housed in the [Daniel van der Meulen Archive](https://www.erfgoedleiden.nl/collecties/archieven/archievenoverzicht/ead/index/zoekterm/meulen/eadid/0096) at the [municipal archive in Leiden](https://www.erfgoedleiden.nl) — provides a rare opportunity to investigate the development of a mercantile correspondence network at an early stage in the maturation of the Atlantic economy. The collection can be divided into two periods: before and after Daniel's move to Leiden in 1591. From 1578 — the date of the first letter addressed to Daniel extant in the archive — until the end of 1591, Daniel received 424 letters. After moving to Leiden, Daniel became more independent from his siblings and developed a much more robust and active correspondence network, receiving well over 6,000 letters in a period of just under nine years (3,211 days). The current state of the project only incorporates the letters sent to Daniel up to the end of 1591. Data entry on the remaining letters is underway.

### Methodology
The analysis and visualization for this project is being done with the [R programming language](https://www.r-project.org). The above map of the letters from 1578–1591 provides an example of the visual possibilities. In addition to static maps, the project will also include interactive maps that enable the viewer to investigate the data on their own. An early example of this can be seen below, which uses the [leaflet package](https://rstudio.github.io/leaflet/). Further analysis and visualizations will be described on the blog.

### Correspondence Network of Daniel van der Meulen, 1578–1591
The contents of this project are very much under development. You can check out the [GitHub page](https://github.com/jessesadler/dvdm-correspondence) to see the development. Below is a partial list of some aspects of the project that are ahead. Feedback on the project is welcome. I can be reached via email, Twitter, or through an issue on GitHub.

### Future developments
* Make website dedicated to the analysis and visualization of the correspondence of Daniel van der Meulen
* Data entry of letters from 1592 to 1600
* Analysis and visualization of more aspects of the data including, distance, number of correspondents, and characteristics of the correspondents

<!--more-->