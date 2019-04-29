# ReadingAPI
This repository contains a notional API specification for World Modelers machine reading components. This can be used as a starting point for the creation of REST services for machine readers so that there is a (relatively) common interface between reading systems.

## Running Swagger Editor
To use this, run the following:

```
docker pull swaggerapi/swagger-editor:latest
docker run -d -p 80:8080 swaggerapi/swagger-editor
```

This will run Swagger Editor (in detached mode) on port 80 on your machine, so you can open it by navigating to http://localhost in your browser. From there, you can paste the content from `Reading-API.yaml` to analyze the schema and models and make edits, leveraging the Swagger Editor's validation functionality.