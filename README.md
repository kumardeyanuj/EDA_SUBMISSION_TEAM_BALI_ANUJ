# Almabetter_EDA_Python_project_Hotel_booking



This project is related to Hotel Booking having two hotel description i.e City Hotel and Resort Hotel. In this dataset contains total rows  119390 and 32 columns.In this we divide data manipulation workflow in three category Data Collection ,Data cleaning and manipulation and EDA(Exploratory Data Analysis).As Further moved i.e Data collections first step to find different columns which is done by coding Head(), tail(), info(), describe(), columns() and some others method used for data collections, some of the columns name is updated here i.e hotel,is_canceled,lead_time,arrival_date_year,arrival_date_month,arrival_date_week_number,arrival_date_day_of_month,stays_in_weekend_nights.As we further moved we find unique value of each columns and generate a list in tabular form and also check the dataset type of each columns’ find some columns not in accurate data types which correct it later done  in Data cleaning part and as well as duplicates data items must be removed as we find duplicates items equal  to 87396 which is dropped from dataset later.

Before visualize any data from the data set we have to do data wrangling.
For that, we are checked the null value of all the columns. After checking, when we are getting a column which has more number of null values, dropped that column by using the 'drop' method. In this way, we are dropped the 'company' column. When we are find minimal number of null values, filling thse null values with necesary values as per requirement by using .fillna()



Different charts are used for data visualization so that better insights and Business objective is attained.
