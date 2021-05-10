# Capstone-2

# Substitute Chef

## Overview

- Allows a chef, prep cook or dishwasher to connect with restaurants and schedule a shift of work
- Targeted toward restaurant workers who may need assistance finding work and restaurants needing workers
- Once logged in, workers create a profile to highlight their experience and choose their hourly wage
- Workers will be able to search for restaurants with open shifts on Google Maps
- Both restaurants and chefs will be able to rate each other after a shift
- Site will be created with dummy restaurant data in a specific city

## Schema 

- Table for workers containing username, password, first name, last name, hourly wage, rating and email  
- Table for restaurants containing name, cuisine type, location and rating

## Potential API issues

- Error handling if API is down or doesn't return a 200 response code

## Functionality/User Flow

- Upon entering the webpage, a user can choose to sign up or login as a worker or a restaurant
- Once logged in as a worker, user will be able to view/edit user information
- A worker user can also search for jobs on an interactive google map with filters for dates, type of work
- A worker can also view a page of all upcoming and past jobs
- If logged in as a restaurant, there will also be an option to view/edit user information
- A restaurant can create a listing for a job which includes type of work, start hour, end hour
- A restaurant will receive an email once a chef agrees to the job. From that email, the restaurant can view the chef's information and choose whether to confirm or deny the job
- The user will receive an email with either a confirmation or denial of the job
- Once the job is complete, all users will be sent an email which links them to a page where they can review and rate the other member

## Data
- Google Maps API will be used to search for locations
- SendGrid will be used to send emails 

## Technology Stack
- Application will be built using Javascript, React and Node

## Stretch Goals
- Restaurants can pay employees through the site
- Mobile version of the app
- Liability waver for both to sign
