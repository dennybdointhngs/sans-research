# sans-research

This repository contains the necessary files to replicate my research paper. It utilizes Docker to generate a Splunk instance. Test data is generated using the SA-Eventgen app from Splunk. The custom sans-research-app contains the necessary files for the various dashboards and searches used.

To start up the container, use docker-compose when you are in the directory with the docker-compose-yml file:
```bash
docker-compose up
```
Navigate to the GUI:
```
http://localhost:8000/
```
Log in with the following username/password: `admin/sans-research2023`
