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
- [VPS Control Panels](#vps-control-panels)
- [Monitoring](#monitoring)
- [Backup Tools](#backup-tools)
- [Storage](#storage)
- [API & SDKs](#api--sdks)
- [Other Tools](#other-tools)
- [CV4PVE Suite](#cv4pve-suite)
- [Mobile Apps](#mobile-apps)
- [Desktop Apps](#desktop-apps)
- [Documentation](#documentation)
- [Tutorials, Blogs & Video](#tutorials-blogs--video)
- [Templates & Marketplace](#templates--marketplace)
- [Security Tools & Best Practices](#security-tools--best-practices)
- [Community, Forum & Social](#community-forum--social)
- [Utilities & Scripts](#utilities--scripts)
- [Benchmark & Comparisons](#benchmark--comparisons)
- [YouTube Channels](#youtube-channels)
- [Forums](#forums)
- [Contributing](#contributing)
- [License](#license)

---

## Proxmox VE

- [Proxmox Virtual Environment](https://proxmox.com/en/products/proxmox-virtual-environment/overview)  
  Complete, open-source server management platform for enterprise virtualization.  
  [[Download ISO](https://proxmox.com/en/downloads/proxmox-virtual-environment/iso)] • [[Install Docs](https://pve.proxmox.com/pve-docs/chapter-pve-installation.html)] • [[Forum](https://forum.proxmox.com/)]

---

## Management

- [CV4PVE-ADMIN (Web UI)](https://corsinvest.it/cv4pve-admin-proxmox/)
  Powerful and easy-to-use web administration interface for monitoring/manage multiple Proxmox VE clusters from a single portal.
  [GitHub](https://github.com/Corsinvest/cv4pve-admin)
- [MultiPortal](https://multiportal.io/)
- [Convoy](https://convoypanel.com/)
- [PegaProx](https://pegaprox.com/) — Datacenter management UI with unified multi-cluster control, intelligent load balancing and seamless cross-cluster migrations.
- [ProxCenter](https://www.proxcenter.io/) — Modern web interface for multi-cluster management, cross-hypervisor migration and workload balancing from a single pane of glass.
- [Proxmox Datacenter Manager](https://www.proxmox.com/en/downloads/proxmox-datacenter-manager)

---

## CV4PVE Suite

**Advanced official Corsinvest tools for integrated multi-platform Proxmox VE management.**

- [**CV4PVE-ADMIN**](https://github.com/Corsinvest/cv4pve-admin)
  Web management platform for Proxmox VE clusters — like vCenter but for Proxmox.
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
  CLI launcher for SPICE remote viewer on Proxmox VE VMs with automatic ticket handling.
- [**CV4PVE-VDI**](https://github.com/Corsinvest/cv4pve-vdi)
  Desktop VDI client for Proxmox VE — SPICE, VNC, RDP and SSH console launchers.
- [**CV4PVE-REPORT**](https://github.com/Corsinvest/cv4pve-report)
  Export Proxmox VE infrastructure to a navigable Excel report — like RVTools for Proxmox.
- [**CV4PVE-NODE-PROTECT**](https://github.com/Corsinvest/cv4pve-node-protect)
  Backup and restore Proxmox VE node configuration files via SSH.

**Related online suite:**
- [cv4pve-tools.com](https://www.cv4pve-tools.com)  
  Official Corsinvest portal for metrics, comparator, converter, online tools and demos, documentation and API reference.

---

## VPS Control Panels

- [Proxmox VE VPS For WHMCS](https://www.modulesgarden.com/products/whmcs/proxmox-ve-vps)
- [SolusVM](https://solusvm.com/)
- [Virtualizor](https://www.virtualizor.com/) [[Docs](https://www.virtualizor.com/docs/)]

---

## Monitoring

- [CheckMK](https://checkmk.com/blog/proxmox-monitoring)
- [LPAR2RRD](https://lpar2rrd.com/Proxmox-monitoring.php)
- [Netdata](https://www.netdata.cloud/integrations/data-collection/containers-and-vms/proxmox-ve/)
- [PandoraFMS](https://pandorafms.com/blog/proxmox-ve-monitoring/)
- [Prometheus Proxmox VE Exporter](https://github.com/prometheus-pve/prometheus-pve-exporter)
- [Pulse](https://github.com/rcourtman/Pulse)
- [VictoriaMetrics](https://victoriametrics.com/blog/proxmox-monitoring-with-dbaas/)
- [Zabbix](https://www.zabbix.com/de/integrations/proxmox)
- [cv4pve-metrics-exporter](https://github.com/Corsinvest/cv4pve-metrics-exporter) — Prometheus metrics exporter for Proxmox VE nodes, VMs, containers and storage.
---

## Backup Tools

- [BACKUP EAGLE](https://www.backup-eagle.com/product/proxmox)
- [Bacula Enterprise](https://www.baculasystems.com/corporate-data-backup-software-solutions/bacula-enterprise-data-backup-software/features/)
- [BDRSuite](https://www.bdrsuite.com/proxmox-backup/) [[Docs](https://www.bdrsuite.com/technical-documents/)] [[Download](https://www.bdrsuite.com/vembu-bdr-suite-download/)]
- [Catalogic DPX](https://www.catalogicsoftware.com/portfolio/proxmox/)
- [Commvault Backup&Recovery](https://www.commvault.com/use-cases/backup-and-recovery) [[Docs](https://documentation.commvault.com/11.38/essential/backups_for_proxmox_vms.html)]
- [NAKIVO Backup & Replication](https://www.nakivo.com/proxmox-backup/) [[Trial](https://www.nakivo.com/resources/download/trial-download/)] [[Docs](https://helpcenter.nakivo.com/User-Guide/Content/Home.htm)]
- [Proxmox Backup Server](https://proxmox.com/en/products/proxmox-backup-server/overview) [[Download](https://proxmox.com/en/downloads/proxmox-backup-server)] [[Docs](https://pbs.proxmox.com/docs/installation.html)]
- [SEP sesam](https://www.sep.de/solutions/proxmox-hypervisor/)
- [Storware Backup&Recovery](https://storware.eu/solutions/virtual-machine-backup-and-recovery/proxmox-ve-backup-and-recovery/)
- [Veeam Backup for Proxmox](https://www.veeam.com/blog/veeam-backup-for-proxmox.html)
- [Vinchin Backup & Recovery](https://www.vinchin.com/proxmox-backup.html) [[Trial](https://www.vinchin.com/vinchin-software-documentation-downloads.html)] [[Docs](https://helpcenter.vinchin.com/)]
- [proxmox-backup](https://github.com/tis24dev/proxmox-backup)
- [CV4PVE-AUTOSNAP](https://github.com/Corsinvest/cv4pve-autosnap)
  - Snapshot automation with policies for Proxmox VE.
- [PBS_Chunk_Checker](https://github.com/VoltKraft/PBS_Chunk_Checker)

---

## Storage

- [Dell PowerStore: Deploying Proxmox Virtual Environment](https://infohub.delltechnologies.com/en-us/t/dell-powerstore-deploying-proxmox-virtual-environment-white-paper/)
- [Setting Up Highly Available Storage for Proxmox Using LINSTOR](https://linbit.com/blog/setting-up-highly-available-storage-for-proxmox-using-linstor-the-linbit-gui/)
- [Netapp: Proxmox VE with ONTAP](https://docs.netapp.com/us-en/netapp-solutions/proxmox/proxmox-ontap.html)
- [Proxmox VE Plugin for Pure Storage as Multipath iSCSI Source](https://github.com/kolesa-team/pve-purestorage-plugin)
- [Proxmox VE Plugin for HPE Nimble Storage (iSCSI)](https://github.com/brngates98/pve-nimble-plugin) — Integration of HPE Nimble Storage arrays with Proxmox VE over iSCSI, using the Nimble REST API to create and manage volumes.
- [TrueNAS Proxmox VE Storage Plugin](https://github.com/WarlockSyno/TrueNAS-Proxmox-VE-Storage-Plugin)

---

## API & SDKs

### Community Maintained

#### Python
- [proxmoxer](https://pypi.python.org/pypi/proxmoxer)
- [proxmox-utils (Console Client)](https://github.com/remofritzsche/proxmox-utils)
- [Proxmoxia (Wrapper)](https://github.com/baseblack/Proxmoxia)
- [pmxc (Console Client)](https://github.com/pcdummy/pmxc)

#### PowerShell
- [cv4pve-api-powershell](https://github.com/Corsinvest/cv4pve-api-powershell)

#### Ruby
- [nledez/proxmox](https://github.com/nledez/proxmox)

#### NodeJS
- [npm:proxmox](https://www.npmjs.com/package/proxmox)
- [AmiCole/pvea](https://github.com/AmiCole/pvea)
- [cv4pve-api-javascript](https://github.com/Corsinvest/cv4pve-api-javascript)

#### C#
- [ProxmoxSharp](https://github.com/ionelanton/ProxmoxSharp)
- [cv4pve-api-dotnet](https://github.com/Corsinvest/cv4pve-api-dotnet)
- [cv4pve-cli](https://github.com/Corsinvest/cv4pve-cli)
- [cv4pve-botgram](https://github.com/Corsinvest/cv4pve-botgram)
- [cv4pve-pepper](https://github.com/Corsinvest/cv4pve-pepper)

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

#### Go
- [proxmox-api-go](https://github.com/Telmate/proxmox-api-go)
- [go-proxmox](https://github.com/luthermonson/go-proxmox)
- [Packer Plugin for Proxmox VE](https://developer.hashicorp.com/packer/integrations/hashicorp/proxmox)

#### Terraform
- [terraform-provider-proxmox (Telmate)](https://github.com/Telmate/terraform-provider-proxmox)

---

## Other Tools

- [Ansible Module - Proxmox VE Cluster](https://docs.ansible.com/ansible/latest/collections/community/general/proxmox_module.html)
- [Cluster API Provider for Proxmox VE (CAPMOX)](https://github.com/ionos-cloud/cluster-api-provider-proxmox)
- [LXC AutoScale](https://github.com/fabriziosalmi/proxmox-lxc-autoscale)
- [osx-proxmox](https://github.com/lucid-fabrics/osx-proxmox-next) - One-command macOS VM automation for Proxmox 9 with TUI wizard, recovery auto-download, and AMD/Intel support.
- [proxmox-backup](https://github.com/tis24dev/proxmox-backup)
- [ProxMenux](https://github.com/MacRimi/ProxMenux)
- [ProxMigrate](https://github.com/AthenaNetworks/ProxMigrate)
- [Proxmox VM Autoscale](https://github.com/fabriziosalmi/proxmox-vm-autoscale)
- [ProxCLMC](https://github.com/gyptazy/ProxCLMC) — Lightweight tool to determine the maximum CPU compatibility level supported across all nodes in a Proxmox VE cluster.
- [ProxLB](https://github.com/gyptazy/ProxLB)
- [ProxmoxMCP](https://github.com/rodaddy/ProxmoxMCP) - MCP server for Proxmox VE management, enabling AI assistants to control VMs, containers, and cluster resources.
- [ProxmoxMCP-Plus](https://github.com/rodaddy/ProxmoxMCP-Plus) - Enhanced Proxmox MCP server with advanced virtualization management and full OpenAPI integration.
- [Proxmox-Enhanced-Configuration-Utility (PECU)](https://github.com/Danilop95/Proxmox-Enhanced-Configuration-Utility)
- [Proxmox VE Helper-Scripts](https://github.com/community-scripts/ProxmoxVE)
- [proxtagger](https://github.com/reginleif88/proxtagger)
- [PVE-mods](https://github.com/Meliox/PVE-mods)
- [pvetui](https://github.com/devnullvoid/pvetui)
- [ProxSave](https://proxsave.dev/) — Backup and restore of Proxmox PBS & PVE system files — save your entire environment and restore it at any time.
- [ProxSnap](https://github.com/gyptazy/ProxSnap) — Lightweight CLI tool for auditing and cleaning up snapshots across Proxmox VE clusters.
- [Terraform Provider for Proxmox](https://github.com/bpg/terraform-provider-proxmox)

---

## Tutorials, Blogs & Video

- [ServeTheHome - Proxmox VE Tutorials](https://www.servethehome.com/tag/proxmox-ve/)
- [Techno Tim - Proxmox Guides (Blog & Video)](https://technotim.live/tags/proxmox/)
- [Nick Sherlock - macOS on Proxmox](https://www.nicksherlock.com/tag/proxmox/)
- [VirtualizationHowTo - Proxmox](https://www.virtualizationhowto.com/tag/proxmox-ve/)
- [The Homelab Wiki - Proxmox Section](https://wiki.homelabos.com/other/proxmox/)

---

## Templates & Marketplace

- [TurnKey Linux Proxmox LXC Templates](https://www.turnkeylinux.org/docs/proxmox-lxc)
- [TTECK Proxmox LXC Templates & Utilities](https://tteck.github.io/Proxmox/)
- [LinuxServer Container Templates](https://github.com/linuxserver/docker-templates)
- [TrueNAS SCALE Community Catalog](https://github.com/truecharts/apps)

---

## Security Tools & Best Practices

- [Proxmox Security Best Practices (official)](https://pve.proxmox.com/wiki/Security)
- [OpenSCAP - Security audit tool](https://www.open-scap.org/)
- [Falco Security - Runtime Linux Security](https://falco.org/)
- [Official Proxmox Firewall Guide](https://pve.proxmox.com/pve-docs/pve-firewall.8.html)
- [fail2ban for Proxmox (HowToForge)](https://www.howtoforge.com/tutorial/how-to-protect-proxmox-ve-with-fail2ban-and-ufw/)

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

- [Proxmox VE Clean Snapshots](https://github.com/Corsinvest/cv4pve-autosnap)
- [pve-zsync (ZFS backup/snapshots)](https://pve.proxmox.com/wiki/PVE-zsync)
- [Proxmox VE Backup Checker](https://github.com/paulie1231/pve-backup-check)
- [PVE7to8 - Major Upgrade Script](https://github.com/Corsinvest/cv4pve-pve7to8)
- [Proxmox Wake on LAN](https://github.com/Aizen-Barbaros/Proxmox-WoL)
- [Proxmox Dark Theme (User script)](https://github.com/Weilbyte/PVEDiscordDark)
- [Proxmox Mail Gateway Custom Themes](https://github.com/IgorG1/PMG-Theme)
- [ProxMox Repo Manager/No-Subscription Script](https://tteck.github.io/Proxmox/)
- [Proxmox VE Helper-Scripts](https://github.com/community-scripts/ProxmoxVE)

---

## Benchmark & Comparisons

- [ServeTheHome Proxmox Benchmarks](https://www.servethehome.com/?s=proxmox+benchmark)
- [OpenBenchmarking Proxmox Results](https://openbenchmarking.org/testbed/2202159-NE-PROXMOXV55)

---

## YouTube Channels

### International Channels
- [Proxmox Server Solutions (Official Channel)](https://www.youtube.com/@ProxmoxServerSolutionsGmbH)  
  Webinars, releases, new Proxmox features.
- [ServeTheHome](https://www.youtube.com/c/ServeTheHomeVideo)  
  Proxmox guides, hardware, servers and storage.
- [Techno Tim](https://www.youtube.com/c/TechnoTimLive)  
  Cluster setup, installation, automated backups with Proxmox.
- [Lawrence Systems](https://www.youtube.com/c/LawrenceSystems/search?query=proxmox)  
  Enterprise deep-dives, security and tutorials.
- [Craft Computing](https://www.youtube.com/c/CraftComputing/search?query=proxmox)  
  Real homelab use cases, containers, storage.
- [The Digital Life](https://www.youtube.com/c/TheDigitalLife/search?query=proxmox)  
  Tutorials, LXC, scripting.
- [DB Tech](https://www.youtube.com/c/DBTechYT/search?query=proxmox)  
  Guides on containers and services.

### Italian Channels
- [Stefano Droghetti](https://www.youtube.com/@stefanodroghetti/search?query=proxmox)  
  Italian tutorials on installation, containers and Proxmox use cases.
- [Maurizio Leo](https://www.youtube.com/@MaurizioLeo/search?query=proxmox)  
  Homelab and virtualization.
- [Francesco Mainardi](https://www.youtube.com/@francescomainardi/search?query=proxmox)

---

## Mobile Apps

### Android
- [Proxmox VE Android App](https://play.google.com/store/apps/details?id=com.proxmox.app.pve_flutter_frontend) — Official app to manage VMs, containers, hosts and clusters.
- [ProxMon](https://play.google.com/store/apps/details?id=dev.reimu.proxmon) — View nodes, storage pools, VMs and containers statuses.

### iOS
- [ProxMan](https://proxman.app) — App for managing Proxmox VE and Proxmox Backup Server environments.
- [ProxMate](https://apps.apple.com/de/app/proxmate/id6470526961) — Manage your Proxmox server from iOS.
- [ProxMate Backup](https://apps.apple.com/de/app/proxmate-backup/id6618157722) — Manage Proxmox Backup Servers.
- [ProxMobo](https://proxmobo.app/) — Monitoring and management app for Proxmox VE and Proxmox Backup Server.

---

## Desktop Apps

### macOS
- [ProxmoxBar](https://github.com/ryzenixx/proxmoxbar-macos) — Native macOS menu bar app for monitoring and controlling Proxmox VE resources.

---

## Documentation

- [10 Ways to Ruin Your Proxmox Setup](https://github.com/SwamiRama/10-ways-to-ruin-proxmox) — Common mistakes and how to avoid them.
- [free-pmx](https://free-pmx.pages.dev/)
- [Proxmox Hardening Guide](https://github.com/HomeSecExplorer/Proxmox-Hardening-Guide) — Actionable recommendations to secure Proxmox VE and Proxmox Backup Server.
- [Thomas Krenn Proxmox Wiki](https://www.thomas-krenn.com/de/wiki/Kategorie:Proxmox)
- [Proxmox VE Wiki](https://pve.proxmox.com/wiki/Main_Page)
- [Proxmox VE Documentation](https://pve.proxmox.com/pve-docs/)

---

## Forums

- [Proxmox Support Forum](https://forum.proxmox.com/)
- [Reddit: Proxmox](https://www.reddit.com/r/Proxmox/)

---

## Contributing

Contributing guidelines can be found [here](https://github.com/alexgoesgit/awesome-proxmox-ve-virtualization/blob/main/contributing.md).
Or see [CONTRIBUTING.md](CONTRIBUTING.md) in this repo for detailed instructions.

---

## License

This list is under the [Creative Commons Attribution-ShareAlike 1.0 Generic License](https://creativecommons.org/licenses/by-sa/1.0/).
Terms of the license are summarized in the link above.
