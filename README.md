# 🍽️ Eat Safe, Love – UK Food Hygiene Ratings (MongoDB Project)

**Author:** Logan Dameron

*A data science project created for educational purposes as part of the edX Data Science Bootcamp.*

---

## 🚀 Overview

This project explores UK food safety inspection data using **MongoDB** and **PyMongo**.  
The objective: help food journalists and critics identify the cleanest (and least clean) establishments across the UK.

The project consists of two parts:
- **Database Setup & Cleaning** (in `NoSQL_setup_starter.ipynb`)
- **Exploratory Data Analysis** (in `NoSQL_analysis_starter.ipynb`)

---

## 🌐 Data Source

- [UK Food Standards Agency Open Data](https://ratings.food.gov.uk/open-data/en-GB)
- Contains food hygiene ratings, geolocation, business types, and inspection scores.

---

## ⚙️ Technologies Used

- MongoDB & PyMongo
- Jupyter Notebook
- Pandas
- JSON

---

## 🔍 Queries & Analysis

Using PyMongo and Pandas, we answered the following:

1. Which establishments have a hygiene score of 20?  
2. Which establishments in London have a rating value of 4 or higher?  
3. What are the 5 best-rated (cleanest) establishments nearest to "Penang Flavours"?  
4. Which local authority areas have the most establishments with a hygiene score of 0?

All logic and analysis are located in `NoSQL_analysis_starter.ipynb`.

---

## 📁 Folder Structure

```bash
📦 nosql-challenge
 ┣ 📂 Resources
 ┃ ┗ 📜 establishments.json
 ┣ 📜 NoSQL_setup_starter.ipynb
 ┣ 📜 NoSQL_analysis_starter.ipynb
 ┣ 📜 README.md