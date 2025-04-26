---
title: Pre-Screening Unpaved Secondary Roads for Pavement Prioritization
date: 2025-03-12
external_link: ''

---

This web application was made for my capstone project in the NCSU MGIST program, where I was partnered with the North Carolina Department of Transportation to create a custom tool and application addressing their need to improve the prioritization process for unpaved secondary roads. I created a custon script tool using Python and the packages OSMnx, ArcPy, Pandas, and GeoPandas that downloads point data from OpenStreetMap, combines it with other input point data, and identifies points located along each segment using a two-step process of identifying points within a buffer and determining if their street address matches the street name of the segment.

The Web application shown above is only available to NCDOT employees, but it lets NCDOT employees explore the results of pre-screening and see which segments in their division have been recommended for the survey. They can then provide input on the tool's decision for a specific segment, supply additional information, and "manually override" the tool's decision using a radio switch. Any manual overrides will be perused by NCDOT Operations Program Management employees before they are accepted.

<!--more-->
