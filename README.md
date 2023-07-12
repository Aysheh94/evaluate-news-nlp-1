# Evaluate News Article With NLP
4th project at Udacity Front End Web Developer Nanodegree program.

## Overview
The news article with NLP project is developed using a client-server architecture which makes a call to the MeaningCloud API after submitting the form. When the call is successful, the API response will be demonstrated in the browser. The result is the sentiment analysis of the text of the URL that is passed into the textbox. 

## The goal of this project:

- Setting up Webpack
- Using Sass styles
- Using Webpack Loaders and Plugins
- Creating layouts and page design
- Setting up Service workers
- Using APIs and creating requests to external urls
- Using Unit Tests using Jest Framework

## Getting started

`cd` into your new folder and run:
- `npm install`
- Setting up the API(MeaningCloud API) and create a request.
- Parse the response body to dynamically fill content on the page.
- Test that the server and form submission work, making sure to also handle error responses if the user input does not match API requirements.
- Go back to the web pack config and add the setup for service workers. 
- Test that the site is now available even when you stop your local server

## Running The Project
After navigating to the folder that includes the project, follow these steps:
1. `npm install`
2. `npm run build-prod`
3. `npm start`
4. Access the url http://localhost:8081
5. In the textbox, enter the url of the page with the text to be analysed.
6. `npm run test` to make testing with jest
