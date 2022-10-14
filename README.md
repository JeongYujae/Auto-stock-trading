# Purpose

Test for backtesting method for stock price.

This repository is linked with the pytrader(https://github.com/JeongYujae/Pytrader)

## How to use

Insert the start and end date with price code, the zipline backtesting asuume buy and sell based on your algorithm.

So you can compare whether your algorithm went well throgh the result based on the past data.

All of the API datas are from Nasdaq API(https://data.nasdaq.com/tools/api)

## Getting started

pip install zipline-reloaded

pip install wheel

pip install numpy

pip install pandas

pip install matplotlib

Need to sign up Nasdaq official website to key your own key code. (https://data.nasdaq.com/)

If you need extra information from zipline,

https://zipline.ml4trading.io/install.html


##Project

The main test file is in the back_testing2 folder.

You can apply your own algorithm by making a new file and running with python shell.

Check back_testing2/buyapple.py to elaborations

## Example
The result from buyapple.py

<img src="https://user-images.githubusercontent.com/96777346/174240962-102ebb87-dfd6-42c8-8aaa-48ce88262d1a.PNG">
