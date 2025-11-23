# 5 DevOps Concepts

### 1 Continuous Integration (CI)
- Developers frequently merge code into a shared repository.
- Automated testing ensures errors are detected early.
- Helps maintain code quality and prevents integration issues.

### 2 Continuous Deployment/Delivery (CD)
- Automatically deploy code changes to staging or production.
- Reduces manual work and speeds up software releases.
- Ensures every update is tested and ready to go live safely.

### 3 Containerization (Docker)
- Packages application and dependencies together to run anywhere.
- Ensures consistency between developer system and server.
- Makes apps lightweight and easy to scale.

### 4 Infrastructure as Code (IaC)
- Infrastructure setup (servers, networks) is written as code (e.g., Terraform).
- Enables version control and automated provisioning.
- Faster, repeatable, and reduces human errors.

### 5 Monitoring & Logging
- Tracks application performance and resource usage.
- Helps detect issues before they impact users.
- Useful for troubleshooting and improving reliability.

# How I completed this assignment

### Repository Setup & Project Start
I began by creating a new GitHub repository and pulled it into my local machine, so I could manage everything using Git from the beginning.

### Dockerfile Development
Inside the cloned folder, I wrote a Dockerfile where I performed simple Linux operations like creating files, listing them, showing system commands, etc.

### Building Image
Once the Dockerfile was ready, I generated the Docker image using:

docker build -t sarvesssshhh/devops-fat2 .


After building, I executed the image to ensure all commands ran successfully:

docker run sarvesssshhh/devops-fat2

### Upload to DockerHub
Since the image was working correctly, I pushed it to my DockerHub account:
docker push sarvesssshhh/devops-fat2

You can view the image here:
 https://hub.docker.com/r/sarvesssshhh/cloud-devops-fat-2

### Upload to Github
I tracked and uploaded my project files to GitHub using:
- git clone https://github.com/Sarvesssshhh/Devops-FAT-2.git
- git add .
- git commit -m "Added working Dockerfile "
- git push

### Documentation Update
- Lastly, I added DevOps concepts and explanation to the README.md file and pushed those updates to github.

# How this assignment helped me learn Devops, Linux, Git and Docker

- This assignment helped me practice basic Linux commands inside a Docker container.
- I learned how to write a Dockerfile, build an image, and run it successfully.
- Pushing the image to DockerHub taught me how container sharing works.
- Using Git and GitHub improved my understanding of version control and documentation.
- Overall, it gave me practical experience with the core tools used in DevOps.