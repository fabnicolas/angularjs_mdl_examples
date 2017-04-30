# angularjs_mdl_tests

## Welcome!

In this repository I'm publishing some tests I'm doing while using AngularJS.

Focus is on AngularJS Material (Design Lite), but there are also AngularJS-only examples used to train myself.
For more info about AngularJS Material: https://material.angularjs.org/latest/getting-started

Notice that most of the code example will require to install npm package 'angular-material' through the following command:
```
npm install angular
npm install angular-animate
npm install angular-aria
npm install angular-material
```
A folder named node-modules will contain inside the necessary libraries that will work with those examples.

To try those packages, in your HTML documents, copy this (in head section):
```
	<!-- Angular.js libraries necessary for Angular Material -->
	<script src="../node_modules/angular/angular.min.js"></script> 
	<script src="../node_modules/angular-aria/angular-aria.min.js"></script> 
	<script src="../node_modules/angular-animate/angular-animate.min.js"></script> 
	  
	<!-- Angular Material library+CSS -->
	<script src="../node_modules/angular-material/angular-material.min.js"></script> 
	<link rel="stylesheet" href="../node_modules/angular-material/angular-material.min.css">
```

Example of using AngularJS to call a module (in head section):
```
<script type="text/javascript">    
	angular.module('first_app_hello_world', ['ngMaterial']);
</script>
```

In body section, instead:

```
<body ng-app="first_app_hello_world" ng-cloak>
	(Content)
</body>
```

Good tutorials and resources (used while learning AngularJS and Material together):
- https://www.tutorialspoint.com/angular_material/index.htm
- https://www.w3schools.com/angular/