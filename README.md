#CI/CD - Azure DevOps and AKS

This project is to :

Implement a CI pipeline, by connecting to a GitHub repository to fetch the source code and YAML files. Build a Docker image and push it to a private container registry on Azure using the 'Docker' task on Azure DevOps. Update the Kubernetes deployment manifest file to use dynamic versioning container each time a new version of the application is released. Create a secret of type 'Docker' in the AKS cluster and configure the manifest file to use the secret. Lastly, deploy the built docker image via CD pipeline to AKS using 'kubectl' commands.

CI Implementation - Azure Pipelines
![Screenshot (20)](https://user-images.githubusercontent.com/59297711/111836464-b6696b00-88cc-11eb-903e-3996c53ea920.png)
![Screenshot (21)](https://user-images.githubusercontent.com/59297711/111836479-bc5f4c00-88cc-11eb-8bee-7cc1138a5ed4.png)
