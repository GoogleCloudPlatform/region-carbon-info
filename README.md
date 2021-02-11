# Carbon free energy for Google Cloud regions 

Read about Google Cloud sustainability efforts at https://cloud.google.com/sustainability

This repository contains carbon characteristics of Google Cloud regions in a machine readable format.

**[Open latest data](data/yearly/2019.csv).**

## Understanding the data

* **Google CFE%**: This is the percentage of carbon free energy consumed in a particular location on an hourly basis, while taking into account the investments we have made in renewable energy in that location. This means that in addition to the carbon free energy that’s already supplied by the grid, we have added renewable energy generation in that location to get closer to increase the renewable energy available to power our operations and reach our 24/7 carbon free energy objective. As a customer, this represents the average percentage of time your application will be running on carbon-free energy.

* **Carbon intensity gCO2eq/kWh**: This metric indicates the average gross emissions per unit of energy from the grid, which does not incorporate Google’s purchase of carbon free energy and carbon offsets. This metric can be used to understand the relative emissions factors for each region, particularly in the cases where there is not yet sufficient data to calculate Google’s CFE score. For regions that are similar in CFE%, this will indicate the relative emissions for when your workload is not running on carbon free energy. As an example, Frankfurt and the Netherlands have similar CFE scores, but the Netherlands has a higher emissions factor.  

* **Google gCO2eq after offsets**: Google invests in enough renewable energy and carbon offsets to neutralize the global operational carbon emissions footprint of Google Cloud. 