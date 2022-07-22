# Metered Video Calling Quickstart for JavaScript
## Powered by [Metered SDK](https://metered.ca)

## Overview

![Metered Demo APP](src/public/images/screenshot.png?raw=true)

In this application would give you a starting point to build your own video calling application with Metered.

The application using Javascript + Node.JS and Express Backend.

## Guide

Here the complete explantion on how this application is built here: https://docs.metered.ca/docs/step-by-step-guide-to-group-video-calling-app-using-metered

## Setup Requirements

Before you can use this application, you would need a `Metered Domain` and `Secret Key`. To Obtain them do the following:

  - Signup for a free account at https://dashboard.metered.ca/signup
  - You will get the Metered Domain During Signup
  - After Signup go to Developers page, from there you can get the `Secret Key`

## Setting up the Application

  1. Clone the Project
  2. In the root folder create a `.env` file, inside the add your `Metered Domain` and `Secret Key`
  
      ```
      METERED_DOMAIN = ""
      METERED_SECRET_KEY=""
      ```
  3. Install dependencies from npm
    
```
npm install
```
  
  ## Run the Application
  
  To run the application, just run npm start and the application will be live at http://localhost:4000
  
  ```
  npm start
  ```
  
  ## Testing on Multiple Devices
  
  To test the application on multiple devices you can use [tsocket](https://tsocket.org), you can download and install it from here: https://tsocket.org
  
  After installing run the demo application then run the command
  
  ```
  tsocket http 4000
  ```
  
  tsocket will give you a URL that you can open on multiple devices to test out video conferencing.
  
  ## Further Reading
  
  Checkout https://docs.metered.ca to read more about the Metered Video API 
  
 
