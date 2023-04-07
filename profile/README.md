## Index
1. [Do's and Dont's](#1-dos-and-donts)
    - 1.1. [Repo Naming Conventions](#11-repo-naming-conventions)
    - 1.2. [Readme's](#12-readmes)
2. [Microservice Groupings](#2-microservice-groupings)
    - 2.1. [App Suite](#21-app-suite)
3. [Server Groupings](#3-server-groupings)
    - 3.1. [MQTT Broker](#31-mqtt-broker)
    - 3.2. [Gateway Static File and DB](#32-gateway-static-file-and-db)
    - 3.3. [TestDBServer](#33-testdbserver)
    - 3.4. [Neura-BusiOpsMan-Staging](#34-neura-busiopsman-staging)
    - 3.5. [Microservices](#35-microservices)

# 1. Do's and Dont's
Below are the general Do's and Dont's of an organizations repos:

## 1.1 Repo Naming Conventions
- Do not put the organizations name in front of a repo's name, for e.g. dont call it Neura-Dashboard, 
just call it Dashboard. The repo is already inside an organization.
- Use dashes "-" between words for a repo, for e.g. dont call it DataUploadMicroservice, call it Data-Upload-Microservice. 
Also do not use underscores "_", or fullstops ".", or anything else.

## 1.2 Readme's
- Whenever a new release of an application or software is released to a client, it needs to be accompanied by a readme
file. The best way to approach this would be to create a readme at the start of a project, so that other collaborators
know how the app is structured, and its intended purpose. Once a major release is pushed the readme gets updated, if neccessary.

# 2. Microservice Groupings
Each grouping below shows which repo's (microservice's) together form a service or app for a client.
The name of the repo, and a link to the repo is provided.

## 2.1 App Suite (BusiOpsMan)
- [BillingMicroservice](https://github.com/Neura-Technologies/BillingMicroservice)
- [DBMS](https://github.com/Neura-Technologies/DBMS)
- [DataUploadMicroservice ](https://github.com/Neura-Technologies/DataUploadMicroservice)
- [TradingMicroservice](https://github.com/Neura-Technologies/TradingMicroservice)
- [Neura-Local-Dashboard](https://github.com/Neura-Technologies/Neura-Local-Dashboard)
- [Neura-Userport](https://github.com/Neura-Technologies/Neura-Userport/)
- [Neura-DEM ](https://github.com/Neura-Technologies/Neura-DEM)
- [Neura-ClientApp](https://github.com/Neura-Technologies/Neura-ClientApp)
- [IntermediateDB-App](https://github.com/Cauchy-Consult/IntermediateDB-App)
    This repo is not in this organization at the moment, it needs to be moved over

# 3. Server Groupings
Each grouping below shows which repo's have been deployed together on the same server.
The name of a grouping is the same name of the EC2 instance (server) deployed on AWS.

## 3.1 MQTT Broker
- The code deployed on this server is not currently in a repo under this organization

## 3.2 Gateway Static File and DB
- [IntermediateDB-App](https://github.com/Cauchy-Consult/IntermediateDB-App)
    This repo is not in this organization at the moment, it needs to be moved over

## 3.3 TestDBServer
- ??

## 3.4 Neura-BusiOpsMan-Staging
- [DBMS](https://github.com/Neura-Technologies/DBMS)
- [Neura-Local-Dashboard](https://github.com/Neura-Technologies/Neura-Local-Dashboard)
- [Neura-Userport](https://github.com/Neura-Technologies/Neura-Userport/)
- [Neura-DEM ](https://github.com/Neura-Technologies/Neura-DEM)

## 3.5 Microservices
- [BillingMicroservice](https://github.com/Neura-Technologies/BillingMicroservice)
- [DataUploadMicroservice ](https://github.com/Neura-Technologies/DataUploadMicroservice)
- [TradingMicroservice](https://github.com/Neura-Technologies/TradingMicroservice)

# 4. Standalone Services
- NeuraDataUpload (Scheduled to be obsolete)
- NeuraDataUpload2 (Scheduled to be obsolete)
- API_Lib (Scheduled to be obsolete)
- Consumption (Scheduled to be obsolete)
- NeuraLibrary (Scheduled to be obsolete)
- NeuraCurrentBilling2 (Scheduled to be obsolete)
- NeuraActiveData (Scheduled to be obsolete)
- NeuraActiveTariffLibrary (Scheduled to be obsolete)
- NeuraCurrentBilling (Scheduled to be obsolete)
- NeuraSentinel (Scheduled to be obsolete)
- NeuraDashboards (Scheduled to be obsolete)

-NeuraGateway
