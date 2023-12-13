# pandas-challenge
This project analyzes district level school data on reading and math passing rates. This is an exploratory analysis to see if there are any trends that could help the district improve academic performance. 
This analysis looks at summary information on a district and school level, and looks more granually at type of school, performance based on school size and budget per student. 


Code under School Summary provided by Ask BCBS: 
# Use the code provided to select all of the school types
school_types = df_sch.set_index(["school_name"])["type"]
school_types

