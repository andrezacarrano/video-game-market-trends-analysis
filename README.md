
# 🎮 Predictive Analysis of Video Game Success: Global Market

## 1. Project Objective

Identify patterns associated with commercial success for the online retailer Ice by analyzing historical sales data, expert reviews, and ESRB age ratings.

The project aims to forecast trends to support advertising campaign planning for 2017, mapping platform life cycles and consumer preferences across the North American, European, and Japanese markets.

## 2. Results

### Platform Life Cycle Analysis

Identified that video game platforms typically have an average life cycle of 5 to 10 years before becoming obsolete, with PS4 and Xbox One leading sales volume during the analyzed period.

### Regional Market Intelligence

Identified significant cultural differences across regions. While Western markets (North America and Europe) show a preference for Action and Shooter genres, the Japanese market demonstrates a stronger preference for RPGs and handheld consoles, particularly the Nintendo 3DS.

### Sales Drivers

Found a moderate positive correlation between critic scores and sales, suggesting that critic reviews are a more reliable indicator of commercial success than user ratings.

### Impact of ESRB Ratings

Demonstrated that specific age ratings influence market share differently depending on the geographic region.

## 3. Tools & Technologies

- **Programming Language:** Python
- **Main Libraries:** Pandas (data cleaning and processing), Matplotlib and Seaborn (exploratory data visualization).
- **Statistical Analysis:** SciPy.stats (hypothesis testing).
- **Development Environment:** VS Code and Jupyter Notebook.

## 4. Skills Developed

- **Data Normalization:** Standardizing column names using the `snake_case` convention and converting data types to optimize memory usage.
- **Handling Data Inconsistencies (TBD):** Managing the abbreviation "TBD" (to be determined) by converting it into missing values (`NaN`), allowing statistical calculations to be performed without compromising the sample.
- **Regional Comparative Analysis:** Building detailed user profiles for each region (North America, Europe, and Japan).
- **Statistical Hypothesis Testing:** Applying the Student's t-test to evaluate the following assumptions:

  - **Hypothesis 1:** Average user ratings for Xbox One and PC platforms are equal.

    \(H_0: \mu_1 = \mu_2\)

  - **Hypothesis 2:** Average user ratings for the Action and Sports genres are different.

    \(H_0: \mu_1 = \mu_2\) vs. \(H_1: \mu_1 \neq \mu_2\)

## 5. Future Improvements

- **Platform Churn Analysis:** Predicting when users will fully migrate to next-generation consoles.
- **Web Scraping:** Integrating real-time data through the Metacritic API to enrich the analysis with additional review scores.
- **Pricing Analysis:** Investigating the impact of promotions and launch prices on sales velocity (sell-through).

---

**Project Focus:** Data Cleaning | Exploratory Data Analysis | Regional Market Analysis | Statistical Hypothesis Testing | Python | Pandas | SciPy
