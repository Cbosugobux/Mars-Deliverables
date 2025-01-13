# Mars-Deliverables

citations:

1. EdX AI Learning Assistant. (2025). Extracting ('th') headers from ('tr') rows. Retrieved from [https://bootcampspot.instructure.com/courses/6669/external_tools/313]

2. EdX AI Learning Assistant. (2025). Name of Mars Months. Retrieved from [https://bootcampspot.instructure.com/courses/6669/external_tools/313]

3. Stack Overflow user. (2020, June 1). Pandas rolling sum that includes previous and coming days. Stack Overflow. Retrieved January 9, 2025, from https://stackoverflow.com/questions/62116694/pandas-rolling-sum-that-includes-previous-and-coming-days

In this exercise we were asked to provide two deliverables for the Mars Website provided by EdX. 

The first of these deliverables, Mars News, was where we used automation to scrape info from the Mars website provided by EdX.  The first notebook makes use of Splinter and BeautifulSoup to extract article titles and a preview of each article from the HTML scripts on the webpage.  This data was extracted and put into a dictionary.  To confirm a successful scrape, I then used the .strip() feature to clean up the appearance of the data.

The second deliverable was a report on some weather statistics for Mars.  I extracted the resource table using Splinter and BeautifulSoup.  We were tasked with using the table to find the following information:

1. How many months exist on Mars?
2. How many Martian days' worth of data are there?
3. Which month, on average, has the lowest temperature? The highest? 
4. Which month, on average, has the lowest atmospheric pressure? The highest? 
5. How many terrestrial days exist in a Martian year?

In order to achieve these outcomes, I had first create a dictionary to hold the data.  Next, I had to loop through the table and extract the table heading and data.

Following the extraction of data, the activity asked us to Panda-fy the data(put it in a DataFrame).  The information we put in the data frame did not have the right data types. As cuh I had to alter the data types using the .astype() feature of Pandas to convert objects to the proper data type. Once this was achieved, I queried the data to answer the various questions we were asked.  In addition to th queries to just find answers to the questions, I also used MatPlotLib to produce visualizations of the data.  These confirmed the findings of my query functions. 

Finally, we were asked to save our data as a .csv using the to_csv function.


