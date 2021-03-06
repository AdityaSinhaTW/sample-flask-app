# sample-flask-application

This application is intended for use with the `sample-deploy-pipeline` Jenkins application located [here](https://github.com/wilvk/sample-deploy-pipeline).

The application consists of two docker containers:

- A frontend website written in Python Flask
- A backend database using PostgreSQL

It is a simple message-posting application where messages entered by the user in the web interface are written to the PostgreSQL database. The web front-end shows all messages entered by users.

**Warning:** this repository deliberately contains vulnerabilities, do not use the code from this
repo in production.

## Instructions

- [0. Setup](instructions/00_setup.md)
- [1. Hawkeye](instructions/01_hawkeye.md)
- [2. Secret Scanning](instructions/02_secret_scanning.md)
- [3. CI/CD](instructions/03_cicd.md)
