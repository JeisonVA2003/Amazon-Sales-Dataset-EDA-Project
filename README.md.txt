Amazon Sales Exploratory Data Analysis (EDA)
📖 Overview
This project performs an Exploratory Data Analysis (EDA) on the Amazon Sales Dataset. The primary goal is to analyze product categories, pricing, and ratings to uncover factors influencing consumer purchasing decisions. By exploring these patterns, the analysis provides actionable insights for businesses to optimize product development and marketing strategies.

🎯 Objectives
The main objectives of this analysis are to:

Identify Key Product Characteristics: Determine which product features drive sales and resonate with customers.

Provide Actionable Recommendations: Translate data insights into strategies for product development and marketing.

Enhance Consumer Alignment: Equip businesses with the knowledge to design products that meet customer needs and preferences.

Optimize Marketing: Develop communication strategies tailored to specific consumer groups to maximize engagement.

🛠️ Process
The analysis follows a structured approach:


Data Cleaning and Preparation: Ensuring data accuracy and consistency by handling missing values and correcting data types.






Descriptive Statistics: Summarizing the data with measures like mean, standard deviation, and quartiles.



Data Visualization: Using histograms and bar charts to identify trends, patterns, and relationships within the data.



Insight Generation: Segmenting data and summarizing key findings to derive meaningful conclusions.

⚙️ Technologies & Libraries
This project utilizes 

Python and the following core data science libraries:



Pandas: For data manipulation and analysis.


NumPy: For numerical operations.


Matplotlib & Seaborn: For data visualization and creating statistical graphics.


SciPy: For scientific and advanced mathematical computing.

📈 Key Findings
Price and Rating Distributions: Most products are priced at the lower end of the spectrum, with prices heavily skewed. Product ratings are generally positive, with a strong concentration between 4.0 and 4.5.


Category Performance: "Computers & Accessories" and "Electronics" are the most dominant categories in terms of product count and have some of the highest average ratings. "Computers & Accessories | Tablets" stands out with the highest average rating of 4.6.



Price Variation: Categories like "Home & Kitchen" and "Electronics" show the highest price variation (standard deviation), indicating a wide range of products from budget to premium.


Correlations: There is a very strong positive correlation (0.96) between actual_price and discounted_price. Other correlations, such as between price and rating, are very weak.



🚀 How to Run
Clone the repository.

Install the required libraries:

Bash

pip install pandas numpy matplotlib seaborn scipy
Run the Jupyter Notebook or Python script to execute the analysis.