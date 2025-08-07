# 🍽️ Zomato Dataset Analysis (SQL Server)

Zomato Data Exploration and Analysis using SQL on a dataset of 9,000+ restaurants across 15 countries.

<p align="center">
  <a href="https://github.com/TechFreak2003/zomato-sql-analysis/issues"><img src="https://img.shields.io/github/issues/TechFreak2003/zomato-sql-analysis"></a> 
  <a href="https://github.com/TechFreak2003/zomato-sql-analysis/stargazers"><img src="https://img.shields.io/github/stars/TechFreak2003/zomato-sql-analysis"></a>
  <a href="https://github.com/TechFreak2003/zomato-sql-analysis/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/License-MIT-blue.svg">
  </a>
</p>

<p align="center">
  <a href="#-features">Features</a> |
  <a href="#️-tech-stack">Tech Stack</a> |
  <a href="#-installation">Installation</a> |
  <a href="#-project-structure">Project Structure</a> |
  <a href="#-contributing">Contributing</a> |
  <a href="#️-author">Author</a>
</p>

## 🌟 Features

- SQL-based data cleaning and transformation
- Country-wise, city-wise restaurant insights
- Online delivery and table booking analytics
- Window functions for moving counts
- Cuisine popularity analysis

## 🛠️ Tech Stack

- **Language**: SQL (T-SQL)
- **Database**: SQL Server
- **Tool**: SSMS / Azure Data Studio
- **Dataset**: CSV (Zomato)

## 🚀 Installation

### Prerequisites

- SQL Server or compatible SQL client
- Any CSV viewer (Excel, Python, etc.)

### Steps

```bash
# Clone the repository
git clone https://github.com/TechFreak2003/zomato-sql-analysis.git
cd zomato-sql-analysis

# Open SQL files in SSMS or Azure Data Studio and execute them
# Import Zomato_Dataset.csv if required for use in a local DB
```

## 📁 Project Structure

```
zomato-sql-analysis/
├── Zomato_Dataset.csv                  # Dataset with restaurant data
├── ZOMATO_DATA_EXPLORATION.sql        # Data cleaning & preprocessing
├── ZOMATO_DATA_ANALYSIS.sql           # Exploratory queries and insights
├── LICENSE
└── README.md
```

## 📊 Dataset

- **Source**: Public domain dataset containing Zomato restaurant listings
- **Columns**: RestaurantId, RestaurantName, CountryCode, City, Location, Cuisines, Votes, Rating, OnlineDelivery, TableBooking, Currency, etc.
- **Size**: 9000+ entries from 15 countries

## 📈 Results & Insights

- 🇮🇳 90.67% of the data belongs to Indian restaurants.
- 🌍 Only India (28.01%) and UAE (46.67%) provide online delivery options.
- 🏙️ Connaught Place (New Delhi) has 122 restaurants — most in the dataset.
- 🍽️ Most popular cuisine in Connaught Place: North Indian
- 🪑 Restaurants with table booking have average rating of 3.9 vs 3.7 without it.
- 🏆 Best moderately priced Indian restaurant: **India Restaurant**, Kolkata (`RestaurantID: 20747`)

## 👥 Contributing

Contributions are welcome! Check the [issues](https://github.com/TechFreak2003/zomato-sql-analysis/issues) and submit PRs to enhance the project.

To contribute:

1. Fork the repo
2. Create a new branch (`git checkout -b feature-name`)
3. Commit changes (`git commit -am 'Add feature'`)
4. Push and open a Pull Request

## 👨‍💻 Contributors

| Avatar | Name | GitHub | Role | Contributions |
|--------|------|--------|------|---------------|
| <img src="https://github.com/TechFreak2003.png" width="50px" height="50px" /> | Suvrodeep Das | [TechFreak2003](https://github.com/TechFreak2003) | Creator | SQL queries, insights, documentation |

## 📄 License

This project is licensed under the [MIT License](LICENSE).

## 🙋‍♂️ Author

Created with ❤️ by [Suvrodeep Das](https://suvrodeepdas.dev)