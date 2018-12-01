# Airbnb Price Recommendation System

<b>Group Name</b>: Enchiladas

<b>Section</b>: SECTION 2

<b>Our project is to</b> build a system that recommends price of an Airbnb apartment based on its features using a regression model. It can be used by Airbnb clients to compare the price of 
a specific apartment with the suggested price and also used by new hosts to price their apartments.

#Your README needs to include:

Installation instructions (if any besides cloning the repo)
Python packages should be listed appropriately in requirements.txt
Run instructions
What do I need to type to get your program to do its thing


## Implemented Skills
#### Web Scraping
*  
  When the program runs, people can press
  * key `s` to store and restore their faces
  * key `r` to remove the faces with specific name   
  
* Faces Detection  
  The program can detect faces in the camera and use
  square the around the faces. Multi-faces are supported.
 

#### Data Preprocessing
* Drop duplicates
* Drop missing values
* Extract `price` and save as `int` format
  - use `re.search`
* Extract `number of reviews` and save as <> format
  -  use `re.search`
* Extract `rating` and save as `int` format
  - use `re.search`
* Convert boolean variable `superhost` into `int`
* Reduce numbers of `room_type` to 7

#### Linear Regression Model Training
* Split data into train and test set
  
* Fit train data into linear regression model

* Get the coefficients
  

#### User Interface Designing
* Send Message to mobiles  
  
* Unlock Control  
  

## Installation instructions
#### pandas: 
* Use conda
```
conda install pandas
```

* Use pypi
```
pip install pandas
```

#### numpy
```
pip install numpy
```

#### requests
```
pip install requests
```

#### beautifulsoup4
```
pip install beautifulsoup4
```

#### selenium
```
pip install selenium
```
  * Selenium requires a driver to interface with the chosen browser. In this project, we used Chrome which requires chromedriver. You need to download the chromedriver and install it at first from here: https://sites.google.com/a/chromium.org/chromedriver/downloads 

  <b>Make sure chromedriver is in your PATH, e.g., place it in /usr/bin or /usr/local/bin</b>

  * And when you run this code, make sure you change the path to your PATH
from selenium import webdriver  
browser = webdriver.Chrome('/Users/yutingzhang/Desktop/chromedriver')

  * You can find detailed instructions here: https://selenium-python.readthedocs.io/installation.html
There is also detailed instruction for windows users.

#### sklearn
  * If you already have working installation of numpy and scipy, the easiest way to install scikit-learn is
'''
pip install -U scikit-learn
'''
  * or conda
```
conda install scikit-learn
```

* If you have not installed numpy and scipy
```
pip install -U numpy scipy scikit-learn
```

## Run instructions
* `Airbnb price recommendation.ipynb` -> check our whole code
* `GUI.ipynb` -> check the user interface
  * In GUI, you need to type in what you want to get your price.

