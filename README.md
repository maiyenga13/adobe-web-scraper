# Web Scraper for Adobe Security Updates

An application that takes in a url to an Adobe security update posting [(ex. https://helpx.adobe.com/security/products/magento/apsb20-47.html)](https://helpx.adobe.com/security/products/magento/apsb20-47.html) and gathers information on the relevant security issues for each specific product versions, and compiles relevant information in a JSON file. 


## Instructions
To run the code file:
- install dependent libraries from requirements.txt (mainly: requests, bs4, datetime, python-dateutil, jsonlib)
- run program from within meghna_iyengar_assigment directory (i.e. $ python3 assignment1.py)
- The program will ask for the url as input
- Once input is entered, the program will write the JSON output to a file "data.txt"
"# adobe-web-scraper" 
