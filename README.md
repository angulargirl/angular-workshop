angular-workshop
================

This is the source code of the app that we built during a week long AngularJS/bootstrap training workshop.

Topics covered: controllers, views, directives, filters, services, responsive design, d3 visual, angular best prectices, bootstrap, bower, gulp, less, app minification and packaging and many more.

The purpose of this training is not to give you every single detail of angular/bootstrap concepts. It is to give you enough understanding of the high level concepts so that you can get started with working on any AngularJS project. To get the details, just read the documentation on [angular](https://angularjs.org/) and [bootstrap](http://getbootstrap.com/) website.

#####The training screencasts are available on [youtube](http://www.youtube.com/playlist?list=PLVUAGjABYyQPVUbpUjJ_tufyq5QCVsGll). 

Get started:
-----------
#####1 - Make sure you have Node/NPM installed on your system. (http://nodejs.org/)

#####2 - install global dependencies
```
sudo npm install -g bower
sudo npm install -g gulp
```


#####3 - Fork original project to your Github account
#####4- Clone that project from your Github account to your local
#####5 - cd to API and do npm install
```
cd api
npm install
```

#####6 - cd to APP and do npm install and install dependencies
```
cd ..
cd app
npm install
bower install
```
Open two terminal windows in WS
#####7 - run api in one window
```
cd api
node server
```

#####8 - run app in the other
```
cd app
gulp
```

#####8 - your app is now running at `http://localhost:9003/#/wines`

