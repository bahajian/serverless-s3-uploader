
<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/othneildrew/README-Template">
    <img src="logo.png" alt="Logo" width="80" height="80">
  </a>
  <h3 align="center">README-Template</h3>
  <p align="center">
    An awesome README template to jumpstart your projects!
    <br />
    <a href="https://github.com/bahajian/Template/edit/master"><strong>Explore the docs »</strong></a>
    <br />
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about">About The Project</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

# Serverless S3 Uploader

The Serverless S3 Uploader allows you to upload JPG files to Amazon S3 buckets from your web applications using pre-signed URLs.

Important: this application uses various AWS services and there are costs associated with these services after the Free Tier usage - please see the [AWS  pricing page](https://aws.amazon.com/pricing/) for details.

```bash
.
├── README.MD                   <-- This instructions file
├── s3UploaderFunction          <-- Source code for the main lambda function
│   └── app.js                  <-- Main Lambda handler
│   └── testHarness.js          <-- For testing code locally
│   └── package.json            <-- NodeJS dependencies and scripts
├── template.yaml               <-- SAM template
```

See this [YouTube video walkthrough](https://www.youtube.com/watch?v=mw_-0iCVpUc&list=PLJo-rJlep0EAY0nMNBv0MZ487l1tOFAjh&index=7) of how uploading to S3 works with presigned URLs.


[![Product Name Screen Shot][product-screenshot]](https://example.com)

There are many great README templates available on GitHub, however, I didn't find one that really suit my needs so I created this enhanced one. I want to create a README template so amazing that it'll be the last one you ever need -- I think this is it.

Here's why:
* Your time should be focused on creating something amazing. A project that solves a problem and helps others
* You shouldn't be doing the same tasks over and over like creating a README from scratch
* You should element DRY principles to the rest of your life :smile:

Of course, no one template will serve all projects since your needs may be different. So I'll be adding more in the near future. You may also suggest changes by forking this repo and creating a pull request or opening an issue. Thanks to all the people have have contributed to expanding this template!

A list of commonly used resources that I find helpful are listed in the acknowledgements.

### Built With

This section should list any major frameworks that you built your project using. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.
* [Python](https://python.com)
* [Nodejs](https://node.com)
* [React](https://react.com)



<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Get a free API Key at [https://example.com](https://example.com)
2. Clone the repo
   ```sh
   git clone https://github.com/your_username_/Project-Name.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```JS
   const API_KEY = 'ENTER YOUR API';
   ```
5. Enter your API in `python`
   ```JS
   import os
   API_KEY = 'ENTER YOUR API'
   ```
### 6. Expose Pod as a Service:
```python
import alaki
import dolaki
kubectl expose pod <Pod-Name>  --type=NodePort --port=80 --name=<Service-Name>

kubectl get service SERVICE_NAME -o yaml
```
```bash
kubectl get nodes -o wide
kubectl describe pod my-first-pod 
kutectl delete nodegroup 

```



<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_



<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/bahajian/Template/edit/master/README.md) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the Bahram License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Your Name - [@your_twitter](https://twitter.com/your_username) - email@example.com

Project Link: [https://github.com/your_username/repo_name](https://github.com/bahajian)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [GitHub Sheet](https://github.com/bahajian)




------------------------------------------------------------------------------------------------------------

## Requirements

If using outside of the AWS Serverless Application Repository:

* AWS CLI already configured with Administrator permission
* [NodeJS 12.x installed](https://nodejs.org/en/download/)

## Installation Instructions

1. [Create an AWS account](https://portal.aws.amazon.com/gp/aws/developer/registration/index.html) if you do not already have one and login.
1. Go to the app's page on the [Serverless Application Repository](https://serverlessrepo.aws.amazon.com/applications/) and click "Deploy"

## Using this Application

* This application creates an API Gateway endpoint where your application can request a pre-signed URL to upload JPG objects to an S3 bucket. Once the API returns the URL, your application can PUT the object data to this URL to complete the upload.
* This application is for educational purposes and does not provide any throttling on the API Gateway endpoint. For production usage, you should [apply throttling to your API resources](https://docs.aws.amazon.com/apigateway/latest/developerguide/api-gateway-request-throttling.html).
* You can modify this application to upload other types of object.

## How it works

* Deploy this serverless application and take a note of the API endpoint.
* Invoke the API to receive a pre-signed URL for uploading a JPG file. Use this pre-signed URL to complete the upload.
* For a live example of this, see [this Fiddle](https://jsfiddle.net/jbeswick/Lq3vkdx2/). View the browser console to see logs of how the Fiddle is interacting with the API Gateway and presigned URL.

==============================================

Copyright 2020 Amazon.com, Inc. or its affiliates. All Rights Reserved.

SPDX-License-Identifier: MIT-0




# fileupload-s3-lambda
# Kubernetes

## line 2

### line 3

#### line 4

##### line 5


## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)



* A `build.yaml` file at the root is the source of truth for listing all the
targets and files needed to build grpc and its tests, as well as a basic system
for dependency description.













## technologies

### 01- Create EKS Cluster using eksctl:

```
eksctl create cluster --name=node-server \
                      --region=us-east-1 \
                      --zones=us-east-1a,us-east-1b \
                      --without-nodegroup 
```
Getting the cluster list:

```
eksctl get clusters
eksctl delete cluster node-server
```

### 02- Create & Associate IAM OIDC Provider for the EKS Cluster:

```
eksctl utils associate-iam-oidc-provider \
    --region us-east-1 \
    --cluster node-server\
    --approve
```

### 03- Create Node Group with additional Add-Ons in Public Subnets:

```
eksctl create nodegroup --cluster=node-server \
                       --region=us-east-1 \
                       --name=node-server-ng-public1 \
                       --node-type=t3.medium \
                       --nodes=2 \
                       --nodes-min=2 \
                       --nodes-max=4 \
                       --node-volume-size=20 \
                       --ssh-access \
                       --ssh-public-key=kube-demo \
                       --managed \
                       --asg-access \
                       --external-dns-access \
                       --full-ecr-access \
                       --appmesh-access \
                       --alb-ingress-access 
```
Get Worker Nodes Status and other actions:

```bash
kubectl get nodes -o wide
kubectl describe pod my-first-pod 
kutectl delete nodegroup 

```

### 04- Create a POD:

```
kubectl run <desired-pod-name> --image <Container-Image> --generator=run-pod/v1

Interact With a Pod:

kubectl get po : Get pod name
kubectl logs <POD_NAME>: dump pod logs
kubectl logs -f POD_NAME: -f option to stream pod logs
kubectl describe pod <Pod-Name>    "good for trouble shooting"
kubectl delete pod <Pod-Name>

Connection into the POD container:

kubectl exec -it POD_NAME -- /bin/bash

Get YAML output of POD and Service:

kubectl get pod POD_NAME -o yaml
```
  

### 05- Expose Pod as a Service:
```python
import alaki
import dolaki
kubectl expose pod <Pod-Name>  --type=NodePort --port=80 --name=<Service-Name>

kubectl get service SERVICE_NAME -o yaml
```
if the container is listening on a port different than 80 we need to define it in the command using the target node.

## setup
## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
<<<<<<< HEAD
[MIT](https://choosealicense.com/licenses/mit/)
=======
[MIT](https://choosealicense.com/licenses/mit/)
>>>>>>> cef72c56ce915b426e74b9b12c3b5b2ed5864e5f
