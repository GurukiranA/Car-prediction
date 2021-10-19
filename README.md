## Table of Content
  * [Demo](#Demo)
  * [Brief Summary](#Brief-Summary)
  * [Aim of the Project](#Aim-of-the-Project)
  * [Package Installation](#Package-Installation)
  * [Directory-Heirarchy](#Directory-Hierarchy)
  * [Technologies-Used](#Technologies-Used)
  * [Credits](#Credits)


## Demo

https://car-prediction0.herokuapp.com/

## Brief Summary

This is a simple car price prediction Flask app which is trained on the dataset available on Kaggle  which takes in the following input parameters like 

     i.) Year                                                    (The year when the car was purchased)
   
    ii.) What is the Showroom Price?(In lakhs)                   (The Price at which the car was bought at the time of purchase)
  
    iii.) How Many Kilometers Driven?                             (The distance travelled by the car)
   
    iv.) How much owners previously had the car(0 or 1 or 3) ?   ( Number of owners who had owned the car previously)
   
     v.) What Is the Fuel type?                                  (Fuel type of the car, Petrol or Diesel)
     
    vi.) Are you A Dealer or Individual?                         (Status of the seller)
    
    vii.) Transmission type                                       (This has two options which includes manual or automatic


   Considering the above parameters, the final selling price of the car is shown as result .


## Aim of the Project
This project was done as part of the Kaggle Competition for Vechicle Dataset(Used cars data) which aims to find out the final selling price of the used cars based on various parameters

## Project Technical Details

1.) The dataset is trained using Random Forest Model.

2.) Building and hosting the Flask App on Heroku.


    * The user must input several parameters displayed on the webpage
    
    * The final output will be the value of the used car based on the input parameters.
		
## Package Installation

The Code is written in Python (Version 3.6).The link for python installation is given [here](https://www.python.org/downloads/).If the python available in the system is of a lower version, then it can be upgraded using the pip package to ensure that one has the latest version of pip.To install the requried packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository: 

pip install -r requirements.txt

## Directory Heirarchy 

1.) app.py

2.)template
   
       i.) index.html
   
3.)requirements.txt

4.)runtime.txt

5.)LICENSE

6.) Procfile

7.) README.md

## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)

<img target="_blank" src="https://user-images.githubusercontent.com/34685034/137955262-a06f3f9e-665c-4e5f-8586-fab3ad5bbf78.png" width=350>            <img target="_blank" src="https://user-images.githubusercontent.com/34685034/137956095-0599307e-7f62-407f-a059-8c6adad9f617.png" width=350>      


<img target="_blank" src="https://user-images.githubusercontent.com/34685034/137956359-36163fc8-3608-422f-9f08-af0b04ff9e59.png" width=250> 

<img target="_blank" src="https://user-images.githubusercontent.com/34685034/137956772-15f5a5df-c423-4662-a8fc-6bdca1bb7af7.jpeg" width=400> 


## Credits

All the images have been downloaded from Google.

Source: Google Images. 







