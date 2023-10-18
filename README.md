# Project1

A data collection and analysis project for I310D class. 
The goal is to sucessfully webscrape a table of choice and transform the data into a cleaned csv file. 
I chose the data from https://dnd-5e.fandom.com/wiki/Gods , an unofficial wiki page for the tabletop roleplaying game Dungeons & Dragons. 

The license for the code written is the MIT License. https://mit-license.org/
The data is owned by Wizards of the Coast and all the material produced by this code is unofficial fan-content that is free to use to abide by the Fan Content Policy: https://company.wizards.com/en/legal/fancontentpolicy

The data types and description for the attributes in the data are below:
deity - string - Shows the name of the deity.
alignment - string - Shows the alignment of the deity.
domains - string - Shows the domain the deity rules over.
symbol - string - Shows the symbol that the deity uses.

The libraries used for this project along with their API is also listed below:
- BeautifulSoup - For pulling data out of HTML files - https://beautiful-soup-4.readthedocs.io/en/latest/
- Requests - HTTP request simplification - https://docs.python-requests.org/en/latest/_modules/requests/api/
- Pandas - Visualization and transformation of data - https://pandas.pydata.org/pandas-docs/stable/reference/index.html
- Copy - For copying the rows into the dataframe - https://docs.python.org/3/library/copy.html
- Numpy - Plotting data - https://numpy.org/doc/stable/reference/
- Scipy - Plotting data - https://docs.scipy.org/doc/scipy/reference/
- Matplotlib - Plotting data - https://matplotlib.org/stable/api/index.html

CSV format of cleaned data is available for download here:
https://data.world/uthosoyaa/dnd-5e-gods-csv


Limitations:
Due to the nature of the way that the values were written in the original data, I would probably get different results if I were to actually separate the domains of gods into separate categories (IE: "War, Tempest" vs "War", "Tempest". 
Aside from this there concerns with the limitation in the data collected is that the wiki is not up to date with the current D&D 5e canon. 
