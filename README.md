### Docker Mojolicous Example

![CI](https://github.com/wkennedy/mojo-docker-app/workflows/CI/badge.svg?branch=master)

    #To run the application
    morbo ./script/application.pl

or to build and run a Docker image:

    #Build the image
    docker build -t mojo-docker-app .
    
    #Run the image
    docker run -it --rm -p 3000:3000 mojo-docker-app:latest
