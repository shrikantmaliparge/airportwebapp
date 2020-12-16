

# # Backend Developer Assessment
## ##Steps:
1. Fork the repo and work on your fork only
2. here are 3 CSV files in the repository. The files contain data for countries, airports and runway information.
3. Write a micro-service modelled application that will support a website with the following functionalities:
   **Query**
    - Query Option will ask the user for the country name or code and print the airports & runways at each airport. The input can be country code or country name.
    - For bonus points make the test partial/fuzzy. e.g. entering zimb will result in Zimbabwe.
    **Report**
    - 10 countries with highest number of airports (with count) and countries  with lowest number of airports.
    - Type of runways (as indicated in "surface" column) per country
    - Bonus: Print the top 10 most common runway latitude (indicated in "le_ident" column)
4. Feel free to use any library/framework in java as necessary.
5. Please write the code as if you are writing production code, possibly with tests
6. Please implement swagger and postman collections for testing
7. Once you are satisfied with the implementation, commit in the application onto your fork
8. As a part of the assessment process, we will be expecting a small demo and code walkthrough
9. We will be grading the application based on multiple criteria including quality, performance and completeness

**_Disclaimer: The data files in this repo have been extracted from https://openflights.org/data.html. Accenture claims no ownership or responsibility to this data or its usage._**
