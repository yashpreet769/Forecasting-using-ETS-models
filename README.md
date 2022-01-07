# Forecasting using ETS models


You have been hired by a company in the hospitality business to help them plan the staffing levels for the following year.  The company operates resorts in three regions of the New South Wales of Australia; the three regions are the **Sydney**, the **South Coast** and the **North Coast NSW** areas.

As it takes time to hire new personnel and it is necessary for any new employee to undergo a detailed training program before starting to work, the company needs to plan its personnel requirements one year in advance.  Furthermore, as it is possible for the company to transfer qualified personnel between regions, they are interested only in an aggregate forecast of their demand 

As the company caters to **Holiday** travelers, and it has been growing faster than the market (i.e., it has been gaining market share), the Chief Commercial Officer estimates that next year they will have respectively (3%, 4%, 4%) of only the **Holiday** travelers in the (**Sydney**, **South Coast**, and **North Coast NSW**) regions respectively.  Furthermore based on prior experience they anticipate that each traveler will stay respectively (5,2,2) hotel-nights in (**Sydney**, **South Coast**, and **North Coast NSW**) respectively

To forecast demand in hotel-nights use the **tourism** data set in **fpp3**.  This data set reports the quarterly trips (in thousands) to different destinations, and as this data set has a *tsibble* structure, you can use **tidyverse** functions to subset the time-series of interest.  

For the purposes of this assignment ignore all data before **2008 Q1** and use the data from **2008 Q1** through **2016 Q4** as a traing set and the four quarters of **2017** as a testing set.
