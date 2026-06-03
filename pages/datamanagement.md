---
title: Data Management
layout: about
permalink: /datamanagement.html
---

Section 1: Project Overview:
Observations of Saturn Through Time is a digital collection of different images, photographs, and visual representations of Saturn from the 19th to 21st century. The collection shows how Saturn has been depicted and observed over time, and these items are pulled from various public domains, museums, libraries, and much more. Together, this digital collection allows us to compare how visual representations of Saturn have changed across time.
I built this project using Google Sheets, GitHub, and CollectionBuilder. I used Google Sheets to store all the metadata for each visual representation, which includes the source, date, author, type of illustration, and more. I then used GitHub to fork the CollectionBuilder-Sheets repository, uploaded my metadata and images, and published using GitHub Pages. CollectionBuilder works as our foundation for the website, using my metadata to create the public digital collection, and create sections for all topics. This collection would be useful for researchers, educators, and individuals who are interested in the history of the planet Saturn and how it has been taught, represented, and how it’s shaped our knowledge of it throughout the years.
  
Section 2: Data Inventory & Provenance:
Source Institution
# Objects
How accessed
Rights
Auckland Museum
2
Direct Download via online catalog (no account required)
No Known Copyright Restrictions
 
The Huntington
1
Direct Download via online catalog (no account required)
Public Domain
NASA
12
Direct Download via online catalog (no account required)
Public Domain
National Archives Catalog
5
Direct Download via online catalog (no account required)
Public Domain
Harvard Art Museums
1
Direct Download via online catalog (no account required)
Personal, non-commercial use
Internet Archive
4
Direct Download via online catalog (no account required)
Creative Commons CC

 
File Type
Description
Number
Approximate Volume
JPG
Digitized object images
25
29MB
PNG
Digitized object images
0
N/A
CSV
CollectionBuilder metadata spreadsheet
1
<1MB
MD
Pages controlling content of the website
11
<1MB

 
For someone to work with my data and / or reproduce this project, they would need CollectionBuilder, a GitHub account, Google Sheets, and available storage on their computer to download, maintain, and access the files included. 
Section 3: Storage & Stewardship:
The project Observations of Saturn Through Time has its files stored in several places. To start, everything is put together in my GitHub repository, which uses CollectionBuilder to put everything together onto a GitHub page. From there, the metadata is stored in a Google Sheet, where each object has all of the information relating to it. I also have everything stored on my local computer in a folder. Anyone can access the finished website from my GitHub page, built off CollectionBuilder, but the editing of the site, access to the original Google Sheet metadata, and my local files are all controlled and accessed by me.
 
For backup and recovery, I have all of the data stored on my personal computer and connected to my personal email for access to the Google Sheet. If I lost access to my metadata sheet, I’m able to recover this by using the files in GitHub to extract the images, and can reverse image search them to find its original source. I plan to keep the GitHub repository and website for as long as possible so others can access and continue to view the collection. This would mean preserving the metadata sheet on my Google Drive and local computer, revisiting the site to ensure the source links are still valid, and confirming file integrity. 
 
Section 4: Access, Reuse & Rights
Observations of Saturn Through Time is publicly available for anyone to access through my live CollectionBuilder website hosted with GitHub Pages. Users and visitors can view the collection, browse individual items, and follow source links back to the original institutions. The collection is meant for educational and research purposes, especially for students, researchers, educators, and anyone who is interested in astronomy and the history of how Saturn has been represented over time. 

For the content I created myself, including the metadata organization and website text, I am allowing reuse for educational and noncommercial purposes with attribution. This means that other users may use or build on my descriptions and metadata as long as they credit the project and do not present the work as their own. However, I do not own the original images in the collection. The images come from outside institutions, so users should follow the rights statement listed for each individual object before downloading, sharing, or republishing the image. 

There are not major ethical concerns in this collection compared to projects involving private information or sensitive community records. However, there are still ethical responsibilities in how the materials are presented. Since the collection uses images from many different institutions, it is important to keep source links, creators, dates, and rights information visible so that users know where each image came from. Being clear about the source and context of each item helps make the collection more transparent and usable for future users. 
 

 
Appendix – Data Dictionary
Field Name
Type
Description
Example Value
objectid
Text
A unique identifier for each item.
Image20
source
URL
The link to the original location where the image was extracted from or found.
https://archive.org/details/dr_11-saturn-12131019
description
Text
A brief description of what the image shows. These descriptions are based on what information we are given from the original source to describing what is going on in the image.
The last photo taken of Saturn by the Cassini Spacecraft. This photo captures a full view of Saturn and its rings from a top angled view.
title
Text
The overview of the image.
Saturn with moons Tethys and Dione
format
Text
The digital format used for the item in the website.
Image/jpeg
latitude
Number
The latitude connected to the item’s location of where it’s stored. This location refers to the physical institution where the item is being kept.
-36.860278
longitude
Number
The longitude connected to the item’s location of where it’s stored. This location refers to the physical institution where the item is being kept.
174.777778
date
Text
The date of the object (If the date starts with 01/01/xxxx, this means that we either did not know the exact date for the year, or we measured the middle of a range of years).
01/01/1907
subject
Text
A general type of category of the image. This is used to separate lithographs, photographs, paintings, etc.
Painting
location
Text
The physical institution where the original record is being held/stored at.
Stanford, California
rights
Text
The reuse statement connected to the object. This helps users understand the rules for using the content.
Public Domain (free use)
filename
Text
The local filename for the image.
Image20/jpeg
creator
Text
The person or organization credited with creating the image
NASA/Glenn Research Center
type
Text
The CollectionBuilder item type
Image;StillImage
space
Text
The spacecraft that was used to take the photograph (only applies to images that were taken in a spacecraft, otherwise left empty).
Pioneer 11

 
 


