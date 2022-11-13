# matplotlib-challenge
This repo contains the Module 5 Matplotlib challenge for Vincent Passanisi
Due on November 14, 2022

## Instructions

This assignment is broken down into the following tasks:

Prepare the data.

Generate summary statistics.

Create bar charts and pie charts.

Calculate quartiles, find outliers, and create a box plot.

Create a line plot and a scatter plot.

Calculate correlation and regression.

Submit your final analysis.

## Files

In the *Pymaceuticals* folder are the following files:

**pymaceuticals_starter.ipynb** - This is the starting Jupyter notebook provided for the challenge.

**pymaceuticals_complete.ipynb** - This is my completed Jupyter notebook with required tables, charts, and annotations.

**mouse_bar.png** - This is a saved image of the bar plot showing timepoints for each drug regimen.

**mouse_pie.png** - Not a strange delicacy, but a saved image file of my pie chart showing distrubution of mice in the study by sex.

**scatter_reg.png** - Saved image of the scatter chart with regression line plotted.

The *Data* folder contains the two data files provided for the challenge.

**Mouse_metadata.csv**

**Study_results.csv**

These two files were merged to create the data frame used in the analysis.

## Thoughts and Observations

This challenge had several roadblocks for me. I had difficulty removing the duplicate mouse. I had to try several different methods without success. My methods resulted in a single row for the duplicate mouse being left in the data set. Finally with much searching, I found the best way to remove all the duplicate mouse data from my data frame.

The bar charts and pie charts were fairly simple, but I ran into another roadblock with the box and whisker chart. My difficulty wasn't with the chart, but with generating the data for the chart. The loop threw me for a loop, so to speak. :-) Finally solved it by going back to the exercises in the class activities. Lots of experimenting to get it right, and then my results didn't match the starter notebook, so I knew there was something wrong with the way I chose my data. I had originally used an *.nlargest* function, but for some reason, this gave me more than one data point for each mouse. I redid my data frame instead by doing a groupby, and I was able to get the correct result.

A practice suggested by one of my tutors that I found very helpful, was saving a csv of my data frame every once in a while in order to see its complete structure. This practice saved me a lot of time because I was able to see when I had too much data or the wrong data. I was also able to use the file to verify my results.

For my line chart of a single mouse, I found a way to choose a different random mouse each time the cell is run. My method is inelegant, but gets the job done. I'll have to research a better way of doing it. I thought this would be more interesting than hard-coding the same mouse every time.

Also, I saved versions of my charts to separate image files, and I learned how to add an image to my initial markdown cell.

This challenge took me a little longer than the others, but I'm happy with the result.






