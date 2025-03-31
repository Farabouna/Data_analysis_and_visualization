# Data_analysis_and_visualization
# 📌 Speed Dating with Tinder

## 📇 Company's Description

[Tinder](https://tinder.com/) is an online dating and geosocial networking application where users "swipe right" to like or "swipe left" to dislike other users' profiles. Each profile includes photos, a short bio, and a list of interests.

Tinder was launched by Sean Rad at a hackathon held at the Hatch Labs incubator in West Hollywood in 2012. As of 2021, Tinder has recorded more than **65 billion matches** worldwide.

---

## 🚧 Project Overview

The **marketing team** at Tinder is facing a **decline in matches** and wants to understand **what makes people interested in each other**. To investigate, they conducted a **speed dating experiment**, where participants provided Tinder with **detailed personal information** that could be reflected in their dating profiles.

The dataset collected from this experiment records **each speed date**, along with whether the participants agreed to a second date.

---

## 🎯 Goals

Analyze the dataset to uncover **key factors** influencing **mutual attraction and second-date decisions**, using:

- 📊 **Descriptive statistics**  
- 📈 **Data visualizations**

---

## 🖼️ Scope of This Project

The dataset was gathered from **experimental speed dating events (2002-2004)**. During these events, attendees had a **four-minute first date** with every other participant of the **opposite sex**. After each date, they were asked:

- **Would you like to see this person again?**
- **Rate your date on six attributes:**
  - ✨ **Attractiveness**
  - 🤝 **Sincerity**
  - 🧠 **Intelligence**
  - 🎉 **Fun**
  - 🚀 **Ambition**
  - 💡 **Shared Interests**

Additionally, participants completed **questionnaires** at different stages:
- **Sign-up survey** (before the event)
- **Follow-up survey** (next day)
- **Follow-up 2 survey** (3-4 weeks later)
- **Scorecard** (immediate rating after each date)

📂 **[Dataset](https://full-stack-assets.s3.eu-west-3.amazonaws.com/M03-EDA/Speed+Dating+Data.csv)**  
📖 **[Dataset Description](https://full-stack-assets.s3.eu-west-3.amazonaws.com/M03-EDA/Speed+Dating+Data+Key.doc)**  

---

## 🔑 Key Information

### 📝 Surveys & Scorecard
- **Sign-Up Survey (Time1)**: Completed during registration
- **Follow-Up Survey (Time2)**: Completed the day after the event
- **Follow-Up2 Survey (Time3)**: Completed **3-4 weeks later**
- **Scorecard**: Filled out after each date

### 🔍 Key Features in the Dataset

- **iid**: Unique participant ID
- **gender**: 👩 `0` (Woman) / 👨 `1` (Man)
- **pid**: Partner’s participant ID
- **wave**: Event iteration number
- **round**: Number of participants in the wave
- **order**: Order of the date within the wave
- **dec / dec_o**: Participant & Partner decision (`1 = Yes`, `0 = No`)
- **match**: Mutual match (`1 = Yes`, `0 = No`)
- **match_es**: Estimated number of matches predicted by the participant

### 🧐 Key Questions Explored
1️⃣ **What do you look for in the opposite sex?**  
2️⃣ **What do you think the opposite sex looks for in a date?**  
3️⃣ **How do you think you measure up?**  
4️⃣ **What do you think most people of your gender look for in the opposite sex?**  
5️⃣ **How do you think others perceive you?**  
6️⃣ **What is the actual importance of these attributes in your decisions?** _(Follow-Ups only)_  

💡 **Note:** The **"Shared Interests"** attribute is **not included** in **questions 3 and 5**!

---

## 📊 Analysis & Insights

Using **statistical analysis** and **data visualization**, we aim to uncover:
- **Which factors** most strongly influence mutual attraction.
- The **importance of different attributes** in second-date decisions.
- Patterns in how people perceive themselves vs. how they are rated by others.

🔎 Stay tuned for insights! 🚀

---

# 🎮 Ubisoft's Steam Market Analysis Project

## 📇 Company's Description
Steam is a digital distribution service and storefront for video games developed by Valve. Launched in September 2003, Steam initially provided automatic updates for Valve's games and later expanded to distribute third-party titles in 2005. Today, Steam is one of the largest online gaming platforms, offering various features such as:

- 🎮 Digital Rights Management (DRM)  
- 🕹️ Game Server Matchmaking with Valve Anti-Cheat measures  
- 🎥 Game Streaming Services  
- 💾 Cloud Storage for game progress  
- 💬 Community Features like in-game overlays, direct messaging, and a virtual collectible marketplace.  

With its robust ecosystem, Steam continues to be a significant player in the video game market. 🚀

---

## 🚧 Project Overview  
Ubisoft, a renowned French video game publisher, is planning to release a revolutionary new video game. To ensure its success, they have requested a comprehensive global analysis of the games available on the Steam marketplace.

The goal is to understand the current video game ecosystem and analyze today's trends within the platform to help Ubisoft make data-driven decisions on their upcoming game release. By identifying successful game attributes, market preferences, and pricing models, Ubisoft aims to develop a game that resonates with players worldwide.

This analysis was conducted using Databricks, a collaborative data science platform, to process and analyze the data efficiently. 🖥️💡

---

## 🎯 Goals  
The primary objective of this project is to understand the factors that influence the popularity and sales of video games. However, Ubisoft also requested an in-depth global analysis of the video game market, leveraging the insights to gain a clearer picture of industry trends.

Key goals of the project include:

- 🔍 Identify key factors driving game success on Steam.  
- 📊 Analyze market trends and player preferences.  
- 🏆 Evaluate competitive landscapes and game genres.  
- 📈 Inform game development and marketing strategies based on findings.  
- 💸 Explore pricing models and their relationship with game popularity.  

---

## 🖼️ Scope of the Project  
The project will analyze data from Steam’s marketplace to uncover patterns and trends across a variety of video game genres, player demographics, and market conditions. By doing so, we aim to:

1. 🎯 Understand which game features attract the most attention.  
2. 🧑‍🤝‍🧑 Identify market segments with high potential.  
3. 📅 Highlight emerging trends in gaming preferences.  
4. 💸 Compare the success of various pricing models and game types.  

This analysis will provide Ubisoft with actionable insights for making informed decisions regarding game development, positioning, and marketing. 🚀

---

## 🔑 Key Data Points & Insights  
The analysis will focus on the following key aspects of the Steam marketplace:

- 🎲 Game Genres: Popular genres, such as action, RPG, and strategy.  
- 💰 Sales Data: Metrics like price, sales figures, and discount patterns.  
- 👥 Community Interaction: Engagement metrics, such as reviews, user ratings, and community feedback.  

---

## 🔍 Approach & Methodology  
To achieve the goals outlined above, the project will involve the following steps:

1. 📥 Data Collection: Gather and clean comprehensive data from Steam, focusing on game titles, sales data, user ratings, and other key metrics.  
2. 📊 Exploratory Data Analysis (EDA): Analyze the dataset to identify patterns, trends, and insights.  
3. 📈 Statistical Analysis: Apply statistical methods to understand the relationships between game attributes and their success.  
4. 📉 Data Visualization: Create interactive charts and visualizations to present key findings and insights.  
5. 🌍 Market Insights: Provide a clear analysis of the current and emerging trends in the video game industry.  

All of these steps were executed using Databricks for Big data handeling. 🖥️💡

---

## 📂 Dataset  
The analysis will be based on the Steam dataset, which includes detailed information about various games, user interactions, and sales data. The dataset is located at the following path: s3://full-stack-bigdata-datasets/Big_Data/Project_Steam/steam_game_output.json

📥 **[Dataset Path](s3://full-stack-bigdata-datasets/Big_Data/Project_Steam/steam_game_output.json)**

🔎 Stay tuned for insights! 🚀
