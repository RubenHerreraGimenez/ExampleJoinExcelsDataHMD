# Database creation from Excel files. A practical case: Human Mortality Database. 1 million rows, 100 Excel files, 10 seconds.

In this example, we start from 100 Excel databases with exposure and death data from different countries and regions.

The objective is to be able to work with all the information to undertake different analyzes. Therefore it is necessary to gather all the information in a single database.

In total we have more than a million rows in 100 files (50 for exposure and 50 for deaths). These dimensions make it inadvisable to do it by hand, which requires automation.

This document proposes a quick solution using R. This code would be used for any type of data arranged in Excel.

**Link to data repository and code for easy reproducibility:** 
https://github.com/RubenHerreraGimenez/ExampleJoinExcelsDataHMD


**Link to the explanatory html of the process:** 
https://rubenherreragimenez.github.io/ExampleJoinExcelsDataHMD/
