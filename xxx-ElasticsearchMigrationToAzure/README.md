# What The Hack - ElasticsearchMigrationToAzure

## Introduction

This hack will give you hands on experience in migrating from on-prem Elasticsearch clusters to Elasticsearch Service (ESS) on Azure.

## Learning Objectives

In this hack you will solve common challenges companies face when migrating from their on-prem Elasticsearch cluster to Azure. Upon completion, participants will learn how to:

1. Assess their on-prem clusters looking at compute and disk sizing
2. Correctly size their Elasticsearch Service cluster in Azure based off compute and storage
3. Replicate data using snapshots and/or cross-cluster replication
4. Do a cutover and validate data consistency in their Elasticsearch Service cluster in Azure
5. Secure network connectivity using private endpoints and IP filters
6. Secure user access with role based access control (RBAC)

## Challenges

- Challenge 00: **[Prerequisites - Ready, Set, GO!](Student/Challenge-00.md)**
	 - Setup your Elasticsearch and Azure environments
- Challenge 01: **[Assess & Gather](Student/Challenge-01.md)**
	 - Gather information about your on-prem Elasticsearch cluster
- Challenge 02: **[Save your data](Student/Challenge-02.md)**
	 - Replicate you Elasticsearch data from on-prem to Azure
- Challenge 03: **[Cutover and Validation](Student/Challenge-03.md)**
	 - Cutover to and validate your Elasticsearch Service in Azure
- Challenge 04: **[Secure network connectivity](Student/Challenge-04.md)**
	 - Secure network connections to your Elasticsearch Service in Azure
- Challenge 05: **[Secure user access](Student/Challenge-05.md)**
	 - Add role based access control to your Elasticsearch Service

## Prerequisites

- Access to an Azure subscription 
  - If you don't have one, [Sign Up for Azure HERE](https://azure.microsoft.com/en-us/free/)
- [Visual Studio Code](https://code.visualstudio.com/) (optional)
- Azure CLI

## Contributors

- Sajit Sasi
- Cody Jackson
- Hemant Malik
- Greg Crist
- Morgan Goeller
