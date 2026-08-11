# 🔭 Are We Alone in Space? NASA Exoplanet Analysis

An exploratory data analysis project using real data from NASA's Exoplanet Archive to investigate relationships between planetary characteristics and patterns in exoplanet discoveries.

## 📌 Project Overview

This project explores a dataset containing **1,653 exoplanets** and **1,272 unique host stars**.

The analysis focuses on understanding relationships between planet size, mass, orbital period, and discovery year, while also examining the different methods used to discover exoplanets.

The project combines Python programming, statistical analysis, and data visualization to explore real scientific data.

## 🎯 Objectives

The main goals of this project were to:

* Load and inspect a real scientific dataset
* Practice data analysis using Python and Pandas
* Use basic Python techniques for working with lists, sets, and dictionaries
* Explore relationships between planetary characteristics
* Calculate descriptive statistics
* Visualize distributions, relationships, and trends
* Create interactive 2D and 3D visualizations

## 🔬 Questions Explored

### 1. Planet Size vs. Planet Mass

Do larger planets necessarily have greater mass?

A scatter plot was used to investigate the relationship between planetary radius and mass.

### 2. Discovery Year vs. Planet Size

Has the size of discovered planets changed over time?

The project explores whether improvements in detection technology may have contributed to the discovery of smaller planets in more recent years.

### 3. Discovery Methods

Which discovery methods have been used most frequently to identify exoplanets?

The project compares the number of planets discovered using different detection methods.

## 📊 Dataset

The dataset contains information about exoplanets and their host stars.

### Main columns

| Column            | Description                        |
| ----------------- | ---------------------------------- |
| `pl_name`         | Planet name                        |
| `pl_rade`         | Planet radius in Earth radii       |
| `pl_bmasse`       | Planet mass in Earth masses        |
| `pl_orbper`       | Planet orbital period              |
| `discoverymethod` | Method used to discover the planet |
| `hostname`        | Host star name                     |
| `disc_year`       | Year the planet was discovered     |

The dataset used in the analysis contains **1,653 records with no missing values in the selected columns**.

## 🛠️ Tools & Technologies

* **Python**
* **Pandas** — data loading, cleaning, manipulation, and statistics
* **Matplotlib** — static visualizations
* **Seaborn** — statistical visualizations
* **hvPlot** — interactive visualizations
* **Plotly Express** — interactive 3D visualization
* **Jupyter Notebook** — development environment

## 📈 Analysis & Visualizations

The project includes several visualizations designed to explore the dataset from different perspectives.

### Planet Radius Distribution

A histogram was used to examine the distribution of planet radii.
<img width="695" height="475" alt="histogram of planet radii" src="https://github.com/user-attachments/assets/fcf047ec-c6b7-4a47-abd3-a8af8ecae0db" />


### Discovery Methods

A horizontal bar chart was used to compare the most common exoplanet discovery methods.
<img width="1031" height="547" alt="top 10 discovery methods" src="https://github.com/user-attachments/assets/25a6ee3f-b34a-40ee-ad0a-1567e6828b72" />


### Radius vs. Mass

An interactive scatter plot was created to explore the relationship between planetary radius and mass.
<img width="1400" height="1000" alt="planet radius vs  planet mass" src="https://github.com/user-attachments/assets/1db85db2-b968-43f5-be2c-f089a6d975be" />


### Orbital Periods

An interactive boxplot was used to examine the distribution of orbital periods and identify potential outliers.
<img width="1400" height="600" alt="distribution of exoplanet orbital periods" src="https://github.com/user-attachments/assets/44b66d97-ad45-46be-a36a-fa0c6af5f5c1" />


### Radius vs. Discovery Year

An interactive scatter plot was used to investigate how planet radius varies across discovery years.

<img width="1400" height="600" alt="planet radius vs  discovery year" src="https://github.com/user-attachments/assets/f5635906-49b5-4574-80b4-cbde95e3b380" />

### Correlation Matrix

A correlation matrix was created to examine relationships between:

* Planet radius
* Planet mass
* Orbital period
<img width="1094" height="754" alt="correlation matrix of numeric veriables" src="https://github.com/user-attachments/assets/96de307f-556b-40cc-a29f-bd5398db6aa1" />


### Planet Radius Statistics Over Time

Mean and median planet radius were calculated for each discovery year and visualized using interactive line plots.

<img width="1400" height="600" alt="planet radius statistics over discovery years" src="https://github.com/user-attachments/assets/4b46cc78-d4a9-4812-a012-c15f1024c9cb" />

### 3D Planetary Characteristics

A 3D interactive scatter plot was created using Plotly to simultaneously explore:

* Planet radius
* Planet mass
* Orbital period

The points are colored by discovery method, with logarithmic scales used across the three axes to handle the wide range of values.

<img width="800" height="517" alt="3D plot of planet characteristics by discovery method" src="https://github.com/user-attachments/assets/3b89e969-81eb-4de1-8de8-c06e67c27fd3" />



## 🌟 Key Findings

### Exoplanet & Host Star Counts

The dataset contains:

* **1,653 unique planets**
* **1,272 unique host stars**

### Host Stars With the Most Known Planets

The three host stars with the highest number of known planets in the dataset were:

| Host Star  | Known Planets |
| ---------- | ------------: |
| TRAPPIST-1 |             7 |
| HD 110067  |             6 |
| K2-138     |             6 |

### Planetary Characteristics

The dataset shows a very wide range of planetary characteristics, including:

* Planet radius from approximately **0.30 to 65.85 Earth radii**
* Planet mass from **0.1 to 8,899 Earth masses**
* Orbital periods ranging from very short periods to extremely long periods

These wide ranges motivated the use of logarithmic scales in several visualizations.

## 🧠 What I Practiced

This project provided hands-on practice with:

* Loading and inspecting datasets with Pandas
* Checking data types and missing values
* Computing descriptive statistics
* Working with Python lists, sets, and dictionaries
* Finding unique values without relying on Pandas `unique()` or `value_counts()`
* Sorting and ranking data
* Grouping data by year
* Calculating mean and median statistics
* Exploring correlations
* Creating static visualizations
* Creating interactive visualizations
* Building an interactive 3D visualization

## 📁 Project Structure

```text
NASA-exoplanet-analysis/
│
├── NASA Exoplanets Analysis.ipynb
├── README.md
│
└── images/
    └── 3d-visualization.gif
```

## 🚀 How to Run

1. Clone this repository.
2. Open `NASA Exoplanets Analysis.ipynb` in Jupyter Notebook, JupyterLab, or Google Colab.
3. Install the required Python libraries if necessary.
4. Run the notebook cells sequentially.

## 🔭 Project Context

This project combines my background in **physics** with my developing skills in **data analytics**, using real astronomical data to investigate scientific questions through data.

---

**Project type:** Exploratory Data Analysis
**Domain:** Astronomy / Exoplanets
**Tools:** Python, Pandas, Matplotlib, Seaborn, hvPlot, Plotly
