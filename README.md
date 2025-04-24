# Zylentrix
This project involves cleaning, analyzing, and visualizing student data from an online learning platform. The goal is to uncover engagement patterns, course performance, and student satisfaction insights that can drive improvements in learning experiences.

Three CSV files were provided:

students.csv – Contains student demographics and enrolment details

course_activity.csv – Tracks time spent and course completion percentages

feedback.csv – Includes student ratings and feedback comments

🧹 Data Cleaning
Handled missing values and inconsistent date formats

Parsed enrolment and activity dates

Created new columns such as Age Group

Merged datasets on Student_ID and Course_ID

📈 Exploratory Data Analysis (EDA)

Key Questions Answered:

📌 What is the overall average course completion rate?

⏱️ Which course has the highest and lowest average engagement time?

🌍 How does engagement differ by age group or location?

⭐ What is the average feedback rating per course?

🔗 Is there a correlation between completion rate and feedback rating?

🏆 What are the top 3 student segments based on engagement and satisfaction?

📊 Visualizations

Bar charts showing engagement across demographics

Heatmap of correlation between variables

Scatter plot of completion vs rating

Time trends and rating comparisons by course

💡 Insights & Recommendations

Overall completion rate is ~54.78%

Highest engagement: DM101, Lowest: PY202

Younger learners (<18) and learners from Kolkata showed higher engagement

Feedback and engagement don't strongly correlate

Recommendations made to improve course engagement and satisfaction

🔧 Tools Used

Python (Pandas, Matplotlib, Seaborn)

Jupyter Notebook in VS Code

GitHub for version control.
