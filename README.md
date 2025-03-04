
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

  Project Overview
This project aims to develop a recommendation system that leverages historical user data to provide tailored product recommendations. Key objectives include:

Personalized Recommendations: Tailor suggestions based on user behavior.

### Additions
Added exploratory data analysis notebook and visualizations
Diverse Use Cases: Focus on e-commerce product recommendations.
Historical Data: Use 4.5 months of user interactions (views, add-to-carts, transactions).
User Engagement: Improve satisfaction and retention.
Scalability: Handle large datasets efficiently.
Business Metrics: Increase sales and conversion rates.
Balance Accuracy & Diversity: Provide relevant and varied recommendations.
