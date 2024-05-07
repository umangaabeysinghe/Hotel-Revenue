# Hotel-Revenue
There are five seperate worksheets in the excel sheet.three worksheets contain hotel details for year 2018,2019 and 2020 and the other two are about meal costs and discounts for different market segments.This data set contains data about two different hotel types called resort hotels and city hotels.My Aim here is Develop a data base to Analyze and Visualize Hotel booking data and overcome with following requirements.

# Requirements
1.Is the hotel revenue growing by year from 2018 to 2020.

The following sql query can be used to get a brief idea of the revenue growth.(without considering meal revenue and discounts)

![Screenshot (374)](https://github.com/umangaabeysinghe/Hotel-Revenue/assets/168299630/dfab4b0b-c83e-45bd-afd1-7820dc1e4715)



2.Should we increase our parking area size.

3.What trends can we see in the data.

# Steps
1.Import Excel file to SQL sever.(SQL server management studio 20)

2.Analyze the data.Used the query as follows

![Screenshot (373)](https://github.com/umangaabeysinghe/Hotel-Revenue/assets/168299630/fd43cc06-3cb3-42aa-a927-1ebe5cb8bf0d)

3.Import data from SQL server to Power BI

4.Create Visualization (power BI)

![Screenshot (375)](https://github.com/umangaabeysinghe/Hotel-Revenue/assets/168299630/c854ceea-c689-4201-ab61-060cf37b13c7)

* Used folllowing equation to get insights

  Meal revenue                    = (stays_in_week_nights+Stays_in_weekend_nights)*cost
  
  Revenue of stays(without meals) = (stays_in_week_nights+Stays_in_weekend_nights)*adr
  
  Revenue(meals+stays)            = (Meal revenue + Revenue of stays) * (1-discount)
  
  Total Revenue                   = SUM [(Meal revenue + Revenue of stays) * (1-discount)]

# Insights

* As we can see in the above line chart revenue is increasing for both hotel types.Total revenue is higher for city hotel than resort hotel.

  In city hotel there are sudden revenue increases in 30th of september in 2018,2nd of january in 2019 and 30th of september in 2019.
  In resort hotel we can see two sudden changes from 7th july to 2nd octomber in 2018 and from 30th july to 15th september in 2019.

  For both hotel types we can see a sudden decrease around september 2020.We can assume that's becauseof covid-19 pandemic.

* According to table it's not really growing the parking percentages.So we don't  have enough evidence to determine whether we should increase the parking space.























































