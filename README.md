# SpaceX-Analysis
In this project I have used Categorizing Machine learning techniques to predict success rates of Space X's Falcon 9 rocket launches.
I will briefly describe the several files so the reader will understand them easily.

1. dataset_part_1.csv -> The cleaned dataset extracted from space x database using API.
2. dataset_part_2(1).csv -> The cleaned dataset with y vaues in class column.
3. dataset_part_3(1).csv -> Cleaned dataset with one hot encoding for machine learning purposes.
4. spacex_launch_geo.csv -> Cleaned dataset with lat and long of launch sites for folium.
5. spacex_web_scraped.csv ->  Additional cleaned launch data scraped through wikipedia, just to find if any more data is available.
6. space-Y-data-extraction.ipynb -> extracting the data from space x database using API.
7. space-Y-data-wrangling.ipynb -> cleaning the extracted dataset and filtering the useful data.
8. space-Y-data-wrangling.ipynb -> Exploratory data analysis of the data.
9. space-y-plotly.ipynb -> Geo-visualization of launch sites and launch specific successes and failures. (https://nbviewer.org/github/SulavDogood/SpaceX-Analysis/blob/main/space-y-plotly.ipynb) since Github only hosts static programs, please click the given link to interact with the folium maps.
10. spaceY-ML.ipynb -> comparision of Logistic Regression, SVM, Decision Trees and KNN models to see their accuracies in predicting the success rates.
    #Note: Github isn't showing the plotly maps. Please download the dataset(spacex_launch_geo.csv) and the file (space-y-plotly.ipynb) in your local device to properly interact with the visualizations.
