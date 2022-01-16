# NoShowAppointments
Investigate the NoShowAppointments Dataset from Kaggle

## Overview
The main aim of this project is to:
  - Use Good Coding Practices
  - Use the right Packages
  - Clean the data
  - Explore the data
  - Use multiple Visualiations

## Introduction
<br>
<div style="text-align: justify">In this project, I will investigate the No-show appointments dataset available from Kaggle. The problem and dataset description can be found on <a href="https://your-site.com">https://www.kaggle.com/joniarroba/noshowappointments/home</a>.</div>

<div style="text-align: justify">For this project, I will first import the needed packages. I will then investigate the data more closely, by inspecting variables type, missing values, unique values, duplicates, spelling errors, values error and multiple other elements to reach a dataset that is well prepared for exploration. This is the Data Wrangling part, at the end of which I will present visuals on the different variable statistics.
For the second part of the project, I will be exploring multiple questions to understand what factors are influencing our dependent variable "no-show". </div>
<div style="text-align: justify">Based on theses findings, conclusion summaries will be discussed as a last section in this notebook. </div>

## Table of Contents
<ul>
    <a href="#top"> </a>
    <br>
<li><a href="#intro">Introduction</a></li>
<li><a href="#wrangling">Data Wrangling</a></li>
    <ol> 
    <li><a href="#properties">General Properties</a></li>
    <li><a href="#errors">Checking for errors and problems</a></li>
    <li><a href="#fixes">Needed Fixes and Feature Engineering</a></li>
    <li><a href="#final">Final Dataset</a></li>
    <li><a href="#descriptives">Statistics and Visuals </a></li>
    </ol>
    <br>
     
<li><a href="#eda">Exploratory Data Analysis</a></li>
    <ol>
    <li><a href="#q1">Is Age a factor leading to not showing up to appointments?</a></li>
    <li><a href="#q2">Is Gender a factor leading to not showing up to appointments?</a></li>
    <li><a href="#q3">Does receiving an SMS or Scholarship decrease the no show ratio?</a></li>
    <li><a href="#q4">Is the appointment's Day of the Week a ruling factor in no show?</a></li>
    <li><a href="#q5">Is the number of missed appointments a ruling factor in no show?</a></li>
    <li><a href="#overview">Overview</a></li>
    </ol>
    <br>
<li><a href="#forest">Feature Importance</a></li>
<br>
<li><a href="#conclusions">Conclusion</a></li>
</ul>

## Program Details
  - Libraries:
    - pandas
    - numpy
    - matplotlib
    - seaborn
  - Python 3.6+
 
 ## Author
 I am, ANgi Ghanem, the sole author of this program.
