# Go-Api-Dapr-template
Go api project for getting started with dapr
This is a simple Go Http api with dapr configuration files and integration to Azure Ci using pipeline as code.

DockerFile - builds the container image.
deploydev.yaml - contains a simplistic Kubernetes file to inject Dapr into the go api.
azure-pipelines.yaml - A ready to go Azure DevOps pipeline for this api. This will build and push the image to docker. And deploy it associated/tagged image to kubernetes.
