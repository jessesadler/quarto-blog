---
title: Test markdown
subtitle: Each post also has a subtitle
date: 2015-02-20
tags: ["example", "markdown"]
---

You can write regular [markdown](http://markdowntutorial.com/) here and Jekyll will automatically convert it to a nice webpage.  I strongly encourage you to [take 5 minutes to learn how to write in markdown](http://markdowntutorial.com/) - it'll teach you how to transform regular text into bold/italics/headings/tables/etc.

**Here is some bold text**

## Here is a secondary heading

Here's a useless table:
 
| Number | Next number | Previous number |
| :------ |:--- | :--- |
| Five | Six | Four |
| Ten | Eleven | Nine |
| Seven | Eight | Six |
| Two | Three | One |
 
[Leaflet map](http://localhost:1313/leaflet/exploratory-data.html)

How about a yummy crepe?

![Crepe](http://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg)

Here's a code chunk with syntax highlighting:

```r
letters <- read_csv("Exploratory Data.csv", col_types = cols(
  date = col_date(format = "%Y%m%d")))
locations <- read_rds("locations.rds")
geo_data <- select(locations, place:lat) # simplify locations data to only necessary variables

geo_letters <- letters %>%
  inner_join(geo_data, by = c("source" = "place")) %>% 
  inner_join(geo_data, by = c("destination" = "place"))

geo_letters$ID <-as.character(c(1:nrow(geo_letters))) # create id for each pair
```

Here is some `in line code`. You can go to `/Documents/Sites` to get this information.

<!--more-->