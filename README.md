# angular-alasql
## AngularJS plugin for [Alasql](https://github.com/agershun/alasql) database


The idea: make it simple as:
```
    <table>
	    <div ng-sql='SELECT * FROM people JOIN cities ON city WHERE country == "Belgium"'>
		    <tr><td>{{id}}<td>{{name}}
	    </div>
    </table>
```
