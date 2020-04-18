<h1>Wind_direction_prediction</h1>
<p>Wind direction prediction using Apache Spark.<br>
This notebook is designed to run in a <a href="https://www.ibm.com/cloud/watson-studio">IBM Watson Studio</a> Apache Spark runtime.<br>
The selected runtime uses 1 driver with 1 vCPU and 4 GB RAM, and 2 executors each with 1 vCPU and 4 GB RAM.</p><p><br>
Notebook makes use of Linear Regression, Gradient Boosted Trees for the regression section and also Logistic Regression, Random Forest Classifier and GBT classifier for the classification task. Here the wind direction prediction has been done by direct regression, and also by bucketizing the wind direction, then using classification algorithms.</p>
<h3>Dataset:</h3>
<p>JFK Weather dataset is used in the notebook. Can be download by running the necessary cell in the jupyter notebook or can manually be downloaded <a href="http://max-training-data.s3-api.us-geo.objectstorage.softlayer.net/noaa-weather/jfk_weather.tar.gz">here</a></p>
<hr>
