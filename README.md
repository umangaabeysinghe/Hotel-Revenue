# Hotel-Revenue
There are five seperate worksheets in the excel sheet.three worksheets contain hotel details for year 2018,2019 and 2020 and the other two are about meal costs and discounts for different market segments.My Aim here is Develop a data base to Analyze and Visualize Hotel booking data and overcome with following requirements.

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

4.Create Visualization

![Screenshot (375)](https://github.com/umangaabeysinghe/Hotel-Revenue/assets/168299630/c854ceea-c689-4201-ab61-060cf37b13c7)

* Use folllowing equation to get insights

  Meal revenue                    = (stays_in_week_nights+Stays_in_weekend_nights)*cost
  Revenue of stays(without meals) = (stays_in_week_nights+Stays_in_weekend_nights)*adr
  Revenue(meals+stays)            = (Meal revenue + Revenue of stays) * (1-discount)
  Total Revenue                   = SUM [(Meal revenue + Revenue of stays) * (1-discount)]

# Insights























































