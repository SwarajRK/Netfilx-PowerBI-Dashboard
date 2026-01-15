# Netflix Power BI Dashboard Project

## 📊 Project Overview

This project involves building an **interactive Power BI dashboard** using the Netflix dataset to analyze content trends, distribution, and key insights across different dimensions such as genre, country, release year, and content type.

The dashboard is designed to help users quickly understand Netflix’s content library and identify patterns in movies and TV shows using intuitive visualizations.

---

## 🗂️ Dataset Information

* **Dataset Name:** Netflix Titles Dataset
* **Source:** Public Netflix dataset (CSV format)
* **File Used:** `netflix_titles.csv`
* **Records:** Movies and TV Shows available on Netflix

### 📌 Key Columns

* `show_id` – Unique ID for each title
* `type` – Movie or TV Show
* `title` – Name of the content
* `director` – Director name
* `cast` – Cast details
* `country` – Country of production
* `date_added` – Date added to Netflix
* `release_year` – Year of release
* `rating` – Content rating
* `duration` – Duration (minutes or seasons)
* `listed_in` – Genre/category
* `description` – Short description

---

## 📈 Dashboard Features

* Total Movies and TV Shows count
* Content distribution by **Type (Movie vs TV Show)**
* Titles by **Release Year** trend
* Content distribution by **Country**
* Popular **Genres/Categories**
* Ratings-wise content analysis
* Interactive slicers for:

  * Type
  * Country
  * Release Year
  * Genre

---

## 🛠️ Tools & Technologies Used

* **Power BI Desktop** – Data modeling & visualization
* **CSV Dataset** – Data source
* **Power Query** – Data cleaning & transformation
* **DAX** – Measures and calculated columns

---

## 🔄 Data Cleaning & Transformation

* Removed null and inconsistent values
* Split multi-valued columns (Genres, Countries)
* Standardized date formats
* Created calculated measures for KPIs

---

## 📌 Key Insights Generated

* Movies dominate Netflix’s content library
* Rapid increase in content after 2015
* USA leads in content production
* Drama and International content are top genres

---

## 📁 Project Files

* `Netfilx.pbix` – Power BI dashboard file
* `netflix_titles.csv` – Raw dataset
* `README.md` – Project documentation

---

## 🚀 How to Use

1. Download all project files
2. Open `Netfilx.pbix` using **Power BI Desktop**
3. Refresh data if required
4. Use slicers and visuals to explore insights

---

## 👤 Author

**Swaraj Karvande**
Aspiring Data Analyst | Power BI | SQL | Python

---

## ⭐ Notes

This project is intended for **learning, portfolio, and resume showcase purposes**.

Feel free to fork, improve, or customize the dashboard.

