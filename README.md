# MIST-4610-Project-2-Group-5

Baby Name Dataset
-

**Team Members and Names**

Group 5
- Gisel Hernandez-Vazquez
- Ansley Hankinson
- Lukas Cornish
- Samuel White
- Malhar Sethia

Baby Name Dataset Visualization Project 
-

This dataset is from the city of New York which lists the most popular names in New York. This dataset includes data from 2011 up until 2021 which only covers New York. It has not been updated since 2021. Names that are given more than 10 times are included in the dataset, so unique/rare names are not included. Our aim for this project is to analyze the popularity of babynames based on their ethncity but also gender-neutral baby names to look at the impacts given names can have in society.


Data Set
-

https://catalog.data.gov/dataset/popular-baby-names

**Dimensions**
-

- **Rows:** 69,215
- **Columns:** 6

**Columns Descriptions**
-

- **Year:** Birth Year Registration
- **Ethnicity:** Population Group
- **Name:** Assigned Birth Name (first name only)
- **Gender:** Female and Male
- **Count:** Number of Babies Given the Name
- **Rank:** Ranking Based on the Popularity

**Data Changes**
-

We had to put the data into excel power query to transform the data into a workable one.
One of the most significant changes made is we removed any duplicates, ascended by rank, ascended by year, and ascended by ethncity. This organization helped us understand the data better and make it easier for Tableau to read.

![Image](https://github.com/user-attachments/assets/66a19166-8c8e-4070-8c26-2e2b9163b41d)

Questions & Findings/Analysis
-
**QUESTION 1: How does the popularity of the top 15 names vary across different ethinicities?**
-

<img width="1225" alt="Image" src="https://github.com/user-attachments/assets/2fa24b0b-c338-467c-9a57-5c319008a288" />


**Analysis**

Analyzing the ethnic distribution of popular baby names can reveal patterns that reflect implicit biases and cultural influences. Since names often carry cultural significance, understanding how they vary by ethnicity helps identify underrepresentation and highlights how name-based assumptions may affect areas like education, healthcare, and employment.

**Findings**

Many of the top names were more shown across the Hispanic ethnicity and white non-hispanic ethnicity. Ethan was the top popular name for Asian and Pacific Islander ethnicity, Noah was the top popular name for Black non hispanic ethnicity, Liam was the top popular name for hispanic ethnicity, and David was top popular name for White non-hispanic. Asian and Pacfic Islander ethnicity had the lowest show out for the top 15 popular names. Some names are more ethnically diverse, while others highlight specific ethnic trends, indicating cultural biases.

**QUESTION 2: How common are gender-neutral baby names in New York City?**
- 

![Image](https://github.com/user-attachments/assets/4446f75e-6b03-44b4-a8cb-3ffb14ba812f)


**Analysis**
This chart analyzes the most gender-neutral baby name from 2011-2021 in the New York City population. By using an aggregate function, we defined 65% as the gender neutrality score for the use of namage. By having gender neautral names, we can explore the evolution of cultural shifts. This also allows for naming flexbility which portrays a change in society gender norms for names. These specific insights for New York allow us to view how naming patterns are becoming inclusive.

**Findings**

Most of the gender neutral names had a balance of usage between female and male children. The top name usage among both was Ariel, with female count having used the name more than male. The second popular name was Alexis, with the male cout using the name more than female. Skyler, Finlet, Jia, and Nana had a strong balance of usuage amongst both male and female. These 9 names were the names that scored more than .65 on the Gender Neutrality score, suggesting that gender neautral names are still not as common for a place as diverse as NYC.

**Aggregate Function**

![image](https://github.com/user-attachments/assets/2c5c7104-0978-4b4c-b5b3-46cea809cefe)

The aggregate function used was named Gender Neutrality score. If the score indicated a 1, the name was used equally among male and female gender. A score of .65 would mean there would be 65 names of one gender and 100 names of the other gender.
