# Sales-Data-Analysis

To access all of the files I recommend you fork this repo and then clone it locally. Instructions on how to do this can be found here: https://help.github.com/en/github/getting-started-with-github/fork-a-repo

The other option is to click the green "clone or download" button and then click "Download ZIP". You then should extract all of the files to the location you want to edit your code.


In this Project I use Python Pandas & Python Matplotlib to analyze and answer business questions about 12 months worth of sales data. The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc. 

# Background Information

I started by cleaning the data. Tasks during this section include:
- Drop NaN values from DataFrame
- Removing rows based on a condition
- Change the type of columns (to_numeric, to_datetime, astype)

Once I have cleaned up the data a bit, I performed the data exploration . In this I explored 5 high level business questions related to the data:
- What was the best month for sales? How much was earned that month?
- What city sold the most product?
- What time should we display advertisemens to maximize the likelihood of customer’s buying product?
- What products are most often sold together?
- What product sold the most? Why do you think it sold the most?

To answer these questions I performed many different pandas & matplotlib functions. They include:
- Concatenating multiple csvs together to create a new DataFrame (pd.concat)
- Adding columns
- Parsing cells as strings to make new columns (.str)
- Using the .apply() method
- Using groupby to perform aggregate analysis
- Plotting bar charts and lines graphs to visualize our results
- Labeling our graphs
- and many more..

I explain every function that I used in this analysis with proper documentation in jupyter notebook only in understandable language or you can search for specific task like how to remove NaN from data on google and you can find everything related to it on stackoverflow. 

there are one sample data folder which contains data for each month and I also uploaded CSV file which contains all the 12 months data in single CSV. You can directly use all_data.csv and start your analysis otherwise you have to first merge all the data just like I did.

If my documenetation helps you to understand the code better then do star this repo and message me on LinkedIn 
My LinedIn: linkedin.com/in/sumit-sarda17

Credit to https://github.com/KeithGalli   as I referred from his youtube channel 

check out his amazing video if you want to learn Pandas and Matplotlib

Pandas:
https://youtu.be/vmEHCJofslg

Matplotlib:
https://youtu.be/DAQNHzOcO5A
https://youtu.be/0P7QnIQDBJY
