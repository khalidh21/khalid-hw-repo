### ***Project 2 Feedback***

***Nico Van de Bovenkamp***

***

**Overall:** Great job on this assignment! You are writing some nice python code, and you have a clear understanding of the concepts at hand. I don't have many comments for you! While we move forward into the modeling section, try to play with the data in different ways and use some of those pandas/python techniques that we cover in class. Let me know if you have any questions on the models/modeling because that's the next **big** part on our journey! 


**Some Notes**

* Very pythonic code here, nice! `df_raw[df_raw.isnull().any(axis=1)]`
* Regarding your analysis plan, you should probably include what models/modeling techniques you think you should use. Considering we haven't gotten into it yet, this is more than okay to not include. However, typically when you write out your analysis plan, you include data cleaning, data manipulation, some analysis, and then modeling techniques to find, in this case, the relationship between Admission and Prestige!

**Something to think about**  
Dropping missing values can be necessary at times. In cases where you you have a lot of missing values, you might have to just drop those rows *or* ignore that feature all together (forget that column, we can't use it). However, as we proceed, you will find that data is gold to these algorithms. Very often, the more data you have, the more information you are giving to your model so it can generalize even better. To ensure we retain as much data as we can, a common practice is to fill missing values with the mean or median or mode so that you can keep those instances, without disturbing your distribution too much. Check out these guides:
https://machinelearningmastery.com/handle-missing-data-python/
https://chrisalbon.com/python/pandas_missing_data.html
