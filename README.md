# Micro-Hell Framework Repo
#### By: Mukund Deepak

The goal is to make a Library Management System. Seeing this you would be thinking, "Ugh, so basic!". Here's the catch, the microservices architecture to be implemented is hell bent crazy! So it aint gonna be easy hehe.

Let's set some milestones shall we now?

## 1. Create an User-Friendly Frontend
You can use any frontend framework that you are comfortable with like Reactjs, Nextjs, etc
## 2. Create atleast 6 microservices with some functionality like Add Books, Remove Books, Return Books, Log lost books, etc.
Here's the catch hehe, all 6 APIs should be created by 6 different programming langauges compatible with API Development like Go, Rust, Javascript and others or backend development frameworks. You can maximum have 2 microservices/APIs made through the same programming langauges.
## 3. Make respective running docker implementations for running all 6 microservices!
Make a dockerfile for running all 6 microservices and make sure to expose a port within the Dockerfile so that you can see whether the API is running on localhost!
## 4. Kubernetes Deployment 
You need to deploy all microservices and frontends to Minikube or Kind and you need to connect all pods or deployments in such a way that they can communicate. Once done, you should be able to connect to the frontend service through localhost and test whether everything is up and running!

You need to figure out a way (It's a tool. That's the hint) to route the request from every page or frontend click to the respective microservice. This should be deployed and configured in your kubernetes cluster itself.

## 5. Pipelining
You need to create a pipeline through Jenkins or Gitlab which **should be deployed within your cluster** in such a way that any time there is a change to the code in the github repository, it should build everything with most recent rolled out changes and roll it out in your cluster.

## 6. Hosting
Once you are done with all the above milestones, you need to host your kubernetes cluster of microservices applications in some hosted instance like a DigitalOcean droplet. **Please make sure to use a free instance hosting platform. If any costs are incurred, the tech team will not be responsible for it.**

Let's see if you are up for the challenge!
