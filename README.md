# 🇺🇸 U.S. Import Tariff Exposure by Region and Metro (2023)

This project analyzes U.S. import flows and their associated tariff exposure using port-level trade data from the [U.S. Census Bureau's International Trade API](https://api.census.gov/data/timeseries/intltrade/imports/porths). It calculates the **weighted average tariff rate** by Census region and by **Core-Based Statistical Area (CBSA)** to estimate how import tariffs impact different parts of the country.

---

## 🔍 Key Features
- 📦 Automated data pull from the U.S. Census API (2023)
- 🧼 Cleaning and standardization of port and country-level trade records
- 🗺️ Mapping of U.S. ports to CBSAs/Metros and Census regions
- 📊 Weighted tariff calculation by region and metro based on country-specific rates
- 🏙️ Identification of top metro areas by estimated tariff burden
- 💾 Outputs stored in CSV format for reproducibility

---
Note - Port to CBSA data was created with ChatGPT - may be less than perfect.
---

## 🛠️ Requirements
- Python 3.8+
- `pandas`, `requests`, `matplotlib`
- A valid U.S. Census API key ([get one here](https://api.census.gov/data/key_signup.html))
