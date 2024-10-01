# microsoft-azure_lab-resume
This repository contains the brief notes of what was leaned at DIO development lab.

## Initial Instructions

- Create Microsoft Azure Account;
- Sign up for a free signature;
- Intro tour in the web platform.


## IaaS, Paas e SaaS na Azure

- Infrastructure as a Service:
    - Resources more accessible to users (setup, updates, general customization);
    - More flexibility.
- Platform as a Service:
    - Only the necessary environment to run applications;
    - Focus on applications development;
    - Platform managed by provider.
- Software as a Service
    - Existing applications.
    - Users pay for what they use.
 

## Shared Responsability Model

<img alt="NextLevelWeek" title="#NextLevelWeek" src="./shared_responsability_model.png" />


## Azure Architecture Components

- Regions:
    - Possibility to choose where to create resources;
    - There are price and availability differences between regions;
    - Regions are composed of a group of datacenters.
- Availability Zones:
    - Inactivity and datacenter failure protection;
    - Datacenter’s hardware separated in the region;
    - Each datacenter has its own resources, like energy and network;
    - They are connected with optical fiber wires.
- Region Pairs:
    - At least 300 miles between regions;
    - Automatic replication for some services;
    - Region recovery prioritized in case of interruption;
    - Every region has its pair.
- Azure Sovereign Regions:
    - Exclusive for USA governmental services:
        - Physically isolated and only accessible for authorized personnel.
    - Exclusive for China:
        - Also isolated and operated by 21Vianet;
        - All data remain inside China for conformity.
- Azure Resources:
    - Virtual Machines, Storage, Virtual Networks, Application Services, SQL Databases, Functions;
    - Resources Groups:
        - A container to manage resources as a unit;
        - Resources can only exist in one group;
        - Resources can exist in different regions;
        - Can be moved to other groups;
        - Applications can use several groups.
- Azure Subscriptions:
    - An account can contain many subscriptions, but a subscription can only be associated to one account.
    - For Azure accounts authentication and authorization;
    - For billing categorization;
    - Management Groups:
        - Can include many subscriptions;
        - Allow hierarchy policies control.


## Building Architectures in Azure

- Explore Azure datacenters around the world;
- Azure Regions:
    - Data residency;
    - Data replication;
- Resource Groups:
    - Choose region;
    - Activity Log;
    - IAM (access control);
    - Tags;
    - Resources Viewer;
    - Events;
    - Prices;
    - Metrics.
- Virtual Network:
    - Automation template;


## Setting up Azure Virtual Machine Resources and Customizations

- Create Customized Virtual Machine:
    - Choose region;
    - Create availability set;
    - Azure Spot discount;
    - Select VM Size (processing power, memory, and storage capacity);
    - It’s also possible to choose a predefined setup for some known solutions;
    - Choose which ports will be open;
    - Set disks to be excluded with VM;
    - Possibility to select the same disk in many VMs;
    - Create a virtual network;
    - Set public IP and NIC to be excluded with VM;
    - Set auto-shutdown, backup, SO updates;
    - Set monitoring tools for alerts, diagnostics and integrity;
    - Add extensions;
    - Add tags;
    - Check price and confirm creation.
- Azure Virtual Desktop:
    - Create Host;
    - Validation Environment;
    - Session type: Personal or Pool;
    - Load Balancing;
    - Session limit.
- Function App:
    - Set code or container image;
    - Runtime stack;
- Region and OS.

