<!-- hide -->
# Data Pre-processing Project Tutorial
<!-- endhide -->

- Download the New York Airbnb data. You can access the file in the current folder or you can load it directly from the link provided on the instructions below.
- Do as much exploratory data analysis as you can to find patterns and get insights from the data.
- Use your explore notebook to try different cleaning methods.
- Once you have your final cleaning process, use your app.py file to create a pipeline that cleans your data.

## 🌱  How to start this project

You will not be forking this time, please take some time to read this instructions:

1. Create a new repository based on [machine learning project](https://github.com/4GeeksAcademy/machine-learning-python-template/generate) by [clicking here](https://github.com/4GeeksAcademy/machine-learning-python-template).
2. Open the recently created repostiroy on Gitpod by using the [Gitpod button extension](https://www.gitpod.io/docs/browser-extension/).
3. Once Gitpod VSCode has finished opening you start your project following the Instructions below.

## 🚛 How to deliver this project

Once you are finished creating your eda notebook and  your cleaning pipeline, make sure to commit your changes, push to your repository and go to 4Geeks.com to upload the repository link.

## 📝 Instructions

**New York City Airbnb data**:

This is a dataset that contains Airbnb data on New York City. You will use it to practice your new EDA (exploratory data analysis) and data cleaning skills.

**Step 1:**

Use the following online dataset: 
```
https://raw.githubusercontent.com/4GeeksAcademy/data-preprocessing-project-tutorial/main/AB_NYC_2019.csv
```


Time to work on it!

**Step 2:**

Use the explore.ipynb notebook to find patterns and valuable information as much as you can. Make graphs that helps us understand the patterns found, get some statistics, create new variables if needed, etc.


- What can we learn about different hosts and areas?

- Which hosts are the busiest and why?

- Is there any noticeable difference of traffic among different areas and what could be the reason for it?

Don't forget to write your observations.

**Step 3:**

Now that you have a beautiful EDA notebook, and you have a better knowledge of the data, let's imagine Airbnb asks you to deliver a machine learning pipeline that cleans the data, in order to give it to their modeling area for future price prediction.

Use the app.py to create your cleaning pipeline that makes data ready for modeling. Save your clean data in the 'Processed' data folder.

We used to add our .env file into the .gitignore file in order to hide our passwords and credentials from version control. 

> This time make sure to add the data folder to your .gitignore file. Specially for big datasets, this is very important. 

In your README file write a brief summary of your cleaning process and explain where the data comes from (Add the link), because you won't upload any of the data folders.
