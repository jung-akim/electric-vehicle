### Data

1. Data is pulled from catalog.data.gov https://data.wa.gov/Transportation/Electric-Vehicle-Population-Data/f6w7-q2d2/about_data which is Washington state data
2. Data with the list of tax exemptions is from https://data.wa.gov/Transportation/WA-Tax-Exemptions-Potential-Eligibility-by-Make-Mo/aug9-4a7g/about_data
2. Data size is (194232, 17) with columns as 

 'VIN (1-10)',
 'County',
 'City',
 'State',
 'Postal Code',
 'Model Year',
 'Make',
 'Model',
 'Electric Vehicle Type',
 'Clean Alternative Fuel Vehicle (CAFV) Eligibility',
 'Electric Range',
 'Base MSRP',
 'Legislative District',
 'DOL Vehicle ID',
 'Vehicle Location',
 'Electric Utility',
 '2020 Census Tract'
 

### EDA

1. CAFV Eligibility difference between Battery Electric Vehicle (BEV) and Plug-in Hybrid Electric Vehicle (PHEV)

- BEV is 99.99% CAFV eligible excluding for the older models before 2020 while PHEV is only 50% CAFV eligible.
    - Can we find the difference between the three groups here:
        - BEV, PHEV CAFV eligible, and PHEV Not CAFV eligible