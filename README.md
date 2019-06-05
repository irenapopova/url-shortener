# URL Shortener challenge

A project to shorten URL's quickly and painlessly. Written using JavaScript, database sql,  [Koa](http://koajs.com/) and [Knex.js](http://knexjs.org/).



* `apache.conf` contains the configuration I used to make `localhost:8088/api` go to `localhost:8989`
* `database.sql` contains the SQL code to create the database so you don't have to just type it all out

###
Here are the stories to implement:
1. As a developer, I have an algorithm which shortens URLs
2. As a developer, I have a local database with all URLs
3. As a user, I can add a URL and receive a short version of it
4. As a user, I'm redirected to the original URL based on the short one
