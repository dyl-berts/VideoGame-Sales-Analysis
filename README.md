### 🎮 Video Game Market Analysis: Decades of Gaming Trends

Project Overview

This project delves into a historical dataset of video game sales to uncover significant trends and competitive dynamics within the global gaming market. Leveraging Python for data manipulation, analysis, and visualization, the goal is to provide a clear understanding of genre popularity shifts and the market share evolution of leading publishers over time.

This analysis is particularly useful for game developers, publishers, and industry enthusiasts looking to identify long-term patterns, understand market dominance, and inform strategic decisions.

Key Features & Analysis

Comprehensive Data Loading & Cleaning: Efficient handling of raw sales data, including necessary cleaning and preparation for robust analysis.

Platform Performance Analysis:

Quantifies the overall contribution of each gaming platform to total global sales.

Visualizes the spread and central tendency of individual game sales on different platforms, identifying platforms with consistently high-selling titles versus those with more varied performance.

Highlights the individual blockbuster titles that drove sales on each major platform.

Genre Market Share Evolution:

Identifies the most prominent video game genres.

Visualizes how the global market share of these genres has changed year-over-year using stacked area charts.

Visualizes the spread and central tendency of individual game sales within different genres, identifying genres with consistently high-selling titles versus those with more varied performance.

Reveals emerging trends, declining categories, and consistent performers.

Top 10 Publisher Dominance:

Determines the overall top 10 publishers based on their cumulative global sales across the entire dataset.

Analyzes and visualizes the annual global market share of these industry giants.

Showcases the shifting landscape of publisher influence and concentration.

Regional Market Analysis:

Visualizes the spread and central tendency of individual game sales across different geographical regions (e.g., North America, Europe, Japan, Other), highlighting regional market peculiarities and average sales performance.

Visualizes the total global sales by region using a map, providing a quick visual understanding of dominant markets.

Explores the relationships and dependencies between sales in different regions using a correlation heatmap, identifying which markets tend to move in tandem.

Further visualizes the correlation between highly correlated regions to provide deeper insights into their sales relationships and consistency.

Interactive Visualizations: Utilizes Plotly Express to create interactive charts, allowing users to hover over data points for detailed insights into sales figures and market percentages.

Narrative-Driven Analysis: The project is presented in a Jupyter Notebook, where Markdown cells provide detailed explanations of methodologies, insights, and conclusions for each analytical step, making the entire process transparent and easy to follow.

Data Source
The analysis is based on a comprehensive dataset of video game sales, which includes:

Game Titles
Platforms
Release Years
Genres
Publishers
Sales figures across different regions (North America, Europe, Japan, Other)
Global Sales
https://www.kaggle.com/datasets/gregorut/videogamesales


Tools & Technologies Used

Python 3.13.1: The primary programming language.

Numpy 2.2.6: For fundamental numerical operations, array computing, and underpinning data structures in Pandas.

Pandas 2.2.3: For powerful data manipulation and analysis.

Matplotlib 3.10.3: For foundational plotting and creating static visualizations (e.g., initial data exploration, basic charts).

Seaborn 0.13.2: Built on Matplotlib, used for creating aesthetically pleasing statistical graphics and more complex data distributions.

Plotly Express 6.1.2: For creating interactive and visually appealing data visualizations.

Jupyter Notebook: For an interactive development environment, combining code, output, and rich text explanations.


How to Run the Project Locally
To set up and run this project on your local machine, follow these steps:

Clone the Repository:

Bash

git clone https://github.com/dyl-berts/VideoGame-Sales-Analysis.git
cd VideoGame-Sales-Analysis

Create a Virtual Environment (Recommended):

    python -m venv venv
# On Windows:
.\venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate
```

Install Dependencies:

Bash

pip install pandas matplotlib seaborn plotly jupyter

Place Your Data:

Ensure your video game sales .csv file is placed in the project's root directory (or update the file path in the notebook if it's elsewhere).
(If you loaded the CSV into SQLite for the project, mention that here: e.g., "If using SQLite, ensure your your_database_name.db file is present or follow instructions in the notebook to regenerate it from the CSV.")
Launch Jupyter Notebook:

Bash

jupyter notebook
This will open Jupyter in your web browser.

Open and Run the Notebook:
Navigate to the project notebook (e.g., video_game_market_analysis.ipynb) and open it. You can then run all cells to reproduce the analysis and visualizations.

Key Findings (Examples - You'll fill these in with your actual insights!)
The Rise of Action/Adventure: [Briefly describe how genres like Action and Adventure showed consistent growth or dominance over specific periods, perhaps displacing older genres.]
Publisher Consolidation: [Explain if the market became more concentrated among the top 10 publishers over time, or if new players emerged to challenge the old guard.]
Impact of Specific Eras/Consoles: [Mention if any specific console generations or industry events visibly impacted genre or publisher market shares.]
"Other" Publishers' Significance: [Discuss how the collective "Other" category either diminished or held a significant share, indicating market fragmentation or consolidation outside the top 10.]
Future Enhancements
Integrate regional sales analysis (NA_Sales, EU_Sales, JP_Sales, Other_Sales).
Analyze sales trends by platform (e.g., PlayStation, Xbox, Nintendo, PC).
Perform predictive modeling to forecast future genre or publisher performance.
Explore sentiment analysis of game reviews to correlate with sales.

Feel free to connect with me if you have any questions or feedback!

LinkedIn: www.linkedin.com/in/dylan-roberts-975572339
GitHub: https://github.com/dyl-berts
Email: d.roberts@ballstate.bsu.edu