# Energy Storage Research

Postgis database: holds Michaelangelo's forecast_io data
 - Separate daily, hourly data

Zip codes: Arbitrary size, but roughly right scale. CA total: 2,590

Census tracts: May be more relevant for us. CA total: 8,057 (2010)

Census block groups: Intermediate. CA total: 23,212 (2010)

Census blocks: Super fine, not of interest. CA total: 710,145 (2010)

[Socialexplorer.com] - good source of demographic data.  Want to download the following data:
  - SE:T2. Population Density
  - SE:T3. Total land area
  - SE:T33. Employment Status for total population 16 and over - want %
  - SE:T49. Industry by Occupation - want %
  - SE:T155. Mean Household income of quintiles 
  - SE:T99. House Heating Fuel  - want electricity

Less useful:
  - SE:T57. Median household income
  - SE:T59. Average household income
  - SE:T56. Household income (breaks into fine-grained chunks) - want %

Outputs large TSV with many empty columns (depending on selections)

Would be useful:
  - Census statistical abstract tables 988-990 (Housing Unit Attributes)
  - Housing attribute data available at Geography library in McCone
  - FEMA HAZUS Database - need to pick up CD of shapefiles

--
[Socialexplorer.com]: http://www.socialexplorer.com
