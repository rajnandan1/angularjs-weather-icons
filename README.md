# angularjs-weather-icons (Animated)
An angularJS(1.X) directive to display 6 animated weather icons.
## How to Install

- Download the js and include it in your project
``` <script src="lib/xurple-weather-icons.js"></script> ```
- You can also directly do it from raw git
``` <script src="https://cdn.rawgit.com/rajnandan1/angularjs-weather-icons/master/xurple-weather-icons.js"></script> ```
- Include the directive in your angular module
```
var myApp = angular.module('app', [
	'wicons'
]);
```
## How to use
- In your view
```<div weather-icon="weather"></div>```
- In your controller you can specify what weather it is
```
angular.module('app.controllers').controller('ViewOneCtrl',function($scope){
	 $scope.weather='cloudy';
})
```
### Possible weather options are
- cloudy
- day
- night
- rainy
- snowy
- thunder
