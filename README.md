## Task
# 1. Analyze the Data:
Schema Exploration: Analyze the structure of the data and identify key patterns in student performance based on topics, difficulty levels, and response accuracy.
Identify Performance Trends: Group and analyze performance by topic to understand where students are excelling and where improvements are needed.
# 2. Generate Insights:
Identify weak areas for each student, based on their performance in different topics.
Recognize improvement trends, if any, from the historical quiz data.
# 3. Create Recommendations:
Propose actionable steps to improve the student’s performance:
Focus on specific topics where accuracy is low.
Practice question types where performance has been weak.
Suggest increasing quiz difficulty or trying new topics.
Recommendations should be tailored based on the student's historical quiz performance.
# 4. Bonus Points:
Persona Creation: Cluster students based on their performance to define unique personas. This will help categorize students into different groups (e.g., "High Achiever," "Needs Improvement").
Creative Labels: Provide fun and insightful labels that describe each student's learning behavior or strengths and weaknesses.
## Approach
# 1. Data Fetching and Preprocessing:
Use API calls to fetch the current quiz and historical quiz data.
Clean and process the data to convert accuracy percentages, handle missing values, and normalize topic names.
# 2. Data Analysis:
Calculate the average performance by topic.
Identify the most common weak areas by comparing performance across topics.
Use clustering techniques (e.g., KMeans) to segment students based on their quiz performance.
# 3. Recommendation Generation:
Based on the analysis, create personalized recommendations for each student.
Provide suggestions on what to focus on based on the accuracy of responses and the difficulty levels.
# 4. Data Visualization:
Generate visualizations (e.g., bar charts) to display topic-wise performance and insights.
Use clustering visualizations to depict student personas.
