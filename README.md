# Node, Express, SQL and live data

There are issues with connecting to the database when the form is run.

Git clone to the directory of your choice, cd into the project folder and NPM install.
Run npm start and navigate to localhost:3000

you'll need to change the settings in config.js to point to your database, if you named it something different than what's in the file.

NOTE - if you hit the delete button, that row will be gone from you database forever; the AJAX call for that car won't work and will start to error out.

So you'll have to add that data back in manually for now, because we haven't done the "post" part of the API.
