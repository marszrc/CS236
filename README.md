# CS236
1. An overall description of how you chose to divide the problem into different spark
operations, with reasoning.


2. A description of each step job
    
    1).Parse input files and create dataframe in Spark, choosing CTRY == US and ST != NULL.
    
    2).Join LOCATIONS dataset and RECORDINGS dataset with RECORDINGS.STN == LOCATIONS.USAF
    
    3).Calculate the average temperature of one month in one station by counting RECORDINGS.temp in one month.
    
    4).Calculate the average temperature of one month in one station of four years.
    
    5).Calculate the average temperature of one month in one state by using the average temperatures in all 
    stations belonged to one state.
    
    6).Choosing the max and min temperature and its month. Then calcualte its difference and output.
    
    7).Ordering states by the difference in ascending order.

3. Total runtime for the whole project


4. A description of anything you did extra for the project, such as adding a combiner. If
there is anything that you feel deserves extra credit, put it here.
