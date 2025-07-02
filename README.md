# Bike_Sales

### Overview
The purpose of this project is to clean the raw dataset, create pivot tables and create a dashboard that can helps us identify differennt trends in the sales of bikes in different locations across different demographics of people. The dataset was found on Alex The Analysits github and I used it for practicing my data analytics skills.

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

      -`Count of Purchased Bike` to show which which age group bought the the most bikes
     ![customer_age_brackets](https://github.com/user-attachments/assets/a02693e3-2941-4a2a-84e8-477f63471348)

3. Dashboard
   - I created graphs using the pivot tables i had in the previous step to visualize the data
   - I then created slicer tools which make it easy to choose which data I want to see based on the different categories I have

Below is an image of the final dashboard I designed which shows the average income of client per purchase, customer age bracket, and customer commute based on customers marital status, Region and Education.
![bike_sale_dashboard](https://github.com/user-attachments/assets/2a82b07c-29be-4eaf-855e-df0224be30b9)

### Findings

