# Standardised Test Results Analysis

Analyse the area-wide standardised test results using a dataset that provides every student's maths and reading scores, as well as various information on the schools they attend. Aggregate the data to showcase obvious trends in school performance.

- This project uses the Pandas library to manipulate data into tables that allow for aggregating and summarizing of district and school data. 
- Array calculations are performed to create a snapshot of school district's key metrics. 
- Analysis done to show trends such as top peforming schools, bottom performing schools, math and reading scores by grade, and scores by school spending, size, and school type.


# My Analysis

The dataset analyses a total of 39,170 students across 15 schools.  The total student average maths score is 70.34%  and the average reading score is 69.98%.  Of the total 15 schools, 7 of these schools are government funded and 8 of the schools are independently funded.  

The government funded schools all have a higher student count (between 2,739 to 4,976 students) than the independent schools (between 427 to 2,283).

When taking a closer look at the results we can see that:
- Independent schools have a higher overall passing rate at 76.973% than government schools at 70.968%
- Small & medium schools have a higher overall passing rate at 78-79% than the large schools at 70%
- The schools with a lower budget per student (under $630) have a higher passing rate at 76-80% than those schools with the highest budgets ($645 - $680) at only 66 - 67%
- In the bottom 5 schools, 4 of them were government schools
- More students are passing maths than reading, with the LGA summary showing % passing maths at 86.076% compared to reading at 84.426%

What we can conclude here is:
- Having a higher budget per student doesn’t not yield better results
- Independent schools outperform government schools

An assignment for Monash University's Data Analytics Bootcamp (2023)
