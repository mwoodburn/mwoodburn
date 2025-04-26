---
title: New River Gorge Enterprise Database and Web Application Creation
date: 2024-10-26
external_link: ''
tags:
  - Hugo
  - Wowchemy
  - Markdown
---

In this project I took field data from its raw .CSV form to a relational spatial database using ArcGIS Server, a registered SDE geodatabase, and PostgreSQL. I used SQL to manipulate the data, taking advantage of its relational aspects, and published various types of services to an ArcGIS Server to be consumed in a user-friendly and highly customized web application. This project enhanced my skills in database management because of the need to develop multiple iterations of my NERI database throughout; I started with a set of .CSV files that shared primary keys and progressed to a nonspatial relational database, and ultimately to a spatially enabled and registered SDE database. I solidified my understanding of the steps required to set up and build a database, such as creating database connections in ArcGIS Pro and creating custom users and roles for myself and professors based on their necessary level of access. I also practiced leveraging the properties of relational databases to add functionality to my web app that would not be possible otherwise. For example, displaying attributes of sampling locations and counts of records sampled at each location was possible because of the PostgreSQL backend of my database and the views I implemented using pgAdmin4 and made spatial in ArcGIS Pro.

<!--more-->
