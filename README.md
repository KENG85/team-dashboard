# Project-Dream_Team
JavaScript Visualization Project

Your task is to tell a story through data visualizations.
Focus on providing users an interactive means to explore data themselves.
Prepare a 10-minute presentation that lays out your theme, coding approach, data munging techniques, and final visualization.
You may choose a project of any theme, but we encourage you to think broadly.
You will have ample time in class to work with your group, but expect to put in hours outside of class as well.

1. Your visualization must include a Python Flask–powered RESTful API, HTML/CSS, JavaScript, and at least one database (SQL, MongoDB, SQLite, etc.).
2. Your project should fall into one of the below four tracks:
○ A custom “creative” D3.js project (i.e., a nonstandard graph or chart)
○ A combination of web scraping and Leaflet or Plotly
○ A dashboard page with multiple charts that update from the same data
○ A “thick” server that performs multiple manipulations on data in a database prior to visualization (must be approved)
3. Your project should include at least one JS library that we did not cover.
4. Your project must be powered by a data set with at least 100 records.
5. Your project must include some level of user-driven interaction (e.g., menus, dropdowns, textboxes).
6. Your final visualization should ideally include at least three views.
===================
# Summary

1. We scraped data from https://www.pro-football-reference.com/years/2006/ 
2. then used google places API to locate the lat and lon of college and states.
3. we loaded it into mongodb and used moment js library for the dates
3. we ran into issues rendernig geojson format from pandas limiting our map display to only one layer.  
4. charts were generated from d3, leaflet, observable and tableau. 
5. Our data and findings were presented on an html "dashboard" webpage. 
