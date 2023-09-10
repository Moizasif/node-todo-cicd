Follow the below steps in Jenkins to set up the Jenkins project


1. Open the Jenkins dashboard and create the FreeStyle project in it.
2. Add the GitHub URL in source code management.
3. Select the GitHub hook trigger for GITSCM polling in build triggers
4. Add the build steps in the execute shell and build the project


Follow the below steps on GitHub to add a Webhook in the GitHub project

1. Go to the GitHub repository and open the settings in the repository
2. Click on Webhook and in the Webhook section click on Create a new Webhook
3. In the payload URL add the public IP address and the port number like https://jenkins_server_ip:8080/github-webhook/
4. After successfully connecting with the Jenkins server make changes in the GitHub Repo and it automatically triggers
   the Jenkins Build with the help of Webhook



