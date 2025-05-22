# 🧱 Examining LEGO Sets History

**A Data-Driven Exploration of LEGO's Evolution, Licensing Strategies, and Set Complexity**

## 📌 Overview

This project delves into the rich history of LEGO sets, utilizing data analysis to uncover trends, patterns, and insights. By examining various aspects such as licensing, theme popularity, and set complexity, we aim to understand how LEGO has evolved over the years and the impact of strategic decisions on its product offerings.

## 📂 Project Structure

* **`datasets/`**: Contains CSV files with detailed information on LEGO sets and themes.
* **`notebooks/`**: Jupyter Notebooks with step-by-step analyses and visualizations.
* **`README.md`**: This documentation file providing an overview and insights into the project.

## 📊 The Data

A summary and preview of the two datasets used in this analysis are provided below.

### `lego_sets.csv`

This dataset contains detailed information about individual LEGO sets.

**Preview:**

| set\_num | name                       | year | num\_parts | theme\_name  | parent\_theme |
| -------- | -------------------------- | ---- | ---------- | ------------ | ------------- |
| 00-1     | Weetabix Castle            | 1970 | 471.0      | Castle       | Legoland      |
| 0011-2   | Town Mini-Figures          | 1978 | NaN        | Supplemental | Town          |
| 0011-3   | Castle 2 for 1 Bonus Offer | 1987 | NaN        | Lion Knights | Castle        |
| 0012-1   | Space Mini-Figures         | 1979 | 12.0       | Supplemental | Space         |
| 0013-1   | Space Mini-Figures         | 1979 | 12.0       | Supplemental | Space         |

**Columns:**

* `"set_num"`: A unique identifier for each set.
* `"name"`: The name of the LEGO set.
* `"year"`: The year the set was released.
* `"num_parts"`: The number of parts contained in the set. Missing values are acceptable.
* `"theme_name"`: The sub-theme of the set.
* `"parent_theme"`: The overarching theme the set belongs to, matching the `name` column in `parent_themes.csv`.

### `parent_themes.csv`

This dataset provides information about the parent themes of LEGO sets.

**Preview:**

| id  | name    | is\_licensed |
| --- | ------- | ------------ |
| 1   | Technic | False        |
| 22  | Creator | False        |
| 50  | Town    | False        |
| 112 | Racers  | False        |
| 126 | Space   | False        |

**Columns:**

* `"id"`: A unique identifier for each parent theme.
* `"name"`: The name of the parent theme.
* `"is_licensed"`: A Boolean indicating whether the theme is licensed.

## 📈 Key Analyses & Findings

### 1. **Licensed Sets & Star Wars Dominance**

* **Insight**: Approximately **45%** of all licensed LEGO sets are Star Wars themed, highlighting the significant impact of this franchise on LEGO's licensing strategy.

### 2. **Peak Year for Star Wars Sets**

* **Finding**: The year **2016** witnessed the highest number of Star Wars set releases, indicating a peak in the theme's popularity and LEGO's focus on this franchise during that period.

### 3. **Top 5 Parent Themes by Set Count**

* **Themes**:

  1. Town
  2. Seasonal
  3. Star Wars
  4. Technic
  5. Service Packs

  These themes have consistently been at the forefront of LEGO's product lines, reflecting their enduring popularity and LEGO's commitment to these categories.

### 4. **Licensed Sets Over Time**

* **Trend**: A visual analysis showcases the trajectory of licensed set releases over the years, providing insights into LEGO's strategic partnerships and market focus.

### 5. **Themes with Highest Average Parts per Set**

* **Top Themes**:

  1. Disney: 4,060.0 parts
  2. Sculptures: 1,904.12 parts
  3. Modular Buildings: 1,670.38 parts
  4. FIRST LEGO League: 1,469.71 parts
  5. Model Team: 725.88 parts

  The **Disney** theme stands out with an average of **4,060.0** parts per set, significantly surpassing other themes and underscoring LEGO's investment in complex, detailed builds for this category.

## 🛠️ Tools & Technologies

* **Programming Language**: Python
* **Data Manipulation**: pandas
* **Visualization**: matplotlib
* **Environment**: Jupyter Notebook

## 📚 Data Source

* **Rebrickable Dataset**: Comprehensive data on LEGO sets and themes, providing a robust foundation for analysis.

## 🚀 Getting Started

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/yourusername/lego-sets-history.git
   cd lego-sets-history
   ```

2. **Install Dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

3. **Launch Jupyter Notebook**:

   ```bash
   jupyter notebook
   ```

4. **Explore Analyses**:

   * Navigate to the `notebooks/` directory and open the desired analysis notebook to explore insights and visualizations.

## 🤝 Contributing

Contributions are welcome! If you have suggestions, enhancements, or new analyses to add, please fork the repository and submit a pull request.

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---
