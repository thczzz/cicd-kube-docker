# CI/CD for Docker Kubernetes Using Jenkins (AWS)
## Flow of Execution:
1. Continuous Integration Setup
   - Jenkins, Sonarqube & Nexus
2. Store Dockerhub credentials in Jenkins
3. Setup Docker Engine in Jenkins
4. Install plugins in Jenkins:
   - Docker Pipeline
   - Docker
   - Pipeline Utility Steps 
   - SonarQube Scanner
5. Create K8s cluster with kOps
6. Install Helm in kOps VM
7. Create Helm Charts
8. Test Charts in K8s Cluster in test namespace
9. Add kOps VM as Jenkins Slave
10. Create Pipeline code
11. Create Jenkins job for Pipeline
12. Run & Test the job

