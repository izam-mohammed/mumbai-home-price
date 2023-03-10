# Mumbai House Price prediction Project

In this end-to-end data science and machine learning project, I Build a model that predict the price of houses in Mumbai. After Hyperparameter tuning and cross validation, I found that a Linear Regression is best for this model. The Model has 87% of accuracy in predicting the house prices.The dataset used is Mumbai prices data set from Kaggle.

Scroll to the end to see the preview !!!!

### The inputs for predicting house prices - 
1) Area
2) BHK
3) No of Bathrooms
4) Location

### Folder structure

* <b>UI : This contains ui website code</b> 
* <b>server: Contains the Python flask server related code</b>
* <b>model: Contains python notebook for model building</b>

### Technologies used in this project,

* `Python`
* `Numpy and OpenCV for data cleaning`
* `Matplotlib & Seaborn for data visualization`
* `Sklearn for model building`
* `Jupyter notebook, visual studio code as IDE`
* `Python flask for http server`
* `HTML/CSS/Javascript for UI`

### Required Libraries

* `seaborn`  0.8.1
* `Flask`  1.0.2
* `numpy`  1.16.2
* `scikit-learn`  0.20.3

### Installation :

A good practice to start with a new project and use it, is to make a virtual enviornment for the particular project. Here is the steps for making virtual enviornment ::

1. `pip install virtualenv`
2. `python -m virtualenv myenv`

#### Install the dependencies of the App ::

Run commands on python terminal or anaconda terimial or any terminal you are using in your system.

* `pip install -r requirements.txt`

### Test the app:

* Clone the repository: `git clone https://github.com/izam-mohammed/mumbai_home_price.git`
* Go to the project directory
* Go to Server Directory: `cd Server`
* Run the app: `python app.py`
* The development server will be up and running on port 5000 at the URL: http://127.0.0.1:5000/
* Now go to the UI Folder and open app.html on the browser. <b>Note that the flask app server must be up and running.</b> 
* Drag an image of your favourite celebrity from the five and hit the classify button. Our app will predict the celebrity name with his/ her image. It will also show us the percentage match of our image with all the five celebrities. 

### The UI is Look like 

![](https://media.licdn.com/dms/image/C5622AQGZbXN_A4rclg/feedshare-shrink_800/0/1671429324763?e=1674086400&v=beta&t=XWg6zHk-6PSQzBi5zwoyTtPgoE-y1WoVeju_02_FtgA)

Hope you like this project !!!
