# MongoDB and Mongoose Practice

## Description: An app that does CRUD operations utilizing Postman.

## Prerequisites
- npm installed
- Mongodb installed
- Postman installed

## How to install and run
1. Run `npm install` in terminal
2. Run `npm start` in terminal
3. In Postman you can go to these endpoints:
  * GET localhost:3001/api/books/
  * GET localhost:3001/api/books/:bookId
  * POST localhost:3001/api/books/
    * Using the below book schema


### Mongoose Book Schema
```
  title: {type:String},
  author: {type:String},
  genre: {type:String},
  read: {type:Boolean, default: false}
```

