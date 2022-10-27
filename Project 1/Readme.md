# Project 1
Deploying an application using Firebase and Google Cloud Run

**Part I**
- Create a group static website that includes a) each students name b) status (Junior/Senior) c) Devops-{Your Group Number}
- You can use HTML only or a combination of any of HTML/CSS/JS.  No Backend/Database Needed.
- Deploy this website to Firebase.
- Invite the professor to the project as a viewver/collaborator
[Group Domain](https://devopsproject1-6ab90.firebaseapp.com/)

**Part 2**
Group App + Website (Applications - Wordpress, your custom HTML website)
- Create a resolved domain with Google domains.  A single domain will suffice here as you can use subdomains as well.   
- Use a single Docker Compose file, create two containers on the same network, one for Wordpress and one for your HTML website)
- Recommend installing any required language or linux dependencies you believe to be necessary.   Size is less of a concern for this project.
- Serve the files on your free GCP cloud server using docker compose up
- Commit the Docker Project to the professor provided Gitlab Repo.
- Ensure docker compose down works as well.  You'll be asked to start and stop the containers during the presentation.
- The professor should be able to clone the repository and perform docker compose up  and docker compose down on a Linux distribution with a single command.

_The first portion of the project was completed but not hosted with google cloud run. My group and I used google cloud platform (specifically a VM instance) to host and make the docker files for the PHP site and I was able to connect the local host website to a domain._
