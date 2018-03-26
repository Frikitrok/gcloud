# Pre-requirements

## Install Cloud SDK:
```
https://cloud.google.com/sdk/?hl=uk#Quick_Start
```

## Set your project ID.
```
gcloud config set project [myproject]
```

## Set your default zone and region
```
gcloud config set compute/region europe-west3
gcloud config set compute/zone europe-west3-b
```

Enable Deployment Manager:
```
https://console.cloud.google.com/start/api?id=deploymentmanager&hl=uk
```

## Clone the repository

### Cretae deployments templates with gcloud
```
cd gcloud
gcloud deployment-manager deployments create splunk-deployment --config splunk-deployment.yaml
```

### for deleting use that comand 
gcloud deployment-manager deployments delete splunk-deployment

### each time when u got fail u have to delete deployments first or use different name 

## some good links
```
https://cloud.google.com/deployment-manager/docs/configuration/supported-resource-types?hl=uk
```

