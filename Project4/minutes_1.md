Rashaun Booker 
October 26, 2026

| PBI | Task | Status | Sprint | Estimate | Assigned | Reviewer |
|---|---|---|---|---|---|---|
| P4-01 | Outline architecture and data flow | To do | Sprint 4 | 1 day | Member 1 | Rashaun |
| P4-02 | List major components and files | To do | Sprint 4 | 1 day | Member 2 | Tyana |
| P4-03 | List database tables and owners | To do | Sprint 4 | 1 day | Member 3 | Jalen |

So far this is my updated table that me and my team have been working on The architecture means behind our prototype and even in general and Architecture is the overall plan that shows the main parts of the app, how they work together, and where information is stored. Three common styles we looked at are **client-server** (a browser talks to a server), **layered/three-tier** (screen, app logic, data), and **microservices** (smaller services that run separately). We chose a layered design for this project because it is easier for our group to manage.

With our Cloud-based software the code runs on a server hosted online, so users access it through the internet. The database is **shared**, not a separate local database on every user's computer. Only the back end connects to it. We would use secure connections and store access credentials in environment variables.

Docker and containers:Docker is a tool for packaging and running software in containers. A container is an isolated running copy of our app with what it needs to work. An **image** is the saved package used to start a container. The **Docker daemon** is the background service that builds images and starts/stops containers. It runs on the Docker host, not inside the app container. We use a `Dockerfile` to describe the image.

I will be finding out what are all the major components for this product, Tyana will be looking into the cloud base, and Jalen will look for the usage of database.
