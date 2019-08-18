# jobly-API
A RESTful API for job searching, written in Express. Used in conjunction with react-jobly-app :) 
Yes there's a config.js (the secret is out, geez). 

To get this API running locally: 

(Optional): Download a database management system (PostGres) and run the appropriate command to 
run the 'tables.sql' script. In this example, I downloaded PostGres and have run this command from within 
this folder. 

```
createdb jobly
psql < tables.sql
```

This API handles three seperate routes for three resources (companies, jobs and users). Authentication is required 
to access these routes, so one must first sign-up. 
