<!--

AngularJS is a JavaScript web framework aimed to make web apps simple to build and easy to maintain.

We'll start by building a simple AngularJS app. After making this app, we'll generalize a few steps that can be used to build more complex apps. By the end of this course, you'll be able to use this sequence of steps to jumpstart your own AngularJS apps.
1.
Let's get started by making a simple AngularJS app. We'll explain each step in the next exercise.

In app.js, type in the contents exactly as you see here:

var app = angular.module("myApp", []);
2.
Open up index.html. Modify the <body> tag so it looks like this:

<body ng-app="myApp">


3.
Open up js/controllers/MainController.js. Type in the contents exactly as you see here:

app.controller('MainController', ['$scope', function($scope) {
  $scope.title = 'Top Sellers in Books';
}]);
4.
Go to index.html. Modify the <div class="main"> tag so it looks like this:

<div class="main" ng-controller="MainController">


In index.html inside <div class="main">, modify the <h1> element so it looks like this:

<h1>{{ title }}</h1>
View the AngularJS app in the browser by visiting http://localhost:8000. The "Top Sellers in Books" content appears as the heading of the page.

-->
