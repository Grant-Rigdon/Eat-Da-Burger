# Eat-Da-Burger

### Overview

In this assignment, you'll create a burger logger with MySQL, Node, Express, Handlebars and Sequelize. Be sure to follow the MVC design pattern.

### Instructions

* Eat-Da-Burger! is a restaurant app that lets users input the names of burgers they'd like to eat.

* Whenever a user submits a burger's name, your app will display the burger on the left side of the page -- waiting to be devoured.

* Each burger in the waiting area also has a `Devour it!` button. When the user clicks it, the burger will move to the right side of the page with customer.

* Your app will store every burger in a database, whether devoured or not.

#### Directory structure

All the recommended files and directories should look like the following structure:

```
.
├── config
│   └── config.json
│ 
├── controllers
│   └── burgers_controller.js
│
├── models
│   ├── index.js
│   └── burger.js
│ 
├── node_modules
│ 
├── package.json
│
├── public
│   ├── css
│   │   └── style.css
│   ├── image
│   │   └── ...
│   ├── js
│   │   └── burgers.js
│   │
│   └── test.html
│
├── schema.sql
│
├── server.js
│
└── views
    ├── index.handlebars
    └── layouts
        └── main.handlebars
```

- - -

## Copyright

Coding Boot Camp (C) 2016. All Rights Reserved.

