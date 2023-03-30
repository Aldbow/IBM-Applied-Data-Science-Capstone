# 🚀 Applied Data Science Capstone
The Capstone course is the final course in the IBM Data Science Professional Certificate specialization, which comprises ten courses in total. This course serves as a culmination of the entire program, as it brings together all of the concepts, techniques, and tools that learners have acquired in the previous courses.

During the IBM Data Science Professional Certificate specialization, learners are introduced to various topics, including data exploration and visualization, data analysis and machine learning, and data product development. Through a combination of lectures, hands-on assignments, and quizzes, learners gain practical experience and build their skills in data science.

In the Capstone course, learners are presented with a real-world problem or project, which they must solve using the knowledge and skills they have acquired throughout the program. This project typically involves working with real-world data sets, performing data cleaning and preprocessing, developing predictive models using machine learning algorithms, and evaluating the performance of these models. Learners are expected to apply best practices in data science, including data visualization, model tuning, and interpretation of results.

By completing the Capstone project, learners demonstrate their proficiency in data science and their ability to apply their knowledge to solve real-world problems. This final course serves as a summary of the entire program, providing learners with an opportunity to showcase their skills and knowledge to potential employers or collaborators.

## 📄 Project Background
SpaceX has emerged as a major player in the commercial space industry, offering cost-effective space travel options to its clients. The company boasts of its Falcon 9 rocket launches on its website, which are priced at 62 million dollars. In contrast, other providers charge upwards of 165 million dollars for their launches, largely due to the fact that SpaceX can reuse the first stage of its rockets. Thus, if we can predict whether the first stage will land successfully, we can accurately estimate the cost of a launch.

With the help of publicly available information and machine learning models, we aim to predict whether SpaceX will be able to reuse the first stage of its rockets. This will allow us to forecast the cost of a launch and provide valuable insights into SpaceX's business model. By leveraging data science techniques and analyzing historical data, we can develop a predictive model that can accurately forecast whether the first stage of a rocket will land successfully or not.

## 📄 Questions to be answered
1. How do factors such as payload mass, launch site, number of flights, and orbits influence the success of the first stage landing in SpaceX rockets?

2. Is there a discernible trend in the success rate of first stage landings over the years?

3. Which machine learning algorithm is most appropriate for binary classification in this scenario?

## 📄 Methodology
1. Data Collection: I collected data from SpaceX's REST API with Web Scraping. The REST API provided me with detailed information on SpaceX rocket launches
2. Data Wrangling: I filtered the data to remove any irrelevant information and dealt with missing values using appropriate techniques. Additionally, I used one-hot encoding to prepare the data for binary classification.
3. Exploratory Data Analysis (EDA): I conducted EDA using visualization techniques and SQL queries to gain insights into the data and identify trends and patterns. This helped me understand how different factors such as launch site, payload mass, and orbits impacted the success of first stage landings.
4. Interactive Visual Analytics: I leveraged tools such as Folium and Plotly Dash to create interactive visualizations that enabled me to explore the data in greater detail. This allowed me to identify relationships between different variables and examine the data from different perspectives.
5. Predictive Analysis: Finally, I used classification models to make predictions about the likelihood of a successful first stage landing. I built, tuned, and evaluated different classification models to ensure the best possible results. I used various techniques such as cross-validation, hyperparameter tuning, and feature selection to optimize my models and improve their accuracy.
