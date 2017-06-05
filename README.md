# OSM_Calgary
Examining the current dataset of The City of Calgary open street map (OSM). The analysis includes data auditing and cleaning. Finally the data was imported into an SQL database and examined.

# Details
The data auditing and cleaning are done using Python. The data cleaning includes correcting spelling mistakes and standardizes street names and types. For example, street names may be written as " Walsh Street" or "Walsh St." depending on the user that entered the data. The cleaning stage standardizes all names and abbreviations.
Once the data is cleaned and standardized, it is stored in an sqlite database so it can be analysed using SQL queries.
