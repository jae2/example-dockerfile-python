Example Dockerfile App
======================

A sample dockerfile which runs python http server inside a container. If required we can create a seperate python script to run inside the container to do something more complicated than display a http page.

## Usage

docker build -t sample .
docker run -p 5000:5000 sample




