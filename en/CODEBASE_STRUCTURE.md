These are the directories that we are actively using in the development:

+ [frontend/server/controllers](https://github.com/kylelobo/The-Documentation-Compendium/tree/master/frontend/server/controllers): 
The controllers do the business logic and expose the server API.
+ [frontend/server/libs](https://github.com/The-Documentation-Compendium/tree/master/frontend/server/libs): Libraries and 
utilities.
+ [frontend/server/libs/dao](https://github.com/The-Documentation-Compendium/tree/master/frontend/server/libs/dao): Data 
Access Objects [DAO] and Value Objects [VO]. Classes used to represent database schemes and facilitate their use by the controllers.
+ [frontend/templates](https://github.com/The-Documentation-Compendium/tree/master/frontend/templates): Smarty templates 
used to generate the HTML that is displayed to users.
+ [frontend/www](https://github.com/The-Documentation-Compendium/tree/master/frontend/www): The complete contents of the 
Internet page.

### frontend / www
Content:

+ js /
+ css /

#### js
As the name implies, here is where all the javascript fonts and javascript frameworks reside. When you want to make changes, please minify the javascript and then upload.

#### css
Similar to js, here are the minified css files.

### frontend / server
Content:

* dao /
* controllers /

None of these modules should be accessible to the outside world. The only one that can call them is the user interface. That's why they're under the www folder.

#### DAO / VO

The *dao* folder contains the classes for the data access layer. It has 2 things to know: *data access objects* and *value objects*. The *value objects* (VO) are nothing much but classes that are mapped directly to each of the tables in the database. Therefore, there is a class in there called Users, since there is a table with the same name. This class has its setters and getters for each of the fields in the database. The *data access objects* (dao) are static classes for each of the tables, and they serve to obtain and make the objects persistent *vo*.

[Here is more info about this model](http://www.ibm.com/developerworks/java/library/j-dao/)

#### Controllers
The controllers are where the decisions are made. The controller uses the dao's and vo's to make decisions, and never call the database directly. This way, we avoid having separate controllers for each module of the project.
