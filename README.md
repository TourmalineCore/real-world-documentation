# To Do real-world project
We have prepared an example of the simplest project called "To Do". This repository includes links to all repositories where the services involved in this project are located.</br> 
The project is closed by authentication, access rights are delimited using a token that contains information about the user's role and his available capabilities in the system. This project contains all the necessary features that are needed for real projects.</br>
We hope this example will be useful to you for further development.
# Repositories
- [API](https://github.com/TourmalineCore/real-world-api)
- [UI](https://github.com/TourmalineCore/real-world-ui)
- [Reverse-Proxy](https://github.com/TourmalineCore/real-world-reverse-proxy)
- [Account management UI](https://github.com/TourmalineCore/real-world-accounts-ui)
- [Account management API](https://github.com/TourmalineCore/real-world-accounts-api)
- [Auth UI](https://github.com/TourmalineCore/real-world-auth-ui)
- [Auth API](https://github.com/TourmalineCore/real-world-auth-api)

# Ports in Docker Compose
If you run services in Docker via Docker Compose, you can access it using this list of ports:

**API's:**
- **API:** 10001
- **Accounts:** 10002
- **Auth:** 10003

If you need to connect to the database of each service, use this ports and database names:

**Databases:**

**API:**
- Name: api-db
- Port: 5001

**Accounts:**
- Name: accounts-db
- Port: 5002

**Auth:**
- Name: auth-db
- Port: 5003

# Repository naming
- the first part of the name includes the name of the project
    - real-world
- the second part of the name includes the name of the service
    - for example, 'accounts' or 'auth'
- the third part of the name includes the type of project
    - ui or api