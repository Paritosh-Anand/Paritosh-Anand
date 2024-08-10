### Hi there 👋

I am an experienced Senior Principal Software Engineer with a proven track record in the internet industry 🌐. Passionate about driving innovation and delivering impactful solutions.

Expert in **Python**, **Linux**, **AWS**, **Jenkins**, and **Docker** 🛠️. I am passionate about continuous learning and consistently delivering projects that drive rapid growth 🚀.

---

### 💼 Primary Skills

- **Linux**, **Docker**, **Kubernetes**, **ECS**, **EKS**
- **AWS**, **Jenkins**, **ArgoCD**, **Argo Workflows**
- **Python**, **Django**, **Celery**
- **Firebase**, **Ansible**, **Terraform**, **Git**

---

### 🔍 Specialties

- **Scalable Deployment Strategy**: Deploying diverse applications across multiple data centers with precision.
- **Real-Time Monitoring Systems**: Building systems that measure millions of metrics in near real-time.
- **Process Automation**: Crafting enterprise-grade applications to automate manual processes.
- **CI/CD Administration**: Managing continuous integration systems using Jira, Git, Gerrit, Jenkins, Nexus, and Sonar.
- **Cloud Infrastructure**: Leveraging AWS and Docker for robust containerization and cloud solutions.

---

### 📌 Responsibilities

- **Deployment Automation**: Developing strategies based on project tech stacks to support zero-downtime deployments.
- **Jenkins Pipelines**: Creating efficient pipelines to handle over 1K code changes daily by hundreds of engineers.
- **Automation & Reliability**: Innovating to reduce Time to Detection (TTD) & Time to Resolution (TTR), minimizing manual efforts to ensure 100% uptime.
- **Cloud Migration**: Adopting cloud methodologies to migrate applications from data centers to AWS.
- **Monitoring Infrastructure**: Designing systems that record millions of metrics in near real-time for centralized dashboards and alerts.

---

### 👥 Team Management

- Directly managed a team of 10 DevOps Engineers, ensuring weekly progress and delivering on organizational and team goals.
- Promote a well-documented approach to projects and incidents, building a comprehensive knowledge base for the team.


### 🏆 Awards

#### Impact Innovator of the Year 2017-18 

I was honored to receive the "Impact Innovator of the Year 2017-18" award at the MMT Town Hall Meet, where it was presented by the CEO as part of the Ring of Honour recognition.

---

#### CTO Champion Award

---

### 🎓 Education

#### M.Tech Data Science & Engineering | Birla Institute of Technology and Science, Pilani 

Master of Technology - MTech Data Science & Engineering

April 2021 - March 2023

---

#### B. Tech Computer Science & Engineering

June 2007 - June 2011

---

### 💼 Experience [13 years]

| **Position**                             | **Company**                | **Location**     | **Tenure**                           |
|------------------------------------------|----------------------------|------------------|--------------------------------------|
| Platform Engineer                        | Fresha                     | 🇬🇧 London        | March 2023 - present                 |
| Principal Consultant                     | Wipro UK                   | 🇬🇧 London        | October 2022 - March 2023 [6 months]|
| DevOps Manager                           | Klevu                      | 🇬🇧 London        | May 2022 - October 2022 [6 months]  |
| Senior Principal Software Engineer       | MakeMyTrip & GoIbibo       | 🇮🇳 Gurgaon       | April 2021 - May 2022 [1 year, 7 months] |
| Principal Software Engineer              | MakeMyTrip & GoIbibo       | 🇮🇳 Gurgaon       | October 2019 - April 2021 [1 year, 7 months] |
| Lead Systems Engineer                    | MakeMyTrip                 | 🇮🇳 Gurgaon       | April 2018 - October 2019 [1 year, 7 months] |
| Senior Software Engineer II              | MakeMyTrip                 | 🇮🇳 Gurgaon       | February 2016 - April 2018           |
| Developer                                | Wize Commerce              | 🇮🇳 Gurgaon       | July 2013 - February 2016 [2 years, 8 months] |
| Software Developer                       | Czentrix                   | 🇮🇳 Gurgaon       | August 2011 - June 2013 [1 year, 11 months] |


