# Active\_Learning\_ODSC_India
Starter code for the 2018 ODSC India active learning workshop

### Steps to get started

1. Clone the repo:
	
	```
	git clone https://github.com/kvajapeyCF/Active_Learning_ODSC_India.git
	cd Active_Learning_ODSC_India/
	```

2. Download the [Waston Setup Tutorial](https://docs.google.com/presentation/d/1GBbJh_v8Z5MEO2Bsi_YLxBq6z-M-glAsRY5XCQyA_kY/edit?usp=sharing)

3. Set up your [jupyter notebook](https://jupyter.readthedocs.io/en/latest/install.html)

4. Create the virtual environment:

	```
	$ pip install virtualenv
	$ virtualenv active_learning --python=python3
	$ source active_learning/bin/activate
	```
5. Install the requirements

	```
	pip install -r requirements.txt
	```
6. Start your jupyter notebook (make sure to be in your virtual environment)

	```
	jupyter notebook
	```
7. Open your browser and navigate to the url provided by the jupyter server and open the `Active_Learning_Class.ipynb`

WATSON_API_KEY = 'r3bd5K-aHVhcFVbiMzapjvFSrqNjx0pg6jOLt3qiNbUD' # INPUT WATSON API KEY

WATSON_CLASSIFIER_ID_1 = "quality_detector_1_1645158165" # INPUT CLASSIFIER 1 ID

WATSON_CLASSIFIER_ID_2 = "qd_2_2048362238" # INPUT CLASSIFIER 2 ID

WATSON_CLASSIFIER_ID_3 = "quality_detector_3_2003464426" # INPUT CLASSIFIER 3 ID
