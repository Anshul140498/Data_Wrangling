# Data_Wrangling
- In this project 3 datasets are beinf used to do Data processing.
- All the steps related to Data wrangling is being covered and further data analysis is also done.
  
**1)** **Data Merging and Concatination**
- Here in two datasets (1&2) are merged .
- I have used left join to merge the datasets as both are related to each other.
- Unnecessary columns (ex- atemp) were dropped as they couldn't contribute much further in the analysis.
- Dataset 3 is being concatenated in the vertical manner resulting in more observations --> that helped in better analysation.
- I've also used the group by clause to have clear insights.

**2)** **Data Cleaning and reshaping**
- After merging the datasets , null values are checked in order to make the dataframe more reliable to use .
- NAN's were being filled up with the mean value of the atrribute --> resulting in better accurate numbers.
- Dataset shape and datatypes also checked.
- Conversion of object data type to datye-time is also done for the date variable.

**3)** **Data Enrichment by Visualization**
- After clean the data , I ued the Seaborn library to visualize the data.
- Boxplot has been used to get the view of the data --> some outliers were being used.
- After removing the outliers , Correlation [corr()] is also used .
- For correlation , I used the heat map that clearly showed that durin clear sky , there were more rides.
- The above gave an insight that more business can be done in the spring season by introducing more offers.

**4)** **Handling Outliers**
- The outliers that were noticed are handled by using the **IQR** mdthod .
- The quantile range was calculated with 75% as the upper limit and 25% as the lower limit.
- After getting the data that lies outside the limit was deleted.
- This resulted in symetrical data that is within the parameters to analyse.
  
