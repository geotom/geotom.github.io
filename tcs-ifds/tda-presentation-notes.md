---
title: Tuscaloosa City Schools - Integrated Facilities and Demographics Study
---

Presentation Notes
==================

Speaking notes for presentation to the selection committee

First Slide
-----------

1.  Introduction - The team leadership has asked me to briefly explain some of the tools involved in collecting and processing the data that will be used for enrollment projections and other study data as well.
  * Goals - Responsive; Extensible;
2.  Raw data
  * Sources - School, US Census, City, 
  * ETL - Text editor, excel, other tools to convert various formats to normalized data
  * Result - We can answer questions now, e.g. How many households with children under age 5 in each school zone.
3.  GeoDatabase
  * PostgreSQL Engine - ORDBMS; SQL; Users: State Farm analytics, Sony Online gaming, International Space Station telemetry, Instagram
  * PostGIS Extension - Provide GIS functions to PostgreSQL to store/serve geometry and do geoprocessing, relational tests
  * GeoServer - Publishes geographic data to the web (Communicate results)
  * Evaluate Results - Trust but verify. Discuss Unit Tests and manual calculations
4.  Aggregated Tables - Groups data in to tables for use in study
  * On-screen Example - Explain how this SQL query finds the population of of people age 1 in each zone.
5.  Spreadsheets - The data graveyard
6.  Report - Speaks for itself

Second Slide
------------

May not be needed, but could make segue to live demo

Live Demonstration
------------------

Switch to QGIS at this point.  Add and edit boundaries to display real-time results.

Notes and Thoughts to be Organised
----------------------------------
