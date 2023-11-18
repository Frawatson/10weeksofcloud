# 10weeksofcloud: Hosting a web applicaton on a kubernetes clusters. 

This project involves the deployment of a React web application using Jenkins, Docker, and Kubernetes, a powerful container orchestration platform. The React application, encapsulated within Docker containers, will be orchestrated and managed by Kubernetes to achieve scalability, reliability, and efficient resource utilization.

Key Objective: 
    Continous deployment,
    Containerization,
    Deployment Strategy.

prerequisite:
    IDE,
    DOCKER,
    Jenkins,
    Kubernete cluster,
    Grafana and Prometheus - Optional.



## To run the project 

Fork the the repository 

```bash
  copy the url: https://github.com/<url repo name>/10weeksofcloud.git
```

Go to your Jenkins UI

```bash
  New Item > Pipeline > add a name
```

Add the jenkinsfile 

```bash
  copy the jenkinsfile, navigate to configure > insert the copy jenkinsfile into the Pipeline script
```

Modify the yaml 

```bash
  Modify the todo-deployment and  todo-service files to fit your env
```


## Deployment

To deploy this project run

```bash
  run the jenkins pipeline jobs
```


## Tech Stack

**Frontend:** React, Javascript, CSS.

**CI/CD:** Jenkins

**Containerization & Orchestraction:** Docker, Kubernetes

**Monitoring:** Prometheus, Grafana.

