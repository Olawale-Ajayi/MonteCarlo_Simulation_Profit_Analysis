# MonteCarlo_Simulation_Profit_Viability_Analysis
Monte Carlo simulation analysis of profit viability of a retail store in UK carried out with Microsoft Excel Data analytics tool

# About The data

The data is source from a retail store in the UK with daily sales data, The department and store name for each product in the store presented in an excel tables <br>
The Sales Store name and department are looked up with VLookup functions in excel into the sales data

# Data cleaning and validation

The daily Sales data consist of underlying incomplete data that needs to be cleaned and validated. This is done with data exploration with simple pivot table<br>
to check for misssing values, mispelled entry and ommited entry. <br<
Quick descriptive analysis of the sales data is carried out to remove outliers and far above the max and average for the daily sales revenue.
The Cleaning process is well documented in one of the sheet in the attached (.xlsx file)
![Screenshot (306)](https://user-images.githubusercontent.com/66826707/116709042-343e8d00-a9c8-11eb-954b-837383430f15.png)

# Data Visualization

![Screenshot (305)](https://user-images.githubusercontent.com/66826707/116708626-cd20d880-a9c7-11eb-8d88-468d1352861f.png)

Data analysis and aggregation is carried out along different metrics contributing to sales revenue. this implemented with Pivot table and presented in an interactive dashboard.<br>
Sales by Store name, by promotion, Department and Time Series is presented in a charts showing how they contributed to daily sales. 
This Dashboard is documented in one of the sheet in the (.xlsx file) attached.

# Data Modeling

The Monte Carlo simulation is model to get the optimal profit from the daily sales by simulating a profit margin between 60-70 on daily sales revenue, daily overheads cost of  £4250. The Profit for this model is claculated and use to run 5000  Monte Carlo simulation to get a varieties of profits for each simulation randomised with the Carlo simulation. The Business Model uses 60-70% gross margin on revenue for the analysis.
This is randomized in the Marlo's simulation to get different profit variance.

# The Summary of Insight form the analysis

The maximum, Minimum, average, standard deviation from the 5000 simulation are obtained with the Common excel statistics formula and used to create a bin of range of profit viabilty starting at the minimum loss profit value at -£4210 to maximum £8370.3 daily profit values from the simualtion. These are bins into 5 categories and their frequency in the 50000 simulation are calculated.

Simple Bar chart is insert as the bin is plotted against their frequency to get their chance of profit viabilty. 
5000 simulations was run and the best performance as display in the chart shows that the retail store has a 75% chance of making profit between 0 and 2000 and 1% chance of loosing more than 4000 in profit. again this is well documented in the (.xlsx file)

![Screenshot (307)](https://user-images.githubusercontent.com/66826707/116709364-82539080-a9c8-11eb-9f2b-9e553f88282c.png)




 £
