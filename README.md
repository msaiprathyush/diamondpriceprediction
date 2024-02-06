Introduction About the Data : The dataset The goal is to predict price of given diamond (Regression Analysis).

There are 10 independent variables (including id):

id : unique identifier of each diamond

carat : Carat (ct.) refers to the unique unit of weight measurement used exclusively to weigh gemstones and diamonds.

cut : Quality of Diamond Cut

color : Color of Diamond

clarity : Diamond clarity is a measure of the purity and rarity of the stone, graded by the visibility of these characteristics under 10-power magnification.

depth : The depth of diamond is its height (in millimeters) measured from the culet (bottom tip) to the table (flat, top surface)

table : A diamond's table is the facet which can be seen when the stone is viewed face up.

x : Diamond X dimension

y : Diamond Y dimension

x : Diamond Z dimension

Target variable:

price: Price of the given Diamond.




![Home_page](https://github.com/msaiprathyush/diamondpriceprediction/assets/122264714/5b8e8d14-06a2-4be9-a989-2e754205891e)


![predict](https://github.com/msaiprathyush/diamondpriceprediction/assets/122264714/697e936f-4282-4656-933a-33b5585fe253)


![result](https://github.com/msaiprathyush/diamondpriceprediction/assets/122264714/07821843-fadf-426f-93a7-5611bd90bdac)

![Airflow](https://github.com/msaiprathyush/diamondpriceprediction/assets/122264714/1d7b497d-bb08-4bac-b6fc-53c249b28e76)

To Run using src code!

After pulling the repository to local begin by running pip install -r requirements_dev.txt.

After Sucessfull installation of requirements_dev.txt run python setup.py install to install src into local package.

Then run python app.py to access the model and when its running in the terminal goto localhost:8000\predict to access the price estimator.

Fill the UI with your required values and click on submit to get the estimated price for the Diamond.

Alternatively you can use Dockerfile to create dockerized container and it will automatically run app.py.

Proceed to localhost:8000\predict to us the model for price estimate.


