Rashaun Booker 

On todays minutes me and my team have been finishing up on our prototype but before we do we have to answer these following questions because they were very helpful in the process.

How is database used? It is local database or shared database?

If it is cloud-based, what are inside your container?

We were able to find out that the data is used by a user that makes a request from the browser the cloud back end checks the input, reads or saves the data in the shared database, and returns the response. The browser never receives database credentials.

Which lets me know its a cloud base software because the code runs on a server hosted online, so users access it through the internet. The database is shared, not a separate local database on every user's computer. Only the back end connects to it. We would use secure connections and store access credentials in environment variables.

To answer my next question which is what is inside the container and its the interface, conversion code, routes, and database connection library are packaged inside one Flask app image. The PostgreSQL database is a separate shared cloud service. The app container does not store permanent user data on its own disk.
