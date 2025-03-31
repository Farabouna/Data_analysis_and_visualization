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

