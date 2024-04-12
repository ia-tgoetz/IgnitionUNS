# Parallel Gateway Network and MQTT Demo

This repository is used as a development stack to demonstrate a Unified Namespace while utilizing MQTT reduce the load on the Gateway Network

# How It Works

* Tag data (realtime and historical) utilizes MQTT to get information between gateways
* Enterprise Administration Module (EAM), Alarm event data, and Audit logs communicate over the Gateway Network
* Each level of the organization has its own MQTT Broker to build out the UNS

![alt text](https://github.com/ia-tgoetz/MQTT-GWN/blob/main/Capture.JPG?raw=true)

# Setup
* Clone Git Repo
* Open dir in your IDE of choice
* Run ` "docker compose up -d" `
* gw username ` admin `
* gw passwords ` password `

# Gateway Info

corpGateway ` localhost:8089 `
* Approve Certificate In Incoming GWN connection from siteGateway
* Approve Incoming connection More > Approve

siteGateway ` localhost:8090 `
* Approve Certificate In Incoming GWN connection from 
* Approve Incoming connection More > Approve

areaGateway ` localhost:8091 `
* Approve Certificate In Incoming GWN connection from 
* Approve Incoming connection More > Approve

edgeGateway1 ` localhost:8092 `
* Approve Certificate In Incoming GWN connection from 
* Approve Incoming connection More > Approve

edgeGateway2 ` localhost:8093 `
* Approve Certificate In Incoming GWN connection from 
* Approve Incoming connection More > Approve