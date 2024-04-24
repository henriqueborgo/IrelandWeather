
# Irish weather

Project to understand about the monthly rainfall by intensity level in two counties of Republic of Ireland, Cork and Galway. However, it's possible to find the results for all counties of Republic of Ireland through the result of this project.




## Authors

- [@henriqueborgo](https://www.github.com/henriqueborgo)


## Introduction

This project was conceived due to curiosity about the rainfall differences between two counties,Galway and Cork. It started when I was moving from Cork to Galway, and many people told me to expect rain at most of the days.

However, I found that it doesn't happen exactly this way. Galway has fewer dry days than Cork, but Cork tends to have heavier rainfall when it does rain.

Analysed data:
Cork:
- Newest date Cork:  2020-06-01
- Oldest date Cork:  1990-01-01

Galway:
- Newest date Galway:  2020-06-01
- Oldest date Galway:  2004-08-01


The execution will result in:

An interactive graph with a dropdown menu (.html file)
Running this project will open the file in the browser, allowing to choose between the counties.









## Summary of Tech Stack

This project was built using **Python**. The work was elaborated in Visual Studio IDE as a notebook format.

To run this project import libraries:

- pandas
- numpy
- seaborn
- matplotlib.pyplot
- datetime
- ipywidgets (interact)
- plotly.graph_objs
- plotly.subplots (make_subplots)
- plotly.io
- plotly.express



## Running Locally

Running the Log project in your local dev environment is very easy. Be sure to have Python installed, then follow the directions bellow.

1. Clone the source code.

2. Create a new token for the API in your Kaggle account: https://www.kaggle.com/settings. Keep it on your local 'Downloads' folder.

3. Running the script will automatically create a /.kaggle directory and copy your API token to the folder.

4. Running the script will generate a .html file called 'monthly_rainfall_Ireland' with the plot (at same folder as you are running the project locally) and open it automatically in your browser.
