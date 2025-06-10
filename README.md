🏐 Volleyball Nations League 2023 – Data Analysis
This project analyzes player performance data from the Volleyball Nations League 2023 (VNL 2023) using Python and visualization libraries like matplotlib and seaborn. It explores individual and country-level stats such as Attack, Block, Serve, Dig, and more.

📁 Dataset
File: VNL2023.csv
Shape: 131 rows × 10 columns
Columns:

Player: Player Name

Country: Represented Country

Age: Age of Player

Attack, Block, Serve, Set, Dig, Receive: Performance Metrics

Position: Playing Position (OH, OP, MB, L, S)

📊 Objectives
Understand the distribution and correlation of player performance metrics.

Compare average performance stats across different countries and age groups.

Visualize position-wise contributions in metrics like Attack and Serve.

Identify trends and relationships (e.g., how Serve varies with Age).

📈 Key Analyses & Visualizations
🔍 Data Exploration
Checked for missing and duplicate values.

Generated summary statistics (mean, std, min, max, etc.).

📉 Correlation Matrix
Used a heatmap to visualize relationships between numeric features.

🧩 Position Distribution
Pie chart showing proportion of player roles (OH, OP, MB, L, S).

🌍 Country-Based Analysis
Average Attack by Country: Bar chart for top 5 performing countries.

Total Attack & Block by Country: Stacked bar chart.

📅 Age-Based Trends
Serve vs. Age: Line chart showing average serve performance across age groups.

Age Histogram: Frequency distribution of players’ ages.

📌 Position-Based Analysis
Average Attack by Position: Bar chart comparing attacking capability.

📦 Outlier Detection
Box plot for Serve values to identify outliers.

🔄 Scatter Plot
Block vs. Receive: Scatter plot to identify potential patterns.

🛠️ Tools & Libraries
Python 3

Pandas for data manipulation

Matplotlib and Seaborn for visualization
