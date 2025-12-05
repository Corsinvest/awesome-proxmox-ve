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
- [Proxmox Datacenter Manager](https://www.proxmox.com/en/downloads/proxmox-datacenter-manager)

---

## CV4PVE Suite

**Suite di strumenti avanzati, ufficiali Corsinvest, per la gestione integrata e multi-piattaforma di Proxmox VE.**

- [**CV4PVE-ADMIN**](https://github.com/Corsinvest/cv4pve-admin)  
  Web administration portal: gestione centralizzata via browser di cluster multipli, utenti/gruppi, metriche, storage, snapshot, firewall, job schedulati e molto altro.
- [**CV4PVE-CLI**](https://github.com/Corsinvest/cv4pve-cli)  
  Interfaccia a riga di comando multipiattaforma avanzata, con centinaia di funzionalità per scripting, automazione, esportazione dati, gestione utenti, report e analisi.
- [**CV4PVE-AUTOSNAP**](https://github.com/Corsinvest/cv4pve-autosnap)  
  Gestione automatica degli snapshot, backup differenziali, politiche temporali, rollback.
- [**CV4PVE-DIAG**](https://github.com/Corsinvest/cv4pve-diag)  
  Strumenti di diagnostica, troubleshooting, audit di configurazioni e analisi della salute del cluster.
- [**CV4PVE-METRIC**](https://github.com/Corsinvest/cv4pve-metric)  
  Raccolta ed esportazione metriche del cluster in Prometheus e altri sistemi di monitoraggio (alerting, dashboard).
- [**CV4PVE-API**](https://github.com/Corsinvest/cv4pve-api-dotnet)  
  Client API ufficiale Corsinvest per integrare, sviluppare, personalizzare Proxmox in .NET/C# ([NuGet](https://www.nuget.org/packages/Corsinvest.ProxmoxVE.Api/)).
- [**CV4PVE-API-PHP**](https://github.com/Corsinvest/cv4pve-api-php)  
  Client API e libreria PHP ufficiale per automatizzare Proxmox in ambienti PHP/Composer.
- [**CV4PVE-API-JAVASCRIPT**](https://github.com/Corsinvest/cv4pve-api-javascript)  
  Client Javascript ufficiale per Node.js e frontend (automation, webapp).
- [**CV4PVE-API-JAVA**](https://github.com/Corsinvest/cv4pve-api-java)  
  Client API ufficiale Java.
- [**CV4PVE-API-POWERSHELL**](https://github.com/Corsinvest/cv4pve-api-powershell)  
  Modulo e CmdLet PowerShell ufficiale per gestire Proxmox VE da Windows, Azure DevOps ecc.
- [**CV4PVE-BOTGRAM**](https://github.com/Corsinvest/cv4pve-botgram)  
  Bot di gestione Proxmox via Telegram.
- [**CV4PVE-PEPPER**](https://github.com/Corsinvest/cv4pve-pepper)  
  Modulo C# per gestione cluster e automazione avanzata.
- [**CV4PVE-PVE7TO8**](https://github.com/Corsinvest/cv4pve-pve7to8)  
  Script avanzati per l'upgrade, audit e test migrazione da Proxmox VE 7 a 8.

**Suite online correlata:**
- [cv4pve-tools.com](https://www.cv4pve-tools.com)  
  Portale ufficiale metriche, comparatore, convertitore, strumenti e demo online Corsinvest, documentazione e API reference.
- [metrics.cv4pve-tools.com](https://metrics.cv4pve-tools.com)  
  Metriche, benchmark e analisi on-line sulla base delle raccolte dati pubbliche.

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
  - Automazione snapshot con policy per Proxmox VE.

---

## Storage

- [Dell PowerStore: Deploying Proxmox Virtual Environment](https://infohub.delltechnologies.com/en-us/t/dell-powerstore-deploying-proxmox-virtual-environment-white-paper/)
- [Setting Up Highly Available Storage for Proxmox Using LINSTOR](https://linbit.com/blog/setting-up-highly-available-storage-for-proxmox-using-linstor-the-linbit-gui/)
- [Netapp: Proxmox VE with ONTAP](https://docs.netapp.com/us-en/netapp-solutions/proxmox/proxmox-ontap.html)
- [Proxmox VE Plugin for Pure Storage as Multipath iSCSI Source](https://github.com/kolesa-team/pve-purestorage-plugin)
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
- [proxmox-backup](https://github.com/tis24dev/proxmox-backup)
- [ProxMenux](https://github.com/MacRimi/ProxMenux)
- [ProxMigrate](https://github.com/AthenaNetworks/ProxMigrate)
- [Proxmox VM Autoscale](https://github.com/fabriziosalmi/proxmox-vm-autoscale)
- [ProxLB](https://github.com/gyptazy/ProxLB)
- [Proxmox-Enhanced-Configuration-Utility (PECU)](https://github.com/Danilop95/Proxmox-Enhanced-Configuration-Utility)
- [Proxmox VE Helper-Scripts](https://github.com/community-scripts/ProxmoxVE)
- [proxtagger](https://github.com/reginleif88/proxtagger)
- [PVE-mods](https://github.com/Meliox/PVE-mods)
- [pvetui](https://github.com/devnullvoid/pvetui)
- [Terraform Provider for Proxmox](https://github.com/bpg/terraform-provider-proxmox)

---

## Tutorials, Blogs & Video

- [ServeTheHome - Proxmox VE Tutorials](https://www.servethehome.com/tag/proxmox-ve/)
- [Techno Tim - Proxmox Guides (Blog & Video)](https://technotim.live/tags/proxmox/)
- [Nick Sherlock - macOS su Proxmox](https://www.nicksherlock.com/tag/proxmox/)
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
- [Guida Firewall Proxmox ufficiale](https://pve.proxmox.com/pve-docs/pve-firewall.8.html)
- [fail2ban per Proxmox (HowToForge)](https://www.howtoforge.com/tutorial/how-to-protect-proxmox-ve-with-fail2ban-and-ufw/)

---

## Community, Forum & Social

- [Forum Ufficiale Proxmox](https://forum.proxmox.com/)
- [Reddit Proxmox VE](https://www.reddit.com/r/Proxmox/)
- [Telegram Proxmox Italia](https://t.me/ProxmoxVE_Italia)
- [Discord Proxmox Global (non ufficiale)](https://discord.gg/WvG4Yc0)
- [Facebook Proxmox Group](https://www.facebook.com/groups/proxmox/)

---

## Utilities & Scripts

- [Proxmox VE Clean Snapshots](https://github.com/Corsinvest/cv4pve-autosnap)
- [pve-zsync (backup/snaps ZFS)](https://pve.proxmox.com/wiki/PVE-zsync)
- [Proxmox VE Backup Checker](https://github.com/paulie1231/pve-backup-check)
- [PVE7to8 - Aggiornamento Major Script](https://github.com/Corsinvest/cv4pve-pve7to8)
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

### Canali Internazionali
- [Proxmox Server Solutions (Canale ufficiale)](https://www.youtube.com/@ProxmoxServerSolutionsGmbH)  
  Webinar, release, nuove funzionalità Proxmox.
- [ServeTheHome](https://www.youtube.com/c/ServeTheHomeVideo)  
  Guide Proxmox, hardware, server e storage.
- [Techno Tim](https://www.youtube.com/c/TechnoTimLive)  
  Cluster, installazione, backup automatizzati con Proxmox.
- [Lawrence Systems](https://www.youtube.com/c/LawrenceSystems/search?query=proxmox)  
  Approfondimenti aziendali, sicurezza e tutorial.
- [Craft Computing](https://www.youtube.com/c/CraftComputing/search?query=proxmox)  
  Uso homelab reale, container, storage.
- [The Digital Life](https://www.youtube.com/c/TheDigitalLife/search?query=proxmox)  
  Tutorials, LXC, scripting.
- [DB Tech](https://www.youtube.com/c/DBTechYT/search?query=proxmox)  
  Guide su container e servizi.

### Canali italiani
- [Stefano Droghetti](https://www.youtube.com/@stefanodroghetti/search?query=proxmox)  
  Tutorial in italiano su installazione, container e use-case Proxmox.
- [Maurizio Leo](https://www.youtube.com/@MaurizioLeo/search?query=proxmox)  
  Homelab e virtualizzazione.
- [Francesco Mainardi](https://www.youtube.com/@francescomainardi/search?query=proxmox)

---

## Documentation

- [free-pmx](https://free-pmx.pages.dev/)
- [Thomas Krenn Proxmox Wiki](https://www.thomas-krenn.com/de/wiki/Kategorie:Proxmox)
- [Promxox VE Wiki](https://pve.proxmox.com/wiki/Main_Page)
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

---
