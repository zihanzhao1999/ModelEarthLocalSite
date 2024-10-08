Python pull from [Google Data Commons (UN Data)](/data-commons/)

# For Location Map Filters 

We've replaced [us-states.json](/localsite/info/data/map-filters/us-states.json) with the new CSV file called [us-states.csv](https://github.com/ModelEarth/localsite/tree/main/info/data/map-filters) for our [state navigation filters](#geoview=country).<!--
Not needed since we're pulling from GDC instead:
Copy population lookups [from this CoLab](https://colab.research.google.com/drive/1wmJ3V9eqD8KbmBiP-hLeSstwOUt5iS2V?usp=sharing) using python libraries.
-->

TO DO: Output countries.csv file with 2-char country codes and similar columns to [us-states.csv](https://github.com/ModelEarth/localsite/blob/main/info/data/map-filters/us-states.csv).  
Existing [country-populations.csv](https://github.com/ModelEarth/localsite/blob/main/info/data/map-filters/country-populations.csv) uses 3-char for our [country navigation filters](#geoview=countries). - Abhishek L


TO DO: Create a GitHub Action for our [State Filters CoLab](https://colab.research.google.com/drive/1CsIjLujiiBoGJlIHCBvDZit3QSVg07zR?usp=sharing).  
Run annually for both states and countries.
Document how to add a private Github token to push from CoLab.

<br>


# UN Goal Topics

Abhishek L, Pratyush, Jack  

Our [Google Sheet with Goal tabs](https://docs.google.com/spreadsheets/d/1IGyvcMV5wkGaIWM5dyB-vQIXXZFJUMV3WRf_UmyLkRk/edit?usp=sharing) for DCID values fed to our Python .csv file generation.

Goal .csv file output is initially in local notebooks, later in this [UN Goals CoLab](https://colab.research.google.com/drive/1riRnKUGNGkJZOU6qJoznAxjySInQjnFQ?usp=sharing).

Also add to our [Data Commons Timelines CoLab](https://colab.research.google.com/drive/1PF8wojIOHxDCdmadsAdkpHnb-An1ymEh?usp=sharing)

From the sheet columsn, display a clean navigation hierarchy with 3 levels:  
Goal (Air) > Topic (Emissions) > Subtopic (Methane)

<br>


## Previous: State Carbon Comparison

Data merged for [Carbon Cycle - State Comparison](/apps/carbon/#state=CA) within apps/js/bc.js

The original BeyondCarbon.org state comparison data seems to be removed from their site.

[BeyondCarbon.org](https://BeyondCarbon.org) data was originally pulled into [fused/result.json](https://model.earth/beyond-carbon-scraper/fused/result.json) by [beyond-carbon-scraper](https://github.com/modelearth/beyond-carbon-scraper/)

<br>
