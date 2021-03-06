
## Introduction

What is Web Scraping?

It is the automated procedure of extracting the large amount of data from websites. The data available on the websites which is unstructured can be converted to structured data using Web Scrapping.

There are different ways to scrape websites such as Online Services, APIs or writing your own code.



## Why is Web Scraping Used?

Why does someone have to collect large data from websites?
To know about this, let’s look at the applications of web scraping:

Price Comparison:
To collect data from online shopping websites and use it to compare the prices of products.

Email address gathering:
To use email as a medium for marketing, use web scraping to collect email ID and then send bulk emails.

Social Media Scraping:
To collect data from Social Media websites such as Twitter to find out what’s trending.

Research and Development:
To collect a large set of data (Statistics, General Information, Temperature, etc.) from websites, which are analyzed and used to carry out Surveys or for R&D.

Job listings:
Details regarding job openings, interviews are collected from different websites and then listed in one place so that it is easily accessible to the user.

How Do You Scrape Data From A Website?

When you run the code for web scraping, a request is sent to the URL that you have mentioned. As a response to the request, the server sends the data and allows you to read the HTML or XML page. The code then, parses the HTML or XML page, finds the data and extracts it.


## To extract data using web scraping with python

you need to follow these basic steps:

1) Find the URL that you want to scrape.

2) Inspecting the Page.

3) Find the data you want to extract.

4) Write the code.

5) Run the code and extract the data.

6) Store the data in the required format.

Now let us see how to extract data from the Flipkart website using Python.


## Libraries used for Web Scraping:

As we know, Python is has various applications and there are different libraries for different purposes. In our further demonstration, we will be using the following libraries:


1) BeautifulSoup:
Beautiful Soup is a Python package for parsing HTML and XML documents. It creates parse trees that is helpful to extract the data easily.

2) Pandas:
Pandas is a library used for data manipulation and analysis. It is used to extract the data and store it in the desired format.

url = "https://www.amazon.in/Redmi-Storage-Display-Qualcomm%C2%AE-SnapdragonTM/product-reviews/B09QSB9RMH/ref=cm_cr_dp_d_show_all_btm?ie=UTF8&reviewerType=all_reviews"


## Data Preparation

So, with this, we will get started with writing our own code for Redmi note 11 Customer Reviews on Amazon website

![1](https://user-images.githubusercontent.com/99526815/160623602-c975d845-965f-4ff3-9728-962ed22ce547.PNG)


Use urlopen to open the url and read the details in it.

Get the Name of the produt:



Get the Customer Name:

![3](https://user-images.githubusercontent.com/99526815/160623761-51f90b88-9c21-490d-8bd5-588de7f61326.PNG)

Get the Customer Reviews for produt:

![4](https://user-images.githubusercontent.com/99526815/160623825-aca96f89-4e3d-4d63-81b0-090943aa7cf8.PNG)

![5](https://user-images.githubusercontent.com/99526815/160623903-f43921cc-6a2d-4b3a-91b9-ee9f1051f5f3.PNG)

Get the Ratings for the produt:

![6](https://user-images.githubusercontent.com/99526815/160623969-cc68f4b2-899d-44cf-b8c4-1bc2b2468f8a.PNG)

![7](https://user-images.githubusercontent.com/99526815/160624032-d2b1ae25-d154-4859-8ac1-e88113a6bec9.PNG)

![8](https://user-images.githubusercontent.com/99526815/160624069-33c86039-2986-485d-819e-0b5933287f84.PNG)

## Conclusion:

This are the reviews from the customers.



