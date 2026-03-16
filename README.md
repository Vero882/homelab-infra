# homelab-infra
This repository is to manage code for homelab infrastructure. 

## infrastructure
### Compute
- san: Minisforum MS-A1
  - CPU: AMD Ryzen 7 8700G
  - RAM: 96GB (2x 48GB) Crucial DDR5 5600MHz

- spike: Custom Build
  - CPU: Intel i7-4790K
  - RAM: 32GB (2x 16GB)

- faye (QDevice): Dell Optiplex
  - CPU: Intel i5-4590S
  - RAM: 8GB

- jet (Cold Backup/Retired): Dell PowerEdge R630
  - CPU: x2 Intel Xeon E5-2683 v4
  - RAM: 672GB (21x 32GB) DDR3 2133MHz

### Storage
Synology NAS: DS920+
CPU: Intel Celeron J4125
RAM: 4GB
Storage: 32TB (4x 8TB HDD) (SHR; 1 drive tolerance)

## Workloads
This homelab infrastructure currently hosts several individual Docker hosts running on Ubuntu, as well as my [GitOps managed Kubernetes cluster](https://github.com/Vero882/homelab) running on k3s.

### Applicaitons
Here are some of the applications that I run on my infrastructure.

| App | Description |
|-----|-------------|
| <img src=https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/png/audiobookshelf.png height=25 length=25> Audiobookshelf | Self-hosted Audiobook manager |
| <img src=https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/png/heimdall-light.png height=25 length=25> Heimdall | Home dashboard |
| <img src=https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/png/it-tools-light.png height=25 length=25> IT-Tools | Handy self-hosted dev tools |
| <img src=https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/png/linkding.png height=25 length=25> Linkding | Local bookmarks manager |
| <img src=https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/png/n8n.png height=25 length=25> n8n | Self-hosted automation platform |
| <img src=https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/png/onedev-light.png height=25 length=25> OneDev | Git, CICD, etc DevOps Platform |
| <img src=https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/png/pi-hole.png height=25 length=25> PiHole | Network-wide ad blocking and local DNS. |
| <img src=https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/png/portainer.png height=25 length=25> Portainer | Docker host container management |
| <img src=https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/png/grafana.png height=25 length=25> Prometheus & Grafana stack | Cluster-wide monitoring |
| <img src=https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/png/twingate-light.png height=25 length=25> Twingate | Zero-trust remote network access |
| <img src=https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/png/uptime-kuma.png height=25 length=25> Uptime Kuma | Homelab monitoring |
