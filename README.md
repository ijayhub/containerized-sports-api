<div id="top"></div>

<details>
  <summary>Table of Contents </summary>
  <ol>
  <li><a href="#technical">Technical Architecture</a></li>
    Project</a>
        <ul>
          <li><a href="#about-the-project">About The Project</li>
          <li><a href="#last-project">Last Project</li>
          <li><a href="#current-project">Current Project</li>
          <li><a href="#overview">Overview</a></li>
          <li><a href="#key-features">Key Features</a></li>
        </ul>
    </li>
  <ul>
    <li><a href="#built-with">Built With</a></li>
    <li><a href="#technologies-used">Technologies Used</a></li>
    <li><a href="#challenges">Challenges</a></li>
    <li><a href="#solution">Solution</a></li>
  </ul>
</details>

# Containerized Sports API Management System

## Technical Architecture 
<img src="./my-lil-expanation.png" alt="my-lil-explanation"/>


# About the project  

## Last Project 
 
I created an event-driven notification app to fetch NBA data and gain a better understanding of AWS Lambda, SNS, and EventBridge. You can check out the project here: [Project Link](https://github.com/ijayhub/game-day-notifications-aws). 

---
<p align="right">(<a href="#top">back to top</a>)</p>

## Current Project

Today, I am building a **containerized management system** that uses Docker as a Orchestration tools for storing code, dependencies, and libraries. The system will query data while running the services in **AWS Fargate**. 

---
<p align="right">(<a href="#top">back to top</a>)</p>


### Overview

* [Blog Documentation]()

<p align="right">(<a href="#top">back to top</a>)</p>


## Key Features

- Fetching real-time data using a **REST API**. 

- Implementing **containerization** with Docker. 

- Creating a customized API route using **Amazon API Gateway**.

<p align="right">(<a href="#top">back to top</a>)</p>

## Tech Stack  

### **Built With**

- **Amazon ECR (Elastic Container Registry)** – Helps with registering Docker images 

- **Amazon ECS (Elastic Container Service)** – Manages the creation of containers.

- **Amazon Fargate** – A serverless compute and runtime environment.  
- **Application Load Balancer (ALB)** – A type of **Elastic Load Balancer (ELB)** that distributes incoming traffic across multiple targets to ensure high availability and fault tolerance.

- **Amazon API Gateway** – Prevents direct user requests by providing a controlled access layer.

- **[SerpAPI](https://serpapi.com/)** – Used to fetch **NFL** data for users. 
--- 

## **Technologies Used**

- **Cloud Provider**: AWS

- **Core Services**: Amazon ECS (Fargate), API Gateway, CloudWatch.

- **Programming Language**: Python 3.x.

- **Containerization**: Docker.

---
<p align="right">(<a href="#top">back to top</a>)</p>


### Challenges

I faced a challenge while creating a second cluster, service, and task. The deployment kept failing.

<img src="./failed.png" alt="failed-service-deployment"/>
<p align="right">(<a href="#top">back to top</a>)</p>


### Solution

If you look closely, the service box was unchecked, so I checked it and used force deployment, which resolved the issue and allowed it to run normally.

<img src="./success.png" alt="success-service-deployment"/>

The success picture above shows it in progress. Just give it some time, and it will be **complete**.  

With this, I am able to query the data.

<p align="right">(<a href="#top">back to top</a>)</p>





