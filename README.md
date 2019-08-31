# Polymer 3.0 Fetch Api Example

#### Thanks to "Polymer App Toolbox - Starter Kit" demo

In my project i clone this demo to use it as an appereance of this project.
https://github.com/Polymer/polymer-starter-kit

## Setup

### Install

After you clone "Polymer Fetch Api Example" as an demo you need to install it with yarn

    yarn install

## Overview

After install you need to run command yarn start to start the project.

    yarn start


#### In Source Code
![Untitled](https://user-images.githubusercontent.com/33189395/64028084-33f34c00-cb6c-11e9-970c-d2a9a29ddaac.png)

#### In Browser
![Untitled2](https://user-images.githubusercontent.com/33189395/64028433-dd3a4200-cb6c-11e9-9ca2-c0ac32bd4298.png)

## How It's Work

#### 1. Dummy Api
In this project i've used an dummy api provided by facebook.

![Untitled1](https://user-images.githubusercontent.com/33189395/64029547-06f46880-cb6f-11e9-803c-8de6af04a5b2.png)

#### 2. First i created a component "MyMovies" in my-movies.js

![Untitled3](https://user-images.githubusercontent.com/33189395/64028995-ea0b6580-cb6d-11e9-90cc-fdb183a83811.png)

#### 3. Then i used the connectedCallback function to fetch api
_connectedCallback: Called when the element is added to a document. Can be called multiple times during the lifetime of an element.
![Untitled4](https://user-images.githubusercontent.com/33189395/64031459-a6ffc100-cb72-11e9-9731-e6559bac8927.png)

#### 4. I defined each of api items is "mymovies"
![Untitled5](https://user-images.githubusercontent.com/33189395/64031794-59378880-cb73-11e9-9d3e-e33a5de64a4f.png)

#### 5. In this api i used "movies" body as an api item.
![Untitled6](https://user-images.githubusercontent.com/33189395/64031920-a3206e80-cb73-11e9-8b11-d34c28e6e0d1.png)

#### 6. Call api to movies body.
![Untitled7](https://user-images.githubusercontent.com/33189395/64032009-ccd99580-cb73-11e9-888f-f353dbbf3128.png)

#### 7. Finally used dom-repeat to array all of the items.
![Untitled8](https://user-images.githubusercontent.com/33189395/64032111-f85c8000-cb73-11e9-85fa-9fced12e9ff4.png)


## Final Results

![Untitled9](https://user-images.githubusercontent.com/33189395/64032171-17f3a880-cb74-11e9-94a0-ef7a159b8791.png)


### Hope you enjoy my work :D
