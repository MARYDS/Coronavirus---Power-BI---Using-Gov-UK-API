# Coronavirus Data

Data is retrieved using the UK Government API. 
See details at https://coronavirus.data.gov.uk/developers-guide.

Weekly MSOA cases data .csv file from https://coronavirus.data.gov.uk/about-data.


Folder Power BI has an example of retrieving and presenting the data using Power BI desktop.
Example output is in the .pdf file.

MSOA shape file from https://geoportal.statistics.gov.uk/datasets/middle-layer-super-output-areas-december-2011-boundaries-ew-bfe-1?geometry=-27.988%2C48.013%2C23.648%2C57.298
imported to https://mapshaper.org, projection changed to wgs84 (proj wgs84 in console) and exported in TopoJSON format (see method in https://www.youtube.com/watch?v=YV6y1pX0-hg).


Folder Python has a Juypter Notebook example of retrieving the data and displaying some simple plots.
Example output is in the .pdf file.
