# Jenkins Freestyle Job with GitHub and Maven

## Objective
Create a Jenkins job that clones a GitHub repository and builds it using Maven.

## Prerequisites
- Jenkins installed
- Git installed
- Maven configured in Jenkins

## Steps
1. Configure Maven in Jenkins
2. Create Freestyle Job
3. Connect GitHub Repository
4. Add Maven Build Step
5. Execute Build

## Verification
Check WAR file in:
/var/lib/jenkins/workspace/<job-name>/target
