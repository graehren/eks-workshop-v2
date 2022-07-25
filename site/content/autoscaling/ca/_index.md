---
title: "Cluster Autoscaler (CA)"
chapter: true
weight: 20
---

# Cluster Autoscaler

Cluster Autoscaler for AWS provides integration with Auto Scaling groups. It enables users to choose from four different options of deployment:

* One Auto Scaling group
* Multiple Auto Scaling groups
* Auto-Discovery
* Control-plane Node setup

Auto-Discovery is the preferred method to configure Cluster Autoscaler. Click [here](https://github.com/kubernetes/autoscaler/tree/master/cluster-autoscaler/cloudprovider/aws) for more information.

Cluster Autoscaler will attempt to determine the CPU, memory, and GPU resources provided by an Auto Scaling Group based on the instance type specified in its Launch Configuration or Launch Template.