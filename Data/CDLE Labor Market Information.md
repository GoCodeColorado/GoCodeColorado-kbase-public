![gcc_logo_2020](https://github.com/GoCodeColorado/GoCodeColorado-kbase-public/blob/master/Images/GC20_Logo_Condensed_transp%20-%20Copy.png)
![cdle_logo](https://github.com/GoCodeColorado/GoCodeColorado-kbase-public/blob/master/Data/images/cdle_logo.jpg)
# CDLE Resources - Labor Market Information Data

**Last Updated:** 01/17/2020

The Colorado Department of Labor &amp; Employment (CDLE) connects job seekers with great jobs; provides an up-to-date and accurate picture of the economy to help decision making; assists workers who have been injured on the job; ensures fair labor practices; helps those who have lost their jobs by providing temporary wage replacement through unemployment benefits; and protects the workplace - and Colorado communities - with a variety of consumer protection and safety programs. Find us at [https://www.colorado.gov/cdle](https://www.colorado.gov/cdle).



## Labor Market Information

The CDLE&#39;s office of [Labor Market Information](https://www.colmigateway.com/vosnet/lmi/default.aspx?pu=1&amp;amp;plang=E) produces data on the labor market in Colorado. Datasets from the LMI that are on CIM include:

- [Unemployment Estimates in Colorado](https://data.colorado.gov/Labor-Employment/Unemployment-Estimates-in-Colorado/4e3w-qire)
  - Number of individuals employed, unemployed, and unemployment rates by period by county
- [Employee Counts by Industry in Colorado](https://data.colorado.gov/Labor-Employment/Employee-Counts-by-Industry-in-Colorado/cjkq-q9ih)
  - Average employees employed by industry by year and quarter
- [Hours Worked by Employees in Colorado](https://data.colorado.gov/Labor-Employment/Hours-Worked-by-Employees-in-Colorado/pt2g-89wc)
  - Number of people employed by year by industry and region
- [Long-Term Employment Projections in Colorado](https://data.colorado.gov/Labor-Employment/Long-Term-Employment-Projections-in-Colorado/gyeb-jc69)
  - Ten-year Industry/Occupation estimates and projections by area in Colorado
- [Short-Term Employment Projections in Colorado](https://data.colorado.gov/Labor-Employment/Short-Term-Employment-Projections-in-Colorado/u2t6-bfhr)
  - Two-year Industry/Occupation estimates and projections by area in Colorado
- [Personal Income in Colorado](https://data.colorado.gov/Labor-Employment/Personal-Income-in-Colorado/2cpa-vbur)
  - Median household income in the United States by year
- [Employment Wages in Colorado](https://data.colorado.gov/Labor-Employment/Employment-Wages-in-Colorado/busm-qa5b)
  - Average wage by occupation by year by region

All of the above datasets come from the same database, and therefore are joinable. This can produce many interesting data combinations. These datasets are updated monthly.

## Field Descriptions

The field descriptions for these datasets can be found towards the bottom of the page under the 'Columns in this Dataset' section. Be sure to check out the [field descriptions csv](./Field_Descriptions/CIM_FieldDescriptions.csv) on GitHub. This file contains a comprehensive list of all field descriptions for datasets on CIM that have been published for the purpose of GoCode. These datasets can be viewed by selecting 'Tags' on [gocodecolorado](https://data.colorado.gov/browse?tags=gocodecolorado).



## LMI Metadata and Data Sources

These datasets utilize the North American Industry Classification System ([NAICS](https://www.census.gov/eos/www/naics/)). The NAICS is the standard used by Federal statistical agencies in classifying business establishments for the purpose of collecting, analyzing, and publishing statistical data related to the U.S. business economy. The CDLE has its own program that assigns NAICS codes. This program calls employers in the state to verify the data. The CDLE also utilizes the below sources to create their datasets/databases. Reference the [PowerBI doc](https://github.com/GoCodeColorado/GoCodeColorado-kbase-public/blob/master/Resources_for_Participants/Tech/PowerBI_GoCodeColorado.pdf) on GitHub to see an example of working with LMI data.

![cdle_powerBI](https://github.com/GoCodeColorado/GoCodeColorado-kbase-public/blob/master/Data/images/cdle_powerBI.jpg)

The [QCEW](https://www.bls.gov/cew/) program publishes a quarterly count of employment and wages reported by employers covering more than 95 percent of U.S. jobs, available at the county, MSA, state and national levels by industry.

## Survey of Households

There is a monthly household survey that is based on work statuses reported by employees. This is used to estimate the Colorado unemployment rate. Work status reported by employees is compared to payroll info from [QCEW](https://www.bls.gov/cew/) to produce an estimate of non-covered payroll jobs and an estimate of multiple job holders in the state. The CDLE utilizes QCEW data to supplement their estimate of non-payroll and unpaid workers to capture the entire spectrum of employed workers, multiple job holders, and unemployed citizens.

## Occupational Employment Statistics (OES) Survey

The [OES](https://www.bls.gov/oes/) produces employment and wage estimates annually for over 800 occupations. Data gathered from their survey includes the number of people in an industry, wage ranges, and staffing patterns.

## Tying it All Together

Each of the above datasets is related to the other in that they are exported from the same database. This means they that many can be joined on id or coded columns. For example, the &quot;areaname&quot; column is used in many of the table on CIM provided by the CDLE + LMI. If something seems odd when working with the data, reach out to the #data channel - the data is challenging to work with, but can provide good info following some cleaning and research. Don&#39;t be discouraged!
