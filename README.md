## The Nashville City Cemetery

![Top 10 Causes of Death](../main/images/Top10CausesRevised.png)


## Table of Contents
* [General Information](#general-information)
* [Technologies](#technologies)
* [Files in this Repository](#files)
* [Data Exploration Questions](#data)
* [Analysis/Conclusions](#analysis)
<br>


## <a name="general-information"></a>General Information
The city of Nashville provides a dataset of known burials in city cemeteries from 1846 through 1979. This dataset holds factual information, but it also offers a fascinating glimpse into historical trends in medicine, literacy, racial equality, and more.

We were tasked with exploring data on the Nashville City Cemetery utilizing Excel to gain insights and then further the data story by creating a marketing piece.
<br>
<br>

## <a name="technologies"></a>Technologies
Project is created with:
* Excel for analysis and data visualizations
* Canva for marketing material design and layout
<br>


## <a name="files"></a>Files in this Repository
The data analysis can be seen in the Excel file in the data folder.
The full PDF of the marketing materials is in the City_Cemetery_Marketing pdf file.
<br>
<br>
<br>

## <a name="data"></a>Data Exploration Questions
1. Use a pivot table to find the 10 most common (known) recorded causes of death, and evaluate the counts of each type. Once you have your metrics, plot these in a bar chart. In the analysis of the top 10 causes of death, you may see spelling mistakes that are affecting your counts. For example, you can assume Cholera and Cholrea are the same cause of death. Create a new column in the original dataset to update spelling errors to make your count of the top 10 causes more accurate. 

2. Create a line chart showing number of burials per year. In what years were there the most burials? Can you think of any plausible reason why?

3. Examine deaths for each decade beginning with the 1850s. Look at the total number of deaths and the proportion of male deaths to female deaths. Use a pivot table with a slicer to do this, and create a clustered bar chart to show how male and female deaths have changed over time.

4. Next look at how age at the time of death has changed over time. Add a column to the original dataset to classify each row to one of the following categories (0-18, 19-25, 26-40, 41-64, and 65+). Be sure to think about a strategy to deal with missing values. Make a series of pie charts or donut charts to show the breakdown of each age group for these four periods: before 1880, 1881-1900, 1900-1920, after 1920.

5. Examine burials by month. Are there months with higher burials? What are the top five causes of death for each month? Choose a visualization that conveys the differences well.

6. Create a new column titled Last Name. Extract the last name from the Name column by subsetting to all characters to the left of the comma (see the DataCamp exercise titled “String Information – LEN, SEARCH” from the Data Analysis with Spreadsheets if you need help with this). This will result in many errors for rows missing commas.   
    a. 	Drill down to those rows without a comma – what do you notice?  
    b.	What are the most common last names of people buried in this cemetery?  
    c.	There was a particularly famous person buried in this cemetery. Can you find that person?

7. Do you notice any interesting patterns regarding where (`Section/Lot`) people were buried?
<br>


## <a name="analysis"></a>Analysis/Conclusions
This was a really messy data set, which was challenging, but it was interesting to explore.  Upon analyzing the data, I was interested to see that nearly half of the burials are women, which was surprising given the large number of Civil War related burials.  I was also curious to see the number of burials each year in comparison to a timeline of Nashville history.  I found a timeline from the Nashville Historic Commission which divided Nashville's history into eras and I grouped burials by those eras and then plotted it against the timeline in a bar chart.  It's not surprising to see that the cemetery had the most burials during three of Nashville's eaerliest eras:  Rock City (1840s-1850s), The Occupied City (1860s) and Athens of the South (1870s-1900).  

![Marketing Materials page 1](../main/images/citycemeterypg1.jpg)

![Marketing Materials page 2](../main/images/citycemeterypg2.jpg)


