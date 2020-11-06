# Webapp--BIke-Usage-

* This is a sample webapp I built which gives real-time predictions of how many bikes a bike renting company will rent out depending on the weather, mainly depending on:
  1. Temperature
  2. Humidity
  3. Windspeed.
  
* All 3 variables above are my features, and the target/label is the number of bikes that will be rented out.
* The I trained my data on the Machine Learning Algorithm, XGBClassifier, and after which I saved the trained model in a pickle format. The Jupyter notebook containing the data exploration and visualization, and then training of the model has been included in this repository
* I built my webapp using the Flask framework, where I created a simple HTML file to take in the input of the user, and return the prediction.
* The webapp was deployed on Heroku

* All the files used in creating the webapp has been included in this repository
### The deployed webapp can be found here: https://bike-usage.herokuapp.com/

* Please click the link and see for yourself.
