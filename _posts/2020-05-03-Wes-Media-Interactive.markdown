---
layout: post
title:  "Wesleyan Media Project: Interactive Map"
categories: viz
---
[LIVE on Wesleyan Media Project Site](http://mediaproject.wesleyan.edu/releases/issues-110518/)
[GITHUB](https://github.com/ekmaus19/wmp_issues-map)

#SUMMARY
Fall 2018, I was tasked with developing a web application for the Wesleyan Media Project as part of a series of analysis regarding issues addressed by political ads, specifically for use by journalists browsing the site. Since the purpose of the WMP is to share analysis on political data that can be utilized by other news outlets, the primary purpose of the app was to give a quick look at general domestic trends for key political issues, one that could be screenshotted and posted elsewhere.

#APPROACH
This map is my second d3 visualization and my first attempt at making a map using the d3 library. The decision to use d3 was a result of previous conversations with project heads about their desire for more unique, flexible visualizations. Again, I attempt to design a visualization that would appear immediately comprehensible to the viewer. I spoke with the WMP heads to gather their ideas on what they thought the project could look like, and their perspectives on the anticipated needs of those coming to the site. I checked in with them regularly on my progress, as well as to gather feedback on the map development.

#METHODOLOGY
I researched the coding approach to this visualization independently from start to finish, consulting many online resources to help me along. The final version of the application opens to a choropleth of the US, filtered to total ad counts across the country. A user has the option of filtering via dropdown to see percentage of ads in a given state that addressed particular issues (jobs, immigration, taxes, and health care); hovering on a state reveals a popup with the relevant value, and clicking on the state brings up a bar plot showing the percentages for all issue ads aired in that state. The bar graph updates with state change. Labels of the plot change to reflect the selections specified by the user (the main title alters in response to the dropdown, and the bar graph title alters based on state selection). All of the analysis for the project  was retrieved from the Wesleyan Media Project, which sourced the data from the Kantar Media Group/CMAG.
