🎬 Netflix Content Analysis
Python Pandas Status Netflix

A data analysis project exploring Netflix content distribution, analyzing movies vs TV shows, country-wise production, and release year trends using Python and Pandas.

🎯 Project Overview
This project analyzes a Netflix content dataset to uncover insights about the platform's content library. The analysis focuses on understanding content distribution patterns, geographical production trends, and temporal patterns in content releases.

Key Objectives:
📊 Analyze the distribution of Movies vs TV Shows
🌍 Identify top content-producing countries
📅 Examine content release trends over time
⭐ Explore rating distributions
📈 Key Findings
1. Content Type Distribution
Content Type	Count	Percentage
Movies	4	50%
TV Shows	4	50%
Insight: The dataset shows an equal split between Movies and TV Shows, indicating Netflix's balanced approach to content diversity.

2. Country-wise Production
Country	Content Count	Market Share
United States	5	62.5%
Spain	1	12.5%
Germany	1	12.5%
South Korea	1	12.5%
Insight: United States dominates content production with over 60% of the content, though Netflix is expanding into international markets.

3. Release Year Trends
Earliest Release: 2008 (Breaking Bad)
Latest Release: 2020 (Extraction)
Peak Years: 2017 & 2019 (2 releases each)
Insight: Most content in this dataset was released after 2016, showing Netflix's recent focus on original content.

4. Rating Distribution
TV-MA (Mature Audiences): Most common rating for TV Shows
R-Rated: All movies in the dataset are R-rated
🛠️ Technologies Used
Python 3.8+ - Programming language
Pandas - Data manipulation and analysis
Jupyter Notebook - Interactive development
📁 Project Structure
Netflix-Content-Analysis/
│
├── netflix.csv                    # Netflix dataset (8 records)
├── Netflix_Analysis.ipynb         # Main analysis notebook
├── README.md                      # Project documentation
└── requirements.txt               # Python dependencies
🚀 Getting Started
Prerequisites
Ensure you have Python 3.8+ installed on your system.

Installation
Clone the repository:
git clone https://github.com/yourusername/netflix-analysis.git
cd netflix-analysis
Install required packages:
pip install pandas jupyter
Or using requirements file:

pip install -r requirements.txt
Launch Jupyter Notebook:
jupyter notebook Netflix_Analysis.ipynb
📊 Dataset Information
The dataset contains 8 popular Netflix titles with the following features:

Column Name	Description	Data Type	Example
Title	Name of the content	String	"Stranger Things"
Type	Movie or TV Show	String	"TV Show"
Country	Production country	String	"United States"
Release_Year	Year of release	Integer	2016
Rating	Content rating	String	"TV-14"
Sample Titles Included:
📺 TV Shows: Stranger Things, Money Heist, Dark, Breaking Bad
🎥 Movies: The Irishman, Extraction, Parasite, Bird Box
🔬 Analysis Performed
1. Data Exploration
Loaded and inspected the dataset
Checked data types and structure
Verified data quality (no missing values)
2. Content Distribution Analysis
Type Analysis: Compared Movies vs TV Shows
Geographical Analysis: Identified top producing countries
Temporal Analysis: Examined release year trends
3. Pattern Identification
Most common content type
Dominant production region
Content rating patterns
Recent vs older content ratio
💡 Key Insights & Takeaways
Content Strategy Insights:
✅ Balanced Portfolio: Equal distribution between Movies and TV Shows shows strategic content diversity

✅ US Dominance: 62.5% content from United States, but international content (Spain, Germany, South Korea) represents growing global strategy

✅ Recent Focus: Majority of content released after 2016, indicating Netflix's push into original content production

✅ Mature Content: TV-MA and R ratings dominate, targeting adult audiences

Business Implications:
Netflix is investing heavily in recent content
Strong US production base with international expansion
Focus on mature audience segments
Balanced approach between episodic (TV) and standalone (Movie) content
📚 What I Learned
Through this project, I developed skills in:

Pandas Operations:

DataFrame filtering and selection
Value counts and aggregations
Data sorting and indexing
Data Analysis:

Exploratory Data Analysis (EDA)
Pattern recognition in datasets
Drawing insights from data
Python Programming:

Writing clean, readable code
Jupyter Notebook workflow
Data visualization preparation
🔮 Future Enhancements
 Add data visualizations (bar charts, pie charts)
 Expand dataset with more Netflix titles
 Include additional features (genre, duration, IMDb ratings)
 Perform sentiment analysis on titles
 Create interactive dashboard using Plotly
 Add time-series analysis of Netflix's content growth
 Compare Netflix with other streaming platforms
📊 Visualization Ideas
Future visualizations to add:

Bar chart: Movies vs TV Shows distribution
Pie chart: Country-wise content share
Line chart: Content releases over time
Heatmap: Rating distribution by country
Word cloud: Popular title keywords
🎓 Skills Demonstrated
This project showcases:

✅ Data loading and preprocessing
✅ Exploratory Data Analysis (EDA)
✅ Pandas DataFrame operations
✅ Statistical analysis
✅ Insight generation
✅ Documentation and presentation
📝 Analysis Code Highlights
Content Type Analysis
df["Type"].value_counts()
# Output: TV Show: 4, Movie: 4
Country Distribution
df["Country"].value_counts()
# Output: United States leads with 5 titles
Release Year Trends
df["Release_Year"].value_counts().sort_index()
# Shows chronological distribution from 2008-2020
📝 License
This project is open source and available under the MIT License.

👤 Author
Hadeed

💼 Aspiring Data Analyst
🎓 Learning: Data Analysis with Python & Pandas
🔧 Skills: Python, Pandas, Data Analysis
📫 [hadeedmalik504@gmail.com] | [https://www.linkedin.com/in/hadeed-malik-28b11731b/] | [https://github.com/hadeed101]
🙏 Acknowledgments
Netflix for providing interesting content data
Pandas library for powerful data manipulation tools
Python community for excellent documentation
🤝 Contributing
Contributions, issues, and feature requests are welcome!

Feel free to:

Fork this project
Add more Netflix data
Improve analysis
Add visualizations
Submit pull requests
⭐ Show Your Support
If you found this project interesting or helpful, please consider giving it a star! ⭐

📞 Contact
Questions or suggestions? Feel free to reach out!

Last Updated: February 2026
Dataset Size: 8 titles
Analysis Type: Exploratory Data Analysis (EDA)
