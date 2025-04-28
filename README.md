# __Awesome Proxmox VE__

![Proxmox VE|300](https://www.proxmox.com/images/proxmox/Proxmox-logo-800.png)

This repo is a collection of **AWESOME** [Proxmox VE](https://pve.proxmox.com) documentation, tools, and resources for **any user or developer**.

Feel free to **contribute** / **star** / **fork** / **pull request** . Any **recommendations** and **suggestions** are welcome.

## Table of Contents
- [API](#api)
- [Articles](#articles)
- [Monitoring](#monitoring)
- [Backups](#backups)
- [Blogs](#blogs)
- [Documentation](#documentation)
- [Community](#community)
- [Tools](#tools)
- [Videos](#videos)
- [License](#license)

## API
- [Proxmox API](https://pve.proxmox.com/wiki/Proxmox_VE_API) Proxmox Documentation API

- Go
  - [proxmox-api-go](https://github.com/Telmate/proxmox-api-go) Using the Proxmox API in golang

- .Net
  - [cv4pve-api-dotnet](https://github.com/Corsinvest/cv4pve-api-dotnet) Proxmox VE Client API .Net C#
  - [ProxmoxSharp](https://github.com/ionelanton/ProxmoxSharp) Proxmox C# API client

- PHP
  - [cv4pve-api-php](https://github.com/Corsinvest/cv4pve-api-php) Proxmox VE Client API PHP
  - [ProxmoxVE](https://github.com/ZzAntares/ProxmoxVE) This PHP 5.5+ library allows you to interact with your Proxmox server API
  - [pve2-api-php-client](https://github.com/CpuID/pve2-api-php-client) Proxmox 2.0 API Client for PHP

- Java
  - [cv4pve-api-java](https://github.com/Corsinvest/cv4pve-api-java) Proxmox VE Client API Java
  - [pve2-api-java](https://github.com/Elbandi/pve2-api-java) Proxmox 2.0 API Client for Java

- Python
  - [Proxmoxer](https://pypi.org/project/proxmoxer/) Python Wrapper for the Proxmox 2.x API (HTTP and SSH)
  - [pyproxmox](https://pypi.org/project/pyproxmox/) Python Wrapper for the Proxmox 2.x API
  - [Proxmoxia](https://github.com/baseblack/Proxmoxia) Yet another Python wrapper for the Proxmox REST API.

- Perl
  - [Net-Proxmox-VE-0.006](https://metacpan.org/release/DJZORT/Net-Proxmox-VE-0.006) Pure perl API for Proxmox virtualization
  
- Ruby
  - [Proxmox](https://github.com/nledez/proxmox) Need to manage a proxmox host with Ruby? This library is for you.
 
- Node.js
  - [Proxmox](https://www.npmjs.com/package/proxmox) Node.js Proxmox client
  - [cv4pve-api-javascript](https://github.com/Corsinvest/cv4pve-api-javascript) Proxmox VE Client API Javascript

- PowerShell
  - [cv4pve-api-powershell](https://github.com/Corsinvest/cv4pve-api-powershell) ProxmoxVE PowerShell module for accessing API


## Articles

- [Setup Docker on Proxmox VE Using ZFS Storage](https://www.servethehome.com/setup-docker-on-proxmox-ve-using-zfs-storage/)
- [Recommended settings for Windows 10 and 2019 Server on Proxmox](https://davejansen.com/recommended-settings-windows-10-2016-2018-2019-vm-proxmox/)
- [Proxmox Training](https://github.com/ondrejsika/proxmox-training)
- [Proxmox: Automatische Snapshots einrichten](https://techlr.de/proxmox-automatische-snapshots-einrichten/)
- [Installing macOS 12 “Monterey” on Proxmox 7](https://www.nicksherlock.com/2021/10/installing-macos-12-monterey-on-proxmox-7/)
- [Proxmox VE 7 Corosync QDevice in a Docker container](https://raymii.org/s/tutorials/Proxmox_VE_7_Corosync_QDevice_in_Docker.html)
- [Proxmox New Import Wizard for Migrating VMware ESXi VMs](https://www.virtualizationhowto.com/2024/03/proxmox-new-import-wizard-for-migrating-vmware-esxi-vms/)
- [Proxmox Ebook Free Download for Home Labs](https://www.virtualizationhowto.com/2024/03/proxmox-ebook-free-download-for-home-labs/)

## Monitoring

- [Monitoring Proxmox with InfluxDB and Grafana in 4 Easy steps](https://www.linuxsysadmins.com/monitoring-proxmox-with-grafana/)
- [Efficient Proxmox monitoring with Checkmk](https://checkmk.com/blog/proxmox-monitoring)
- [Proxmox VE Monitoring](https://pandorafms.com/blog/proxmox-ve-monitoring/)
- [SNMP Scripts to monitor Proxmox VE](https://github.com/in-famous-raccoon/proxmox-snmp)
- [CheckMK](https://checkmk.com/blog/proxmox-monitoring) - Proxmox Monitoring: How to Do it Efficiently with Checkmk.
- [LPAR2RRD](https://lpar2rrd.com/Proxmox-monitoring.php) - Server Performance Monitoring Tool - agentless monitoring, all data is gathered from Proxmox API.
- [Netdata](https://www.netdata.cloud/integrations/data-collection/containers-and-vms/proxmox-ve/) - Netdata can be used to monitor all kinds of infrastructure, from tiny stand-alone IoT devices to complex hybrid setups combining on-premise and cloud infrastructure, mixing bare-metal servers, virtual machines and containers.
- [PandoraFMS](https://pandorafms.com/blog/proxmox-ve-monitoring/) - Proxmox VE monitoring with Pandora FMS.
- [Prometheus Proxmox VE Exporter](https://github.com/prometheus-pve/prometheus-pve-exporter) - This is an exporter that exposes information gathered from Proxmox VE node for use by the Prometheus monitoring system.
- [VictoriaMetrics](https://victoriametrics.com/blog/proxmox-monitoring-with-dbaas/) - The High-Performance, Open Source Time Series Database & Monitoring Solution.
- [Zabbix](https://www.zabbix.com/de/integrations/proxmox) - Template for monitoring Proxmox with Zabbix.

## Backups

- [EAGLE](https://www.backup-eagle.com/product/proxmox) - Backup Monitoring and Reporting. Centralised view of backups, backup system health and backup storage for on-prem and cloud backups.
- [Bacula Enterprise](https://www.baculasystems.com/corporate-data-backup-software-solutions/bacula-enterprise-data-backup-software/features/) - Bacula Enterprise is a subscription-based enterprise data backup solution. The Proxmox-Plugin is designed to work seamlessly with the latest releases of Proxmox VE.
- [BDRSuite](https://www.bdrsuite.com/proxmox-backup/) - Comprehensive Backup and Disaster Recovery solution for virtual, physical, cloud, and SaaS applications. Agentless Backup and Recovery for Proxmox Virtual Machines. [[docs](https://www.bdrsuite.com/technical-documents/)] [[download](https://www.bdrsuite.com/vembu-bdr-suite-download/)]
- [Catalogic DPX](https://www.catalogicsoftware.com/portfolio/proxmox/) - Integrates seamlessly with Proxmox Virtual Environment (VE). DPX vPlus enables agentless Proxmox backup and recovery.
- [Commvault Backup&Recovery](https://www.commvault.com/use-cases/backup-and-recovery) - Protects VMs that are hosted in the Proxmox Virtual Environment [[docs](https://documentation.commvault.com/11.38/essential/backups_for_proxmox_vms.html)]
- [NAKIVO](https://www.nakivo.com/proxmox-backup/) - Offers backup, replication, failover, backup to cloud, backup to tape, backup copy, backup data reduction, instant verification, granular restore and disaster recovery orchestration for virtual, physical, cloud and SaaS environments. [[trial](https://www.nakivo.com/resources/download/trial-download/), [docs](https://helpcenter.nakivo.com/User-Guide/Content/Home.htm)]
- [PBS Proxmox Backup Server](https://proxmox.com/en/products/proxmox-backup-server/overview) - Enterprise backup solution, for backing up and restoring VMs, containers, and physical hosts. [[download](https://proxmox.com/en/downloads/proxmox-backup-server), [docs](https://pbs.proxmox.com/docs/installation.html)]
- [SEP](https://www.sep.de/solutions/proxmox-hypervisor/) - SEP sesam provides efficient data protection for virtual machines (VMs) running on Proxmox VE
- [Veeam](https://www.veeam.com/blog/veeam-backup-for-proxmox.html) - Well-known Enterprise backup solution.
- [Vinchin](https://www.vinchin.com/proxmox-backup.html) - Ease-of-use, secure and reliable data protection and disaster recovery solution designed to support protecting virtual machines (VM), cloud instances, databases, Exchange (on-premise and online) and unstructured data (file server and NAS server). [[trial](https://www.vinchin.com/vinchin-software-documentation-downloads.html), [docs](https://helpcenter.vinchin.com/)]

## Blogs

- [pveCLI](https://pvecli.xuan2host.com/) article Proxmox VE
- [servethehome](https://www.servethehome.com/tag/proxmox-ve/) article Proxmox VE
- [Techno Tim](https://docs.technotim.live/tags/proxmox/)  Techno Tim - Proxmox VE
- [ElectronicsWizardry](https://www.youtube.com/@ElectronicsWizardry) Electronics Wizardry - A YouTube channel featuring a wealth of videos on Proxmox

## Documentation

- [Official Wiki](https://pve.proxmox.com) Index Wiki
- [Official Docs](https://pve.proxmox.com/pve-docs/) Index official documentation

## Community

- [Official Forum](https://forum.proxmox.com/) Official Forum
- [Git Developer](https://git.proxmox.com/?o=age) Git Developer Proxmox VE
- [Bugzilla](https://bugzilla.proxmox.com/) Bugzilla Proxmox VE
- [pve-devel](https://www.mail-archive.com/pve-devel@pve.proxmox.com/index.html) Mailing List Developer Proxmox VE
- [pve-user](https://www.mail-archive.com/pve-user@pve.proxmox.com/) Mailing List User Proxmox VE
- [cv4pve-tools](https://www.cv4pve-tools.com) cv4pve-tools Utility for Proxmox VE
- [cv4pve-metrics](https://metrics.cv4pve-tools.com) Metrics cloud for Proxmox VE
- [Reddit Proxmox](https://www.reddit.com/r/Proxmox/) Reddit
- [Reddit Proxmox VE](https://www.reddit.com/r/ProxmoxVE/) Reddit
- [Facebook Group](https://www.facebook.com/groups/proxmox/) Facebook Group

## Tools

- [cv4pve-admin](https://github.com/Corsinvest/cv4pve-admin) Admin Web for Proxmox VE
- [cv4pve-autosnap](https://github.com/Corsinvest/cv4pve-autosnap) Automatic snapshot tool for Proxmox VE
- [cv4pve-barc](https://github.com/Corsinvest/cv4pve-barc) Backup And Restore Ceph for Proxmox VE
- [cv4pve-cli](https://github.com/Corsinvest/cv4pve-cli) Cli for Proxmox VE (Command Line Interfaces)
- [cv4pve-botgram](https://github.com/Corsinvest/cv4pve-botgram) Telegram Bot for Proxmox VE
- [cv4pve-diag](https://github.com/Corsinvest/cv4pve-diag) Diagnostic tool for Proxmox VE
- [cv4pve-node-protect](https://github.com/Corsinvest/cv4pve-node-protect) Proxmox VE protect configuration file nodes
- [cv4pve-pepper](https://github.com/Corsinvest/cv4pve-pepper) Launching SPICE remote-viewer having access VM running on Proxmox VE
- [cv4pve-metric](https://github.com/Corsinvest/cv4pve-metric) Metrics for Proxmox VE
- [cv4pve-metrics-exporter](https://github.com/Corsinvest/cv4pve-metrics-exporter) Metric exporter Prometheus for Proxmox VE
- [cv4pve-api-pwsh](https://github.com/Corsinvest/cv4pve-api-powershell) Power Shell for Proxmox VE
- [pve-cli-utils](https://github.com/aheahe/pve-cli-utils) ProxmoxVE Command Line Interface Utilities
- [proxmox-utils](https://github.com/remofritzsche/proxmox-utils) Useful shell (python) scripts for managing proxmox virtual environment.
- [proxmove](https://github.com/ossobv/proxmove) Migrate virtual machines between different Proxmox VE clusters
- [pvekclean](https://github.com/jordanhillis/pvekclean) Easily remove old/unused PVE kernels on your Proxmox VE system
- [xshok-proxmox](https://github.com/extremeshok/xshok-proxmox) proxmox post installation scripts
- [pve-patches](https://github.com/ayufan/pve-patches) Incremental backup
- [proxmox-pci-switcher](https://github.com/rosineygp/proxmox-pci-switcher) Switch among Guest VMs organized by Resource Pool
- [proxmox-tools](https://github.com/marrobHD/proxmox-tools) 📦 A collection of stuff that I wrote for Proxmox 📦
- [proxmox-vm-to-ct](https://github.com/thushan/proxmox-vm-to-ct) Easily convert Proxmox VMs to Containers
- [Proxmox-Launcher](https://github.com/domingoruiz/Proxmox-Launcher) Proxmox Launcher
- [Proxmox Helper Scripts](https://github.com/community-scripts/ProxmoxVE)
- [pbs-exporter](https://github.com/rare-magma/pbs-exporter) Bash script that uploads proxmox backup server API info to prometheus' pushgateway. 
- [Proxmox-WoL](https://github.com/Aizen-Barbaros/Proxmox-WoL) A script to enable Wake on LAN on Proxmox
- [Proxmox Paste](https://gist.github.com/amunchet/4cfaf0274f3d238946f9f8f94fa9ee02) - Proxmox Tampermonkey script to allow pasting into UI client (for VMs)
- [Proxmox LXC AutoScale](https://github.com/fabriziosalmi/proxmox-lxc-autoscale) - Automatically scale the LXC containers resources on Proxmox hosts, with or without AI.
- [Proxmox-Enhanced-Configuration-Utility (PECU)](https://github.com/Danilop95/Proxmox-Enhanced-Configuration-Utility) - Proxmox Scripts: Repos Update and GPU Passthrough
- [Promxox-Knockoff-Vapps](https://github.com/ryanq47/Proxmox-Knockoff-Vapps) - A pool-based control plane for ProxmoxVE that mimics "VAPP" functionality

## Videos
- [Resizing Virtual Hard Drives in Proxmox](https://www.youtube.com/watch?v=hRP7u3QPNOM)
- [Creating a Ubuntu LXC in Proxmox for Docker](https://www.youtube.com/watch?v=1EYAGl96dZY&t)
- [Proxmox 6.1 and 6.2 PCIe Passthrough](https://www.youtube.com/watch?v=_fkKIMF3HZw)
- [Proxmox Monitoring Tools: InfluxDB2 + Grafana](https://www.youtube.com/watch?v=f2eyVfCTLi0)


# License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

This project is not affiliated with Proxmox, which is free software distributed under the [GNU Affero General Public License](https://www.gnu.org/licenses/agpl-3.0.en.html) (aGPLv3).
