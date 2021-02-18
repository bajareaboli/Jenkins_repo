
# Deployment of Small-App is a part of  MYOB Technical Challenge.

Approach:
  - Write a simple code
  - Build and compile the code
  - Push on tomcat serve
  - Automate deployment using jenkins


Step1: setup/install java env

  - Created a simple project in java.
  
Step2: Setup/install git

  - Created a branch myob branch.
  - Commited and pushed the changes to git hub.
    
Step3: Setup/install jenkins 

  - Created the jenkins job to automate the code build.
  - This will build the job on 1st of every month.
  - Push the artifacts on tomcat server.

Note: Link to access jenkins provided in email.

# Tools used in Deployment:
1. Jenkins- Integration tool 
   - Plugins used:
            > Git plugin for source code management 
   - Build trigger method used:
            > Build periodically
   - Build env:
            > Execute shell
   - Post-Build:
            > Prepare test reports
            > Deploy war fiel to container on server
            > Delete workspace to save memory

3. Git- Version maintaining
4. Tomcat server -for deployment of website
