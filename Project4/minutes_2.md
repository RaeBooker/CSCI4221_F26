Rashaun Booker 

So on todays update me and my team have been looking over together what is daemon and an image?
We also came together to see what are the major and sub components?


 The Docker daemon is the background service that builds images and starts/stops containers. It runs on the Docker host, not inside the app container. We use a `Dockerfile` to describe the image.

What is inside the container? The interface, conversion code, routes, and database connection library are packaged inside one Flask app image. The PostgreSQL database is a separate shared cloud service. The app container does not store permanent user data on its own disk.

One of the components that we have is | Component 1: Conversion | Take a number or Roman numeral, check the input, and return a correct conversion. | Team member 1 (confirm name) 

 Conversion.** Take a number or Roman numeral, check the input, and return a correct conversion. **Sub-components:** input checks, service logic, API route, and testing. **Database use:** Reads and writes recent conversions so users can see what they entered before. **Needed files:** `conversion.py, routes/conversion_routes.py, tests/test_conversion.py`.

That is what I have so far for this minutes so on the next one we should be wrapping it up
