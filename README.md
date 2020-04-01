# airbnb-photogallery

This repo creates the backend photo gallery module of Airbnb. The goal is for the app to handle web scale traffic serving at least 1000 requests per second. 

## Related Projects
https://github.com/yumnoms/lilly-gallery-service-proxy

## Table of Contents
1. [Usage](#Usage)
2. [Requirements](#requirements)
3. [Development](#development)

## Usage

> Some usage instructions

### Setting up mySQL database & seeding the database

For mySQL, if the user 'Student' doesn't exist, access mySQL and run:

```javascript
CREATE USER 'student'@'localhost' IDENTIFIED BY 'student';
```

You may need to grand privileges to the 'student' user on all databases. Run this script in MySQL.

```sql
GRANT ALL PRIVILEGES ON *.* TO 'student'@'localhost';
```

Then in the terminal:

```
npm run schema //password: student
npm run seed:postgres

```



### Start the server

```
npm run start

```

## Requirements

An `nvmrc` file is included if using [nvm](https://github.com/creationix/nvm).

- Node 6.13.0
-  "async": "^3.1.0",
- "axios": "^0.19.0",
- "cors": "^2.8.5",
 -    "express": "^4.17.1",
 -   "fs": "0.0.1-security",
 -   "mongo": "^0.1.0",
-  "mongoose": "^5.7.13",
-    "nano": "^8.1.0",
-    "newrelic": "^6.2.0",
-    "os": "^0.1.1",
-    "path": "^0.12.7",
-    "pg": "^7.15.1",
-    "react": "^16.12.0",
-    "react-dom": "^16.12.0",
-    "sequelize": "^5.21.3"

## Development

### Installing Dependencies

From within the root directory:

```sh
npm install
```
