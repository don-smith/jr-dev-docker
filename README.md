# Junior Dev Meetup: Docker

* What is Docker and why should I care about it?
  * Historically: dev !== staging !== production
  * Software, all of its dependencies and everything it needs to run
  * Shares kernel with _host_ operating system (faster to start)
* What are some of the Docker basics?
  * Images and containers
  * Pulling an image (`docker pull OPIONS IMAGE`)
  * Running a container (`docker run OPIONS IMAGE`)
  * Running detached (`-d`)
  * Exposing ports (`-p HOST:CONTAINER`)
  * Adding a volume (`-v ./app:/usr/share/nginx/html:ro`)
  * Deleting containers (`docker rm CONTAINER`) automatically (`run --rm`)
  * Create a simple `Dockerfile`
* How do I set up a dev environment?
  * Bind volume mappings
  * docker-compose to simplify using Docker (`docker-compose up`)
* Where should I go to learn more?
  * [Getting started with Docker](https://docs.docker.com/get-started/)
  * [The repo for this talk](https://github.com/don-smith/jr-dev-docker)
