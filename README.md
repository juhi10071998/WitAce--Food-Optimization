# Food Usage and Inventory Optimzer App

## Short description

### What's the problem?
Food wastage is a major environemntal problem facing the world today, and one of the major causes for the global food wastage is higher inventory due to poor forecasts. Many hotels end up over buying raw materials which remain unused till they go bad and are discarded. That end's up in lanfills and rots where it decomposes to produce harmful methane gas which causes green house effect. The energy that went into growing, transporting and harvesting the wasted food is also lost. 

### How can technology help?
With AI/ML, and sophisticated training models, it is not so hard to get near perfect predictions. Moreover, in today's time, it is also not hard to find resources for the training dataset. Technoloagy can go a long way in monitoring, maintaing and updating billing logs and using the data to forecast food consumption patterns.

### The idea
Using a set of open sourced tools, IBM Cloud and Watson Services, it was possib;e for us to create and Food Usage and Inventory Optimizer, that uses flask on the frontend and LSTM models to get restaurant data in the form of bills ( no extra effort from the users! ) and make predictions on the food consumption pattern for the next 7 days.

![Test Image 5](https://github.com/Ishika11/WitAce--Food-Optimization/blob/main/diag.PNG)

 ### Go to the Comman Prompt
 Select the directory where the files are saved, that is, within: eCommerceFlask directory
 ```
 $pushd D:\Food_Optimiser_FE\eCommerceFlask
 ```

Set up a virtual environment
```
python -m venv test-env
```

Activate the virtual environment
```
test-env\Scripts\activate.bat
```
Install dependencies
```
pip install -r requirements.txt
```

## Start this project ⚙️

```
python run.py
```

### Finally open loopback URL address  🤓

http://127.0.0.1:5000/

