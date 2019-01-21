# Coursera Capstone Report
## 1. Introduction/Business Problem
New York City is the US's top city for small business for the second year in a row, according to Biz2Credit's annual study of the Top Small Business Cities in America, which analyzed the financial performance of 27,000 small businesses and their local market economic conditions.

A Canadian restaurant owner who have multiple restaurants in Toronto is planning to expand to the US. Seeing the potential of NYC, he/she choose to open a new restaurant in this city. But there is a question: Where should the new restaurant be located? 

The main purpose of this report is showing a Data Science approach to solve that question.
## 2. Data
* What are the needed datas?
  * New York City Neighborhood data from https://geo.nyu.edu/catalog/nyu_2451_34572.
  * Toronto Neighborhood data from web scraping https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M
  * Venues data foreach neighborhood from FourSquare.
  * Type of restaurant of the client: Chinese Restaurant
  * In which neighborhood in Toronto the client have efficiency restaurant?
* How to solve the problem with them?
  * From this 2 datasets, create a new dataset which have Neighborhood's name and its top 10 venues type.
  * Have an assumption: A neighborhood which is similar  of restaurant is a good place to open a new one.
  * Suggest the best neighborhood to open customer's restaurant based on neighborhood's top 10 venues type.
