# docker-jenkinsblueocean-dockered

jenkinsblueocean image with docker command binded

Run with

`docker run --rm -u root -p 8080:8080 -v jenkins-data:/var/jenkins_home -v /var/run/docker.sock:/var/run/docker.sock -v "$HOME":/home aleixyz/jenkinsblueocean-dockered`