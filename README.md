# Final-Project-Statistical-Modelling-with-Python

## Project/Goals

- Use various APIs to access data under a variety of parameters,
- Use Python Pandas to clean and transform the collected data,
- Use Python Pandas to generate a database from this data,
- Performed EDA techniques to visualize and analyze statistical value,
- Applied statistical models to attempt to identify dependant variables and the independent variables capable of demonstrating influences on them.
- And interpreting the results of the performed statistical models and visualizations.

## Process

### Step 1

- Become familiar with the JSON format results of each API's get query with the use of an API platform such as postman, and by the API's own documentation resources.
- Created reusable code functions able to take in the variables needed for each search query, and to direct how the resulting JSON dictionaries of each successful query will be navigated to select, sort, and store the required data.
- Creation of subsequent or secondary functions able to loop through an array of input values to call through the primary function.
- Finalize the structure of the accumulated data for EDA readiness.

### Step 2

- Cleaned and transformed the collected data to refine the format of data types, organization of the data values, split the data from certain columns into additional columns, and added new columns with additional data where needed to facilitate merges.
- A Python Pandas dataframe database was created from this data.
- Data analysis was performed using a variety of EDA techniques for visualization and statistical analysis, including application of a statistical model for simple linear regression.

## Results

This project was able to successfully demonstrate a statistically significant strong negative linear correlational relationship between the number of available auto- and assisted propulsion transportation units - _by MobiBikes_ - and the number of empty storage slots at the Mobibikes stations throughout Vancouver, BC, Canada.

## Challenges

Time limitations remain the most precious resource within the constraints of this project and therefore are naturally in conflict with the self-teaching model applied to learning how to use APIs.

Finding relevant correlational data with this particular assignment was another significant challenge.

- The time of day at which the data was collected on the points of interest businesses in proximity to the bike stations was a challenge, since finding correlations between commuter transportation uses and these businesses can only be relevant if both variables are valid.
- It is also possible the time of year impacted the relatability of these data sets, and is likely the cultural correlations between outdoor cycling for leisure with various points of interest would become more prominent in the warmer seasons.

## Future Goals

I would have enjoyed the opportunity to have spent a great deal more time with these data collection, filtering and organizing techniques. This project encorporated a wide range of new skill sets, and I regret that am unable to invest more time into learning and using them.
