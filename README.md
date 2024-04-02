# Introduction 
This project is a simple web application that can be dockerized and deployed to the cloud.  Where it is deployed depends on the pipeline but the build steps are the same.  
We could push this same project to GitHub (wheeler0772) and use GitHub Actions to push to DockerHub.  Or we could build the image via an ADO pipeline and push the image to Azure Container Registry, etc.

This project is focused on the Azure DevOps (ADO) and Azure Portal CI/CD.

Since the project is in ADO, we will demo how to build and deploy it using ADO pipelines.

To learn how to build and deploy an image using GitHub Actions and DockerHub, etc. checkout the similare project in [GitHub/wheeler2889](https://github.com/wheeler2889/maarc)

# Getting Started
Typically the first step in the SDLC for a new developer is to install all of the software and tools locally and run Maven or some other build to verify you have everything setup.  But for this project, there is no
need to insall anything.  You can if you want.  But the focus of this project how to build and deploy a simple web application. 

There is a similar project in GitHub, but this document assumes the repor is a Azure DeveOps (ADO) Git Repo.

1.	[Azure DevOps (ADO)](https://aex.dev.azure.com/)
2.  [Azure Portal](https://portal.azure.com)
3.	[DockerHub (0ptional) if you are going to push to DockerHub](https://hub.docker.com/)
4.  [APS MAARC Replatform Developer Cheatsheet](https://mn365-my.sharepoint.com/:w:/g/personal/doug_wheeler_state_mn_us/EfoPcQruKehJnF9YIHEj2w0Bk1_Sv0Tk1zP_SV-H1gpbRw?email=doug.wheeler%40state.mn.us&e=srd0jS)

# Clean Build
## Building the application
If you wanted to run the applicatio locally, you would either need [install and configure NGINX](https://docs.nginx.com/nginx/deployment-guides/setting-up-nginx-demo-environment/) or Docker and to run the image.

# Building and Pushing the Docker Image to..
There a several options for how to build the Docker image and push to a Registry.  This project is focused on how to do this in ADO and Azure Portal.

## Azure DevOps (ADO) + Azure Portal
Assuming the source code is in a project in ADO Git repos and you want to push the image to Azure Container Registry and run in Azure Services (Web App).

- [Create Service Connection](https://www.youtube.com/watch?v=pSmKNbN_Y4s)
- [Simple Hello World Web application](https://bartek-blog.github.io/nginx/node/javascript/2019/12/15/nginx-hello-world.html )

# Contribute
TODO: Explain how other users and developers can contribute to make your code better. 

If you want to learn more about creating good readme files then refer the following [guidelines](https://docs.microsoft.com/en-us/azure/devops/repos/git/create-a-readme?view=azure-devops). You can also seek inspiration from the below readme files:
- [ASP.NET Core](https://github.com/aspnet/Home)
- [Visual Studio Code](https://github.com/Microsoft/vscode)
- [Chakra Core](https://github.com/Microsoft/ChakraCore)