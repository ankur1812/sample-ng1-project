# Sample NG-1 Project

### Project Info

This is a starter boiler plate for creating an AngularJS (NG-1) Application

### File Sections

The app.html file includes the below key sections

#### Dependencies

The key scripts and stylesheets are linked at the top. These include: 

- AngularJS (v1.8.2)
- JQuery (v3.5.1)
- Bootstrap (v3.4.1)
- Font-Awesome Icons library (v4.7.0)

#### HTML

This is the generic HTML included inside the `body` tag. The app is defined as a ng-1 application by including the attributes `ng-app` and adding a  `ng-controller` either in the body tag or inside its child div.

#### Styles

Generic styles needed for the project.

#### Script

The script creates a new ng-1 app, sampleApp, by calling 
`var app = angular.module("sampleApp")`

Once the app is created, a controller for the html div is defined using `app.controller()` function, which is also using an angular service, ApiServices, created using `app.service()` function.

Creating a service for making HTTP calls is not compulsary; $http dependency used inside it can be used directly inside the controller too, in that case the code for the service can be moved inside the controller directly

