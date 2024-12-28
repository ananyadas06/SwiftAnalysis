# SwiftAnalysis🎵 Taylor Swift: A Data-Driven Musical Journey (2006–2024)
Welcome to an in-depth exploration of Taylor Swift's musical evolution! This project combines data from Spotify and Billboard Hot 100 charts to analyze her discography, from country roots to global pop superstardom.

Project Overview
This repository contains a data-driven analysis of Taylor Swift's music career, focusing on:

Audio properties of her songs (tempo, key, energy, etc.).
Chart performance on Billboard Hot 100.
Trends and shifts in her music over time.
Through advanced data cleaning, analysis, and visualization, this project sheds light on her artistic growth and commercial success.

Files and Structure
plaintext
Copy code
├── data/
│   ├── Taylor_Swift_Spotify_Data_07-23.csv  
│   ├── Taylor_Swift_Spotify_Data_11-24-2024.csv  
│   └── ... (Additional datasets)  
├── notebooks/
│   ├── Data_Analysis.ipynb    # Jupyter Notebook with the analysis pipeline.  
├── scripts/
│   ├── data_cleaning.py       # Python script for cleaning and processing data.  
│   ├── billboard_integration.py  # Fetching and merging Billboard data.  
├── README.md                  # Project documentation (You're here!).  
└── visualizations/            # Generated plots and graphs. 


Data Sources
Spotify: Audio features dataset for Taylor Swift’s songs.
Billboard Hot 100: Weekly chart performance data, retrieved via the Billboard API.
Installation and Setup
Requirements
Python 3.8+
Libraries: pandas, numpy, matplotlib, seaborn, billboard, datetime, statsmodels
Steps
Clone the repository:
bash
Copy code
git clone https://github.com/your-username/taylor-swift-analysis.git
cd taylor-swift-analysis
Install required dependencies:
bash
Copy code
pip install -r requirements.txt
Run the scripts or Jupyter Notebook:
bash
Copy code
jupyter notebook notebooks/Data_Analysis.ipynb


Key Features
Data Cleaning: Removal of duplicate songs, live versions, and non-relevant album data.
Billboard Integration: Chart performance metrics like weeks on chart and peak position.
Visualizations: Yearly song releases, album chart success, and audio feature trends.


Insights and Findings
Some of the trends uncovered in this analysis include:

Growth in popularity and consistency across albums.
Evolution in musical style, from country to pop to alternative influences.
Chart dominance with multiple albums producing numerous Hot 100 hits.


Sample Visualizations
Songs Released Per Year

Album Chart Success

Contributing
Contributions are welcome! If you have ideas to improve the analysis or want to add features:

Fork the repository.
Create your feature branch (git checkout -b feature/AmazingFeature).
Commit your changes (git commit -m 'Add some AmazingFeature').
Push to the branch (git push origin feature/AmazingFeature).
Open a Pull Request.


License
This project is licensed under the MIT License. See the LICENSE file for details.


Acknowledgments
Taylor Swift: For inspiring this project through her incredible music.
Spotify & Billboard: For providing the data.
