# DATA334 Final Project: Data Science Salaries

My Data Visualization final project is an exploration of salaries in the field of data science and other related fields. 

The dataset I used is called **Latest Data Science Job Salaries**, published on Kaggle by Sourav Banerjee: 
<a href = "https://www.kaggle.com/datasets/iamsouravbanerjee/data-science-salaries-2023">https://www.kaggle.com/datasets/iamsouravbanerjee/data-science-salaries-2023</a>. These data encompass job salary data for the field of data science and other related fields through the years 2020 through early 2024. Most of the salary data comes from the United States of America, but also does include data from 74 other countries across the world.

**Variables of Interest**

* `Salary.in.USD`: job salary converted to USD
* `Job.Title`: job position title
* `Job.Category`: category of job position (added by myself)
* `Experience.Level`: factor of individual's experience level (Entry, Mid, Senior, Executive)
* `Company.Size`: factor of the company's size (Small, Medium, Large)
* `Company.Location`: geographic location of the company
* `Employment.Type`: factor of job position type (Full-Time, Part-Time, Freelance)
* `Year`: year of employment (2020-2024)

I made a Shiny App to allow users to visualize the data in many different ways: histograms of salary per `Job.Title`, faceted frequency plots to visualize relationships between two variables of interest, and violin plots to compare the centers and shapes of as many job positions as you want!

Link to the Shiny App: <a href = "https://brodypinto.shinyapps.io/DATA334_final_project/">https://brodypinto.shinyapps.io/DATA334_final_project/</a>