---

### 🚀 Projects

#### 🐳 ☸️ ☁️ Argo Workflows

Argo Workflows is a powerful, open-source container-native workflow engine designed to orchestrate parallel jobs within Kubernetes environments.

During my tenure, I played a pivotal role in the design and setup of Argo Workflows on AWS EKS. My primary responsibilities included:

- **Architectural Design:** Crafted the architecture for integrating Argo Workflows into our existing infrastructure, ensuring seamless compatibility with AWS EKS and alignment with our development practices.
- **Pipeline Migration:** Led the comprehensive migration of legacy CI/CD pipelines from CircleCI to Argo Workflows. This involved mapping out existing workflows, reconfiguring build and deployment processes, and translating all components into the Argo environment.
- **Performance Optimization:** Focused on optimizing the performance of the new workflows post-migration. Addressed any bottlenecks and fine-tuned configurations to enhance overall efficiency and reliability.
- **Collaboration & Training:** Worked closely with development and operations teams to ensure a smooth transition. Conducted training sessions and created documentation to facilitate adoption and understanding of the new workflows.

The successful migration modernized our CI/CD infrastructure and significantly improved the scalability and maintainability of our deployment processes.

---

#### 🐳 ☁️ Docker Platform for Production using AWS ECS

For encashing the benefits of Docker in the Production environment, we started migrating services to Docker using AWS ECS as a core Infra platform. Key highlights in this project -

1. Added support to generate Docker image - by adding Dockerfiles in the source code repo and extending the CI system to generate Docker images and push images to AWS ECR.
2. Deployment orchestration - Integrating blue-green deployment approach for ECS services that includes
 - Automation for creating ECS Task Definitions
 - Automation for creating ECS Services
 - Canary metric comparison b/w blue and green pools
 - State management and handling failure scenarios
3. Log management for services running on the ECS platform - using Filebeat, Kafka, Logstash, ES, Kibana & S3
4. ECS cluster management to ensure maximum utilization of resources and providing a cost-effective solution.
5. Taking advantage of SPOT instances, managing early detection using SPOT interrupt. 

---

#### 🐳 ☁️ Application migration from DataCenter to AWS migration

Planned & executed migration of application and micro-services hosted in DataCenters to AWS Cloud

- Designed the strategy for application provisioning using automation.
- Designed the approach for achieving blue-green deployments. Coded to enhance existing deployment automation tool i.e. Edge
- The migration involved porting more than 400 applications.
- Added advanced features like Canary deployments along with the Blue-Green approach.
- Created an event-oriented state management system for AWS resources.

Layed the design for monitoring applications in the AWS Cloud using Logstash, Kafka, ElasticSearch, Apache Storm and Open TSDB. The architecture helped in creating a hybrid solution that can monitor applications hosted either in Datacenter or AWS Cloud

---

#### Continuous Integration Pipeline

Continuous Integration System using Jenkins Pipeline + Docker + AWS autoscaling

Jenkins CI system is implemented in such a way that it supports projects built in Java, React, Go & NodeJS. Extensively utilizing Jenkins Pipeline concepts to build a robust and sustainable solution that enables hundreds of Engineers to collaborate with more than 1k code changes per day.

Dockerized Jenkins agents are used which have all the dependencies builtin and ready to use. Making the system fault tolerant and helps to keep infra requirements as a code.

Autoscaling of Jenkins slave (worker) nodes using the EC2 plugin. This enables to optimize EC2 instances costing as instances are only launched when required and terminated once there are no jobs to be run.

#### Deployment strategies at scale using Edge at MakeMyTrip

Reliable, Robust, Rapid and Scalable approach to deployment automation

Salient features ensuring reliability and speed:-

