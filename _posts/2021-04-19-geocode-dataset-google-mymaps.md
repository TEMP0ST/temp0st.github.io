---
title: 'Try It Yourself: Geocode a dataset and display with Google MyMaps'
date: 2021-04-01
permalink: /posts/2021/04/geocode-dataset-and-display-google-mymaps
tags:
  - maps
---

## Try It Yourself: Geocode a dataset and display with Google MyMaps

This tutorial goes through the process of geocoding addresses in an existing dataset and then shows how to import the dataset into Google MyMaps.

### Requirements
You will need the following to complete this exercise:

- Google account (if you don’t have one already)
- Google Sheet / Google My Map
- Geocode Add-on 

### Set-up & Install 

We will need to install a particular geocoder to complete this task. [**Geocode**](https://workspace.google.com/u/0/marketplace/app/geocode_by_awesome_table/904124517349) is a free tool that helps you get latitudes & longitudes from addresses in a Google Sheet. 

<br>

![](https://i.imgur.com/Z4lAq6G.gif)

<br>

---
## Import a dataset to geocode
You will need a `.csv` file with some place-based data, such as street addresses, suburb, city name or country to carry out the geocoding.

For the purpose of this exercise we will use a dataset of [Arts Organisations (Victoria)](https://data.gov.au/data/dataset/arts-organisations-victoria) and import it into our Google sheet.

Go to the web page of the dataset and copy the link of the csv file (OrgList.csv) as shown below:

<br>

![](https://i.imgur.com/pkRlSAm.gif)

<br>

Now open a new Google sheet and paste the URL using the IMPORTDATA function into the top cell (A1).

<br>

> `=IMPORTDATA("PASTE THE WEB ADDRESS HERE")`

<br>

![](https://i.imgur.com/yywvfAA.gif)

<br>

Once data has been imported make a duplicate of the sheet  to use for the geocoding (for some reason this add-on deletes all the other columns so it always pays to have a backup).

The geocoder requires the complete address to be in a single column. Once started it gives you the option to concatenate the cells if the place data is in seperate columns as shown below:

<br>

![](https://i.imgur.com/nOcrjAX.gif)


<br>

Finally, copy and paste the new `Full Address`, `Latitude` and `Longitude `columns back into our original sheet. Our dataset now has spatial coordinates that can be used to display individual entities (pins) in any spatial analysis tool.

<br>

---
## Import dataset into My Map

[Google MyMaps](https://www.google.com.au/maps/d) is great to make a quick and easy web map. It is an easy first step to explore the spatial relationships within your data. You can easily share the web address of your map with others or embed the map into your own blog or webpage. If your goal is to develop a more permanent mapping interface Google MyMaps is a quick way to start developing your specifications for the functionality of the map and the level of data you intend to display.

To start go to MyMaps and select the `Create a new map` button. We can customise our new map in a number of ways. 
- Edit the Title and Description of the map by clicking on the `title`. 
- To edit the title of the layer click on `untitled layer`. 
- Experiment with different styles of the underlying basemap by selecting `Basemap`. 

To import our dataset select `Import` and locate our sheet in Google Drive. Select the columns with your address information to identify where the pins will be located on your map as shown below:

<br>

![](https://i.imgur.com/mzSdQWH.gif)

<br>

Finally, click on the three dots to open the `Data Table`. Any red rows haven’t been mapped. You can click in any cell to edit an address or add further details. You can also style the pins and colour them by category.

---
## Observations
What do you think are the advantages or limitations of each of these tools. 

- Did the Geocoder code all the places in the dataset correctly?
- Does the map display any unexpected locations or outliers?

<br>




