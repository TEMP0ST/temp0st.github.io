---
title: 'Introduction to digital mapping for non-programmers'
date: 2021-04-01
permalink: /posts/2021/04/intro-digital-mapping-for-non-programmers
tags:
  - maps
---

## Introduction to digital mapping for non-programmers

This session is aimed at graduate students and early career researchers (ECR) interested in using web mapping systems in their humanities research. We will provide an overview of some of the diverse techniques in humanities mapping, examine common geospatial terms and techniques, and look at some basic tools that support digital mapping. No prior experience with coding, web development or GIS is needed

This forms part of a training series delivered through the **Social & Cultural Informatics Platform** [(SCIP)](https://scip.unimelb.edu.au) at The University of Melbourne. 


---
## Session Outline
| Time        | Section  | 
| ----------- | ---------|
| 2:00–2:10 | Introduction |
| 2:10–2:30 | Why map? What makes a good map? | 
| 2:30–2:50 | Try It Yourself: Geocoding & Google MyMaps | 
| 2:50–3:00 | Storymaps | 
| 3:00–3:30 | Try It Yourself (Extension): Create a Leaflet Storymap | 
| 3:00-3:30 | Q&A |

<br>

---
## Why map?

Through out the centuries maps have been a form of technology humans have used to explain and navigate their way through the world. 

![](https://i.imgur.com/lpjcRAg.jpg)

Today maps are everywhere you look. We use maps to find restaurants, roads, directions to places, countries, population, and weather. 

![](https://i.imgur.com/tQNXV9i.jpg)

Maps help us to learn about our world. Digital maps  are created using *spatial data*. Spatial data is data that has a locational component that is connected to some place on Earth.

![](https://i.imgur.com/xNN1HOo.png)

<br>

### Why use maps in research?
Key issues of the 21st Century, including population change, demographics, natural hazards, energy, water, human health, transportation, biodiversity and climate change, occur at specific locations and can exhibit geographic patterns, relationships and trends. Using **spatial data** allows us to analyse and better understand the world. We can describe information by location, and we can query attributes to provide more detail about those locations.

<br>

### Maps in the humanities
Researchers in the humanities, arts and social sciences (HASS) are increasingly engaging with a variety of digital resources and services to exploit the availability of historical and real-time data.

**Digital mapping** covers a range of methods/publication in the humanities including:
- Digitising historic maps
- Georeferencing historic maps
- Geo-locating data (objects, statistics, literature, narratives, archival information)
- Network analysis - how things connect or relate to each other in space and time
- Using maps as a user interface for collections/data ([Digital Mapping in the Humanities. Grant, 2018.](http://bit.ly/DM_KG))

<br>

![](https://i.imgur.com/s8bxe91.jpg)
[Oslo World music festivals](https://maptheworld.no)

<br>

Maps can act as:
- A visualisation of data about/connected to place. 
- A tool to analyse place-based relationships. 
- A way of understanding change over time

<br>

![](https://i.imgur.com/U9VAI1r.png)
[Trans-Atlantic Slave Voyages](https://slavevoyages.org)

<br>

It's worth remembering that all tools have their strengths and weaknesses. Often many tools (esp in digital humanities) have been created based around a specific method of enquiry and at a specific moment in time (ie: development stops once the research funding runs out). The tool you go with ultimately depends on what you're trying to achieve and your level of motivation in learning a particular tool.

<br>


---
## What makes a good map?
The power of using digital maps allows us to interpret what we're seeing in the data. How easy is it to interpret the data from this earthquake magnitude table?

![](https://i.imgur.com/0BsdFvJ.png)

<br>

Compared to this map:

![](https://i.imgur.com/5Xwz8kd.png)

<br>

Maps are good for disseminating research, as they can convey information at a glance in a way that a long text cannot. Maps provide a visualisation that enables us to see patterns we would not have otherwise seen and potentially make research discoveries.

<br>

### Maps as a form of data visualisation

<br>

> 'A map is not just a picture—it’s also the data behind the map, the methodology used to collect and parse that data, the people doing that work, the choices made in terms of visualization and the software used to make them'. [When Maps Lie](https://www.bloomberg.com/news/articles/2015-06-25/how-to-avoid-being-fooled-by-bad-maps)

<br>

While it's easy to get lost in the tech-wizardry and potential of creating stunning interactive maps, it's important not to loose sight of the focus of the research questions you are trying to answer. Most analysis, whether spatial or not, begins with asking questions or querying our data. 

<br>

![](https://i.imgur.com/3L6IuxT.png) 

[XKCD comics](https://xkcd.com/1138/)

<br>

And like all data visualisations it's also important to consider the purpose, use and intended audience for your map.

<br>

### Working with real data is messy
For geographic information to be associated with an artefact, its data or information, there needs to be some form of **geospatial grounding**. Geospatial tools allow humanities researchers to map their data in time and space, and then integrate and explore it in relation to other disparate cultural datasets.

What are the spatial elements in a research question/project/collection:
- Can you attach your data to a place?
- Can you attach a place to your data? ([Digital Mapping in the Humanities. Grant, 2018.](http://bit.ly/DM_KG))

<br>

Mapping tools work best with **well structured data**. Inaccuracies can creep in due to data entry, location ambiguities, and changes that have occured over time.



![](https://i.imgur.com/AOjyRKM.png)

([Dougherty & Ilyankou, 2021](https://handsondataviz.org/clean.html))

<br>

On average data scientists can spend up to 40-45% of their time in projects just cleaning and preparing data for analysis [Kaggle ML & DS Survey, 2018. Machine Learning and Data Science Survey (n=23,859)](https://www.kaggle.com/kaggle/kaggle-survey-2018/)

<br>

---
### Try It Yourself: Geocode a dataset and display with Google MyMaps

[This tutorial walks through the process of geocoding a list of addresses in an existing dataset and then goes through how to import the dataset into Google MyMaps](https://hackmd.io/@gregarious09/S1aW5o5Ld).


---
## Some key terms 

| Term        | Definition  | 
| ----------- | ---------|
| Basemap | An underlying reference map used to overlay multiple layers of spatial or geographic data. |
| Choropleth map | A map that displays divided geographical areas or regions that are coloured, shaded or patterned in relation to a numeric variable (data variable / summary statistic). |
| Comma-separated values (.csv/CSV) | A plain text file that stores tabular data (numbers and text) using a comma to separate values. |
| Geographic information System (GIS) | Tool used to capture, store, process, analyse and visualise spatial information. |
| Geo-Location | A location on the Earth’s surface, commonly referenced using either geospatial data (e.g. coordinates) or textual place names (toponyms). 
| Geoparsing | The process of extracting toponyms from a corpus of text. Common methods included Named Entity Recognition (NER) and Classification (NERC).
| Georeferencing | The linking between an entity and a spatial footprint (Leinder, 2017). Entities may be any artefact (e.g. image or text) with a spatial grounding. |
| Geocoding | A specific form of georeferencing, linking an entity to a spatial footprint. There are two main types of geocoding: address and toponym resolution (Leinder, 2017).  |
| Layer | Web maps separate information into layers. The data used in layers comes from a variety of sources, and different types of layers have different capabilities. You can show or hide information on the map by activating or deactivating layers. There are two types of layers: *Vector layers* represents information as either a point, a line, or a polygon. *Raster layers* are made up of pixels in a grid, much like digital photographs. |
| Shapefile | A common format for storing vector GIS data of the geometric location and attribute information of geographic features. |

<br>

---
## Storymaps

**Story maps** use Geographic Information System (GIS) tools to combine geospatial data with photos, video, audio and text to visualise a narrative theme or sequential event.

Some examples:

- [The Living Archive of Aboriginal Collections](https://uploads.knightlab.com/storymapjs/8e541eaeb142af0ece3ca45ea3ea72f2/the-living-archive-of-indigenous-collections/index.html)
- [Shakespeariana in Melbourne](https://melbourneshakespeare.github.io/)
- [James Cook: The Third Voyage](https://www.arcgis.com/apps/MapJournal/index.html?appid=8ee32984ba12486a94263b47d66be2b4)
- [Legacies of Labor](https://ncsu.maps.arcgis.com/apps/Cascade/index.html?appid=1ef4e3f14c8b45f59346dc3ab34d870d)

<br>

---
### Try It Yourself (Extension): Create a Leaflet Storymap

[This tutorial provides the instriuctions and source code to create your own 'free' online map](https://hackmd.io/@gregarious09/Sy7sxu98u).

<br>

---
## Where to go for help at the university
- Next SCIP session in [Advanced Geospatial Mapping (14 May 2021)](https://scip.unimelb.edu.au/home/training/training-events/digital-mapping-advanced)
- [Geospatial (GIS), Spatial Data and Map Resources](https://unimelb.libguides.com/GIS)
- [Centre for Spatial Data Infrastructures and Land Administration](https://csdila.unimelb.edu.au)
- [Australian Urban Research Infrastructure Network (AURIN)](https://aurin.org.au)


<br>

---
## Some further resources to explore
- When Maps Lie / https://www.bloomberg.com/news/articles/2015-06-25/how-to-avoid-being-fooled-by-bad-maps
- The Importance of Where: How spatial analysis leads to insight / https://www.esri.com/arcgis-blog/products/analytics/analytics/the-importance-of-where-how-spatial-analysis-leads-to-insight/
- ArcGIS StoryMaps / https://www.esri.com/en-us/arcgis/products/arcgis-storymaps/resources 
- ArcGIS Blog: Story Maps and the Digital Humanities / https://www.esri.com/arcgis-blog/products/story-maps/sharing-collaboration/story-maps-and-the-digital-humanities/
- Story Maps list & tutorials / https://storymaps-classic.arcgis.com/en/app-list/ 
- Geo-coding historical data / https://programminghistorian.org/en/lessons/geocoding-qgis 
- Geocomputation with R / https://geocompr.robinlovelace.net/ 
- Geospatial Data Curriculum / https://datacarpentry.org/lessons/#geospatial-curriculum
- KML tutorial / https://developers.google.com/kml/documentation/kml_tut


<br>







