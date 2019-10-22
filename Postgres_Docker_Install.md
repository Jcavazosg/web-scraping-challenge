Step 1: Signup for DockerHub
https://hub.docker.com/signup

    * Remember to save your Docker ID and Password!

Step 2: Download Docker
- Mac:
https://docs.docker.com/docker-for-mac/install/

- Windows:
https://docs.docker.com/docker-for-windows/install/

Step 3: Clone compose-postgres
git clone https://github.com/khezen/compose-postgres.git

The navigate into repo and run
`docker-compose up`

To learn more visit
https://github.com/khezen/compose-postgres

Step 4: Connecting
Visit: http://localhost:5050
    
    Username: pgadmin4@pgadmin.org
    
    Password: admin

Add a new Server: *Object->Create->Server...*

1) Fill in `Name` (e.g local)

2) Click on `Connection` tab

Fill in with info below

    Host: host.docker.internal
    Username: postgres
    Password: changeme
    Port: 5432

Then hit `Save`