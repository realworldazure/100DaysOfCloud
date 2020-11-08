
# Day 23 - Azure Storage Accounts

## Introduction

Azure Storage accounts provide some interesting and useful features. Here is some background info on the types of replication options and their features.

	- LRS
		○ Synchronous
		○ 3 replicas
		○ Most economical 
		○ ONLY of Performance tier selected
	- Geo-redundant
		○ 2 regions
		○ 6 copies, 3 in each region
		○ Microsoft handles failover
		○ ONLY available for reads and writes after Microsoft have initiated a failover
	- RA-GRS
		○  ALWAYS available for reads
		○ Becomes AVAILABLE for writes only when Microsoft have initiated a failover
	- ZRS
		○ Uses 3 Availability Zones
		○ Availability Zones connected via high speed fibre
Provides Synchronous replication between 3 replicas within the same region

## Prerequisite

None, though some knowledge of Azure might be useful


## Cloud Research

[AZ-104: Implement and manage storage in Azure (Learn)](https://bit.ly/3eDPRF0)


## Try yourself

LAB the following
a) Create a CNAME record that points to your Storage Account FQDN
b) Create a Container in a Storage Account, set the 'Public Access Level' to private, Secure it with Key Vault
c) Create a PrivateLink between a VM in a VNET and connect it to a Storage Account that cannot be access via public access

## Social Proof


[Tweet](https://bit.ly/3k6uWeV)
