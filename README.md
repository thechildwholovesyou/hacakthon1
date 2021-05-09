# hacakthon1


With the help of Puppeteer and NodeJS, I have written an automated script which helps an user to get the following details :

1. The covid vaccination centers' current data in his/her district is fetched through an url, which is stored in json format and also an screenshot is generated.

2. The json formatted data is converted into an excel file using nodeJS module.

3. The nearest covid vaccination centre is fetched from google maps , screenshot of map is generated and link of the shortest path is extracted. 

4. Using nodemailer , excel file and screenshot of map and site is mailed to the uers's email address.

Steps to run the file on your system : 
Step 1: clone the repo
Step 2: delete node modules and nodemailer 
Step 3: npm i nodejs
Step 4: npm i puppeteer 
Step 5: npm i cheerio 
Step 6: npm i nodemailer
Step 7: npm i xlsx

Ready to go !!
