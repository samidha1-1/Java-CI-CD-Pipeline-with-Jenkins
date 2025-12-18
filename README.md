# Jenkins Pipeline Demo with Java

## Overview
This project demonstrates a simple **Jenkins CI/CD pipeline** using a Java program. The pipeline is implemented with a `Jenkinsfile` and showcases practical knowledge of Jenkins setup, pipeline creation, and GitHub integration.

The Java program simply prints **"Hello World"**. The project covers:

- Writing a basic Java program.
- Creating a `Jenkinsfile` for pipeline automation.
- Setting up Jenkins on an **AWS EC2 instance**.
- Cloning a GitHub repository into Jenkins.
- Building and executing the Jenkins pipeline successfully.

---

## Project Structure

---

## Procedure / Steps Taken

1. **Java Program**
   - Wrote a simple Java program `HelloWorld.java` that prints "Hello World".

2. **Jenkins Setup**
   - Launched an **EC2 instance** to host Jenkins.
   - Installed Jenkins on the EC2 server.
   - Installed necessary Jenkins plugins (Pipeline, Git, etc.).

3. **Pipeline Job**
   - Created a Jenkins pipeline job.
   - Connected the job to the GitHub repository containing the Java program and `Jenkinsfile`.

4. **Jenkinsfile**
   - Defined stages to:
     1. Clone the GitHub repository.
     2. Build and run the Java program.
   - Used `agent any` to run the pipeline on any available agent.

5. **Build**
   - Triggered the pipeline build.
   - All stages executed successfully, demonstrating a working CI/CD pipeline.

---

## Key Learnings
- Hands-on experience with **Jenkins pipelines** and `Jenkinsfile`.
- Knowledge of **EC2 setup for Jenkins**.
- Integration with **GitHub repository** for automated builds.
- Understanding of pipeline stages, agents, and job configuration.

---

## How to Run
1. Clone this repository:  
   git clone https://github.com/samidha1-1/Java-CI-CD-Pipeline-with-Jenkins



