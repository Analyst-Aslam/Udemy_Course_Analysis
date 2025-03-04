
# Udemy Course Analysis

##  Project Overview
This project provides a comprehensive analysis of Udemy course data from 2011 to 2017, to uncover key trends in course popularity, pricing strategies, and subscriber distribution across various subjects and difficulty levels. The insights derived from this analysis can be valuable for educators, learners, and business analysts aiming to understand the dynamics of the e-learning industry.

##  Dataset Description
### **Source**
Udemy Course Dataset

### **Key Features**
- `course_id`: A unique identifier for each course.
- `course_title`: The title of the course as listed on Udemy.
- `url`: The URL link to the course page on Udemy.
- `is_paid`: Indicates whether the course is paid (`True`) or free (`False`).
- `price`: The price of the course in USD (applicable only for paid courses).
- `num_subscribers`: The number of students enrolled in the course.
- `num_reviews`: The total number of reviews left by subscribers.
- `num_lectures`: The number of lectures included in the course.
- `level`: The difficulty level of the course (e.g., All Levels, Intermediate Level).
- `content_duration`: The total duration of the course content in hours.
- `published_timestamp`: The date and time when the course was published.
- `subject`: The primary subject category of the course (e.g., Business Finance, Web Development).

##  Analysis Conducted
### **1️ Data Cleaning & Preprocessing**
- Standardized course duration format for consistency.
- Converted and formatted date values for time-based analysis.

### **2️ Exploratory Data Analysis (EDA)**
- Examined the distribution of courses across different subjects.
- Analyzed the relationship between course difficulty level and subscriber count.
- Conducted a pricing analysis to compare free and paid courses.
- Investigated trends in course publication over time.

### **3️ Data Visualization**
- **Bar Charts**: Course distribution by subject and difficulty level.
- **Pie Charts**: Proportion of free vs. paid courses.
- **Line Charts**: Trends in course publication over the years.
- **Strip Plots**: Subscriber distribution across different course levels.

##  Key Insights
- **Web Development Courses** attract the highest number of subscribers.
- Most courses fall under **Beginner and All Levels**, highlighting strong demand for entry-level content.
- **Paid courses** generally have significantly higher enrollments than Free courses.
- Udemy experienced rapid course growth from **2014 to 2016**, indicating a surge in content creation. This could be due to increasing adoption of online learning and more instructors joining the platform.
- The majority **(91.6%)** of Udemy courses are paid, while only **8.4%** are free.
- Despite **free courses** being only **8.4%** of total courses, they still attract a significant number of subscribers.
- The dominance of **Quick Learning** and **Short Courses** suggests that Udemy learners prefer concise and time-efficient courses over longer, more detailed ones.

##  Technologies Used
- **Python** (pandas, seaborn, matplotlib)
- **Jupyter Notebook** for analysis and visualization
- **Seaborn & Matplotlib** for data visualization

##  How to Run the Project
### **1️ Install Required Libraries**
```bash
pip install pandas numpy matplotlib seaborn
```
### **2️ Open Jupyter Notebook**
```bash
jupyter notebook
```
### **3️ Run the Notebook**
Execute each cell sequentially to load the dataset and perform the analysis.

##  Conclusion
This analysis offers valuable insights into Udemy's course landscape, including subscriber preferences, pricing patterns, and course difficulty trends.

---
