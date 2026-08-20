# 🏏 IPL Batting Performance Analysis

## 📌 Project Overview

This project analyzes **Indian Premier League (IPL) batting performance** using player-level career progression data.

The analysis focuses on exploring batting performance across different IPL seasons, comparing players, engineering additional batting metrics, identifying top performers, and discovering relationships between batting statistics.

The project was developed using **Python and Pandas**, with visualization and statistical analysis performed using common Python data-analysis libraries.

---

## 📊 Dataset

The dataset used in this project was obtained from **Kaggle**.

It contains **2,782 player-season records** and **15 features**, covering IPL batting performance across different seasons.

Each row represents a player's batting performance for a particular IPL season.

### Dataset Features

| Feature               | Description                                            |
| --------------------- | ------------------------------------------------------ |
| `player_name`         | Name of the IPL player                                 |
| `country`             | Player's country                                       |
| `season`              | IPL season/year                                        |
| `team`                | Team the player represented during that season         |
| `innings`             | Number of innings played by the player                 |
| `not_outs`            | Number of innings in which the player remained not out |
| `runs_scored`         | Total runs scored by the player                        |
| `balls_faced`         | Total number of balls faced                            |
| `batting_average`     | Batting average for the season                         |
| `batting_strike_rate` | Runs scored per 100 balls faced                        |
| `highest_score`       | Player's highest individual score during the season    |
| `hundreds`            | Number of centuries scored                             |
| `fifties`             | Number of half-centuries scored                        |
| `fours`               | Number of fours hit                                    |
| `sixes`               | Number of sixes hit                                    |

---

## 🧹 Data Cleaning

The dataset was inspected for:

* Missing values
* Duplicate records
* Incorrect data types
* Invalid numerical values
* Potential inconsistencies in batting statistics

---

## ⚙️ Feature Engineering

Additional batting metrics were calculated during the analysis.

### Runs Per Innings

Measures the average number of runs scored per innings.

```text
Runs Per Innings = Runs Scored / Innings
```

### Dismissals

The number of times a player was dismissed.

```text
Dismissals = Innings - Not Outs
```

### Batting Average

Measures the number of runs scored per dismissal.

```text
Batting Average = Runs Scored / Dismissals
```

### Balls Per Innings

Measures the average number of deliveries faced per innings.

```text
Balls Per Innings = Balls Faced / Innings
```

### Strike Rate

Measures how quickly a player scores runs.

```text
Strike Rate = (Runs Scored / Balls Faced) × 100
```

### Boundary Runs

Measures runs scored through fours and sixes.

```text
Boundary Runs = (Fours × 4) + (Sixes × 6)
```

### Boundary Percentage

Measures the percentage of a player's runs that came from boundaries.

```text
Boundary Percentage = (Boundary Runs / Runs Scored) × 100
```



## 🔎 Analysis Performed

The project explores several aspects of IPL batting performance, including:

### Player Performance

* Top run scorers
* Players with the highest batting averages
* Players with the highest strike rates
* Players with the most sixes and fours
* Players with the highest runs per innings

### Comparative Analysis

Players are compared using multiple batting metrics rather than relying only on total runs.

Minimum-innings filters can also be applied to prevent players with very few appearances from dominating rankings.





---

## 📈 Visualizations

The project includes visualizations such as:

* Top run scorers
* Batting average comparisons
* Career progression across seasons


---

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Scikit-learn**
* **Jupyter Notebook / Google Colab**

---

## 📁 Project Structure

```text
ipl-batting-analysis/
│
├── data/
│   └── ipl_batting_career_progression.csv
│
├── notebooks/
│   └── ipl_batting_analysis.ipynb
│
├── README.md
│
└── requirements.txt
```

---

## 🎯 Project Objectives

The main objectives of this project are to:

1. Clean and prepare IPL batting data for analysis.
2. Perform exploratory data analysis.
3. Engineer meaningful cricket performance metrics.
4. Compare IPL batsmen using multiple statistics.
5. Analyze relationships between batting metrics.
6. Study player performance across IPL seasons.
7. Generate meaningful insights from cricket data.

---

## 💡 Key Questions

The analysis attempts to answer questions such as:

* Who are the highest-scoring IPL batsmen?
* Which players have the highest batting averages?
* Which batsmen are the most aggressive?
* Does a high strike rate come at the cost of batting average?
* Who performs best when multiple batting metrics are considered together?

---

## 🚀 Future Improvements

Possible extensions to this project include:

* Adding IPL bowling performance data
* Creating a combined batting and bowling performance score
* Analyzing team performance
* Building an interactive dashboard using Power BI or Streamlit
* Predicting future player performance using machine learning
* Comparing players from different IPL eras

---

## 📚 Data Source

**Source:** Kaggle

The dataset used in this project was obtained from Kaggle and is used for educational and data-analysis purposes.

---

## 👤 Author

**Hammad Ur Rehman Tariq**

BS Computer Science, UMT LAHORE
Interested in Data Analysis, Machine Learning, and AI
