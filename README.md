The tutorial assumes that you have a free Heroku account (Heroku CLI installed), git installed, and that you have Node.js and npm installed locally.

# Run localy

To run this yourself, do the following steps:

1. Clone this repo with `git clone https://github.com/jenizar/sap-ui5-walkthrough.git`

2. Setup the dependencies with `npm install` (make sure you are in `sap-ui5-walkthrough` directory)

3. `npm start`

4. Open http://localhost:5000/webapp/ in yoiur favorite browser.

# Deploy to Heroku cloud

$ heroku login

$ heroku create jenizar-sapui5-walkthrough

$ git push heroku main

$ heroku open

--> if problem use:

$ git remote rm heroku

$ heroku create jenizar-sapui5-walkthrough

$ git push heroku HEAD:master

Note:

- jenizar-sapui5-walkthrough is name your apps in the url

- It automatically open your browser and add /webapp in the end of url https://jenizar-sapui5-walkthrough.herokuapp.com/webapp

- It utilize nodejs buildpack

![alt text](https://github.com/jenizar/sap-ui5-walkthrough/blob/main/Screenshot/Screenshot%20from%202021-12-19%2015-18-09.png)

![alt text](https://github.com/jenizar/sap-ui5-walkthrough/blob/main/Screenshot/Screenshot%20from%202021-12-19%2016-09-08.png)


![SAP UI5 YouTube Course/ Tutorial](https://user-images.githubusercontent.com/19891236/95460237-996b5c00-096c-11eb-9417-b15a384e098c.png)

# SAP UI5 walkthrough

Learn SAP UI5 with this walkthrough repository to be used with the full Youtube course/tutorial found [here](https://youtu.be/mmSB85rWQ3w).
 
You can find each step from the repository linked with a timestamp in the video description. Feel free to start at any point and download the code from the relevant commit depending on which step you want [here](https://github.com/brandoncaulfield/sap-ui5-walkthrough/commits/main).


 
