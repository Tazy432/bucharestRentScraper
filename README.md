# Project Name

## Overview
A Python program that scrapes apartment data—such as
 address, rooms, area, and price—for a given city and exports it
 to a CSV file. It calculates travel time in minutes by bus
 between a user-provided address and each apartment using
 Google Maps data, automated with Selenium and processed
 with Pandas. This project helped me find great rent and
 deepened my skills in web scraping, automation, and data
 handling.

---
## What are the practical applications of this app ?
I have created this app to find affordable rent near my workplace and it worked. 300€ rent for a 3 bedroom apartment in bucharest near the subway station i'd say it's a real catch.

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

### Step-by-Step Manual


