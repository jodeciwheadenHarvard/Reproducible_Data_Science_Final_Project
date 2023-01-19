# Reproducible_Data_Science_Final_Project

## Built with
RStudio version: RStudio 2022.07.1+554 "Spotted Wakerobin" Release (7872775ebddc40635780ca1ed238934c3345c5de, 2022-07-22) for macOS
Mozilla/5.0 (Macintosh; Intel Mac OS X 13_1_0) AppleWebKit/537.36 (KHTML, like Gecko) QtWebEngine/5.12.10 Chrome/69.0.3497.128 Safari/537.36

## Getting Started
1. Clone git repository.
2. Open 358_RDS_Project.Rmd file in RStudio
3. Set your working directory 
4. Run source code

Please remember that there is a complication when your git repository is stored on your GoogleDrive.

## Challenges
The only challenge I came across while trying the reproduce the study selected were the number of years column. The table at the end of their Read.me provided the time periods for the public records received from each city, however, I believe for some cities they did not receive records for year in the time period provided. For instance, Boston, MA received files for time period 2010-2019 and the number of years is 10 but Atlanta, GA received files for time period 2015-2020 and the number of years is 5 instead of 6. Hence, I came to the conclusion that some of the years were not provided by the city. 

## Future Improvements
In the future, I plan to encapsulate my code by adding functions that accept arguments to increase reusability and cleanliness. 

Further investigation into why there is discrepancy with the number of years column and time period provided.

## References
Article:
Thomson-DeVeaux, A. (2021, February 22). Cities Spend Millions On Police Misconduct Every Year. Here’s Why It’s So Difficult to Hold Departments Accountable. FiveThirtyEight. https://fivethirtyeight.com/features/police-misconduct-costs-cities-millions-every-year-but-thats-where-the-accountability-ends/

Code:
Police misconduct settlements. (2022, October 5). GitHub. https://github.com/fivethirtyeight/police-settlements
