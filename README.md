# DataCamp-Courses

This repository consists of all the courses and subsequent materials I have taken so far in DataCamp as a part of my journey into Data Science.

## Courses
- [Understanding Data Science](https://app.datacamp.com/learn/courses/understanding-data-science)
  - Basics of Data science workflow
  - Data Collection and Storage
  - Preparation, Exploration, and Visualization: Data Cleaning, ETL, EDA
  - Experimentation and Prediction: A/B testing, ML concepts and ethics
- [Introduction to ChatGPT](https://www.datacamp.com/courses/introduction-to-chatgpt)
- [Data Manipulation with pandas](https://app.datacamp.com/learn/courses/data-manipulation-with-pandas)
  - Basics of Data Frames: .head(), .describe(), .tail(), .shape, .info(), .columns, .index, .values  
  - Sorting and Subsetting of DF: using .sort_values(["col1", "col2"], ascending = ["T", "F"]), DF subsetting methods (DF[DF["colname"] ">,<,==" conditions]), adding new columns as a resultant of columnar arithmetic
  - Aggregating DF and Summary Statistics: .agg([funct1,funct2]), .mean(), .median(), .mode(), .cumsum(), .cummax(), .drop_duplicates(subset=["Basis_col1","Basis_col2"]), df["colname"].value_count(sort= "T",normalize="T")
  - Grouped summary Statistics: .groupby(["col1","col2"])["feature"].agg(["stats1","stats2","stats3"]), Pivot Tables: .pivot_table(values="summary col", index = "groupby col",columns= "additional cols",fill_value= "value for missing relations", margins = True(enables mean display for col-row wise entries) ,aggfunc= ["stats function"])

## Course Material/exercises
- [Pandas Data Manipulation Exercises ](/Data_Manipulation_with_pandas/)

## References
- 

