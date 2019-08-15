# Demo of ACME Fitness App with rvice Mesh

This repository contains all the assets and instructions required to demonstrate some comon  Istio \ NSX Service Mesh capabilities with the [ACME Fitness App](https://github.com/vmwarecloudadvocacy/acme_fitness_demo) created by the [VMware cloud advocacy team](https://cloudjourney.io/about/). 

## Getting Started

These instructions will allow you to run entire ACME Fitness App 

## Requirements

Based on the type of deployment the requirements will vary 

1. **kubernetes**
2. **Istio, 1.1 or later OR NSX Service Mesh**


## Overview

![Acmeshop Architecture](https://github.com/vmwarecloudadvocacy/acme_fitness_demo/blob/master/acmeshop.png)


## Instructions

1. Clone this repository 

2. You will notice the following directory structure

``` 
.
├── README.md
├── traffic-generator
├── docker-compose
│   ├── README.md
│   └── docker-compose.yml
└── kubernetes-manifests
    ├── README.md
    ├── cart-redis-total.yaml
    ├── cart-total.yaml
    ├── catalog-db-initdb-configmap.yaml
    ├── catalog-db-total.yaml
    ├── catalog-total.yaml
    ├── frontend-total.yaml
    ├── order-db-total.yaml
    ├── order-total.yaml
    ├── payment-total.yaml
    ├── users-db-initdb-configmap.yaml
    ├── users-db-total.yaml
    └── users-total.yaml
```

3. Switch to the appropriate directory for deployment
  
b. [kubernetes-manifest](kubernetes-manifests)  


### Additional Info

The [traffic-generator](traffic-generator) is based on **locust** and can be used to create various traffic patterns, if you need it for other demos associated with **Monitoring and Observability.** 

