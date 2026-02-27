# Jenkins task

## MCQs Questions

### 1) What is Jenkins mainly used for?
- A Server Monitoring
- B Continuous Integration and Continuous Delivery
- C Database Management
- D Container Orchestration

Ans: B

### 2) Which type of job allows you to define build steps using code in Jenkins?
- A Freestyle Project
- B Pipeline Project
- C Multi-Configuration Project
- D External Job

Ans: B

### 3) Which file is used to define a pipeline in Jenkins?
- A pipeline.yaml
- B dockerfile
- C Jenkinsfile
- D build.gradle

Ans: C

### 4)What is the purpose of a Jenkins Agent (Node)?
- A To store source code
- B To execute jobs assigned by the Jenkins controller
- C To manage plugins
- D To configure webhooks

Ans: B

### 5) Which plugin is required to connect Jenkins with GitHub?
- A Docker Plugin
- B Git Plugin
- C Kubernetes Plugin
- D Maven Plugin

Ans: B

### 6) What is the purpose of a Webhook in Jenkins CI/CD?
- A To install plugins
- B To trigger build automatically on code push
- C To secure Jenkins server
- D To restart Jenkins

Ans: B

### 7) Which command is used inside Jenkins Pipeline to execute shell commands?
- A bash
- B cmd
- C sh
- D run

Ans: C

### 8) What is the purpose of post block in Jenkins Pipeline?
- A Define environment variables
- B Execute steps after pipeline stages
- C Define agents
- D Install plugins

Ans: B

### 9) What is the use of sshagent in Jenkins Pipeline?
- A Install SSH on server
- B Store SSH keys
- C Use stored SSH credentials during execution
- D Restart SSH service

Ans: C

### 10) What happens if a stage fails in Jenkins Pipeline (by default)?
- A The pipeline continues to next stage
- B The pipeline stops execution
- C Jenkins restarts automatically
- D All stages are skipped but marked successful

Ans: B

## Scenario Based questions

You are hired as a Junior DevOps Engineer in a startup fitness company called FitLife Gym.
The development team has created a static HTML website for the gym.
Your manager has assigned you the following tasks:
- Set up CI/CD infrastructure.
- Host the website on a target server.
- Ensure automatic deployment when code is pushed to GitHub.
- Troubleshoot and fix pipeline issues if deployment fails.

You are responsible for complete automation

### Task 1: Infrastructure Setup
Create two Linux servers:
1) Jenkins Server
- Install Java
- Install Jenkins
- Configure required plugins
- Configure SSH credentials

[![qfGYS5l.md.jpg](https://iili.io/qfGYS5l.md.jpg)](https://freeimage.host/i/qfGYS5l)

2) Target Server
- Install nginx
- Ensure port 80 is open
- Website should be accessible via browser

[![qfG7RGs.md.jpg](https://iili.io/qfG7RGs.md.jpg)](https://freeimage.host/i/qfG7RGs)

### Task 2: Create GitHub Repository
- Create a new public GitHub repository:
        - gym-static-website
- Add code and push to github

[![qfGag3J.md.jpg](https://iili.io/qfGag3J.md.jpg)](https://freeimage.host/i/qfGag3J)

### Task 3: Make Required Change
- Modify the website:
    - Change:
Hello from FitLife Gym
    - To:
Hi from FitLife Gym

- Push the changes to GitHub.

[![qfGcn8x.md.jpg](https://iili.io/qfGcn8x.md.jpg)](https://freeimage.host/i/qfGcn8x)

### Task 4: Configure Webhook
- Configure GitHub webhook

[![qfG1gVI.md.jpg](https://iili.io/qfG1gVI.md.jpg)](https://freeimage.host/i/qfG1gVI)

- Trigger Jenkins job automatically on push
[![qfGEof1.md.jpg](https://iili.io/qfGEof1.md.jpg)](https://freeimage.host/i/qfGEof1)

### Task 5
[![qfG5cI1.md.jpg](https://iili.io/qfG5cI1.md.jpg)](https://freeimage.host/i/qfG5cI1)
