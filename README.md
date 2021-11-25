# This project uses the NODE.js cloudant SDK from IBM

## To run the project go to examples and run the commands

```
npm install
```

## Set credentials

Create an environment variable with your Cloudant credentials e.g.

```
export CLOUDANT_URL=https://myusername:mypassword@mydomain.cloudant.com
```

## Run

```
node crud.js
```

This creates a database called `crud`, adds a document `mydoc`, reads it back, updates it, deletes it and then deletes the database.

## This is what has been done till now. Need to develop custom functions for generating query and retriving data