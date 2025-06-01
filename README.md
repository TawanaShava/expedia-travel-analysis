 Expedia Hotel Search Analysis Project

![Analysis Overview](Expedia_Analysis/visualizations/hotel_search_analysis.png)

🔍 Project Overview
Analysis of Expedia's hotel search data to understand user behavior, booking patterns, and market trends. Processed 100,000+ search records to identify key insights for business optimization.

📊 **Key Insights**
1. **Mobile Dominance**: 62.3% of searches come from mobile devices
2. **Booking Conversion**: Overall booking rate of 36.5%
3. **Popular Destinations**: United States (ID: 219) is the most searched hotel country
4. **Traveler Profiles**: 45% solo travelers, 30% couples
5. **Package Deals**: 28.7% of searches include package deals

📂 **Repository Structure**

expedia-hotel-analysis/Expedia Analyss
├── data/ # Dataset directory (not included in repo)
├── notebooks/ # Jupyter notebooks with analysis
├── visualizations/ # Generated charts and graphs
├── requirements.txt # Python dependencies
└── README.md # Project documentation

🔍 **Analysis Highlights**
Top Hotel Countries

Top Countries
United States, UK and France are the most popular hotel destinations

**Daily Search Trends**

Daily Searches
Peak search volumes on weekends with Friday seeing 15% more searches than Monday

**Booking Rates by Traveler Type**

Booking by Type
Family travelers show highest conversion rate at 42.1%

📊 **Key Metrics Summary**
----------------------------------------------------------------------------------
Metric	                 |Value	                 | Insight
----------------------------------------------------------------------------------
Total Searches          |	100,000	              |
----------------------------------------------------------------------------------
Mobile Search Share	    |62.3%	                 |Mobile-first strategy recommended
----------------------------------------------------------------------------------
Booking Conversion	     |36.5%	                 |Opportunity to improve conversion
----------------------------------------------------------------------------------
Popular Hotel Country	  |219 (US)               |Focus marketing efforts
----------------------------------------------------------------------------------
Package Deal Share	     |28.7%	                 |Potential growth area
----------------------------------------------------------------------------------

🛠️ **Technologies Used**

Python 3.9

Pandas: Data manipulation and cleaning

Seaborn & Matplotlib: Data visualization

Jupyter Notebook: Interactive analysis environment

Scikit-Learn: Statistical analysis (optional)

📝 **Methodology**

Data Cleaning:

Handled missing values in orig_destination_distance

Standardized data formats

Created new features (traveler_type, search_date)

Exploratory Analysis:

Analyzed booking patterns by device type

Identified peak search periods

Compared conversion rates by traveler segment

**Visualization**:

Created publication-quality charts

Developed actionable business insights

💡 **Business Recommendations**
Optimize mobile experience to capture 62% mobile searchers

Create family-targeted promotions (42% conversion rate)

Increase package deal offerings (currently 29% of searches)

Focus marketing on top destination countries (US, UK, FR)

📚 **References**
Dataset Source: [Kaggle - Expedia Travel Dataset](https://www.kaggle.com/datasets/jacopoferretti/expedia-travel-dataset)

Inspired by: Expedia Personalization Challenge

Visualization Techniques: Seaborn Gallery

⁉️ **Frequently Asked Questions**
Q: Can I run this without the original dataset?
A: The notebook includes sample code to generate simulated data for testing.

Q: How were traveler types determined?
A: Based on search parameters:

Solo: 1 adult, 0 children

Couple: 2 adults, 0 children

Family: Any children > 0

👤 Author
[Tawana Shava]
[https://www.linkedin.com/in/tawanafshava/]
