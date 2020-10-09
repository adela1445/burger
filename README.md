# EatDaBurger: Node Express Handlebars

### Overview

- Eat-Da-Burger! is a restaurant app that lets users input the names of burgers they'd like to eat.

- Whenever a user submits a burger's name, your app will display the burger on the left side of the page -- waiting to be devoured.

- Each burger in the waiting area also has a `Eat me..if you dare!` button. When the user clicks it, the burger will move to the right side of the page.

- App will store every burger in a database, whether devoured or not.

### Submission on BCS

- Heroku Link: https://young-reaches-09984.herokuapp.com/

- GitHub: https://github.com/adela1445/burger

#### NPM Packages/Dependencies

dotenv": "^8.2.0",
"express": "^4.17.1",
"express-handlebars": "^5.1.0",
"fs": "^0.0.1-security",
"inquirer": "^7.3.3",
"method-override": "^3.0.0",
"mysql": "^2.18.1"

1. Express

2. Fs

3. Inquirer

4. Method-override

5. Express-handlebars

6. Mysql

#### DB Setup

- Create the `burgers_db`.
- Create a `burgers` table with these fields:
  - **id**: an auto incrementing int that serves as the primary key.
  - **burger_name**: a string.
  - **devoured**: a boolean.

#### Directory structure

All the recommended files and directories from the steps above should look like the following structure:

```
.
├── config
│   ├── connection.js
│   └── orm.js
│ 
├── controllers
│   └── burgersController.js
│
├── db
│   ├── schema.sql
│   └── seeds.sql
│
├── models
│   └── burger.js
│ 
├── node_modules
│ 
├── package.json
│
├── public
│   └── assets
│       ├── css
│       │   └── burger_style.css
│       |── img
│       |   └── burger.png
│       ├── js
│           └── burgers.js
│
├── server.js
│
└── views
    ├── index.handlebars
    └── layouts
        └── main.handlebars
```
