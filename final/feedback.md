# Feedback on your final

**Final Score: 47/60**

The grading rubric for the final can be found in GitHub: https://github.com/paulboal/hds5210-2023/blob/main/final/final-instructions.pdf

**Functional Requirements**
* 5 points - Uses data from at least two different sources: local file, internet, web service, relational database, AWS S3, etc; and formats: CSV, JSON, database, XML, Excel, etc
* 5 points - Data from multiple sources has to be joined together at least twice
* 5 points - Data is aggregated or pivoted at least twice during the program
* 5 points - Some kind of field-level transformation is performed at least 5 times
* 5 points - The program creates 3 or more data visualizations 
* 5 points - The program serves a theoretical purpose described in documentation, that could potentially do something in healthcare or another industry of interest

**Modularity / Style**
* 15 points - The code is broken up into various functions or classes to make testing and reuse easier

**Documentation and Professionalism**
* 15 points - All functions are documented and notebook cells include annotations and explanations.


**(-1) The creation of some functions upfront can be helpful, but you should have followed standard docstring and doctest (if appropriate)**

**(-1) Your visualizations of City Data vs Population aren't readable and it's unclear what they show us**

**(-4) You merged data together into data_mrg and data_mrg_1, but never used those data frames.**

**(-2) You performed data type conversions on some fields, but didn't perform any field level transformations to cleanse or reformat your data**

**(-5) Your analysis didn't look at your core dataset - Kidney data from Snowflake. You plotted all of the variables for some different age groups, but didn't really organize the data to draw any inferences from the data**