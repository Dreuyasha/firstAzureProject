# My Flask Azure Web App

A simple Flask web application deployed on Azure Web App using GitHub Actions. This project showcases my ability to deploy Python apps in Azure cloud.

## Features
- Simple Flask app with a test route (`/`) returning "Azure Python App Running 🚀"
- Deployed on Azure Web App
- Continuous deployment from GitHub using GitHub Actions

## Steps Taken to Deploy
- Created a **Resource Group** in Azure.
- Created an **Azure Web App**:
  - Python 3.13 runtime
  - Linux operating system
- Enabled **GitHub deployment** in the Deployment Center.

  ### 2. Prepared Flask Application
- Added app.py, requirements.txt, and startup.txt files to repo
- Linked the Azure Web App to this GitHub repo.
- Configured GitHub Actions for continuous deployment:
- Every push to the main branch triggers deployment.
- Azure automatically builds and deploys the Flask app.

- ## Lessons Learned
- Understanding Azure Web App Deployment: Learned how to create and configure Azure resources, including resource groups and web apps, for Python applications.  
- Continuous Deployment with GitHub Actions: Learned to automate deployment from GitHub to Azure using GitHub Actions workflows.  
- Flask App Cloud Readiness: Learned how to make a Flask app compatible with cloud hosting by using host="0.0.0.0" and dynamic ports via environment variables.  
- Dependency Management: Learned the importance of listing all Python dependencies in requirements.txt to prevent deployment failures.  
- Debugging Deployment Issues: Learned to use Azure Log Stream to troubleshoot startup or runtime errors in cloud deployments.  
- Documentation Skills: Learned how to create clear, detailed README documentation so others can understand and reproduce the deployment process.  
