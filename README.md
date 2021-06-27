# covid-19-au-vaccinations
DataViz of Australian COVID-19 Vaccinations

[Link to interactive DataViz](https://app.powerbi.com/view?r=eyJrIjoiNDI4ZWJjY2QtMjM3NC00NGQzLWJiMjQtOWYzNDczN2VjZWRkIiwidCI6ImRjMWYwNGY1LWMxZTUtNDQyOS1hODEyLTU3OTNiZTQ1YmY5ZCIsImMiOjEwfQ%3D%3D)

[![Click to view and interact with the report](https://github.com/Mike-Honey/covid-19-au-vaccinations/raw/main/covid-19-au-vaccinations%20AUS%20vs%20adult.png)](https://app.powerbi.com/view?r=eyJrIjoiNDI4ZWJjY2QtMjM3NC00NGQzLWJiMjQtOWYzNDczN2VjZWRkIiwidCI6ImRjMWYwNGY1LWMxZTUtNDQyOS1hODEyLTU3OTNiZTQ1YmY5ZCIsImMiOjEwfQ%3D%3D)

[![Click to view and interact with the report](https://github.com/Mike-Honey/covid-19-au-vaccinations/raw/main/covid-19-au-vaccinations%20AUS%20page.png)](https://app.powerbi.com/view?r=eyJrIjoiNDI4ZWJjY2QtMjM3NC00NGQzLWJiMjQtOWYzNDczN2VjZWRkIiwidCI6ImRjMWYwNGY1LWMxZTUtNDQyOS1hODEyLTU3OTNiZTQ1YmY5ZCIsImMiOjEwfQ%3D%3D)

[![Click to view and interact with the report](https://github.com/Mike-Honey/covid-19-au-vaccinations/raw/main/covid-19-au-vaccinations%20Daily%20page.png)](https://app.powerbi.com/view?r=eyJrIjoiNDI4ZWJjY2QtMjM3NC00NGQzLWJiMjQtOWYzNDczN2VjZWRkIiwidCI6ImRjMWYwNGY1LWMxZTUtNDQyOS1hODEyLTU3OTNiZTQ1YmY5ZCIsImMiOjEwfQ%3D%3D&pageName=ReportSection882ed22d8cd78465ae9a)


**Reference:**

Data on Australian Vaccinations from [covidlive.com.au](https://covidlive.com.au/report/vaccinations-people).  This is the source for Australian numbers presented in [Our World In Data](https://ourworldindata.org/). Unfortunately concise government sources are not available, so there is a significant citizen data science effort to collate these figures in a consistent way.

Data on Australian Population from [abs.gov.au](https://www.abs.gov.au/statistics/people/population/national-state-and-territory-population/sep-2020). Summarised population is unsuitable as their bands of age ranges do not align with the "Adult = 16+" definition used by Health Departments. So the method used is to get the most detailed time series spreadsheets, e.g. "Population - Victoria". Each column represents a single year age, by Gender.  The columns for "Persons" Gender are selected. "Adult" is derived by summing the columns for ages 16+ (note: split across 2 sheets). The latest row available (dated June 2020) is selected.

Following the visualisation design of [Marta Fioni](https://twitter.com/martafioni), as featured on the [UK government "equivalent" dashboard](https://coronavirus.data.gov.uk/) - we can dream...

**Summary**

This project seeks to boil down the many figures on vaccinations into an easily digested infographic. I've been looking for inspiration on this for quite a while - the key questions in my mind are:
- How many people are protected?
- How many to go?

The "waffle chart" visual chosen by Marta presents the vaccination data, standardised by the population of various Geographies.  Geographies of wildly differing populations (e.g. New South Wales vs Tasmania) can be easily compared.

The data is presented in an interactive data visualisation tool: [Power BI](https://powerbi.microsoft.com). This allows interactive filtering of the data (e.g. by Geography or Date), and includes supporting charts and data tables.  

The dataviz is refreshed automatically, roughly every 2 hours during the daytime (AEST GMT+10). 

I have similar projects running for other countries:
 - [World](https://github.com/Mike-Honey/covid-19-world-vaccinations#readme) (select country, countries, continents or global summary)
 - [New Zealand](https://github.com/Mike-Honey/covid-19-nz-vaccinations#readme) (select country, or Area/DHB)


THIS REPORT IS NOT HEALTH ADVICE - REFER TO YOUR LOCAL HEALTH AUTHORITY.

Note: Prior to 1 June 2021, the figure shown for % 1st dose (and the pale green boxes representing that figure) were overstated - I misunderstood the meaning of the total 1st dose count as excluding people who received a 2nd dose, when in fact they are included.
