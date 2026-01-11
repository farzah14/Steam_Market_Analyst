# Steam Market Analyst from 2021 to 2025🎮📊



## 📌 Project Description
This project aims to analyze market steam, the dataset have a 65.000 Games. Project includes Get Data From STEAM API, Cleaning Data, Exploratory Data Analyis(EDA), and Visualize on POWER BI.

This analyze give the deep insight about price games, genres, and games release patterns. And correlation between games popularity with the games features.



## 🚀 Key Features
- Data Cleaning and Processing : Cleaning raw data, fix missing values, convert type data for analysis, and fix many values of one column. 
- Exploratory Data Analysis(EDA) : Analyis genres are growing the fastest in 2025, market share from 2021 to 2025 by Indie Genres, months have the highest number of game releases, correlation between price and user recommendations.
- Dashboard : Visualize from final the dataset using POWER BI. For makie decision business or market research.



## 📊 Dataset

The dataset used (a_steam_data_2021_2025.csv) contains 65,521 unique entries with the following information:
- appid: Unique game ID on Steam.
- name: Game title.
- release_date: Release date (including upcoming releases in 2025).
- price: Game price in USD.
- genres: Genre category (e.g., Action, Indie, Strategy).
- categories: Supported features (e.g., Single-player, Multiplayer).
- developer & publisher: Name of the game developer and publisher.
- recommendations: Number of user recommendations (popularity indicator).



## 📂 Repository Structure
| File / Asset | Description |
|---|---|
| `a_steam_data_2021_2025.csv` | Main dataset (Steam market snapshot for 2021–2025). |
| `steam_market_analyst.ipynb` | Jupyter notebook used for cleaning, exploration, and analysis. |
| `visualization_steam_market.pbix` | Power BI dashboard file. |
| `Visualization Steam Market.png` | Preview image/export of the dashboard. |



## 🛠️ Installation and Use
### 1. Clone Repository
Cloning the repository on your laptop/computer.
```bash
git clone https://github.com/farzah14/Steam_Market_Analyst.git
cd Steam_Market_Analyst
```

### 2. Create a Python Environment(Recommended) using VENV.
```bash
# Create venv
python -m venv .venv

# Windows:
.venv\Scripts\activate

# macOS/Linux:
source .venv/bin/activate
```
### 3. Requirement
Make sure on your laptop already installed Python 3 and Library is Required.
```bash
pip install pandas numpy matplotlib seaborn aiohttp tqdm sqlalchemy
```
### 4. Open the Notebook 
For see result analysis, fix missing values, and convert type data is required. There is a separation of columns namely Genre, Category, and Developer because there are many values ​​in 1 row. Columns such as Genre, Category, and Developer are converted to SQL.
```bash
steam_market_analyst.ipynb
```


## Installation Microsoft SQL Server ![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat&logo=microsoft-sql-server&logoColor=white)
### 1. Install Microsoft SQL Server(Windows)
### 2. Setup your server on your laptop/computer
### 3. Create the database for Accommodate your SQL File

## Installation Power BI ![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=microsoft-power-bi&logoColor=black)
### 1. Install Power BI(Windows)
### 2. Get data using Microsoft SQL Server and select your Database which has been made
### 3. You can see the final results of analysis 

