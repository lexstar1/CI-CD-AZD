##CICD for AKS with Azure DevOps

This project is to :
Implement a CI pipeline, by connecting to a GitHub repository to fetch the source code and YAML files. Build a Docker image and push it to a private container registry on Azure using the 'Docker' task on Azure DevOps. Update the Kubernetes deployment manifest file to use dynamic versioning container each time a new version of the application is released. Create a secret of type 'Docker' in the AKS cluster and configure the manifest file to use the secret. Lastly, deploy the built docker image via CD pipeline to AKS using 'kubectl' commands.
