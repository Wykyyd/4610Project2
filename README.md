# MIST-4610-Project-2-Group-5

Baby Name Dataset
-

**Team Members and Names**

Group 5
- [Gisel Hernandez-Vazquez](https://github.com/giselhernandezv/MIST-4610-Project-2-Group-5/tree/main)
- [Ansley Hankinson](https://github.com/ansleyhankinson/Project-2/tree/main)
- [Lukas Cornish](https://github.com/LukasCornish/Project-2)
- [Samuel White](https://github.com/Wykyyd/4610Project2)
- [Malhar Sethia](https://github.com/MalharSethia/Project2MIST4610)

Baby Name Dataset Visualization Project 
-

This dataset is from the city of New York which lists the most popular names in New York. This dataset includes data from 2011 up until 2021 which only covers New York City. It has not been updated since 2021. Names that are given more than 10 times are included in the dataset, so unique or rare names are not included. Our aim for this project is to analyze the popularity of baby names based on their ethnicity but also gender-neutral baby names to look at the impacts given names can have in society.


Data Set
-

https://catalog.data.gov/dataset/popular-baby-names

**Dimensions**
-

- **Rows:** 69,215
- **Adjusted Rows:** 21,613
- **Columns:** 6
- **Adjusted Columns:** 7

**Column Descriptions**
-

- **Year:** Birth Year Registration
- **Ethnicity:** Population Group
- **Standardized Ethnicity:** Population Group (combined same ethnicities spelled differently)
- **Name:** Assigned Birth Name (first name only)
- **Gender:** Female and Male
- **Count:** Number of Babies Given the Name
- **Rank:** Ranking Based on the Popularity

**Data Changes**
-

We had to put the data into excel power query to transform the data into a workable one.
The changes we made were: removed any duplicates, created a Standard Ethnicities column to fix differences in ethnicity names, made the Child's First Name column uppercase to fix case differences, ascended by year, rank, and ethnicity. This organization helped us understand the data better and make it easier for Tableau to interpret.

![Image](https://github.com/user-attachments/assets/ef16565e-10b0-4fe0-a795-8ca6a46a137f)

Questions & Findings/Analysis
-
**QUESTION 1: How does the popularity of the top 25 names vary across different ethnicities?**
-

<img width="1225" alt="Image" src="https://github.com/user-attachments/assets/4e226ed1-ea89-44b5-bef4-3abf4605b499" />


**Analysis**

Analyzing the ethnic distribution of popular baby names can reveal patterns that reflect implicit biases and cultural influences. Since names often carry cultural significance, understanding how they vary by ethnicity helps identify underrepresentation and highlights how name-based assumptions may affect areas like education, healthcare, and employment.

**Findings**

Certain names show strong ethnic clustering such as Liam and Isabella among Hispanic children, David and Joseph among White Non-Hispanic children, Ethan within the Asian and Pacific Islander group, and Noah within the Black group. Some names such as Ava, Daniel, and Ryan appear strongly across all ethnic groups in the dataset, suggesting those names have more broad cultural appeal. Some names are more ethnically diverse, while others highlight specific ethnic trends, indicating cultural biases.

**QUESTION 2: How common are gender-neutral baby names in New York City?**
- 

![Image](https://github.com/user-attachments/assets/057aaea0-f3a9-4f79-827b-5a0fbdc960a7)


**Analysis**
This chart analyzes the most gender-neutral baby name from 2011-2021 in the New York City population. By using an aggregate function, we defined 65% as the gender neutrality score for the use of the names. By having gender neutral names, we can explore the evolution of cultural shifts. This also allows for naming flexibility which portrays a change in society gender norms for names. These specific insights for New York allow us to view how naming patterns are becoming inclusive.

**Findings**

Most of the gender neutral names had a balance of usage between female and male children. The top name usage among both was Ariel, with female count having used the name more than male. The second popular name was Alexis, with the male count using the name more than female. Skyler, Finlet, Jia, and Nana had a strong balance of usage amongst both male and female. These 9 names were the names that scored more than .65 on the Gender Neutrality score, suggesting that gender neutral names are still not as common for a place as diverse as NYC. We chose .65 as that is the standard metric. The darker the color, the higher the gender neutrality score. 

**Aggregate Function**

![image](https://github.com/user-attachments/assets/2c5c7104-0978-4b4c-b5b3-46cea809cefe)

The aggregate function used was named Gender Neutrality score. If the score indicated a 1, the name was used equally among male and female gender. A score of .65 would mean there would be 65 names of one gender and 100 names of the other gender.

[Tableau Packaged Workbook](MIST4610Project2.twb)
-
