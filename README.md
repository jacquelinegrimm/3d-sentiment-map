# 3D Visualization of Sentiment Analysis
This repo contains code to conduct sentiment analysis on text and plot the results on a 3D globe. It was produced as part of a project to visualize songs associated with locations, color-coded according to sentiment analysis of their lyrics, which can be found [here](https://jacqueline.dev/mapofsongs/).

To conduct sentiment analysis using the model `distilbert-base-uncased-finetuned-sst-2-english` on Hugging Face and generate a corresponding color, use the Jupyter notebook `sentiment_colors.ipynb`. An example dataset containing text, coordinates, and color labels, `data.json`, is included for reference. The files `script.js` and `index.html` provide examples for how to create the map using plotly.
