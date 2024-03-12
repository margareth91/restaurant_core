# Restaurant Core
Simple fullstack web app created with Django and Django REST framework for a back-end and with Next.js for front-end.

## Table of Contents
* General info
* Main technologies
* Setup
* Status
* Sources

## General info
This web app allows to manage a restaurant's menu. The user can list, create, updatie and delete a menu.

The reason for building this app was to understand how to connect a Django app in back-end with a front-end app using DRF instead of making a use of Django built-in Model - View - Template architecture.

## Main technologies
* Django 5.0
* Django REST framework 3.14
* Next.js 14.1
  
## Setup
Please make sure you have Python and Next.js already installed on your machine.
Then, clone this repo to your desktop and install all dependencies.

For back-end:
activate virtual env and run `py manage.py runserver` to start the back-end app on your localhost: `http://localhost:8000`.

For front-end:
go into `menu-frontend` folder and run `npm run dev` to start the web app on your localhost: `http://localhost:3000`.

## Status
App is completed and ready to be implemented.

## Sources
This app is created based on Mangabo Kolawole tutorial "Building a FullStack Application with Django, Django REST & Next.js", published in DEV Community [here](https://dev.to/koladev/building-a-fullstack-application-with-django-django-rest-nextjs-3e26), based on the latest versions of the technlogies used.

