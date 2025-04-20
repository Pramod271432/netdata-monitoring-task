# Netdata Monitoring Task

## Objective
Monitor system and app performance metrics using Netdata, a lightweight, open-source monitoring tool.

## Tools
- Netdata (via Docker)
- Docker

## Setup

```bash
docker run -d --name=netdata -p 19999:19999 --cap-add=SYS_PTRACE --security-opt apparmor=unconfined netdata/netdata

# netdata-monitoring-task
