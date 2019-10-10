# Simple marketplace API using JavaScript, Node.js, Express, MongoDB, Mongoose, JWT, Kue, Redis, Nodemailer and Handlebars

The API allows you to create users, ads and make purchases.

For the database and redis configuration, in development environment I suggest using Docker. Just run the following commands:

```shell
docker run --name databasename -p 27017:27017 -d -t mongo
```

```shell
docker run --name redisname -p 6379:6379 -d -t redis:alpine
```

Replace databasename and redisname with the name you prefer.

And for the SMTP server in development environment I suggest using [Mailtrap](https://mailtrap.io/).
