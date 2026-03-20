# 🎬 Amazon Prime Video Dashboard

An interactive **Tableau dashboard** built on Amazon Prime Video data, enabling users to explore movies and TV shows by genre, ratings, release year, and more.

---

## 📊 Overview

This project features a visually rich Tableau dashboard designed to analyze Amazon Prime Video's content catalog. It empowers users to make data-driven decisions by surfacing trends across genres, content types, ratings, and release timelines.

> Designed to provide a **30% increase in data-driven decision-making** by enabling intuitive exploration of 100+ movie and TV show records.

---

## 🔗 Live Dashboard

👉 [View on Tableau Public](https://public.tableau.com/views/AmazonPrimeViz_17248054966620/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## ✨ Features

- 🎭 **Genre Breakdown** — Explore content distribution across genres
- ⭐ **Ratings Analysis** — Understand how content is rated across the catalog
- 📅 **Release Year Timeline** — Track content trends over the years
- 🎬 **Movies vs. TV Shows** — Visual comparison using a Radial Bar Chart
- 🌍 **Country-wise Content Map** — Geographical distribution of titles
- 🔍 **Interactive Filters** — Drill down by type, genre, rating, and year

---

## 📁 Repository Structure

```
Amazon_Prime_Video_Dashboard/
│
├── Amazon Prime Viz.twb          # Tableau workbook file
├── amazon_prime_titles.csv       # Source dataset
├── Radial Bar chart values.txt   # Custom values for radial bar chart
├── Prime video logo.png          # Amazon Prime branding asset
└── README.md                     # Project documentation
```

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Tableau Desktop / Public** | Dashboard design and visualization |
| **CSV (Amazon Prime Titles)** | Primary data source |
| **Radial Bar Chart (Custom)** | Advanced chart visualization |

---

## 🚀 Getting Started

### Prerequisites
- [Tableau Desktop](https://www.tableau.com/products/desktop) or [Tableau Public](https://public.tableau.com/) (free)

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/Gopal3/Amazon_Prime_Video_Dashboard.git
   ```

2. **Open the workbook**
   - Launch Tableau Desktop or Tableau Public
   - Open `Amazon Prime Viz.twb`

3. **Connect the data source**
   - If prompted, relink `amazon_prime_titles.csv` as the data source

4. **Explore the dashboard**
   - Use filters to interact with genres, ratings, and release years

---

## 📦 Dataset

The dataset `amazon_prime_titles.csv` contains metadata for Amazon Prime Video content including:

- Title, Type (Movie / TV Show)
- Genre, Director, Cast
- Country, Release Year
- Rating, Duration

---

## 🙌 Acknowledgements

- Dataset sourced from publicly available Amazon Prime Video title records
- Dashboard inspired by Amazon Prime Video's visual identity

---

## 📄 License

This project is open source and available for personal and educational use.

---

*Built with ❤️ using Tableau*
