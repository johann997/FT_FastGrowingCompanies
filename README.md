# FT_FastGrowingCompanies
 
# Financial Times Top 1000 Fastest Growing Companies (Europe) 2019 - 2024

This project scrapes data from the Financial Times "Top 1000 Fastest Growing Companies in Europe" (https://www.ft.com/ft1000-2024) list for the past 6 years. It cleans, aggregates, and stores the data in a CSV file and generates a Tableau visualization to provide insights into the top-performing countries and sectors over time.


<img width="450" alt="Screenshot 2025-01-24 at 07 30 35" src="https://github.com/user-attachments/assets/16d25fae-54ea-490f-875a-d1914d957efb" />

## Project Features

- **Web Scraping:** Extracts data for the top 1000 fastest-growing companies from the Financial Times website.
- **Data Cleaning:** Handles missing values, normalizes column formats, and ensures consistency across years.
- **Aggregation:** Aggregates data by country, sector, and year, calculating key metrics such as the count of companies and median Compound Annual Growth Rate (CAGR).
- **Export:** Saves the processed and aggregated data into a CSV file.
- **Visualization:** Creates a Tableau dashboard showcasing:
  - Top 10 countries by the count of companies.
  - Country ranking by median CAGR.
  - Top 5 sectors by the count of companies.
  - Top 10 sectors by median CAGR.

## Tableau Dashboard

The Tableau dashboard provides an intuitive way to explore the data:

1. **Top 10 Countries Per Year By Count Of Companies:** A bump chart showing the annual rank of countries based on company counts.
2. **Country Rank By Median CAGR:** A bar chart ranking countries based on their median CAGR.
3. **Top 5 Sectors Per Year By Count Of Companies:** A line chart illustrating sector trends over time.
4. **Top 10 Sectors By Median CAGR:** A table highlighting the fastest-growing sectors.


## Future Work

- Automate updates by scheduling regular scrapes.
- Expand analysis to include additional metrics such as revenue size or employee count.
- Publish the Tableau dashboard online for interactive access.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments

- **Financial Times** for providing the original data.
- **Tableau** for enabling advanced data visualization.
- **Flaticon** download of flag icons (created by Freepik) https://www.flaticon.com/free-icons.

---

