
# Recommendation System for getINNOtized 🛍️

[![GitHub stars](https://img.shields.io/github/stars/1realbzy/Recommendation-System-getINNOtized?style=social)](https://github.com/1realbzy/Recommendation-System-getINNOtized)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

A recommendation system built for an e-commerce platform using user behavior, item properties, and category hierarchies. The project follows the CRISP-DM framework to develop personalized suggestions, improve user engagement, and boost conversion rates for getINNOtized.

## Quick Start 🚀

### Prerequisites
- Python 3.11
- pip
- git
- jupyter notebooks

### Installation
``bash
git clone https://github.com/1realbzy/Recommendation-System-getINNOtized.git
cd Recommendation-System-getINNOtized
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt


### Data Download Instructions
The raw data files are too large to be stored in this repository. Please download them from the following OneDrive link: [Data Files](https://imperialgeneralcom-my.sharepoint.com/:u:/g/personal/hbempong_imperialgeneral_com/ESNnuUUceTNBt-VMLTrkhW0BkKflTTZ-hcABLSDztQylnQ?e=Rwfool). Extract the files into the `data/` directory. The zip file contains:
- `category_tree.csv`
- `events.csv`
- `item_properties_part1.csv`
- `item_properties_part2.csv`

  **#Project Overview#**
This project aims to develop a recommendation system that leverages historical user data to provide tailored product recommendations. Key objectives include:
## Project Objectives

The "Recommendation-System-getINNOtized" project aimed to:

| Objective                  | Description                                                                 |
|----------------------------|-----------------------------------------------------------------------------|
| Personalized Recommendations | Deliver tailored product suggestions to boost user satisfaction.           |
| Diverse Use Cases          | Focus on products, with potential for content/services expansion.          |
| Historical Data Utilization| Leverage 2.7M interactions (811,499 rows) for insights.                   |
| User Engagement            | Increase interaction with relevant, diverse recommendations.               |
| Scalability & Real-Time    | Handle large-scale data and real-time updates.                             |
| Business Metrics           | Improve conversions, targeting Precision@5 >0.02.                          |
| Accuracy & Diversity       | Balance low RMSE (e.g., 0.7139) with Diversity >0.5 (achieved 0.6520).    |

Personalized Recommendations: Tailor suggestions based on user behavior.


**##Business Questions**

How can we personalize product recommendations to enhance user satisfaction and retention?

What are the most effective strategies to improve conversion rates from views to transactions?

How do seasonal patterns or trends influence user interactions and sales?

Which products or categories are most popular or have the highest interaction rates?

How can we identify and filter out bot activity or anomalous user behavior to ensure accurate recommendations?

How can we balance recommendation accuracy with diversity to cater to a wide range of user preferences?

What machine learning algorithm provides the most accurate and efficient recommendations for our platform?
