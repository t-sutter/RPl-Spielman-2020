
### 2008-2012 American Community Survey (5-year)

**Standard Metadata**

- `Abstract`: The 5-year ACS provides estimates surrounding demographic information in the USA. These estimates are more reliable than 1-year and 3-year estimates but less reliable than decennial census data. On the other hand, 5-year estimates are less current than 1-year and 3-year estimates because they represent measurements taken over 60 months. See the [census website](https://www.census.gov/programs-surveys/acs/guidance/estimates.html) for more details.
- `Spatial Coverage`: United States, excluding Puerto Rico
- `Spatial Resolution`: County and county-equivalents
- `Spatial Reference System`: None, just attribute data
- `Temporal Coverage`: 2008-2012
- `Temporal Resolution`: One-time observations
- `Lineage`: Original data downloaded from Social Explorer and then placed in the [original study's GitHub repository](https://github.com/geoss/sovi-validity). Reproduction data obtained directly from the census via API.
- `Distribution`: The reproduction data is distributed via a census API. See the detailed tables on the [census website](https://www.census.gov/data/developers/data-sets/acs-5year/2012.html) and instructions for drawing census data directly into python on the [pygris website](https://walker-data.com/pygris/). Spielman et al originally accessed the ACS data with Social Explorer from the following two tables.
  - http://www.socialexplorer.com/pub/reportdata/HtmlResults.aspx?reportid=R10728365
  - http://www.socialexplorer.com/pub/reportdata/HtmlResults.aspx?reportid=R10775556
- `Constraints`: Census data is available in the public domain
- `Data Quality`: Margin of error provided by the Census Bureau for relevant variables
- `Variables`:  

| Reproduction Label   | Spielman Label      | Alias                                                                         | Definition                                                                                                                                                                                                                         | Type    | Domain                 |   Missing Data Value(s) |   Missing Data Frequency |
|:---------------------|:--------------------|:------------------------------------------------------------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:--------|:-----------------------|------------------------:|-------------------------:|
| B01002_001E          | ACS12_5yr_B01002001 | median age                                                                    | MEDIAN AGE BY SEX: Estimate!!Median age!!Total                                                                                                                                                                                     | float64 | 21.7 - 63              |                     nan |                        0 |
| B03002_001E          | ACS12_5yr_B03002001 | total population of respondents to race/ethnicity                             | HISPANIC OR LATINO ORIGIN BY RACE: Estimate!!Total                                                                                                                                                                                 | int64   | 66 - 9840024           |                     nan |                        0 |
| B03002_004E          | ACS12_5yr_B03002004 | total Black population                                                        | HISPANIC OR LATINO ORIGIN BY RACE: Estimate!!Total!!Not Hispanic or Latino!!Black or African American alone                                                                                                                        | int64   | 0 - 1267825            |                     nan |                        0 |
| B03002_005E          | ACS12_5yr_B03002005 | total Native American population                                              | HISPANIC OR LATINO ORIGIN BY RACE: Estimate!!Total!!Not Hispanic or Latino!!American Indian and Alaska Native alone                                                                                                                | int64   | 0 - 59060              |                     nan |                        0 |
| B03002_006E          | ACS12_5yr_B03002006 | total Asian population                                                        | HISPANIC OR LATINO ORIGIN BY RACE: Estimate!!Total!!Not Hispanic or Latino!!Asian alone                                                                                                                                            | int64   | 0 - 1343920            |                     nan |                        0 |
| B03002_012E          | ACS12_5yr_B03002012 | total Latinx population                                                       | HISPANIC OR LATINO ORIGIN BY RACE: Estimate!!Total!!Hispanic or Latino                                                                                                                                                             | int64   | 0 - 4694846            |                     nan |                        0 |
| B06001_002E          | ACS12_5yr_B06001002 | total population under 5 years of age                                         | PLACE OF BIRTH BY AGE IN THE UNITED STATES: Estimate!!Total!!Under 5 years                                                                                                                                                         | float64 | 0 - 651662             |                     nan |                        0 |
| B09020_001E          | ACS12_5yr_B09020001 | total population over 65 years of age                                         | RELATIONSHIP BY HOUSEHOLD TYPE (INCLUDING LIVING ALONE) FOR THE POPULATION 65 YEARS AND OVER: Estimate!!Total                                                                                                                      | int64   | 5 - 1078555            |                     nan |                        0 |
| B01003_001E          | ACS12_5yr_B01003001 | total population                                                              | TOTAL POPULATION: Estimate!!Total                                                                                                                                                                                                  | int64   | 66 - 9840024           |                     nan |                        0 |
| B25008_001E          | ACS12_5yr_B25008001 | total population in occupied housing units                                    | TOTAL POPULATION IN OCCUPIED HOUSING UNITS BY TENURE: Estimate!!Total                                                                                                                                                              | int64   | 62 - 9664175           |                     nan |                        0 |
| B25002_002E          | ACS12_5yr_B25002002 | total occupied housing units                                                  | OCCUPANCY STATUS: Estimate!!Total!!Occupied                                                                                                                                                                                        | int64   | 35 - 3218511           |                     nan |                        0 |
| B25003_003E          | ACS12_5yr_B25003003 | total renter occupied housing units                                           | TENURE: Estimate!!Total!!Renter occupied                                                                                                                                                                                           | int64   | 14 - 1695180           |                     nan |                        0 |
| B25002_001E          | ACS12_5yr_B25002001 | total housing units for which occupancy status is known                       | OCCUPANCY STATUS: Estimate!!Total                                                                                                                                                                                                  | int64   | 70 - 3441416           |                     nan |                        0 |
| B09020_021E          | ACS12_5yr_B09020021 | total 65+ living in group quarters                                            | RELATIONSHIP BY HOUSEHOLD TYPE (INCLUDING LIVING ALONE) FOR THE POPULATION 65 YEARS AND OVER: Estimate!!Total!!In group quarters                                                                                                   | int64   | 0 - 37611              |                     nan |                        0 |
| B01001_026E          | ACS12_5yr_B01001026 | total female population                                                       | SEX BY AGE: Estimate!!Total!!Female                                                                                                                                                                                                | int64   | 20 - 4987765           |                     nan |                        0 |
| B11001_006E          | ACS12_5yr_B11001006 | total female-headed family households                                         | HOUSEHOLD TYPE (INCLUDING LIVING ALONE): Estimate!!Total!!Family households!!Other family!!Female householder, no husband present                                                                                                  | int64   | 0 - 498851             |                     nan |                        0 |
| B11001_001E          | ACS12_5yr_B11001001 | total households for which household type is known                            | HOUSEHOLD TYPE (INCLUDING LIVING ALONE): Estimate!!Total                                                                                                                                                                           | int64   | 35 - 3218511           |                     nan |                        0 |
| B25002_003E          | ACS12_5yr_B25002003 | total vacant housing units                                                    | OCCUPANCY STATUS: Estimate!!Total!!Vacant                                                                                                                                                                                          | int64   | 35 - 245069            |                     nan |                        0 |
| B19025_001E          | ACS12_5yr_B19025001 | aggregate household income                                                    | AGGREGATE HOUSEHOLD INCOME IN THE PAST 12 MONTHS (IN 2012 INFLATION-ADJUSTED DOLLARS): Estimate!!Aggregate household income in the past 12 months (in 2012 inflation-adjusted dollars)                                             | int64   | 1785600 - 263044380000 |                     nan |                        0 |
| B23022_025E          | ACS12_5yr_B23022025 | total males unemployed for last 12 months                                     | SEX BY WORK STATUS IN THE PAST 12 MONTHS BY USUAL HOURS WORKED PER WEEK IN THE PAST 12 MONTHS BY WEEKS WORKED IN THE PAST 12 MONTHS FOR THE POPULATION 16 TO 64 YEARS: Estimate!!Total!!Male!!Did not work in the past 12 months   | int64   | 1 - 726803             |                     nan |                        0 |
| B23022_049E          | ACS12_5yr_B23022049 | total females unemployed for last 12 months                                   | SEX BY WORK STATUS IN THE PAST 12 MONTHS BY USUAL HOURS WORKED PER WEEK IN THE PAST 12 MONTHS BY WEEKS WORKED IN THE PAST 12 MONTHS FOR THE POPULATION 16 TO 64 YEARS: Estimate!!Total!!Female!!Did not work in the past 12 months | int64   | 0 - 1131737            |                     nan |                        0 |
| B23022_001E          | ACS12_5yr_B23022001 | total population for which unemployment and sex cross-tabulations known       | SEX BY WORK STATUS IN THE PAST 12 MONTHS BY USUAL HOURS WORKED PER WEEK IN THE PAST 12 MONTHS BY WEEKS WORKED IN THE PAST 12 MONTHS FOR THE POPULATION 16 TO 64 YEARS: Estimate!!Total                                             | int64   | 45 - 6658456           |                     nan |                        0 |
| B17021_002E          | ACS12_5yr_B17021002 | total population below poverty level                                          | POVERTY STATUS OF INDIVIDUALS IN THE PAST 12 MONTHS BY LIVING ARRANGEMENT: Estimate!!Total!!Income in the past 12 months below poverty level                                                                                       | int64   | 0 - 1658231            |                     nan |                        0 |
| B17021_001E          | ACS12_5yr_B17021001 | total population for which poverty information available                      | POVERTY STATUS OF INDIVIDUALS IN THE PAST 12 MONTHS BY LIVING ARRANGEMENT: Estimate!!Total                                                                                                                                         | int64   | 64 - 9684503           |                     nan |                        0 |
| B25024_010E          | ACS12_5yr_B25024010 | number of mobile home housing units in structure                              | UNITS IN STRUCTURE: Estimate!!Total!!Mobile home                                                                                                                                                                                   | int64   | 0 - 85377              |                     nan |                        0 |
| B25024_001E          | ACS12_5yr_B25024001 | total housing units in structure                                              | UNITS IN STRUCTURE: Estimate!!Total                                                                                                                                                                                                | int64   | 70 - 3441416           |                     nan |                        0 |
| C24010_038E          | ACS12_5yr_C24010038 | total female employed                                                         | SEX BY OCCUPATION FOR THE CIVILIAN EMPLOYED POPULATION 16 YEARS AND OVER: Estimate!!Total!!Female                                                                                                                                  | int64   | 12 - 2056023           |                     nan |                        0 |
| C24010_001E          | ACS12_5yr_C24010001 | total population for which sex and occupation known                           | SEX BY OCCUPATION FOR THE CIVILIAN EMPLOYED POPULATION 16 YEARS AND OVER: Estimate!!Total                                                                                                                                          | int64   | 54 - 4495118           |                     nan |                        0 |
| B19055_002E          | ACS12_5yr_B19055002 | total households with social security income                                  | SOCIAL SECURITY INCOME IN THE PAST 12 MONTHS FOR HOUSEHOLDS: Estimate!!Total!!With Social Security income                                                                                                                          | int64   | 9 - 726298             |                     nan |                        0 |
| B19055_001E          | ACS12_5yr_B19055001 | total households for which social security income status known                | SOCIAL SECURITY INCOME IN THE PAST 12 MONTHS FOR HOUSEHOLDS: Estimate!!Total                                                                                                                                                       | int64   | 35 - 3218511           |                     nan |                        0 |
| B09002_002E          | ACS12_5yr_B09002002 | total children in married couple families                                     | OWN CHILDREN UNDER 18 YEARS BY FAMILY TYPE AND AGE: Estimate!!Total!!In married-couple families                                                                                                                                    | int64   | 0 - 1380977            |                     nan |                        0 |
| B09002_001E          | ACS12_5yr_B09002001 | total children for which family type and age are known                        | OWN CHILDREN UNDER 18 YEARS BY FAMILY TYPE AND AGE: Estimate!!Total                                                                                                                                                                | int64   | 0 - 2032147            |                     nan |                        0 |
| B19001_017E          | ACS12_5yr_B19001017 | total households with over 200k income                                        | HOUSEHOLD INCOME IN THE PAST 12 MONTHS (IN 2012 INFLATION-ADJUSTED DOLLARS): Estimate!!Total!!$200,000 or more                                                                                                                     | int64   | 0 - 208954             |                     nan |                        0 |
| B06007_005E          | ACS12_5yr_B06007005 | total Spanish-speakers who speak english less than very well                  | PLACE OF BIRTH BY LANGUAGE SPOKEN AT HOME AND ABILITY TO SPEAK ENGLISH IN THE UNITED STATES: Estimate!!Total!!Speak Spanish!!Speak English less than "very well"                                                                   | float64 | 0 - 1695391            |                     nan |                        0 |
| B06007_008E          | ACS12_5yr_B06007008 | total people who speak another language and speak English less than very well | PLACE OF BIRTH BY LANGUAGE SPOKEN AT HOME AND ABILITY TO SPEAK ENGLISH IN THE UNITED STATES: Estimate!!Total!!Speak other languages!!Speak English less than "very well"                                                           | float64 | 0 - 743418             |                     nan |                        0 |
| B06007_001E          | ACS12_5yr_B06007001 | total population with known language spoken at home and English ability       | PLACE OF BIRTH BY LANGUAGE SPOKEN AT HOME AND ABILITY TO SPEAK ENGLISH IN THE UNITED STATES: Estimate!!Total                                                                                                                       | float64 | 66 - 9188362           |                     nan |                        0 |
| B16010_002E          | ACS12_5yr_B16010002 | total population with less than a high school graduate education              | EDUCATIONAL ATTAINMENT AND EMPLOYMENT STATUS BY LANGUAGE SPOKEN AT HOME FOR THE POPULATION 25 YEARS AND OVER: Estimate!!Total!!Less than high school graduate                                                                      | int64   | 5 - 1508273            |                     nan |                        0 |
| B16010_001E          | ACS12_5yr_B16010001 | total for which education, employment, language at home known                 | EDUCATIONAL ATTAINMENT AND EMPLOYMENT STATUS BY LANGUAGE SPOKEN AT HOME FOR THE POPULATION 25 YEARS AND OVER: Estimate!!Total                                                                                                      | int64   | 65 - 6380366           |                     nan |                        0 |
| C24050_002E          | ACS12_5yr_C24050002 | total population in extractive industries                                     | INDUSTRY BY OCCUPATION FOR THE CIVILIAN EMPLOYED POPULATION 16 YEARS AND OVER: Estimate!!Total!!Agriculture, forestry, fishing and hunting, and mining                                                                             | int64   | 0 - 54942              |                     nan |                        0 |
| C24050_001E          | ACS12_5yr_C24050001 | total population for which industry known                                     | INDUSTRY BY OCCUPATION FOR THE CIVILIAN EMPLOYED POPULATION 16 YEARS AND OVER: Estimate!!Total                                                                                                                                     | int64   | 54 - 4495118           |                     nan |                        0 |
| C24050_029E          | ACS12_5yr_C24050029 | total people in service occupations                                           | INDUSTRY BY OCCUPATION FOR THE CIVILIAN EMPLOYED POPULATION 16 YEARS AND OVER: Estimate!!Total!!Service occupations                                                                                                                | int64   | 4 - 837607             |                     nan |                        0 |
| B08201_002E          | ACS12_5yr_B08201002 | total households with no available vehicle                                    | HOUSEHOLD SIZE BY VEHICLES AVAILABLE: Estimate!!Total!!No vehicle available                                                                                                                                                        | int64   | 0 - 577967             |                     nan |                        0 |
| B08201_001E          | ACS12_5yr_B08201001 | total households for which vehicle status and family size known               | HOUSEHOLD SIZE BY VEHICLES AVAILABLE: Estimate!!Total                                                                                                                                                                              | int64   | 35 - 3218511           |                     nan |                        0 |
| B25064_001E          | ACS12_5yr_B25064001 | median gross rent                                                             | MEDIAN GROSS RENT (DOLLARS): Estimate!!Median gross rent                                                                                                                                                                           | int64   | 296 - 1678             |                     nan |                        0 |
| B25077_001E          | ACS12_5yr_B25077001 | median home value                                                             | MEDIAN VALUE (DOLLARS): Estimate!!Median value (dollars)                                                                                                                                                                           | float64 | 19400 - 944100         |                     nan |                        1 |
| GEOID | Geo_FIPS | FIPS code unique identifier | Unique code for every county and county-equivalent in USA | string | 01001 - 56045 | None | 0 |