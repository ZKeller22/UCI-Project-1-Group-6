# UCI-Project-1-Group-6


# Government Education Expenditure v Measures of Prosperity 
# Analysis Project

## Project Overview

  This project looked at  education expenditure as a percent of government expenditure compared to measures of prosperity:
      
      - Consumer Price Index
      - Gross Domestic Product ($)
      - Government R&D expenditure (%)
      - Unemployment Rate (%)
      -Crime Rate
        - Homicide
        -Assault
        -Robbery
        -Sexual Assault
        -Theft
## Hypothesis
  
  Our hypothesis was that the greater the  percent spend by government on education the better the measures of prosperity. The countries with the highest percent spend on education as a percent of total government expenditiure would have a lower crime rate, lower unemployment, higher CPI, higher percent spend on R&D, higher GDP compared to the rest of the countries in the data set.
 
 ## Data Clean-up
 
 The data we gathered for our analysis came from https://data.worldbank.org/ and we saved them to a file called "raw_data" and pulled them into the jupyter notebook "project_data_cleanup.ipynb". The first row was blank so it had to be removed so that the proper header was in place. New column headers were input. The N/A values were dropped as well as any additional value in the "Source Data" field that was not going to be used for the analysis.
  The dataframes were then saved to a csv file and pushed to the folder "output_data". Finally, we merged each of the measures of propserity csv fiels with the spend on education file and saved that to the folder "merged_data". 
  
  ## Visualizations
    
The merged csv files were read into a second jupter notebook "project_visualizations.ipynb". We had to filter the data by yers 2010 and forward and only looked at the top 10 countries in terms of spend % in each of the merged dataframes becuase there we so many countries it did not fit the bar chart. We created a bar chart  and scatter chart for each merged data frame (for crimes we split out by each sub-category). We displayed the mean, standard deviation and correlation coefficent. 
    
   ## Results
    
The data shows no real correlation between education spend as a percent of government expenditure and the measures of prosperity. The strongest correlation we had was 0.59 for GDP, which we had to divide by 100 so it could all fit in the bar chart. Each of the standard deviations was greater and often a multiple of the mean.
    
   ## Conclusion
    
The data could not prove our hypothesis.
