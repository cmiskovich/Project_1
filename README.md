# Project_1
# Primary application file

Produce a Jupyter lab notebook that shows pricing between Washington, DC, Silver Spring, MD, and Takoma Park.  
.



---

## Technologies

The following Technologies were used to develop this program:

Python 
    Version 3.9.7

Terminal
    Version 2.12.5 (444)

Visual Studio Code
    Version: 1.66.2 (Universal)
    Commit: dfd34e8260c270da74b5c2d86d61aee4b6d56977
    Date: 2022-04-11T07:49:20.994Z
    Electron: 17.2.0
    Chromium: 98.0.4758.109
    Node.js: 16.13.0
    V8: 9.8.177.11-electron.0
    OS: Darwin x64 21.4.0
    
Jupyter Lab 
    Version 3.2.9
    
Git version 2.24.0.windows.2

FRED economic data - St. Louis Federal Reserve

Zillow web services

---

## General information about analysis.

Goiong through the project we realized it was not easy to find real estate data in large quanitites.  Success was finally finding an API that could give us the data we need after trial and error which cost the team a lot of time in obtaining data. We narrowed down the data to the 

---

## Information about datasets

Functions to reuse in searches:

    search_str_list:
    
        states
        
        county
        
        zip code
        
Load env environment variables into notebook:

env_path

load_dotenv


Get API key from environment variable:

quandl_api_key

Create indicators in a dataset:

df_ind

Create dataset by region:

df_regions

Normalize regions data:

df_regions_zip

Normalize request using json:

df

Select Region:

_states

Filter data by state:

df_state

Filter on region:

df_filter

Median home price:

df_region_price

Merge price and rent tables:

_df_merge

Merger price and rent with region detail:

df_merge

Dataframe consisting of the city PRR, lat and long columns:

df_plot

Plot the data using geoviews:

map_plot

Zip codes to avoid:

zip_codes_to_avoid

df_new_merge

Dataframe with historical housing prices in Washington, DC, Silver Spring, MD, and Takoma Park, MD:

df_housing


       

---

## Libraries used in analysis

pandas

os

json

requests

dotenv

matplotlib

Path

numpy

quandl

pgeocode

re

hvplot

plotly

nomi




---

## Contributors


**Chris Miskovich**

Contact Information:

Email: cmiskovich@verizon.net

[LinkedIn](https://www.linkedin.com/in/christopher-miskovich-9a61b0234/) 

---

**Daniel Watson**

Contact information: 

Email: watsondaniel1984@gmail.com

[LinkedIn](https://www.linkedin.com/in/daniel-watson-87819a20/)

---
**Santiago Pesantez**

Contact information: 

Email: pesantez.santiago.i@gmail.com

[LinkedIn](https://www.linkedin.com/in/santiago-pesantez/)

---
**KaBria Broadwater**

Contact Information:

Email: KaBria.Broadwater@gmail.com

[LinkedIn](https://www.linkedin.com/in/kabriabroadwater/)

## License

[MIT](/license.txt)
