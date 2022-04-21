# DockerLearning
Docker learning from Youtube

Workflow with Docker

Step 1: You are developing a JavaScript Application

Step 2: Committing it to a version control tool like git

Step 3: As soon as you commit to git it will trigger to CI tool jenkins for building the application in jenkins.

Step 4: Jenkins will create artifacts and create a Docker image from it and push that image to private repository.

Step 5: Here Application Server pulls image from docker repository and start the container.
