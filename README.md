# simple-rest--api-node-js

Simple single file REST-API using:

-ExpressJS For basic routing handler
-Sequelize for Databases (MySQL) ORM
-body-parser for HTTP POST method handler
-multer for multipart-form and file upload handling
-MySQL database

### Routes
`GET /book/`
Get all books

`GET /book/<isbn>`
Get book by ISBN

`POST /book/`
Add new book into collection

`PUT /book/`
Update existing book

`DELETE /book/<isbn>`
Delete book by ISBN
