angu-fixed-header-table
=======================

An AngularJS fixed header scrollable table directive

###Demo

To see a demo and further details go to http://pointblankdevelopment.com.au/blog/angularjs-fixed-header-scrollable-table-directive

###Installation

Install using bower: `bower install angu-fixed-header-table`

Alternatively download the code and include the angu-fixed-header-table.js file in your page.

Add the 'anguFixedHeaderTable' directive as a dependency of your AngularJS application:

```javascript
angular.module('myApp', ['anguFixedHeaderTable']);
```

###Usage

Simply add the *fixed-header* attribute to any tables you'd like to have a fixed header:

```html
<table fixed-header>
...
</table>
```