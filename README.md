MatPlotLib Challenge - Bootcamp Module #5

Introduction:

In this challenge, we were tasked with merging datasets, creating a new dataset and creating various chart types. These chart tyes included bar, pie, scatter and line. I also applied some techniques from our crash course in statistics (quantiles, linear regression, etc.) to evalutate the data presented.

Pymaceuticals:

Merging & Creating New Datasets - I merged the datasets (mouse_metadata and study_results) to form a new dataset using and outer join. From this dataset, I pulled out the unique mouse_IDs. I then used the duplicated built-in function to tease out the mouse_id that contained duplicates. I then created a new dataset.


Retreiving Statsical values:

I retreived and displayed statiscal values in a Summary Statistics table. I then created a new DataFrame housing these new statisical data using the groupby method

Charts:




Resources Used:

Aggregation Function = 'https://www.scaler.com/topics/pandas-agg/
Duplicate Values = https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.duplicated.html
