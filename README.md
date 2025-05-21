
# Excel Salary Dashboard – My First Project 🎉

This is my first Excel dashboard project, inspired by the work of [Luke](#). I followed his example as a learning guide and tried to build something similar on my own to practice my Excel skills.

## 📁 File

- `Excel Salary Dashboard – My First Project Inspired by Luke.xlsx
  ` – The main Excel dashboard file

## 📊 Project Description

The goal of this project is to explore and analyze salaries for data-related jobs across different countries, job types, and roles using Excel.

I used a dataset provided in Luke's Excel course that contains real-world data science job information from 2023, including:

- 👨‍💼 Job titles
- 💰 Salaries
- 📍 Locations
- 🛠️ Skills

## 🛠 Excel Skills I Practiced

- **Charts**: Created bar charts and map charts to visualize salary data
- **Formulas & Functions**: Used functions like `MEDIAN`, `IF`, and `FILTER` to calculate salary data based on filters
- **Data Validation**: Created dropdown lists to filter job titles, countries, and schedule types

## 📈 Dashboard Highlights

- **Salary by Job Title (Bar Chart)**: Shows median salaries across different job roles
- **Salary by Country (Map Chart)**: Displays how salaries vary by location
- **Filtered Tables**: Allows dynamic salary lookup based on job title, country, and schedule type

## 🔢 Example Formula

```excel
=MEDIAN(
  IF(
    (jobs[job_title_short]=A2)*
    (jobs[job_country]=country)*
    (ISNUMBER(SEARCH(type,jobs[job_schedule_type]))),
    jobs[salary_year_avg]
  )
)

This formula helped me calculate the median salary based on selected filters.

✅ What I Learned
How to structure and clean a dataset

How to build visuals in Excel that tell a story

How different Excel functions work together

How to use data validation to make a user-friendly dashboard

🚀 Next Steps
Learn more about advanced Excel functions like XLOOKUP or Power Query

Try connecting multiple sheets and using slicers

Continue practicing by building dashboards on different topics

Thanks for checking out my project! 👩‍💻🧠


