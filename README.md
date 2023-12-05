# Nightlight Analysis of factories 

## EarthEngine Code link

A major milestone in the project was achieved by the following [https://code.earthengine.google.com/a1a789c5f867d2d0f640d2714d0d4a92](https://code.earthengine.google.com/a1a789c5f867d2d0f640d2714d0d4a92).

## Objective 

There is evidence consistent with managers manipulating real activities to avoid reporting annual losses. Specifically, evidence suggesting price discounts to temporarily increase sales, **overproduction** to report lower cost of goods sold, and reduction of discretionary expenditures to improve reported margins. To understand how global firm networks operate, we need consistent information on their activities, unbiased by their reporting choices. We collect a novel dataset on the light that factories emit at night for a large sample of car manufacturing plants. We show that nightlight data can measure activity at such a granular level. We use this data to quantify the misreported data for various firms with focus on overproduction as a means of Real Earnings Management (REM).

## Execution

### VIIRS Dataset

Remote sensing of nighttime light emissions offers a unique perspective for investigations into some of these human behaviors. The Visible Infrared Imaging Radiometer Suite (VIIRS) instruments aboard the joint NASA/NOAA Suomi National Polar-orbiting Partnership (Suomi NPP) and NOAA-20 satellites provide global daily measurements of nocturnal visible and near-infrared (NIR) light that are suitable for Earth system science and applications studies. VIIRS Day/Night Band (DNB) data are used for estimating population, assessing electrification of remote areas, monitoring disasters and conflict, and understanding biological impacts of increased light pollution. 

### EPA Dataset

The VIIRS provides information on imaginary "tiles" on earth which can be approximated by a lattitude and longitude. To analyse a factor, one needs a geomarker to identify the tiles corresponding to a factory location. The Environmental Protection Agency (EPA) in the USA keeps of records of firms in the country in regards to their impact on the environment. It is an elaborate data that consists od the latitude and longitude information of each firm.

### Accounting Data

The nightlight data of factory is correlated to the accounting data of various firms. The tuning of the regression in process.

## Impact

It would help identify firms that have been misreporting their data and also make for a useful tool for investors in the upcoming years.

_Note: Since Kaggle provides a cloud for storing the data and has a great IDE, it is being used as a primary platform to work on_
