# Machine_Learning_Trading_Bot

---

![14-4-challenge-image](https://user-images.githubusercontent.com/95719899/162638574-19f9c7dd-8f38-4a3c-a3fe-b86ccf7b7bec.png)

---

The purpose of this exercise is to enhance existing trading signals with machine learning algorithms that can adapt to new data.




---




## Technologies

**A Python 3.9.7 (ipykernal) in JupyterLab** was used to write this notebook.


Additional Python libraries are imported into the start of the app: 

![Screenshot 2022-04-10 142315](https://user-images.githubusercontent.com/95719899/162638304-4a681e0b-942f-41cb-9e1e-db8529f51d01.jpg)



---

## Installation Guide

To use the app, from the Github repository, download:
- **machine_learning_trading_bot.ipynb** Jupyter file 
- **Resources** folder for .csv data

Use either Terminal or GitBash to run the app in a conda dev environment. 
To enter a conda dev environment, type
'conda activate dev'

You may need to install hvplot or sklearn in Terminal or GitBash.
Install hvplot by using the conda install command as follows:
> pip install hvplot.pandas

Install skikit-learn by using the conda install command as follows:
> pip install -U scikit-learn

To run the app, navigate to the root directory, which contains **machine_learning_trading_bot.ipynb** and the **Resources** folder and then type
'jupyter lab'



---

## Usage

As you run through the exercise, observe how I analyzed my machine learning trading bot through the following steps:


* Establish a Baseline Performance 

* Tune the Baseline Trading Algorithm

* Evaluate a New Machine Learning Classifier

* Create an Evaluation Report

---

## Evaluation Report Part 1

### Performance of Baseline Trading Algorithm:
(SMA window of 4 days and 100 days)

![Screenshot 2022-04-10 135914](https://user-images.githubusercontent.com/95719899/162638845-e38e37ac-1063-44b6-a1db-3dee975a18b5.jpg)


### Impact of increasing or decreasing the training window:
(Training window from 05-30-2019 to 05-30-2020)
The model provided better returns when it was trained for a 1 year window from 05-30-2019 to 05-30-2020.

<img width="191" alt="image" src="https://user-images.githubusercontent.com/95719899/162641952-5a7c18a4-93ba-44e7-adbc-67b9cbe796f8.png">



### Impact of increasing or decreasing either or both of the SMA windows:
For each value of increasing or decresing the sma window values, it was found that the model returns would be lower than actual returns. One SMA window of 2 days and 200 days presented a similar return to the baseline:

<img width="190" alt="image" src="https://user-images.githubusercontent.com/95719899/162639347-2b5881c6-7c00-4018-9319-938d6642cdd5.png">


### Best trading algorithm returns:
(Training window of 05-30-19 to 05-30-2020, SMA window of 2 days and 200 days)

![Screenshot 2022-04-10 161451](https://user-images.githubusercontent.com/95719899/162642098-bafd9a1f-d12e-41e2-9f2b-5bcde5c32b7b.jpg)





---
## Evaluation Report Part 2
What happens when I layer in a new machine learning classifier?

### Logistic Regression Machine Learning Classifier:
<img width="189" alt="image" src="https://user-images.githubusercontent.com/95719899/162639692-ce05b61b-66c6-4842-9bd5-56ba573bb3fd.png">

The Logistic Regression classifier produced worst returns when used with the same time parameters as the baseline model.

---

## Contributors

This exercise was based on a challenge problem from UC Berekely Fintech Bootcamp Module , accessed on 2022.04.10. 

For any questions, please reach out to me on [LinkedIn](https://www.linkedin.com/in/lari-rupp-5baa49153/)

---

## License

Creative Commons Zero
