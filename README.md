# 📊 Unmasking YouTube Dislikes: An Exploratory Data Analysis Journey in Social Media

Welcome to my graded Python project, where I dived deep into the world of YouTube to uncover intriguing insights about **video dislikes** using data science techniques. This project was completed as part of the **Programming with Python** course at Great Learning under the mentorship of Professor Sreevasan P S.

---

## 🚀 Project Summary

With YouTube deciding to hide dislike counts in late 2021, this dataset captures a crucial time frame just before that decision. The goal of this project is to explore the **YouTube Dislikes Dataset** and derive insights into user behavior and content engagement using **Python**, specifically **Pandas**, **NumPy**, **Matplotlib**, and **Seaborn**.

---

## 🎯 Project Goals

- Perform end-to-end **Exploratory Data Analysis (EDA)** on YouTube trending video data
- Analyze the factors that influence **dislikes** on videos
- Understand trends based on **publish month**, **channel activity**, and **viewer engagement**
- Provide actionable **visual insights** into user interaction before dislike counts were hidden

---

## 🗂️ Data Structure

The dataset consists of trending YouTube video records from **August 2020 to December 2021** for the USA, Canada, and Great Britain. Key columns include:

| Column Name         | Description                                |
|---------------------|--------------------------------------------|
| `video_id`          | Unique video identifier                    |
| `title`             | Title of the video                         |
| `channel_id`        | Unique ID of the channel                   |
| `channel_title`     | Name of the channel                        |
| `published_at`      | Date and time when the video was published |
| `views`             | Total number of views                      |
| `likes`             | Number of likes                            |
| `dislikes`          | Number of dislikes                         |
| `comment_count`     | Number of comments                         |
| `tags`              | Video tags                                 |
| `description`       | Video description                          |
| `comments`          | Top 20 comments (in one string)            |

---

## 🧼 Data Preparation

- Loaded the dataset using Pandas
- Inspected data types and structure
- Handled missing values via dropping/imputation
- Converted `published_at` to datetime format
- Extracted and mapped the `published_month` column from `published_at`

---

## 📈 Exploratory Data Analysis (EDA)

Key tasks performed:

1. **Basic Exploration**:
   - Top 5 & bottom 5 records
   - Dataset shape and data types
   - Missing values percentage

2. **Descriptive Statistics**:
   - Summary statistics of numerical and categorical features

3. **Temporal Trends**:
   - Extracted and visualized video counts per month
   - Identified peak months of video publishing

4. **Content Insights**:
   - Found most and least liked/disliked videos
   - Count of unique `video_id`, `channel_id`, and `channel_title`
   - Top 10 and Bottom 10 channels by video count

5. **Correlation Analysis**:
   - Investigated relation between **views** and **dislikes** using scatter plots and correlation metrics

6. **Focused Filter**:
   - Isolated videos published in **January** and analyzed them separately

---

## 📊 Key Insights

- **October** was the month with the highest number of video uploads.
- A strong **positive correlation** was found between views and dislikes — more views often meant more dislikes too.
- Certain channels like *The Tonight Show Starring Jimmy Fallon* appeared frequently with high video counts.
- Videos with polarizing or viral content received disproportionate dislikes.
- The **most disliked video** had millions of views, confirming that visibility often invites criticism.

---

## 🧾 Conclusion

This project offered a comprehensive look into the **dislike metrics** of YouTube before it became hidden from the public. The findings support that:
- **User engagement (views, likes, dislikes)** is deeply interlinked.
- Trends vary **monthly and per channel**.
- EDA helps surface unexpected patterns, such as spikes in activity or anomalies in dislikes.

It was an enriching experience that honed my Python skills and deepened my understanding of social media data analysis.

---

## 📚 Dataset Information

- **Name**: YouTube Dislikes Dataset
- **Size**: ~190 MB (CSV)
- **Timeframe**: Aug 2020 – Dec 13, 2021
- **Regions**: USA, Canada, Great Britain

---

## 🧠 Tech Stack Used

- **Languages**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn
- **Platform**: Jupyter Notebook

---


## 🙌 Acknowledgements

- **Professor Sreevasan P S**, for invaluable guidance
- **Great Learning Academy**, for the platform and curriculum

---


