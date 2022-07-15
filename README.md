# Carbon free energy for Google Cloud regions 

This repository contains sustainability characteristics of Google Cloud regions in a machine readable format. Read more [on the Google Cloud website](https://cloud.google.com/sustainability/region-carbon).

## Data

* **[2019](data/yearly/2019.csv)**
* **[2020](data/yearly/2020.csv)**
* **[2021](data/yearly/2021.csv)**

## Understanding the data

**Google CFE**: This is the average percentage of carbon free energy consumed in a particular location on an hourly basis, while taking into account the investments we have made in renewable energy in that location. This means that in addition to the carbon free energy that’s already supplied by the grid, we have added renewable energy generation in that location to reach [our 24/7 carbon free energy objective](https://www.gstatic.com/gumdrop/sustainability/247-carbon-free-energy.pdf). As a customer, this represents the average percentage of time your application will be running on carbon-free energy.

**Grid carbon intensity (gCO2eq/kWh)**: This metric indicates the average operational gross emissions per unit of energy from the grid. This metric should be used to compare the regions in terms of carbon intensity of their electricity from the local grid. For regions that are similar in CFE%, this will indicate the relative emissions for when your workload is not running on carbon free energy. As an example, Frankfurt and the Netherlands have similar CFE scores, but the Netherlands has a higher emissions factor.

**Google Cloud net carbon emissions (Scope 2 market-based)**: Google invests in enough renewable energy and carbon offsets to neutralize the global operational carbon emissions footprint of Google Cloud per the GHG protocol under the Scope 2 market-based methodology.
