# CS 1090a + 1710 Final Project Submission 

The .js files contain the multiple visualizations throughout the project website -- from `barchart.js` to `sentimentwordcloud.js`. The landing page is contained in `index.html` while the EDA and sentiment analysis dashboards are contained in `eda.html` and `dashboard.html` (all necessary files are outside the __MACOSX folder). The data is contained within the data folder, where `data1_eda.csv` contains the raw headline data cleaned for news desks and includes a column for article word count. The file `current_df_retry_final` contains 10,000 article headlines labeled and scored for sentiment, with the `grouped (2).json` file containing the sentiment dataset processed in Python to contain the frequency of select words classified positive, negative, and neutral. 

The `styles.css` file contains all the styling for the website, including the landing page and dashboards. All files contained in the `__MACOSX` and `.idea` folders were created by my partner for the CS 1090a project Mohamed Zidan Cassim to port my visualizations into a website format. 

To run the website: 
- run python -m http.server 8000 in the terminal in VS code or your preferred IDE (ensure you are in the correct directory)
- go to localhost:8000/ to see the index page


[Screencast video](https://drive.google.com/file/d/13rK3A7AAaepee6yi46w2UweK4QJTWj5z/view?usp=drive_link)


