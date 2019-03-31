# World-Food-Production
Comparing Top food and feed Producers around the globe and also seeking some interesting answers, solutions, patterns, hints and warnings through the power of Data Analysis and Data Visualization using Machine Learning.

# Description


# Context

Our world population is expected to grow from 7.3 billion today to 9.7 billion in the year 2050. Finding solutions for feeding the growing world population has become a hot topic for food and agriculture organizations, entrepreneurs and philanthropists. These solutions range from changing the way we grow our food to changing the way we eat. To make things harder, the world's climate is changing and it is both affecting and affected by the way we grow our food – agriculture. This dataset provides an insight on our worldwide food production - focusing on a comparison between food produced for human consumption and feed produced for animals.

# Content

The Food and Agriculture Organization of the United Nations provides free access to food and agriculture data for over 245 countries and territories, from the year 1961 to the most recent update (depends on the dataset). One dataset from the FAO's database is the Food Balance Sheets. It presents a comprehensive picture of the pattern of a country's food supply during a specified reference period, the last time an update was loaded to the FAO database was in 2013. The food balance sheet shows for each food item the sources of supply and its utilization. This chunk of the dataset is focused on two utilizations of each food item available:

Food - refers to the total amount of the food item available as human food during the reference period.
Feed - refers to the quantity of the food item available for feeding to the livestock and poultry during the reference period.
Acknowledgements
This dataset was meticulously gathered, organized and published by the Food and Agriculture Organization of the United Nations.

# Inspiration
Animal agriculture and factory farming is a a growing interest of the public and of world leaders.

Can you find interesting outliers in the data?
What are the fastest growing countries in terms of food production\consumption?
Compare between food and feed consumption.
Data (874 KB)

# About this file
The Food Balance sheet's data was relatively complete. A few countries that do not exist anymore, such as Czechoslovakia, were deleted from the database. Countries which were formed lately such as South Sudan were kept, even though they do not have all full data going back to 1961. In addition, data aggregation for the 7 different continents was available as well, but was not added to the dataset.

Food and feed production by country and food item from 1961 to 2013, including geocoding.
Y1961 - Y2011 are production years that show the amount of food item produced in 1000 tonnes

Note: The CSV file is Latin1-encoded. Read in the file using, e.g., fao = pd.read_csv("../input/fao.csv", encoding='latin1')

# Columns
Area AbbreviationCountry name abbreviation
Area CodeCountry code
AreaCountry name
Item CodeFood item code
ItemFood item
Element CodeFood or Feed code
ElementFood or Feed
UnitUnit of measurement
latitudelatitude
longitude 
