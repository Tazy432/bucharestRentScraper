# bucharestRentScrape 

## Overview
A Python program that scrapes apartment data—such as
 address, rooms, area, and price—for a given city and exports it
 to a CSV file. It calculates travel time in minutes by bus
 between a user-provided address and each apartment using
 Google Maps data, automated with Selenium and processed
 with Pandas. This project helped me find great rent and
 deepened my skills in web scraping, automation, and data
 handling.
![image](https://github.com/user-attachments/assets/f3426245-19da-4943-8976-d7f640dc4f07)

---
## What are the practical applications of this app ?
I have created this app to find affordable rent near my workplace and it worked. 300€ rent for a 3 bedroom apartment in bucharest near the subway station i'd say it's a real catch.
## Let's bury those arrogant real estate agencies !!!
---

## Technologies Used

### **Python Jupyter notebook**
Python serves as the backbone of the project, providing simplicity and readability. Key libraries used include:
- **Selenium:** For web automation and browser interaction.
- **Pandas:** For data handling and manipulation
- **Ftfy:** For correcting encoding errors ( cleaning data )
- **tkinter&customtkinter:** For GUI 

---

## Installation & Setup

Follow these steps to get the project up and running:

### 1. Clone the repository

Clone this repository to your local machine using the following command:
```bash
git clone https://github.com/Tazy432/bucharestRentScraper
```
In order to be able to clone the repository you need to make sure that you have git installed on your machine. 
If you do not have GIT , you can get it from https://git-scm.com/downloads

### 2. Create a virtual enviroment (optional but recommended)
It’s recommended to create a virtual environment to isolate the project’s dependencies.

## i. On Windows:

```bash
python -m venv [name_of_virtual_enviroment]
```
## ii. On macOS/Linux:

```bash
python3 -m venv [name_of_virtual_enviroment]
```

After you have created the virtual enviroment, you need to activate it with the following command:

## i. On Windows:
```bash
.\venv\Scripts\activate
```

## ii. On macOS/Linux:

```bash
source venv/bin/activate
```

Now that the virtual environment is active, install the required packages by running the following command:

```bash
pip install -r requirements.txt
```
Now the setup is done and you should be able to run the application.

## Step-by-Step Manual

The program in really simple the user is asked to input **4** things , in the following order:

### 1.The number of rents the user intends to scrape with the app
This should be an positive integer greater than 1
eg: 10
### 2.The address of the workplace ,the address of the mistress , favorite club , whatever
This should be a street name , street number(optional), zipcode(optional) and most important **THE CITY** in which the street is found.
It is of great importance to specify the city because the app scrapes data from google maps , and if only
the street is present , that might result in an error because a street named *X* might be found in 
more than one cities . Let's avoid that ☺
eg: Iuliu maniu 152A bucuresti
### 3.The city in which the bot looks for rent announcements
The user can choose from a dropdown list one out of the 42 romanian counties
eg :Bucuresti
### 4.The directory in which the scraped data shall be saved
The user should press on the **choose directory** button to select a directory in which to save the scraped data , or insert by hand the full path of the directory
eg: C:/Users/Andrei/Desktop

---
The scraped data will be saved in the directory chosed by the user in a csv file of the following format
[city_from_user_input][yyyymmdd_hhmmss]
eg: brasov20250109_130607
## Future improvements:
- Connect to a relational database 
- Add a loading bar to watch the progress 
- More user input validation 
- I saw that on storia.ro , the site from which i scrape that , i can see the dates at which the rents are actualized and so i could be able to track the changes of the rents in time ( pretty f cool )
- More cleaning fundtions 
- A statistics part to analyze rents in certain neighbourhoods , or how much more expensive are rents near subway stations ... endless posibilities
---
Great project , great results . Hope you think its great aswell, if you have some constructive criticism don't hesitate to contact me here on github or on gmail panzanihoratio@gmail.com .This project is made 100% by Andrei Pantazi (yours trully)


