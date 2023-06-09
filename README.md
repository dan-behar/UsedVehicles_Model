# UsedVehicles_Model
The aim of this Machine Learning Model exercise is to create a regression model that can predict the price of used cars. The dataset that I used came from UK.

#### Structure of the notebook:
* `Libraries`: Includes a briefly description of where they were used in the process
* `Data Export`: Includes the data export, the cleaning of it, an analysis of its behaviour and the final categorial imputations
* `Models`: Includes all the models that I built previously to select the best one
* `Best Model`: The prediction of the test data with the best model

#### Description of the repo:
* `Test.csv`: The dataset without the variable *price*
* `Train.csv`: The dataset with the variable *price*, which is the variable to predict. This dataset was used to create the model
* `script.ipynb`: Jupyter Notebook with all the creation process
* `solutions.csv`: A CSV file with the answers. This competition was submitted in Kaggle and it requiered a specific format to upload the answers

#### Variables:
* `model`: Model of the car
* `year`: Year the car was built
* `transmission`: Type of transmission of the vehicle
* `mileage`: Current mileage of the vehicle
* `fuelType`: Fuel type of the vehicle
* `tax`: Current tax value of the vehicle
* `mpg`: Motor efficiency in miles per gallon
* `egineSize`: Size of the engine
* `make`: Vehicle manufacturer
* `price`: Price of sale (variable to classify)
