# Python-Sql-Data-Analysis Project 

**Overview**

This project aims to securely manage, streamline, and perform analysis on the Kaggle dataset

**#Python Codebase**:-

!/usr/bin/env python

import libraries

!pip install kaggle

import kaggle

!kaggle datasets download https://www.kaggle.com/datasets/ankitbansal06/retail-orders

extract file from zip file

import zipfile

read data from the file and handle null values

import pandas as pd

rename columns names ..make them lower case and replace space with underscore

derive new columns discount , sale price and profit

convert order date from object data type to datetime

drop cost price list price and discount percent columns

load the data into sql server using replace option

import sqlalchemy as sal

load the data into sql server using append option


#**SQL Codebase**:-
--find top 10 highest reveue generating products 

--find top 5 highest selling products in each region
with cte 

--find month over month growth comparison for 2022 and 2023 sales eg : jan 2022 vs jan 2023
with cte 

--which sub category had highest growth by profit in 2023 compare to 2022
with cte

#Dataset Used:-

This Kaggle dataset contains statistics (CSV files) on retail-orders over the course of many months. The data for each region is in its own file.  

https://www.kaggle.com/datasets/ankitbansal06/retail-orders
