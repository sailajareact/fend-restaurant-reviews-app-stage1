# Restaurant Reviews App (Stage: 1)

---
# Table of Contents

* [Description](#project-overview)
* [Project Instructions](#project-instructions)
* [Run the Application](#run-the-app-locally)
* [Code Dependencies](#dependencies)


## Project Overview: 

Duering the FEND program , implemented this project from
 #### _Three Stage Course Material Project - Restaurant Reviews_
 For the **Restaurant Reviews** project, 
 I have to incrementally convert a static webpage to a mobile-ready web application. In **Stage One**, you will take a static design that lacks accessibility and convert the design to be responsive on different sized displays and accessible for screen reader use. You will also add a service worker to begin the process of creating a seamless offline experience for your users.


### project-instructions

**Restaurant Reviews stage1**
I have been provided by the code for a restaurant reviews website. The code has a lot of issues. It’s barely usable on a desktop browser, much less a mobile device. It also doesn’t include any standard accessibility features, and it doesn’t work offline at all. Your job is to update the code to resolve these issues while still maintaining the included functionality. 

### Run the app locally
In order to run the application
1. Open it [here](https://sailajareact.github.io/fend-restaurant-reviews-app-stage1/)

2. Run it locally
* Download as .zip file or clone this project:

    ```
    $ git clone https://github.com/sailajareact/fend-restaurant-reviews-app-stage1.git
    ```
3. In this folder, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this, and you don't even need to know Python. For most people, it's already installed on your computer. 

In a terminal, check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.) For Python 3.x, you can use `python3 -m http.server 8000`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.

4. With your server running, visit the site: `http://localhost:8000`, and look around for a bit to see what the current experience looks like.


## Dependencies

* [Project Restaurant Reviews (Stage 1) - Starter Code](https://github.com/udacity/mws-restaurant-stage-1)
* Leaflet.js and Mapbox:
* Normalize.css
This repository uses [leafletjs](https://leafletjs.com/) with [Mapbox](https://www.mapbox.com/). You need to replace `<your MAPBOX API KEY HERE>` with a token from [Mapbox](https://www.mapbox.com/). Mapbox is free to use, and does not require any payment information. 

### Note about ES6

Most of the code in this project has been written to the ES6 JavaScript specification for compatibility with modern web browsers and future proofing JavaScript code. As much as possible, try to maintain use of ES6 in any additional JavaScript you write. 



