#CI/CD - Azure DevOps and AKS

This project is to :

Implement a CI pipeline, by connecting to a GitHub repository to fetch the source code and YAML files. Build a Docker image and push it to a private container registry on Azure using the 'Docker' task on Azure DevOps. Update the Kubernetes deployment manifest file to use dynamic versioning container each time a new version of the application is released. Create a secret of type 'Docker' in the AKS cluster and configure the manifest file to use the secret. Lastly, deploy the built docker image via CD pipeline to AKS using 'kubectl' commands.

CI Implementation - Azure Pipelines
![Screenshot (20)](https://user-images.githubusercontent.com/59297711/111836464-b6696b00-88cc-11eb-903e-3996c53ea920.png)
![Screenshot (21)](https://user-images.githubusercontent.com/59297711/111836479-bc5f4c00-88cc-11eb-8bee-7cc1138a5ed4.png)

Using Token Prefix '#{', Token Suffix '#}' implement Dynamic Versioning while Deploying to AKS
![Screenshot (24)](https://user-images.githubusercontent.com/59297711/111840463-cedc8400-88d2-11eb-8dbb-47f2fa8f6160.png)
![Screenshot (25)](https://user-images.githubusercontent.com/59297711/111840476-d1d77480-88d2-11eb-8d05-6a841b4a8d62.png)



