Please check the description branch readme. <br>
Here a new file Canada_Immigration_check.ipynb is added where the issue with name differences in .json file <br>
and the .xlsx file is addressed to make a more meaningful world map plot with Folium. <br>
In the data file (.xlsx) United Kingdom of Great Britain and Northern Ireland creates a conflict <br>
with .json file United Kingdom. So no changes are seen in the Choropleth map over the years in UK region.<br> 
After changing the column entry <br> 
```
  dataframe.column_name = dataframe.column_name.replace{"United Kingdom of Great Britain and Northern Ireland": "United Kingdom"}
```
the changes can be seen in Choropleth map. 
