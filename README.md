### Steps to build& run sample FHIR server

1. Build the image.

        ``` docker build -t wso2healthcare/demofhirapp .```

        Note: If you are on a Mac M1 set the following env variable before build

        ``` export DOCKER_DEFAULT_PLATFORM=linux/amd64 ```

2. Run the image.

        ``` docker run -p 8080:8080 wso2healthcare/demofhirapp ``` 
