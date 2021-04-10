---
title: "APIs for use in Research: The Nuts And Bolts"
author: "Greg D'Arcy"
date: "2020-07-29"
permalink: /posts/2020/11/apis-for-research
tags: 
- api
- data collection
- web dev
---

![](https://cpb-ap-se2.wpmucdn.com/blogs.unimelb.edu.au/dist/2/88/files/2020/07/woman-writing-on-whiteboard-3861943.jpg)

Ever stop to think about how the apps on your mobile phone or tablet receive and exchange data over the Internet? The next time you check your Facebook app, look for directions using Google maps, or do your online banking, chances are these are all happening using an **Application Programming Interface** (or **API** for short). 


## Getting started

APIs work using the underlying protocols of the Internet that send data from one network device to another. So, when you open an app on your phone it sends a request for data to a server somewhere on the Internet. The server then interprets your request, and sends back some data to display on your phone. It’s no wonder that APIs are often described as the glue that holds the Internet together.  

## That Thing you do: integration into practice

APIs provide researchers from all corners of academia with a way to access online platforms for data – platforms that can be used to examine social attitudes and trends, political exchanges, social interactions, and a wealth of other social phenomena. For scholars in the humanities and the social sciences, the National Library’s [Trove website ](https://trove.nla.gov.au "Trove") has a wealth of resources in the form of books, digitised newspaper articles, maps, government reports, and heritage records. 

A/Prof. Tim Sherratt has put together something he calls his GLAM Workbench, which uses the Trove API to [download and explore the contents of Trove](https://glam-workbench.net/trove/ "Trove") using Jupyter notebooks. In case you’ve never heard of them before, [Jupyter notebooks](https://realpython.com/jupyter-notebook-introduction/ "Jupyter notebooks") let you combine text, images, and live code in a single web page that analyses and visualises your data.


## Considerations

Not all APIs work in the same way, and most have strict requirements for what you can and can’t do with the data you collect. Some issues you’ll need to consider include: 


* **Authentication**: Collecting data through APIs is only possible if the data collection programs are authorised to do so. Most APIs typically have some sort of authentication (or access permission) in place to request and access their data. To use an API, you need to register an account where you’re issued with an API Key or Token. These are long strings of numbers and letters that allow you to query and receive data back from the API. 

* **Rate and access limits**: Many APIs are rate limited, which means that you can only send a certain number of requests per hour. For example, the standard free Twitter API only lets you collect tweets from the past 7-10 days, and doesn’t provide mechanisms to work with historical tweets. If you go over your rate limit, you often have to wait a while before performing another request. 

* **Data formats**: While we as humans can easily interpret information displayed for us on a web page or mobile app, computers need more help. Instead of sending back a nicely formatted web page, APIs deliver data in a digital form that computers can understand (which is often referred to as machine-readable data). 

* **Privacy and ethics**: One of the most important purposes of research ethics is to protect research participants, and ethical issues are a major consideration in any form of online research. The question of whether public tweets are by default public data is an ethical issue that is contested. Most API providers have some Terms of Service (TOS) agreement in place to access their data. However, it’s important not to confuse TOS compliance with a human subject’s compliance or privacy protection. 

## Learn more

If you’d like to start working with Jupyter notebooks, head over to [Tim Sherratt’s GLAM Workbench](https://glam-workbench.net "GLAM Workbench"). As well as Trove, there are notebooks to access data from a number of other Galleries, Libraries, Archives and Museums (GLAM). 

[IFTTT (If This Then That)](https://ifttt.com "If This Then That") is a free service that lets you stitch different APIs and services together. For example, you can back up your Instagram photos to Dropbox, or save tweets with a particular hashtag to a Google spreadsheet. 

JSON (JavaScript Object Notation) is a standard data format APIs use to transmit data. [W3Schools](https://www.w3schools.com/whatis/whatis_json.asp "W3Schools") has some great tutorials on how to use JSON.




