# Geocat Live
### Overview
---

## Live 1.0

+ Virtualization of SDI orchestrations
+ Virtualization of servers
+ Servers and orchestrations are managed manually.

<img src="assets/live-stack.png" width="50%">

---
## Live 2.0

+ Implementation of a meta-system, which manages SDI orchestrations

![team](assets/live_meta.png)

---
## Meta-system

![team](assets/live_front_back.png)

+ The backend itself, is an orchestration of virtualized (micro) services.

---
## Meta-system

![team](assets/docker-compose.png)

---
## Software Pipeline

+ Shipping containers.
+ From source code to compose files.
+ Semi-automated process.

![team](assets/live_pipeline.png)

---
## Live entities

+ **Customer**: information from the initial register on WHMCS.
+ **Product**: set of orchestrated services, defined on the config-repo on gitlab.
+ **Order**: implementation of a product for a given customer.

![team](assets/live_entities.png)

---
## Live Scope

<span style="font-size: 0.8em;">The meta-system is designed to manage and related these three entities.</span>
+ <span style="font-size: 0.5em;">Provisioning Servers</span>
+ <span style="font-size: 0.5em;">Launching compositions</span>
+ <span style="font-size: 0.5em;">Registering services for availability monitoring</span>
+ <span style="font-size: 0.5em;">Informing customers of the order status</span>
+ <span style="font-size: 0.5em;">Retrieving the status of servers and services</span>
+ <span style="font-size: 0.5em;">Monitoring services for availability</span>
+ <span style="font-size: 0.5em;">Removing Servers</span>
+ <span style="font-size: 0.5em;">Deregistering services for availability monitoring</span>
+ <span style="font-size: 0.5em;">Invoicing clients</span>
---
## Live composition

The composition itself was also improved in live 2.0:
+ Upgrade to version 3 of docker-compose
+ Use of named volumes
+ Replacement of NR by Zabbix
+ Inject EE with relevant container information
+ Externalize data dirs as build arguments
+ Multi-stage builds (experimental)

---
## Live composition

![team](assets/docker-compose2.png)

---
## Next Steps
+ Marketing & Sales |
+ Marketing & Sales |
+ Marketing & Sales |
---
## Next Steps (technical)
+ Backups (ongoing) |
+ Service logging |
+ Integration of Zabbix in the UI |
+ Clustering |
+ DNS managing |
+ Bridge integration (?) |
