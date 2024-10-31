# Titanic End to End Data Analysis Project
testing documenting data analysis on git hub

## Table of content
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tools](#tools)
- [Project Structure](#project-structure)
- [Data Analysis](#data-analysis)
- [Results](#results)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
## Project Overview 
 A ship building company wants to know how the passenger class on the titanic affetced the survival rate on the titanic. they want to use this analysis to build better cabins for their ships. he project aims to investigate whether passenger class and age impacted survival rates in the Titanic tragedy to improve future ship designs. The company suspects that higher-class passengers had better chances of survival and wants to ensure equal access to emergency equipment for all passengers in emergencies.
## Data Source 
  Titanic - Machine Learning from 
  https://www.kaggle.com/competitions/titanic/data
## Tools
 MySQL | Jupiter notebook | Tableau | Ms Excel | Ms Word 
## Project Structure
 Data
  - Data Collection
     downloaded the Kaggle csv file
    ![image](https://github.com/user-attachments/assets/c5c7c1b6-2672-417d-8acd-d63a49c83259)

  - data overview
     excel spread sheets is used in data overview so as to get a general understanding of the dataset
    ![image](https://github.com/user-attachments/assets/eb9c13c7-087f-453f-adc0-513c150f3ecc)

  - data transforation
     MySQL workbench is used to select useful columns from the table (Age, Survived, Pclass)
    ![image](https://github.com/user-attachments/assets/e22097af-b39a-4180-8fde-37f292d9be93)
    after the selection the new output is then save and exported as a .CSV file
  - data transfer
    after the selection the new output is then save and exported as a .CSV file
    the data set is now ready to be tranfered to the juptyter notebook for analysis 

## Data Analysis
 jupyter note book is used to perform the data anlysis because we are using python to analyse this dataset 
 python gives us a lot of flexibility when handling data
 ![image](https://github.com/user-attachments/assets/fbfb53d0-bd33-4ac4-9b79-66b030c82d97)
description of the data 
![image](https://github.com/user-attachments/assets/6e172ff1-af84-42e9-9f02-987c630f5411)

 we can see the data type, mean, meadian std and so on from this quick analysis 

 ![image](https://github.com/user-attachments/assets/2c5abbbd-077c-4f2a-bfe9-0e30e09d7a82)
 created a new age category (children, youth & adult, seniors) column 
 then when we have done all of these processes we save and export the data as an excel file and then send it to tableu for visualization 

 Tableau is a data visualization software that gives us a wild range of of data visualization capabilities (https://public.tableau.com/views/TITANICTEST2FORGITHUB/Titanic?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
 ![image](https://github.com/user-attachments/assets/5f68096e-e55a-4eba-be8c-a592758cfd22)
 we showed the relationship between the total number of survived with the rate of survived in each class 
 ![image](https://github.com/user-attachments/assets/a4a159f1-a7f3-48b4-a33a-d9d45e0cf57a)
 we also showed the relationship between survival rate  and age category 
 ![image](https://github.com/user-attachments/assets/9edc56f3-6fe9-43c5-aaf7-3407f76d407a)
 
 total dome of survived pie chart 
 ![image](https://github.com/user-attachments/assets/b0454aa6-e578-4f40-bdbb-384e72217d8e)

  we showed the age category data in an histogram 
 ![image](https://github.com/user-attachments/assets/fb232ad7-537a-4d7b-a5a6-39b71da54ef5)

 now we put everything together in a dynamic dashboard that can be filterd by age or by pclass
 ![image](https://github.com/user-attachments/assets/3cdd379f-1f21-470a-b918-bc6b22e51b22)


## Results
 The data analytics dashboard reveals significant differences in survival rates among various passenger classes on the Titanic. When examining the survival percentages, a substantial disparity is evident. First-class passengers had almost three times the survival rate compared to third-class passengers. This underscores the importance of analyzing survival percentages rather than merely the total number of survivors.

For first-class passengers, the survival rate is approximately 60%. However, when considering the percentage of survivors within each class, the rate is notably higher, emphasizing the critical need to differentiate between overall survival rates and class-specific survival percentages.

Age also played a significant role in survival outcomes. Second-class children had a 100% survival rate, compared to 80% for first-class and 40% for third-class children. No seniors survived in the second and third classes, while only 17% (one individual) survived in the first class. It is essential to conduct a deeper statistical analysis for the first class result to determine if this survival rate among seniors is statistically significant or due to chance.
## Recommendations
   Focus on minimizing the disparity between passenger classes. • Investigate emergency accessibility measures to improve survival rates for all age categories across all classes. • Use these insights to initiate further data analysis (statistical analysis) to design ships that ensure more equitable safety provisions for all passengers, regardless of class or age.
## Limitations 
 the dataset did not contain other information that could have lead to other analysis 