1. Zero downtime staggered deployments
2. Canary checks for metric comparison
3. Auto roll-forward or roll-back based on Canary decision
4. Parallel deployments across data center
5. Application health checks
6. Robust and readily available reporting
7. Scheduled rollouts to production.

#### Code Quality and Code Coverage

Designed a framework which can be used to gather facts about the quality of code using technologies like Jenkins, Maven, Jacoco & Sonar.

Jenkins being the job automation framework was used to create a pipeline of jobs being used to: 

1. Get the project source code. Compile the project & publish coverage numbers unit tests generated by executing unit tests using Maven build cycle.
2. Deploy the deliverable of the project to a server or a docker container. 
3. Execute integration tests, pointing to the server over which application is deployed.
4. Generate Jacoco reports and then run Sonar analysis on Jacoco reports.
5. Raise alarms or break build lifecycle if coverage errors are beyond specified thresholds.

The system being used to benchmark quality of the project with each iteration before new changes are rolled out to the production environment.

---

#### LB Manager

LB Manager is an application that is one stop for managing all the live traffic.

LB Manager is capable of hooking to one or more F5 load balancer and present information in a single view, so that it is easier & quicker to take actions.

It presents users with following functionality

1. LTM Pools, Nodes and VIPs.
2. GTM Pools.
3. DC switch: to move traffic from on DC to another.
4. Route53's entries.

Challenge of this project is to get information from multiple sources and often such operations are of high latency. Hence made a design that is capable of making multiple parallel and controlled requests to all of the sources. Implemented caching to serve data.

Integrated this tool with AWS's Route53. Use case was to get DNS entries from multiple Route53s and provide a way to change these entries as in when required.

---

#### Anomaly Detection for Business Metrics

Taking the alerting system to the next level, from static thresholds to dynamic thresholds. Tracking anomalies based on unsupervised machine learning from the past data points and predicting if current datapoint matches the forecast. 

1. Data Engineering: developed pipeline using Apache Kafka, Apache Storm and Cassandra for collecting metrics & respective data points.

2. Machine Learning: built a system around Facebook Prophet, VAR & Isolation Forest. Creating models at runtime and predicting and checking anomalies.

---

#### Monitoring Framework Using Graphite [Python][Cubism.js][HTML][bash script]

Setup , Developed and integrated a whole new Monitoring framework organizational wide. 
1. Setup and integerated graphite and statsd
2. Deployed and reused the statsd daemon agent in code for better performance monitoring.
3. Integrated and developed as per need graphite and statsd client.
4. Deployed Latest realtime dashboards using cubism.js , d3.js and backbone.js integrated with HTML using graphite as backend. 
5. For NRT Monitoring deployed Team-Dashboard using RoR. 

---

#### Docker-Envoy

Utility to send docker events to kafka.

Docker Envoy aims to make customized processing over Docker events feasible. Design enables to publish events to Apache Kafka, this happens instantly (i.e. NRT). This project can run as an agent on each of the Docker hosts and publish messages to a single Kafka cluster.

Since this project has the capability to process each event before-hand and publish more meaningful messages to Kafka. We can write Apache Storm topologies to consume these messages and do required processing something like Docker-Serf.

---

#### Change Tracking System [JAVA] [J2EE]

* Developed and integerated change tracking system and been working on Incident management system using J2EE.
* Developed timer framework or batch job scheduler using Quartz scheduler
* Basic system level automation and code integeration with Python 
* Application keeps track for each and every changes went on live site with a date range to ensure uptime of website or web application.
* Connected with different data sources with different framework

#### Deployment Architecture using Linkedin Glu

Engineered deployment automation that is used for deploying different application on around 2000 servers across 4 data centres.

1. Setup of Linkedin Glu agents on all the servers.
2. Programming in Groovy for deployment automation scripts.
3. Creating custom states required to accommodate new deployment phases.
4. Automating other manual efforts using Python, Jenkins and Glu REST APIs.
