# Cyber Assignment

## Project structure

This project is made up of two applications stored in the folders /frontend and /backend.

The code for each of these applications is stored in the src directory. Files in the etc directory are used to build and run docker images.

## Running this project

To run this project, use command:

```bash
docker-compose up
```

## Lifecycle

* User visits the application forntend
* User uploads CSV file via dropzone
* App checks to see if file is CSV
* App uploads the file to S3 and stores a record of S3 object key used
* App returns s3 object key to user