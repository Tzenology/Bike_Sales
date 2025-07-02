# Bike_Sales

### Overview
The purpose of this project is to clean the raw dataset, create pivot tables and create a dashboard that can helps us identify different trends of factors that may influence the sales of bikes in different locations across different demographics of people. The dataset was found on Alex The Analysit's github and I used it for practicing my data analytics skills.

### Process
1. Cleaning Data
   - I removed some duplicated data in the table
   - Some columns were written in abbreviations. eg, Gender had F & M and I wrote those in full to avoid any confusion and wrote marital statuses in full too
   -  I then removed the decimal places in income to have the figures more presentable and easier to deal with when making charts
   -  To make visualization easier, I added a column named `Age Brackets` to group all ages into 3 categories "Old", "Middle Age" and "Adolescent".
   -  For visualization purposes, I changed "10+ Miles" to "More than 10 Miles" under the `Commute Distance` column because pivot tables translated that data incorrectly.
  
2. Pivot Tables
   - I created 3 pivot tables;
     
      -`Average Income` to show which gender purchased more bikes based on their income,
     ![avg_income_per_purchase](https://github.com/user-attachments/assets/e5daf689-db38-407b-9433-12b588c76272)

      -`Count of Purchased Bike` to show how many customers bought bikes based on their commute distance
     ![customer_commute](https://github.com/user-attachments/assets/63ec2f2b-e39b-43e6-b1a8-5ee0a12d23c2)

      -`Count of Purchased Bike` to show which age group bought the the most bikes
     ![customer_age_brackets](https://github.com/user-attachments/assets/a02693e3-2941-4a2a-84e8-477f63471348)

3. Dashboard
   - I created graphs using the pivot tables i had in the previous step to visualize the data
   - I then created slicer tools which make it easy to choose which data I want to see based on the different categories I have

Below is an image of the final dashboard I designed which shows the average income of client per purchase, customer age bracket, and customer commute based on customers marital status, Region and Education.
![bike_sale_dashboard](https://github.com/user-attachments/assets/2a82b07c-29be-4eaf-855e-df0224be30b9)

### Findings
The analysis revealed several interesting trends in bike purchases across different demographics and regions:

1. Middle-aged individuals are the most likely to purchase bikes, followed by adolescents. The older age group showed the lowest purchase activity, suggesting that age significantly influences buying behavior.
2. Commute distance plays a nuanced role. Most buyers live within 0–1 mile of their commute, which initially seems counterintuitive. However, this could indicate purchases made for leisure, short trips, or lifestyle preferences, rather than strictly for long-distance commuting.
3. Further inspection of the data revealed that some bike buyers have children, which supports the theory that bikes may be bought for family use or recreational purposes, not just commuting
4. A notable finding is that all commuters in Europe who purchased bikes do not own cars, implying that bike ownership in this region may be driven by necessity — potentially due to urban design, limited access to vehicles, or a stronger cultural preference for biking over driving.
5. In the Pacific region, although buyers generally had lower average incomes than non-buyers, the presence of bike purchases suggests that factors other than income — such as commute practicality or environmental values — influence purchasing decisions.

Overall, the data highlights how personal lifestyle, regional infrastructure, and socioeconomic context intersect to shape purchasing patterns.


### Tools Used
- Ms Excel
- Pivot Tables
- Slicers

### Next Steps
- Learn how to automate this using Power BI
- Learn how to clean this dataset using Python

