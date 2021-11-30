---
layout: post
title:  Using Google Data Studio to follow-up students grades
description: A small example based on the dashboard I manage with my son
published: true
---

# Summary

In this post I explain how you as a student (or a parent trying to follow-up your kids grades at school) can use Google Data Studio to create a cool dashboard about school/university progress.

This blog will explain the detail on how to configure the dashboard. The idea is share the idea of using Data Studio for that purpose.

# Google Data Studio

Data Studio is free cloud-based dashboard tool from Google which allows you to connect with different data sources, specially those on behalf of Google, like YouTube, Google Ads, Google Sheets data and many others.

You can access it on

[https://datastudio.google.com/](https://datastudio.google.com/)

# Data Source

In this example, I use a simple Google Sheets to store my son's grades (I do it together with him and it's quite fun - at least for me).

![Grade Google Sheet](/assets/2021-12-01-Using Google Data Studio to follow-up students grades/1-spreadsheet.png)

# Creating the Data Source

On Data Studio first page, start creating a connection to a data source.

![Create data source](/assets/2021-12-01-Using Google Data Studio to follow-up students grades/2-data-studio-home-create-data-source.png)

Among the list of available connectors, select [Google Sheets](https://support.google.com/datastudio/answer/6370353)

![Google Connectors](/assets/2021-12-01-Using Google Data Studio to follow-up students grades/3-google-connectors.png)

Select the desired file and confirm.

![Google Sheet document](/assets/2021-12-01-Using Google Data Studio to follow-up students grades/4-google-sheets.png)

The document structure will be loaded and you might need to adjust some stuff like the column names and types.

![Google Sheet structure](/assets/2021-12-01-Using Google Data Studio to follow-up students grades/5-data-source-columns.png)


# Exploring the data source

A good idea is to use the "Explorer" feature to really discover what cool information you can get from your data source. The interface is very similar to the one where you create your dashboards (reports).

![Explorer](/assets/2021-12-01-Using Google Data Studio to follow-up students grades/6-explorer.png)

Going back to Data studio first page, you can check your data sources and explorations.

![Explorer list](/assets/2021-12-01-Using Google Data Studio to follow-up students grades/7-explorer-list.png)

# Creating a Report

Finally, you can create a Report. The first thing needed is to select the data source. 

![Create a report - select data source](/assets/2021-12-01-Using Google Data Studio to follow-up students grades/8-report-new.png)

If you are comfortable excel, specially charts and pivot tables in there, you will find easy to create different kinds of charts inside your report.

With this simple file stucture, I could create the following report in a matter of a few minutes.

![Report example](/assets/2021-12-01-Using Google Data Studio to follow-up students grades/9-report-example.png)

# Publishing and sharing

You can for sure allow multiple people to edit or view your report. It's even possible to embed it inside a web page with just a few clicks.
  
https://datastudio.google.com/embed/reporting/9b3ffcf8-35a2-4340-bc3a-5fc59074bbb5/page/mnfgC


<iframe width="600" height="450" src="https://datastudio.google.com/embed/reporting/9b3ffcf8-35a2-4340-bc3a-5fc59074bbb5/page/mnfgC" frameborder="0" style="border:0" allowfullscreen></iframe>



