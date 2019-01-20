# Coursera Capstone Report
## 1. Introduction/Business Problem
New York City is the country's top city for small business for the second year in a row, according to Biz2Credit's annual study of the Top Small Business Cities in America, which analyzed the financial performance of 27,000 small businesses and their local market economic conditions.

Nowadays, plenty of business owner want to drive their business to NYC. So, there is a question: Where should they open their restaurant, their store or their representative office?

The main purpose of this report is showing a Data Science approach to solve that question by creating a recommender system.
## 2. Data
* What are the needed datas?
  * New York City Neighborhood data from https://geo.nyu.edu/catalog/nyu_2451_34572.
  * Venues data foreach neighborhood from FourSquare.
* How to solve the problem with them?
  * From this 2 datasets, create a new dataset which have Neighborhood's name and its top 10 venues type.
  * Have an assumption: A neighborhood which have lots of type A venue is a good place to open a new type A venue.
  * Suggest the best neighborhood to open customer's venue based on neighborhood's top 10 venues type.
