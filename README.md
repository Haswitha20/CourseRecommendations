# 🎓 Course Recommendation Expert System

A rule-based expert system that recommends suitable courses based on a learner's interests, skill level, and preferred learning style.

## 📌 Project Overview

The Course Recommendation Expert System uses rule-based reasoning to suggest courses that match the learner's preferences.

The system takes three inputs:

- **Interests**
- **Skill Level**
- **Learning Preference**

It then calculates a match score and displays ranked course recommendations.

## ✨ Features

- Select one or more areas of interest
- Choose Beginner, Intermediate, or Advanced skill level
- Choose Practical Projects, Theory, or Both as learning preference
- Get ranked course recommendations
- View match scores for recommended courses
- View reasons for each recommendation
- Simple and user-friendly Streamlit interface

## 🧠 How the Expert System Works

The system uses a knowledge base containing course information and a rule-based scoring mechanism.

The scoring system is:

- **Interest Match:** 50 points
- **Skill Level Match:** 30 points
- **Learning Preference Match:** 20 points

The courses are then ranked from the highest score to the lowest score.

## 📚 Course Areas

The system currently provides recommendations for:

- Programming
- Web Development
- Data Science
- Cybersecurity
- Design

## 🛠️ Technologies Used

- Python
- Streamlit
- Rule-Based Expert System
- IF–THEN style reasoning

## 📁 Project Structure

```text
CourseRecommendations/
│
├── app.py
├── knowledge_base.py
├── inference_engine.py
├── requirements.txt
├── README.md
├── .gitignore
│
└── .streamlit/
    └── config.toml