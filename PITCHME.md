# Geocat Live
### Overview
---

## Live 1.0

+ Virtualized SDI orchestrations
+ Virtualized of servers
+ Backups, Monitoring (Third-party)
+ Servers and orchestrations are managed manually.

<img src="assets/live-stack.png" width="50%">

<!-- TADA -->
+++?image=assets/toast.jpg

+++
## Live 2.0

+ Implementation of a meta-system, which manages SDI orchestrations

![team](assets/live_meta.png)

---
## Meta-system

![team](assets/live_front_back.png)

- The backend itself, is an orchestration of virtualized (micro) services. |

<!-- --- -->
<!-- ## Meta-system -->

<!-- ![team](assets/docker-compose.png) -->

<!-- --- -->


+++?image=assets/docker-compose.png
+++

## Software Pipeline

+ Shipping containers.
+ From source code to compose files.
+ Semi-automated process.

![team](assets/live_pipeline.png)

---
## Live entities

+ Customer: information from the initial register on WHMCS.
+ Product: set of orchestrated services, defined on the config-repo on gitlab.
+ Order: implementation of a product for a given customer.

+++?image=assets/live_entities.png&size=auto 60%

+++
## Live Scope

The meta-system is designed to manage and related these three entities.
+++?image=assets/live_functionality.png&size=auto 90%

+++?image=assets/toast.jpg

---
## Live composition 2.0

+ Upgrade to version 3 of docker-compose
+ Use of named volumes
+ Replacement of NR by Zabbix
+ Inject EE with relevant container information
+ Externalize data dirs as build arguments
+ Multi-stage builds (experimental)

+++?image=assets/docker-compose2.png

+++?image=assets/ahead.jpg

+++
## Next Steps
- Marketing & Sales |
- Marketing & Sales |
- Marketing & Sales |
+++
## Next Steps (technical)
- Backups (ongoing) |
- Service logging |
- Integration of Zabbix in the UI |
- Clustering |
- DNS managing |
- Bridge integration (?) |
<!-- Deployment -->

<!-- CHAMPAGNE -->
