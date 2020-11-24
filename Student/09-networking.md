# Challenge 9: Networking

[< Previous Challenge](./08-storage.md) - **[Home](../README.md)** 

## Introduction

We started out with some very simple, default networking that Kubernetes gives us for free. But this is rarely what we'll need to go into production. Now we'll get a little more in depth on networking in Kubernetes

## Description

In this challenge you will be installing an Ingress Controller and learning how the "Ingress" resource in Kubernetes works. 

- Delete the existing content-web deployment and service.
- Find the DNS Zone created for your AKS cluster.
- Deploy the content-web service and create an Ingress resource for it. 
	- The reference template can be found in the Challenge 9 Resources folder: `template-web-ingress-deploy.yaml`
	- Change the ACR & AKS DNS Name to match yours.
- Verify the DNS records are created, and if so, access the application using the DNS name, e.g: 
    - `http://fabmed.[YOUR_AKS_DNS_ID].[REGION].aksapp.io`

## Success Criteria

1. You've recreated a new Ingress for content-web that allows access through a domain name.