# SFO weather prediction

We use historical weather data from a weather station at San Francisco International Airport (SFO) to see if we can predict weather at a daily resolution using this historical data alone. In particular, we will be using a special type of recurrent neural network (RNN) called long short-term memory (LSTM) to make these predictions.

The data was downloaded from the National Climatic Data Center: https://www.ncdc.noaa.gov/cdo-web/datasets#GHCND

Full documentation of the data can be found either at the website above, or in `GHCND_documentation.pdf` within this repository.

Note that the notebook was executed using a Google Colab GPU kernel.
