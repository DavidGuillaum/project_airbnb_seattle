<h1 align="center">Airbnb Seattle Project</h1>

<p align="center">
This repository contains a project with the Airbnb in Seattle dataset. This project is part of the Data Scientist nanodegree by Udacity.  <br>
  <a href="https://www.kaggle.com/datasets/airbnb/seattle"><strong>Original dataset</strong></a>
  <br>
  <a href="https://www.udacity.com/course/data-scientist-nanodegree--nd025?campaign_name=back2skills&coupon=BACK2SKILLS&utm_source=gsem_brand&utm_medium=ads_r&utm_campaign=19167921312_c_individuals&utm_term=143524475679&utm_keyword=data%20science%20udacity_e&gclid=CjwKCAjwrranBhAEEiwAzbhNtU2AhXMTLOAIxbb7dFpKJJ5RpY5AJ2vrr2QDXU5EzU5AiBIidf2R_hoCqrYQAvD_BwE"><strong>Udacity nanodegree</strong></a>
  <br>
  <a href="https://medium.com/@guillaume.david11/my-first-step-in-the-data-science-world-fb0600c59cf8"><strong>My blog post</strong></a>
  <br>
</p>

## Table of contents

- [How to run the project](#How-to-run-the-project)
- [Motivation and goals](#Motivation-and-goals)
- [Structure](#Structure)
- [Files description](#Files-description)
- [Author and acknowledgement](#author-and-acknowledgement)

## How to run the project

Here is the list of installed packages for this project:
- numpy
- pandas
- matplolib
- seaborn
- Scikitlearn
<br>
The project use jupyter notebook framework, so if you don't to install it you can use google colab and just upload the project_airbnb_seattle.ipynb file.
<br>
Regarding the data is splitted in 3 files in the data folder.
<br>

## Motivation and goals

The goals of this project are the following:
- Use the CRISP-DM process
- Pose 3 questions related to business or real-world application of how the data could be used answer it
- Communicate your business insights with a Github repository and a blog post

## Structure
I structured the project following the CRISP-DM process and adding some subtitles. The data contain variables about airbnbs, customers and owners. In the fisrt dataframe named "calendar.csv", observations correspond to a rental with date and price (the primary key is used to match the airbnb in the next dataframe). The second one named listings.csv has observation corresponding to a property to be rented and its characteristics. The last dataframe "reviews.csv" contains reviews about the locations.
<br>
I first took a look a the data and poses 3 questions. I came up with the following questions:
- Is there an increase of price in time ?
- What features have the greater impact on price ?
- Can you predict the price with given values ?
<br>
I then wrangled the data and made the analises to answer to the 3 questions.
<br>
You can take a look at the .ipynb file to see the answers and how I tried to answer it. &#128521;

## Author and acknowledgement
I'm David Guillaume, currently studying for a master's degree in Data Analytics and Economics at the University of Fribourg (Switzerland). I'm very interested in data sciences and economics in particular (bachelor's degree in Political Economy). I hope you'll like my project. I would like to thank Udacity for overseeing this program.
<br>
<a href="https://www.linkedin.com/in/david-guillaume-a7bb1b201/"><strong>Here is my Linkedin</strong></a>
<br>