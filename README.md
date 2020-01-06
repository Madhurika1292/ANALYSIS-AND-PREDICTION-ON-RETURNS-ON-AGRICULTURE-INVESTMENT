# ANALYSIS-AND-PREDICTION-ON-RETURNS-ON-AGRICULTURE-INVESTMENT

##Background –
• The Global Financial Development Database is an extensive dataset of financial system characteristics for 214 economies.
• The World Development Indicators dataset presents the most current and accurate global development data, and includes national, regional and global estimates.
• The Statistics Division of Food and Agriculture Organization of the United Nations collects annually data on Government Expenditure on Agriculture through a questionnaire, which was developed in partnership with the International Monetary Fund.

##Data Source-
• Global Financial Development dataset- This data set is downloaded from https://datacatalog.worldbank.org/dataset/global-financial-development . This data contains financial report of 203 economies from 1960 to 2017 The database includes measures of:
Size of financial institutions and markets (financial depth)
Degree to which individuals can and do use financial services (access)
Efficiency of financial intermediaries and markets in intermediating resources and facilitating financial transactions (efficiency)
Stability of financial institutions and markets (stability). CSV files 
GFDDCountry.csv
GFDDCountry-Series.csv
GFDDData.csv (around 25000 rows and around 60 column)
GFDDFootNote.csv
GFDDSeries.csv
• World Development Indicators dataset- This data set is downloaded from https://datacatalog.worldbank.org/dataset/world-development-indicators .
The primary World Bank collection of development indicators compiled from officially-recognized international sources. It presents the most current and accurate global development data available, and includes national, regional and global estimates.
This data contains financial report of 217 economies from 1960 to 2019.
The database includes measures of- Agriculture and Food Security, Climate Change, Economic Growth, Education, Energy and Extractives, Environment and Natural Resources, Financial Sector Development, Gender, Health, Nutrition and Population, etc.
CSV files
WDICountry.csv
WDICountry-Series.csv
WDICountry-Series.csv
WDIFootNote.csv
WDISeries.csv
WDISeries-Time.csv
• Government Expenditure dataset- This data set is downloaded from http://www.fao.org/faostat/en/#data/IG/metadata .
The Statistics Division of FAO collects annually data on Government Expenditure on Agriculture through a questionnaire, which was developed in partnership with the International Monetary Fund. The IMF is the responsible institution for the Government Finance Statistics (GFS) methodology and annually collects GFS data, including Expenditure by Functions of Government (COFOG). The Classification of the Functions of Government (COFOG) is an international classification developed by Organization for Economic Co-operation and Development (OECD) and published by the United Nations Statistical Division (UNSD), with the aim of categories governments' functions according to their purposes.
Time coverage - 2001-2018 Columns – 11 Rows- around 60,000

##Analysis goals-
How much government has invested in agriculture through years and did agriculture sector had made progress using that investment in all over the world?
Top 3 countries that has highest investment on agriculture and their returns?
Top 3 countries that has highest returns on agriculture sector and in which year?
How much contribution (in percentage) does agriculture and forestry takes place in Gross National Income of the country.
Here, for above analysis, i am creating a function main() that takes years for analysis and coutries list as input from user and all the analysis will be carried out in pdf format in results.pdf file for future references

##Machine learning models for predictions on-
Hypothesis 1- Does agriculture play important contribution to Gross National Income for that country on that year. (Predictions will be Yes/No).
Hypothesis 2 -Are the government’s investments in the agriculture and forestry sector profitable or not. (Prediction will be Yes/No)
