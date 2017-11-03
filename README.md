# microservice-docker-seed
The careercolony microservice seed with docker ducker plugin
Dockerize app

clone the project and run: $ sbt docker:publishLocal

Run container

After generating the container (step above), run the container:

$ docker run -dit -p 8080:8080 --name akka-minimal-seed akka-http-docker-minimal-seed:1.0

You will get a response like this:

$ docker run -dit -p 8080:8080 --name akka-minimal-seed akka-http-docker-minimal-seed:1.0
6c3ceda8b0a4dc67633c577bb57dd949e17afbc101fd1b190c2e67efba9c9b7f
Test app

Open address on a web browser: http://localhost:8080/users

To test using Postman, use this link:

Run in Postman

Stop the container

To stop the container, run:

$ docker stop akka-minimal-seed

