# Awesome Proxmox VE

<div align="center">
  
  ![Proxmox VE Banner](https://www.proxmox.com/images/proxmox/Proxmox-logo-800.png)
  
  <h3>The Ultimate Collection of Proxmox VE Resources</h3>
  
  [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
  [![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg?style=flat-square)](http://creativecommons.org/publicdomain/zero/1.0/)
  [![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat-square&logo=github)](https://github.com/Corsinvest/awesome-proxmox-ve/issues)
  [![Stars](https://img.shields.io/github/stars/Corsinvest/awesome-proxmox-ve?style=flat-square&logo=github)](https://github.com/Corsinvest/awesome-proxmox-ve)
  [![Forks](https://img.shields.io/github/forks/Corsinvest/awesome-proxmox-ve?style=flat-square&logo=github)](https://github.com/Corsinvest/awesome-proxmox-ve/fork)
  
  <p><em>A comprehensive collection of <strong>excellent</strong> <a href="https://pve.proxmox.com">Proxmox VE</a> resources including documentation, tools, tutorials, and community contributions.</em></p>
</div>

---

## Contents

- [Proxmox VE](#proxmox-ve)
- [Management](#management)
- [CV4PVE Suite](#cv4pve-suite)
- [VPS Control Panels](#vps-control-panels)
- [VDI](#vdi)
- [Monitoring](#monitoring)
- [Backup Tools](#backup-tools)
- [Storage](#storage)
- [Networking](#networking)
- [Inventory](#inventory)
- [AI](#ai)
- [API & SDKs](#api--sdks)
- [Infrastructure as Code](#infrastructure-as-code)
- [Kubernetes](#kubernetes)
- [Cluster & Autoscaling](#cluster--autoscaling)
- [Other Tools](#other-tools)
- [Migration](#migration)
- [Tutorials, Blogs & Video](#tutorials-blogs--video)
- [Training](#training)
- [Templates & Marketplace](#templates--marketplace)
- [Security Tools & Best Practices](#security-tools--best-practices)
- [Community, Forum & Social](#community-forum--social)
- [Utilities & Scripts](#utilities--scripts)
- [Benchmark & Comparisons](#benchmark--comparisons)
- [YouTube Channels](#youtube-channels)
- [Mobile Apps](#mobile-apps)
- [Desktop Apps](#desktop-apps)
- [Smart Home](#smart-home)
- [Documentation](#documentation)
- [Contributing](#contributing)
- [License](#license)

---

## Proxmox VE

- [Proxmox Virtual Environment](https://proxmox.com/en/products/proxmox-virtual-environment/overview)  
  Complete, open-source server management platform for enterprise virtualization.  
  [[Download ISO](https://proxmox.com/en/downloads/proxmox-virtual-environment/iso)] • [[Install Docs](https://pve.proxmox.com/pve-docs/chapter-pve-installation.html)] • [[Forum](https://forum.proxmox.com/)]
- [Proxmox on NixOS](https://github.com/SaumonNet/proxmox-nixos) - Unofficial port of the Proxmox VE hypervisor to NixOS.
- [PXvirt](https://github.com/jiangcuo/pxvirt) - Fork of Proxmox VE for ARM and LoongArch architectures.

---

## Management

- [CV4PVE-ADMIN (Web UI)](https://corsinvest.it/en/cv4pve/admin/)
  Powerful and easy-to-use web administration interface for monitoring/manage multiple Proxmox VE clusters from a single portal.
  [GitHub](https://github.com/Corsinvest/cv4pve-admin)
- [MultiPortal](https://multiportal.io/)
- [Convoy](https://convoypanel.com/)
- [PegaProx](https://pegaprox.com/) - Datacenter management UI with unified multi-cluster control, intelligent load balancing and seamless cross-cluster migrations.
- [ProxCenter](https://www.proxcenter.io/) - Modern web interface for multi-cluster management, cross-hypervisor migration and workload balancing from a single pane of glass.
- [Proxmox Datacenter Manager](https://www.proxmox.com/en/downloads/proxmox-datacenter-manager)
- [P3Portal](https://github.com/P3Portal-org/p3portal)
  Web portal to manage Proxmox VE: cluster dashboard, Ansible/Packer automation, networking/SDN/firewall, VM/LXC lifecycle and fine-grained RBAC. Core is AGPLv3; an optional Plus edition adds declarative Stacks (OpenTofu), pools & quotas, 4-eyes approval and visual editors.
- [AtlasPVE](https://atlaspve.com) - Safety-focused control layer for Proxmox VE: live map of VMs and storage, host updates sorted by impact, snapshot-before-change and one-click rollback. Commercial, early access.
- [Tainer](https://tainer.sh) - Management platform for Proxmox VE.
- [Proxion](https://github.com/C2Tech-sys/proxion) - Open-source web console for managing Proxmox VE nodes, VMs and containers.
- [ferrum](https://github.com/anand34577/ferrum) - Fleet dashboard for Proxmox VE clusters and standalone nodes with live inventory, backups, HA, firewall and alerting.
- [PVMSS](https://github.com/julienhmmt/pvmss) - Lightweight self-service web portal that lets users create and manage VMs without access to the Proxmox VE web UI.

---

## CV4PVE Suite

**Advanced official Corsinvest tools for integrated multi-platform Proxmox VE management.**

- [**CV4PVE-ADMIN**](https://github.com/Corsinvest/cv4pve-admin)
  Web management platform for Proxmox VE clusters: like vCenter but for Proxmox.
- [**CV4PVE-CLI**](https://github.com/Corsinvest/cv4pve-cli)
  kubectl-style remote CLI for Proxmox VE with multi-cluster support and shell completion.
- [**CV4PVE-AUTOSNAP**](https://github.com/Corsinvest/cv4pve-autosnap)
  Automatic snapshot tool for Proxmox VE VMs and containers with retention policies.
- [**CV4PVE-DIAG**](https://github.com/Corsinvest/cv4pve-diag)
  Diagnostic and health-check tool for Proxmox VE clusters.
- [**CV4PVE-METRICS-EXPORTER**](https://github.com/Corsinvest/cv4pve-metrics-exporter)
  Prometheus metrics exporter for Proxmox VE nodes, VMs, containers and storage.
- [**CV4PVE-API**](https://github.com/Corsinvest/cv4pve-api-dotnet)  
  Official Corsinvest API client to integrate, develop and customize Proxmox in .NET/C# ([NuGet](https://www.nuget.org/packages/Corsinvest.ProxmoxVE.Api/)).
- [**CV4PVE-API-PHP**](https://github.com/Corsinvest/cv4pve-api-php)  
  Official PHP API client and library for automating Proxmox in PHP/Composer environments.
- [**CV4PVE-API-JAVASCRIPT**](https://github.com/Corsinvest/cv4pve-api-javascript)  
  Official JavaScript client for Node.js and frontend (automation, webapps).
- [**CV4PVE-API-JAVA**](https://github.com/Corsinvest/cv4pve-api-java)  
  Official Java API client.
- [**CV4PVE-API-POWERSHELL**](https://github.com/Corsinvest/cv4pve-api-powershell)  
  Official PowerShell module and CmdLets for managing Proxmox VE from Windows, Azure DevOps, etc.
- [**CV4PVE-BOTGRAM**](https://github.com/Corsinvest/cv4pve-botgram)
  Telegram bot to manage and monitor Proxmox VE from your mobile.
- [**CV4PVE-PEPPER**](https://github.com/Corsinvest/cv4pve-pepper)
  Open a Proxmox VE SPICE or VNC console from the command line.
- [**CV4PVE-VDI**](https://github.com/Corsinvest/cv4pve-vdi)
  Desktop VDI client for Proxmox VE: SPICE, VNC, RDP and SSH console launchers.
- [**CV4PVE-REPORT**](https://github.com/Corsinvest/cv4pve-report)
  Export Proxmox VE infrastructure to a navigable Excel, HTML or JSON report: like RVTools for Proxmox.
- [**CV4PVE-NODE-PROTECT**](https://github.com/Corsinvest/cv4pve-node-protect)
  Backup and restore Proxmox VE node configuration files via SSH.
- [**CV4PVE-BARC**](https://github.com/Corsinvest/cv4pve-barc)
  Incremental backup and restore for Ceph RBD images on Proxmox VE.
- [**CV4PVE-METRICS-GRAFANA**](https://github.com/Corsinvest/cv4pve-metrics-grafana)
  Grafana + InfluxDB + Telegraf monitoring stack for Proxmox VE.

**Related online suite:**
- [corsinvest.it/en/cv4pve](https://corsinvest.it/en/cv4pve/)  
  Official Corsinvest page of the cv4pve suite.

---

## VPS Control Panels

- [Proxmox VE VPS For WHMCS](https://www.modulesgarden.com/products/whmcs/proxmox-ve-vps)
- [SolusVM](https://solusvm.com/)
- [Virtualizor](https://www.virtualizor.com/) [[Docs](https://www.virtualizor.com/docs/)]

---

## VDI

- [CV4PVE-VDI](https://github.com/Corsinvest/cv4pve-vdi) - Official Corsinvest desktop VDI client for Proxmox VE with SPICE, VNC, RDP and SSH console launchers.
- [Kasm Workspaces](https://www.kasmweb.com/) - Streaming containerized desktops and apps with Proxmox VE as an autoscale provider.
- [PVE-VDIClient](https://github.com/joshpatten/PVE-VDIClient) - Lightweight VDI kiosk client for launching Proxmox VE VM consoles.
- [OpenUDS](https://github.com/VirtualCable/openuds) - Open-source multiplatform VDI connection broker with Proxmox VE support.

---

## Monitoring

- [CheckMK](https://checkmk.com/blog/proxmox-monitoring)
- [LPAR2RRD](https://lpar2rrd.com/Proxmox-monitoring.php)
- [Netdata](https://www.netdata.cloud/integrations/data-collection/containers-and-vms/proxmox-ve/)
- [PandoraFMS](https://pandorafms.com/blog/proxmox-ve-monitoring/)
- [Prometheus Proxmox VE Exporter](https://github.com/prometheus-pve/prometheus-pve-exporter)
- [Pulse](https://github.com/rcourtman/Pulse) - Real-time monitoring for Proxmox VE and PBS with guest, storage and backup visibility, alerting, and a multi-client mode for providers.
- [VictoriaMetrics](https://victoriametrics.com/blog/proxmox-monitoring-with-dbaas/)
- [Zabbix](https://www.zabbix.com/de/integrations/proxmox)
- [cv4pve-metrics-exporter](https://github.com/Corsinvest/cv4pve-metrics-exporter) - Prometheus metrics exporter for Proxmox VE nodes, VMs, containers and storage.
- [Proxmox Atlas](https://github.com/Losstarot85/proxmox-atlas) - Real-time multi-cluster monitoring dashboard for Proxmox VE infrastructure
- [check_pve](https://github.com/nbuchwitz/check_pve) - Icinga/Nagios plugin to monitor Proxmox VE nodes, VMs, storage and cluster health.
- [Fivenines](https://fivenines.io/features/proxmox-monitoring) - Hosted monitoring for Proxmox VE clusters, QEMU VMs and LXC containers, with an open-source agent.
- [pve-metrics-exporter](https://github.com/drumandbytes/pve-metrics-exporter) - Prometheus and Glance exporter for Proxmox VE: node, VM and LXC resource usage plus CPU/GPU/NVMe temperatures from lm-sensors.
- [Datadog](https://docs.datadoghq.com/integrations/proxmox/) - Datadog integration for monitoring Proxmox VE.
- [Grafana: Proxmox via Prometheus](https://grafana.com/grafana/dashboards/10347-proxmox-via-prometheus/) - Grafana dashboard for the Prometheus Proxmox VE exporter.
- [ManageEngine OpManager](https://www.manageengine.com/network-monitoring/proxmox-monitoring.html) - Proxmox monitoring with the OpManager network and infrastructure monitoring platform.
- [pbs-exporter](https://github.com/natrontech/pbs-exporter) - Prometheus exporter for Proxmox Backup Server.
- [PVE-UPS](https://github.com/ffind-dev/pve-ups) - UPS shutdown appliance for Proxmox VE with a web wizard, an alternative to NUT.
- [XorMon](https://xormon.com/server/monitoring/Proxmox/Proxmox-monitoring.php) - Performance monitoring for Proxmox VE alongside servers, storage, databases and cloud.

---

## Backup Tools

- [BACKUP EAGLE](https://www.backup-eagle.com/product/proxmox)
- [Bacula Enterprise](https://www.baculasystems.com/corporate-data-backup-software-solutions/bacula-enterprise-data-backup-software/features/)
- [BDRSuite](https://www.bdrsuite.com/proxmox-backup/) [[Docs](https://www.bdrsuite.com/technical-documents/)] [[Download](https://www.bdrsuite.com/vembu-bdr-suite-download/)]
- [Catalogic DPX](https://www.catalogicsoftware.com/portfolio/proxmox/)
- [Commvault Backup&Recovery](https://www.commvault.com/use-cases/backup-and-recovery) [[Docs](https://documentation.commvault.com/v11/software/backups_for_proxmox_vms.html)]
- [NAKIVO Backup & Replication](https://www.nakivo.com/proxmox-backup/) [[Trial](https://www.nakivo.com/resources/download/trial-download/)] [[Docs](https://helpcenter.nakivo.com/User-Guide/Content/Home.htm)]
- [Proxmox Backup Server](https://proxmox.com/en/products/proxmox-backup-server/overview) [[Download](https://proxmox.com/en/downloads/proxmox-backup-server)] [[Docs](https://pbs.proxmox.com/docs/installation.html)]
- [SEP sesam](https://www.sep.de/solutions/proxmox-hypervisor/)
- [Storware Backup&Recovery](https://storware.eu/solutions/virtual-machine-backup-and-recovery/proxmox-ve-backup-and-recovery/)
- [Veeam Backup for Proxmox](https://www.veeam.com/blog/veeam-backup-for-proxmox.html)
- [Vinchin Backup & Recovery](https://www.vinchin.com/proxmox-backup.html) [[Trial](https://www.vinchin.com/vinchin-software-documentation-downloads.html)] [[Docs](https://helpcenter.vinchin.com/)]
- [ProxSave](https://github.com/tis24dev/proxsave) - Backup and restore of Proxmox PBS & PVE system files: save your entire environment and restore it at any time. [[Site](https://proxsave.dev/)]
- [pve-bindsnap](https://github.com/bitranox/pve-bindsnap)
  - Snapshot LXC containers that have bind/device mounts, which stock Proxmox greys out. Can also exclude specific volumes from a snapshot. Works with the GUI, API, pct and cv4pve-autosnap.
- [PBS_Chunk_Checker](https://github.com/VoltKraft/PBS_Chunk_Checker)
- [pbs-autobackup](https://github.com/ferr079/pbs-autobackup) - Unattended backup cycle for a Proxmox Backup Server that stays powered off: Wake-on-LAN, enable the storage, vzdump every node, prune, garbage-collect, then shut the host back down.
- [Joulenap](https://github.com/Joulenap/joulenap) - Web UI and scheduler for backups to a Proxmox Backup Server that stays powered off: wakes it, runs the backups, prunes, garbage-collects and shuts it down. Any number of PVE hosts and PBS, PBS to PBS sync, notifications.
- [ProxSnap](https://github.com/gyptazy/ProxSnap) - Lightweight CLI tool for auditing and cleaning up snapshots across Proxmox VE clusters.
- [Cloud-PBS](https://cloud-pbs.com/) - Hosted Proxmox Backup Server in the cloud for Proxmox VE backups.
- [Proxmox Backup Client](https://pbs.proxmox.com/docs/backup-client.html) - Official command-line client for Proxmox Backup Server.
- [Rubrik](https://www.rubrik.com/solutions/proxmox-ve) - Data protection for Proxmox VE workloads.
- [proxmox-backup-arm64](https://github.com/wofferl/proxmox-backup-arm64) - Build scripts for Proxmox Backup Server on arm64.

---

## Storage

- [Dell PowerStore: Deploying Proxmox Virtual Environment](https://infohub.delltechnologies.com/en-us/t/dell-powerstore-deploying-proxmox-virtual-environment-white-paper/)
- [Setting Up Highly Available Storage for Proxmox Using LINSTOR](https://linbit.com/blog/setting-up-highly-available-storage-for-proxmox-using-linstor-the-linbit-gui/)
- [Netapp: Proxmox VE with ONTAP](https://docs.netapp.com/us-en/netapp-solutions/proxmox/proxmox-ontap.html)
- [Proxmox VE Plugin for Pure Storage as Multipath iSCSI Source](https://github.com/kolesa-team/pve-purestorage-plugin)
- [Proxmox VE Plugin for HPE Nimble Storage (iSCSI)](https://github.com/brngates98/pve-nimble-plugin) - Integration of HPE Nimble Storage arrays with Proxmox VE over iSCSI, using the Nimble REST API to create and manage volumes.
- [TrueNAS Proxmox VE Storage Plugin](https://github.com/truenas/truenas-proxmox-plugin)
- [StorPool](https://storpool.com/proxmox-virtual-environment) - High-performance distributed storage platform with native Proxmox VE integration.
- [Everpure](https://support.everpuredata.com/access?dita:id=m_proxmox) - Storage technology integrations for Proxmox VE.
- [Snapbridge](https://github.com/abdoufermat5/snapbridge) - Rust CLI for managing Proxmox snapshots on NetApp ONTAP-backed storage (for both NAS and SAN).
- [ANAS](https://github.com/ccebelenski/anas) - Storage management inside the Proxmox VE web UI: ZFS and hybrid RAID pools, SMB/NFS shares, iSCSI target, snapshots and replication.
- [SharedLVM](https://github.com/delltech1/proxmox-sharedlvmthin) - Snapshot-capable shared FC/iSCSI SAN storage for Proxmox VE 9 clusters on top of an existing shared LVM volume group.

---

## Networking

- [NetBird on Proxmox VE](https://docs.netbird.io/get-started/install/proxmox-ve) - Install guide for the NetBird open-source zero trust networking platform on Proxmox VE.
- [tailmox](https://github.com/willjasen/tailmox) - Cluster Proxmox VE nodes over Tailscale.
- [Tailscale](https://tailscale.com/docs/integrations/proxmox) - Guide to running Tailscale on Proxmox VE hosts.

---

## Inventory

- [CV4PVE-REPORT](https://github.com/Corsinvest/cv4pve-report) - Export Proxmox VE infrastructure to a navigable Excel, HTML or JSON report: like RVTools for Proxmox.
- [netbox-proxbox](https://github.com/emersonfelipesp/netbox-proxbox) - NetBox plugin to sync and inventory Proxmox VE clusters, nodes and VMs.
- [iTop CMDB: Data collector for Proxmox](https://www.itophub.io/wiki/page?id=extensions%3Acombodo-proxmox-data-collector) - Combodo data collector to import Proxmox VE assets into the iTop CMDB.
- [netbox Enterprise Proxmox VE Integration](https://netboxlabs.com/docs/integrations/platform-integrations/proxmox-ve/) - Official NetBox Labs integration to inventory Proxmox VE infrastructure.
- [Proxmox Virtual Environment CMDB importer](https://versio.io/en/import-proxmox-cmdb-configuration-item.html) - Import Proxmox VE configuration items into the Versio.io CMDB.
- [Homedex](https://github.com/HarshShah0203/homedex) - Read-only homelab inventory that lists Proxmox VE nodes, VMs and LXC containers with a PVEAuditor token and links them to Docker services, reverse proxy routes and certificate expiry.
- [Proxmox Report Generator](https://github.com/AungThuMyint/ProxmoxReportGenerator) - Generate infrastructure reports for Proxmox VE clusters.
- [Netbox-SSOT](https://github.com/bl4ko/netbox-ssot) - Microservice that syncs objects from multiple sources, Proxmox VE included, into NetBox.

---

## AI

- [ProxmoxMCP](https://github.com/canvrno/ProxmoxMCP) - MCP server for Proxmox VE management, enabling AI assistants to control VMs, containers, and cluster resources.
- [ProxmoxMCP-Plus](https://github.com/RekklesNA/ProxmoxMCP-Plus) - Enhanced Proxmox MCP server with advanced virtualization management and full OpenAPI integration.
- [Proximo](https://github.com/john-broadway/proximo) - AI-driven natural-language assistant for managing Proxmox VE.
- [mcp-proxmox](https://github.com/antonio-mello-ai/mcp-proxmox) - MCP server for managing Proxmox VE clusters through AI assistants.

---

## API & SDKs

### Community Maintained

#### Python
- [proxmoxer](https://pypi.python.org/pypi/proxmoxer)
- [proxmox-utils (Console Client)](https://github.com/sitrox/proxmox-utils)
- [Proxmoxia (Wrapper)](https://github.com/baseblack/Proxmoxia)
- [pmxc (Console Client)](https://github.com/jochumdev/pmxc)
- [proxmox-sdk](https://github.com/emersonfelipesp/proxmox-sdk)

#### PowerShell
- [cv4pve-api-powershell](https://github.com/Corsinvest/cv4pve-api-powershell)

#### Ruby
- [nledez/proxmox](https://github.com/nledez/proxmox)

#### NodeJS
- [npm:proxmox](https://www.npmjs.com/package/proxmox)
- [cv4pve-api-javascript](https://github.com/Corsinvest/cv4pve-api-javascript)

#### C#
- [ProxmoxSharp](https://github.com/ionelanton/ProxmoxSharp)
- [cv4pve-api-dotnet](https://github.com/Corsinvest/cv4pve-api-dotnet)

#### PHP
- [pve2-api-php-client](https://github.com/CpuID/pve2-api-php-client)
- [ProxmoxVE](https://github.com/ZzAntares/ProxmoxVE)
- [pve-cli-utils](https://github.com/aheahe/pve-cli-utils)
- [cv4pve-api-php](https://github.com/Corsinvest/cv4pve-api-php)
- [MrKampf/proxmoxVE](https://github.com/MrKampf/proxmoxVE)

#### Java
- [pve2-api-java](https://github.com/Elbandi/pve2-api-java)
- [cv4pve-api-java](https://github.com/Corsinvest/cv4pve-api-java)

#### Perl
- [Net-Proxmox-VE (CPAN)](http://search.cpan.org/~djzort/Net-Proxmox-VE-0.006/)
- [pve-apiclient (official)](https://git.proxmox.com/?p=pve-apiclient.git;a=summary)

#### Go
- [proxmox-api-go](https://github.com/Telmate/proxmox-api-go)
- [go-proxmox](https://github.com/luthermonson/go-proxmox)

---

## Infrastructure as Code

- [Packer Plugin for Proxmox VE](https://developer.hashicorp.com/packer/integrations/hashicorp/proxmox)
- [terraform-provider-proxmox (Telmate)](https://github.com/Telmate/terraform-provider-proxmox)
- [Ansible Collection - community.proxmox](https://github.com/ansible-collections/community.proxmox)
- [Proxmox-GitOps](https://github.com/stevius10/Proxmox-GitOps) - GitOps workflow to manage Proxmox VE infrastructure declaratively.
- [Terraform Provider for Proxmox](https://github.com/bpg/terraform-provider-proxmox)
- [Ansible Role - Proxmox](https://github.com/lae/ansible-role-proxmox) - Ansible role that installs Proxmox VE on Debian hosts and builds the cluster.
- [OpenTofu Provider for Proxmox](https://search.opentofu.org/provider/bpg/proxmox/latest) - OpenTofu registry entry for the bpg Proxmox provider.
- [Pulumi Proxmox VE](https://github.com/muhlba91/pulumi-proxmoxve) - Pulumi provider for creating and managing Proxmox VE resources.
- [foreman_fog_proxmox](https://github.com/theforeman/foreman_fog_proxmox) - Foreman plugin that adds Proxmox VE as a compute resource.

---

## Kubernetes

- [Cluster API Provider for Proxmox VE (CAPMOX)](https://github.com/ionos-cloud/cluster-api-provider-proxmox)
- [Proxmox CSI Plugin](https://github.com/sergelogvinov/proxmox-csi-plugin) - Kubernetes CSI driver that provisions persistent volumes on Proxmox VE storage.
- [Proxmox Cloud Controller Manager](https://github.com/sergelogvinov/proxmox-cloud-controller-manager) - Kubernetes cloud controller manager for Proxmox VE.
- [Karpenter Provider for Proxmox](https://github.com/sergelogvinov/karpenter-provider-proxmox) - Karpenter node autoscaling provider for Proxmox VE.
- [cluster-api-provider-proxmox (k8s-proxmox)](https://github.com/k8s-proxmox/cluster-api-provider-proxmox) - Cluster API provider implementation for Proxmox VE.
- [Proxmox Kubernetes Engine (PKE)](https://github.com/Caprox-eu/Proxmox-Kubernetes-Engine) - Deploy and manage highly available Kubernetes clusters directly on Proxmox VE.
- [TJ's Kubernetes Service](https://github.com/zimmertr/TJs-Kubernetes-Service) - Provision highly available Kubernetes clusters on Proxmox VE with Talos and OpenTofu.

---

## Cluster & Autoscaling

- [LXC AutoScale](https://github.com/fabriziosalmi/proxmox-lxc-autoscale)
- [Proxmox VM Autoscale](https://github.com/fabriziosalmi/proxmox-vm-autoscale)
- [ProxCLMC](https://github.com/credativ/ProxCLMC) - Lightweight tool to determine the maximum CPU compatibility level supported across all nodes in a Proxmox VE cluster.
- [ProxLB](https://github.com/credativ/ProxLB)
- [ProxPatch](https://github.com/gyptazy/ProxPatch) - Rolling patch orchestration for Proxmox VE clusters: migrates running VMs, then updates and reboots nodes one at a time.

---

## Other Tools

- [osx-proxmox](https://github.com/lucid-fabrics/osx-proxmox-next) - One-command macOS VM automation for Proxmox 9 with TUI wizard, recovery auto-download, and AMD/Intel support.
- [ProxMenux](https://github.com/MacRimi/ProxMenux)
- [ProxDeploy](https://github.com/NordicsSys/proxdeploy) - Production-ready Python CLI to deploy, list, and destroy KVM guests from YAML templates, with cloud-init, SSH provisioning, dry-run, and API retry resilience.
- [Proxmox Manager](https://github.com/TimInTech/proxmox-manager) - CLI toolkit for common Proxmox VE administration tasks.
- [pve-microvm](https://github.com/rcarmo/pve-microvm) - Run lightweight microVMs on Proxmox VE.
- [Proxmox-Enhanced-Configuration-Utility (PECU)](https://github.com/Danilop95/Proxmox-Enhanced-Configuration-Utility)
- [Proxmox VE Helper-Scripts](https://github.com/community-scripts/ProxmoxVE)
- [proxtagger](https://github.com/Reginleif86/proxtagger)
- [PVE-mods](https://github.com/Meliox/PVE-mods)
- [pvetui](https://github.com/devnullvoid/pvetui)
- [lws](https://github.com/fabriziosalmi/lws) - Unified CLI for Proxmox, LXC, and Docker.
- [valheim-proxmox](https://github.com/PawelSzymanski89/valheim-proxmox) - One-command Valheim dedicated server in an LXC, with a web panel for players, bans, worlds, backups and mods.
- [dockur/proxmox](https://github.com/dockur/proxmox) - Proxmox VE node running inside a Docker container, for labs and CI.
- [PVE Scripts Local](https://github.com/community-scripts/ProxmoxVE-Local) - Local web UI to browse and run the Proxmox VE Helper-Scripts.
- [proxmox-guestos-customization](https://github.com/RobertLukan/proxmox-guestos-customization) - Clone and customize Windows templates on Proxmox VE (hostname, network, domain join) through the QEMU guest agent.
- [pvecontrol](https://github.com/enix/pvecontrol) - CLI to control and inspect Proxmox VE clusters.
- [OSX-PROXMOX](https://github.com/luchina-gabriel/OSX-PROXMOX) - Script to install macOS on Proxmox VE 7 to 9.
- [OpenCore-ISO](https://github.com/LongQT-sea/OpenCore-ISO) - Preconfigured OpenCore ISO image to run macOS on Proxmox VE and QEMU/KVM.
- [intel-igpu-passthru](https://github.com/LongQT-sea/intel-igpu-passthru) - Intel GVT-d iGPU passthrough for Proxmox VE, QEMU and KVM.
- [pve-notebuddy](https://github.com/JangaJones/pve-notebuddy) - Web UI to generate formatted Proxmox guest notes.

---

## Migration

- [ProxMigrate](https://github.com/AthenaNetworks/ProxMigrate)
- [Migrate to Proxmox VE](https://pve.proxmox.com/wiki/Migrate_to_Proxmox_VE) - Official wiki page on migrating VMs from other hypervisors, with the ESXi import wizard.
- [proxmove](https://github.com/ossobv/proxmove) - Migrate VMs between different Proxmox VE clusters with minimal downtime.
- [machine-to-proxmox-lxc-ct-converter](https://github.com/my5t3ry/machine-to-proxmox-lxc-ct-converter) - Convert any GNU/Linux machine into a Proxmox LXC container.

---

## Tutorials, Blogs & Video

- [ServeTheHome - Proxmox VE Tutorials](https://www.servethehome.com/tag/proxmox-ve/)
- [Techno Tim - Proxmox Guides (Blog & Video)](https://technotim.live/tags/proxmox/)
- [Nick Sherlock - macOS on Proxmox](https://www.nicksherlock.com/category/proxmox/)
- [VirtualizationHowTo - Proxmox](https://www.virtualizationhowto.com/tag/proxmox-ve/)
- [The Homelab Wiki - Proxmox Section](https://wiki.homelabos.com/other/proxmox/)
- [Peira Labs - Homelab & Proxmox Guides](https://peira.dev/tags/proxmox/)

---

## Training

- [Proxmox VE Training Courses](https://www.proxmox.com/en/services/training-courses/training) - Official training courses from Proxmox Server Solutions.
- [Corsinvest Training](https://corsinvest.it/en/training/proxmox-ve/) - Proxmox VE training courses by Corsinvest.
- [Croit Academy](https://www.croit.io/academy/topics/proxmox) - Proxmox VE trainings and workshops.
- [Fast Lane](https://www.flane.de/en/courses/proxmox) - Instructor-led Proxmox courses.

---

## Templates & Marketplace

- [TurnKey Linux Proxmox LXC Templates](https://www.turnkeylinux.org/docs/proxmox-lxc)
- [TTECK Proxmox LXC Templates & Utilities](https://tteck.github.io/Proxmox/)
- [LinuxServer Container Templates](https://github.com/linuxserver/docker-templates)
- [TrueNAS SCALE Community Catalog](https://github.com/trueforge-org/truecharts)

---

## Security Tools & Best Practices

- [Proxmox Security Best Practices (official)](https://pve.proxmox.com/wiki/Security)
- [OpenSCAP - Security audit tool](https://www.open-scap.org/)
- [Falco Security - Runtime Linux Security](https://falco.org/)
- [Official Proxmox Firewall Guide](https://pve.proxmox.com/pve-docs/pve-firewall.8.html)
- [fail2ban for Proxmox (HowToForge)](https://www.howtoforge.com/tutorial/how-to-protect-proxmox-ve-with-fail2ban-and-ufw/)
- [Darkmoon](https://github.com/ASCIT31/Dark-Moon) - Open source (GPL-3.0) autonomous AI penetration testing platform covering web, API, Active Directory and Kubernetes.
- [proxmox-ftagent](https://github.com/Flowtriq/proxmox-ftagent) - One-command LXC deployment of the Flowtriq DDoS detection agent on Proxmox VE, with automatic dependency and systemd service setup.
- [Proxmox VE Security Advisories](https://forum.proxmox.com/threads/proxmox-virtual-environment-security-advisories.149331/) - Official list of security advisories for Proxmox VE.
- [Proxmox VE Security Reporting](https://pve.proxmox.com/wiki/Security_Reporting) - Official procedure for reporting a vulnerability to Proxmox.

---

## Community, Forum & Social

- [Official Proxmox Forum](https://forum.proxmox.com/)
- [Reddit Proxmox VE](https://www.reddit.com/r/Proxmox/)
- [Telegram Proxmox Italy](https://t.me/ProxmoxVE_Italia)
- [Discord Proxmox Global (unofficial)](https://discord.gg/WvG4Yc0)
- [Discord Proxcord (unofficial)](https://discord.gg/w9Y5UPz4FG)
- [Facebook Proxmox Group](https://www.facebook.com/groups/proxmox/)

---

## Utilities & Scripts

- [pve-zsync (ZFS backup/snapshots)](https://pve.proxmox.com/wiki/PVE-zsync)
- [Proxmox Wake on LAN](https://github.com/Aizen-Barbaros/Proxmox-WoL)
- [Proxmox Dark Theme (User script)](https://github.com/Weilbyte/PVEDiscordDark)
- [ProxMox Repo Manager/No-Subscription Script](https://tteck.github.io/Proxmox/)
- [pve-disk-shrink](https://github.com/Garfieldttt/pve-disk-shrink) - Dialog-based offline shrinking of Proxmox VE VM disks and LXC volumes (zvol/qcow2/LVM), no live ISO or manual partitioning needed.
- [Proxmox VMID Updater](https://github.com/sannier3/proxmox-vmid-updater) - Safely renames QEMU VM and LXC container VMIDs, including configurations, storage volumes, snapshots, backups, HA and firewall resources, with transactional rollback.
- [homelab-scripts](https://github.com/ferr079/homelab-scripts) - Small shell toolbox for a Proxmox homelab: cluster and container status through the API, TLS expiry checks for services behind a reverse proxy, bulk HTTP availability checks, and a Loki query wrapper.
- [proxmox-ct-deploy](https://github.com/answ-kaz/proxmox-ct-deploy) - Deploy a Docker Compose app to an LXC container from your laptop over LAN or Tailscale: `pct push` sync, migrations after the DB is healthy, generation-managed Postgres backups, and the Cloudflare Tunnel / webhook gotchas.
- [proxmox-stuff](https://github.com/DerDanilo/proxmox-stuff) - Collection of scripts and tools written for Proxmox.
- [pvetools](https://github.com/ivanhao/pvetools) - Script for common Proxmox VE host setup: email, Samba, NFS, ZFS memory limit, nested virtualization and PCI passthrough.
- [PVE-Tools-9](https://github.com/PVE-Tools/PVE-Tools-9) - One-click maintenance script for Proxmox VE 9: VM lifecycle, host networking and firewall, GPU/PCI passthrough and system maintenance (Chinese).
- [Proxmox Updater](https://github.com/BassT23/Proxmox) - Updater script for Proxmox VE.
- [ProxmoxScripts (CCPVE)](https://github.com/coelacant1/ProxmoxScripts) - Scripts for management and task automation in Proxmox VE.
- [ProxMorph](https://github.com/IT-BAER/proxmorph) - CSS themes for Proxmox VE, PBS and PDM that plug into the native color theme selector.
- [proxmox_toolbox](https://github.com/Tontonjo/proxmox_toolbox) - Toolbox for the first configuration of Proxmox VE and Proxmox Backup Server.
- [zamba-lxc-toolbox](https://github.com/bashclub/zamba-lxc-toolbox) - Script collection to set up LXC containers on Proxmox VE with ZFS, including a Samba file server that exposes ZFS snapshots as Previous Versions.
- [proxmox-hetzner](https://github.com/ariadata/proxmox-hetzner) - Install Proxmox VE on a Hetzner dedicated server without a KVM console.

---

## Benchmark & Comparisons

- [ServeTheHome Proxmox Benchmarks](https://www.servethehome.com/?s=proxmox+benchmark)
- [OpenBenchmarking Proxmox Results](https://openbenchmarking.org/testbed/2202159-NE-PROXMOXV55)
- [IdleWatt - Homelab Mini-PC Idle-Power & Passthrough Finder](https://idlewatt.vercel.app)

---

## YouTube Channels

### International Channels
- [Proxmox Server Solutions (Official Channel)](https://www.youtube.com/@ProxmoxVe)  
  Webinars, releases, new Proxmox features.
- [ServeTheHome](https://www.youtube.com/c/ServeTheHomeVideo)  
  Proxmox guides, hardware, servers and storage.
- [Techno Tim](https://www.youtube.com/c/TechnoTimLive)  
  Cluster setup, installation, automated backups with Proxmox.
- [Lawrence Systems](https://www.youtube.com/@LAWRENCESYSTEMS/search?query=proxmox)  
  Enterprise deep-dives, security and tutorials.
- [Craft Computing](https://www.youtube.com/c/CraftComputing/search?query=proxmox)  
  Real homelab use cases, containers, storage.
- [The Digital Life](https://www.youtube.com/c/TheDigitalLife/search?query=proxmox)  
  Tutorials, LXC, scripting.
- [DB Tech](https://www.youtube.com/c/DBTechYT/search?query=proxmox)  
  Guides on containers and services.
- [apalrd's adventures](https://www.youtube.com/@apalrdsadventures/search?query=proxmox)  
  Proxmox, IPv6 and deep dives.
- [Jim's Garage](https://www.youtube.com/@Jims-Garage/search?query=proxmox)  
  k3s, Proxmox and self-hosting.

### Italian Channels
- [Stefano Droghetti](https://www.youtube.com/@stefanodroghetti/search?query=proxmox)  
  Italian tutorials on installation, containers and Proxmox use cases.
- [Maurizio Leo](https://www.youtube.com/@MaurizioLeo/search?query=proxmox)  
  Homelab and virtualization.
- [Francesco Mainardi](https://www.youtube.com/@francescomainardi/search?query=proxmox)

---

## Mobile Apps

### Android
- [Proxmox VE Android App](https://play.google.com/store/apps/details?id=com.proxmox.app.pve_flutter_frontend) - Official app to manage VMs, containers, hosts and clusters.
- [ProxMon](https://play.google.com/store/apps/details?id=dev.reimu.proxmon) - View nodes, storage pools, VMs and containers statuses.
- [ProxMan (Android)](https://play.google.com/store/apps/details?id=com.windium.proxman) - Manage Proxmox VE nodes, VMs and containers from Android.
- [Mobile SSH](https://mobile-ssh.github.io) - SSH, SFTP and terminal client for administering Proxmox nodes and guests from Android.
- [ProxMate Backup](https://play.google.com/store/apps/details?id=com.itss.proxmatebackup) - Overview of your Proxmox Backup Server from Android.

### iOS
- [ProxMan](https://proxman.app) - App for managing Proxmox VE and Proxmox Backup Server environments.
- [Proxmox VE Companion](https://apps.apple.com/de/app/proxmox-ve-companion/id6748314140) - Monitor and manage Proxmox VE environments from iOS.
- [ProxMate](https://apps.apple.com/de/app/proxmate/id6470526961) - Manage your Proxmox server from iOS.
- [ProxMate Backup](https://apps.apple.com/de/app/proxmate-backup/id6618157722) - Manage Proxmox Backup Servers.
- [ProxMobo](https://proxmobo.app/) - Monitoring and management app for Proxmox VE and Proxmox Backup Server.
- [Reeve](https://reeveapp.io) - Monitor and manage Proxmox VE nodes, VMs, and containers from iOS.
- [Mobile SSH](https://mobile-ssh.github.io) - SSH, SFTP and terminal client for administering Proxmox nodes and guests from iOS.

---

## Desktop Apps

### macOS
- [ProxmoxBar](https://github.com/ryzenixx/proxmoxbar-macos) - Native macOS menu bar app for monitoring and controlling Proxmox VE resources.

### Windows & Linux
- [VirtDeck](https://github.com/mcluremail/virtdeck) - Native desktop client for Proxmox VE: monitoring, VM/container management, backups and direct Proxmox Backup Server integration (PySide6, Windows and Linux).
- [Nexus Terminal](https://github.com/evdanil/vscode-NexTerminal) - VS Code and VSCodium extension that syncs Proxmox VMs and containers into SSH profiles and opens their web consoles.

---

## Smart Home

- [Proxmox VE Custom Integration for Home Assistant](https://github.com/dougiteixeira/proxmoxve) - Home Assistant integration to poll data and control a Proxmox VE instance.
- [Proxmox Extended Sensors](https://github.com/Javisen/proxmox_sensors) - Monitoring and control of Proxmox VE and Proxmox Backup Server in Home Assistant.

---

## Documentation

- [10 Ways to Ruin Your Proxmox Setup](https://github.com/SwamiRama/10-ways-to-ruin-proxmox) - Common mistakes and how to avoid them.
- [free-pmx](https://free-pmx.pages.dev/)
- [Proxmox Hardening Guide](https://github.com/HomeSecExplorer/Proxmox-Hardening-Guide) - Actionable recommendations to secure Proxmox VE and Proxmox Backup Server.
- [Thomas Krenn Proxmox Wiki](https://www.thomas-krenn.com/de/wiki/Kategorie:Proxmox)
- [Proxmox VE Wiki](https://pve.proxmox.com/wiki/Main_Page)
- [Proxmox VE Documentation](https://pve.proxmox.com/pve-docs/)
- [Proxmox VE API Viewer](https://pve.proxmox.com/pve-docs/api-viewer/index.html) - Official interactive API reference.
- [Ubuntu-CloudInit-Docs](https://github.com/UntouchedWagons/Ubuntu-CloudInit-Docs) - Short guide to building an Ubuntu VM template with cloud-init.
- [smallab-k8s-pve-guide](https://github.com/ehlesp/smallab-k8s-pve-guide) - Guide to running a small Kubernetes cluster on a single Proxmox VE node.

---

## Contributing

Contributions are welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) before opening a pull request.

The short version: **new entries are always appended at the end of their section**, one suggestion per pull request.

---

## License

This list is released into the public domain under the [Creative Commons Zero v1.0 Universal](LICENSE) license.
