# Awesome Proxmox VE Virtualization with stars

> A list of Proxmox VE related software, tools and documentation. This project is not affiliated with Proxmox.

![GitHub License](https://img.shields.io/github/license/alexgoesgit/awesome-proxmox-ve-virtualization)
![GitHub last commit](https://img.shields.io/github/last-commit/alexgoesgit/awesome-proxmox-ve-virtualization)

## Contents

* [AI](#ai)
* [API](#api)
* [Autoscaling](#autoscaling)
* [Backup Tools](#backup-tools)
* [CLI & Community Tools](#cli--community-tools)
* [Cluster Tools](#cluster-tools)
* [Desktop Apps](#desktop-apps)
* [Documentation](#documentation)
* [Forums](#forums)
* [Guest Automation](#guest-automation)
* [Infrastructure as Code](#infrastructure-as-code)
* [Inventory](#inventory)
* [Management](#management)
* [Migration](#migration)
* [Mobile Apps](#mobile-apps)
* [Monitoring](#monitoring)
* [Proxmox VE](#proxmox-ve)
* [Reporting](#reporting)
* [Smarthome](#smarthome)
* [Security](#security)
* [Storage](#storage)
* [Trainings](#trainings)
* [Tutorials, Blogs & Video](#tutorials-blogs--video)
* [VDI](#vdi)
* [VPS control panels](#vps-control-panels)

## AI

* [ProxmoxMCP-Plus](https://github.com/RekklesNA/ProxmoxMCP-Plus) ⭐ 517 | 🐛 4 | 🌐 Python | 📅 2026-09-03 - MCP and OpenAPI integration to safely control Proxmox VE VMs, LXCs, backups, and snapshots from LLMs and AI agents.
* [ProxmoxMCP](https://github.com/canvrno/proxmoxmcp) ⭐ 289 | 🐛 15 | 🌐 Python | 📅 2025-02-19 - Python-based MCP server for interacting with Proxmox hypervisors, providing a clean interface for managing nodes, VMs, and containers.
* [Proximo](https://github.com/john-broadway/proximo) ⭐ 42 | 🐛 1 | 🌐 Python | 📅 2026-09-01 - MCP server for Proxmox VE, Backup Server, Mail Gateway, and Datacenter Manager with audited trust core (plan, prove, undo, diagnose). MCP + A2A.

## API

* [Proxmox API documentation](https://pve.proxmox.com/pve-docs/api-viewer/index.html) - Explore the official API documentation.
* Go
  * [Proxmox API Go](https://github.com/Telmate/proxmox-api-go) ⭐ 491 | 🐛 55 | 🌐 Go | 📅 2026-08-30 - Proxmox API in golang. For /api2/json.
  * [go-proxmox](https://github.com/luthermonson/go-proxmox) ⭐ 285 | 🐛 2 | 🌐 Go | 📅 2026-08-09 - Typed Go client for the Proxmox VE REST API.
* Java
  * [Proxmox VE Client API Java](https://github.com/Corsinvest/cv4pve-api-java) ⭐ 78 | 🐛 0 | 🌐 Java | 📅 2026-07-26 - Java API client Libraries.
* Perl
  * [Proxmox Perl API client](https://git.proxmox.com/?p=pve-apiclient.git;a=summary) - Official Proxmox Maintained Perl API.
* PHP
  * [cv4pve-api-php](https://github.com/Corsinvest/cv4pve-api-php) ⭐ 83 | 🐛 1 | 🌐 PHP | 📅 2026-05-29 - Proxmox VE Client API for PHP.
* Powershell
  * [PowerShell for Proxmox VE](https://www.powershellgallery.com/packages/Corsinvest.ProxmoxVE.Api/) - CmdLet for PowerShell to manage Proxmox VE.
* Python
  * [proxmoxer](https://pypi.org/project/proxmoxer) - Python wrapper around the Proxmox REST API v2.

## Autoscaling

* [Proxmox VM Autoscale](https://github.com/fabriziosalmi/proxmox-vm-autoscale) ⭐ 302 | 🐛 3 | 🌐 Python | 📅 2026-07-20 - Service that dynamically adjusts your Proxmox virtual machine (VM) resources (CPU cores, RAM) based on real-time metrics and user-defined thresholds.
* [LXC AutoScale](https://github.com/fabriziosalmi/proxmox-lxc-autoscale) ⭐ 257 | 🐛 18 | 🌐 Python | 📅 2026-08-25 - Resource management daemon specifically designed for Proxmox environments. It automatically adjusts CPU and memory allocations with no downtime and can clone LXC containers based on real-time usage metrics and predefined thresholds.

## Backup Tools

* [cv4pve-autosnap](https://github.com/Corsinvest/cv4pve-autosnap) ⭐ 563 | 🐛 3 | 🌐 C# | 📅 2026-07-03 - Automatic snapshots for VMs and containers with retention policies, via the Proxmox API.
* [proxmox-backup](https://github.com/tis24dev/proxmox-backup) ⭐ 515 | 🐛 5 | 🌐 Go | 📅 2026-09-02 - Backup tool for Proxmox PBS & PVE System Files with advanced features and notifications.
* [Joulenap](https://github.com/Joulenap/joulenap) ⭐ 124 | 🐛 2 | 🌐 Python | 📅 2026-09-03 - Web UI and scheduler for backups to a Proxmox Backup Server that stays powered off: wakes it, runs the backups, prunes, garbage-collects and shuts it down. Any number of PVE hosts and PBS, PBS to PBS sync, notifications.
* [ProxSnap](https://github.com/gyptazy/ProxSnap) ⭐ 22 | 🐛 0 | 🌐 Rust | 📅 2026-01-22 - Lightweight CLI tool for auditing and cleaning up snapshots across Proxmox VE clusters.
* [pve-bindsnap](https://github.com/bitranox/pve-bindsnap) ⭐ 6 | 🐛 0 | 🌐 Perl | 📅 2026-08-27 - Snapshot LXC containers that have bind/device mounts, which stock Proxmox greys out, via a small AGPL overlay. Can also exclude specific volumes from a snapshot; works with the GUI, API, pct and cv4pve-autosnap.
* [BACKUP EAGLE](https://www.backup-eagle.com/product/proxmox) - Backup Monitoring and Reporting. Centralised view of backups, backup system health and backup storage for on-prem and cloud backups.
* [Bacula Enterprise](https://www.baculasystems.com/corporate-data-backup-software-solutions/bacula-enterprise-data-backup-software/features/) - Subscription-based enterprise data backup solution with a Proxmox plugin for the latest PVE releases.
* [BDRSuite](https://www.bdrsuite.com/proxmox-backup/) - Comprehensive backup and disaster recovery solution for virtual, physical, cloud, and SaaS applications with agentless backup for Proxmox VMs ([docs](https://www.bdrsuite.com/technical-documents/), [download](https://www.bdrsuite.com/vembu-bdr-suite-download/)).
* [Catalogic DPX](https://www.catalogicsoftware.com/portfolio/proxmox/) - Integrates seamlessly with Proxmox Virtual Environment (VE). DPX vPlus enables agentless Proxmox backup and recovery.
* [Commvault Backup\&Recovery](https://www.commvault.com/use-cases/backup-and-recovery) - Protects VMs hosted in Proxmox Virtual Environment ([docs](https://documentation.commvault.com/11.38/essential/backups_for_proxmox_vms.html)).
* [NAKIVO Backup & Replication](https://www.nakivo.com/proxmox-backup/) - Backup, replication, failover, cloud/tape backup, granular restore, and disaster recovery orchestration for virtual, physical, cloud, and SaaS environments ([trial](https://www.nakivo.com/resources/download/trial-download/), [docs](https://helpcenter.nakivo.com/User-Guide/Content/Home.htm)).
* [Proxmox Backup Client](https://pbs.proxmox.com/docs/backup-client.html) - Official command-line client for Proxmox Backup Server, including host, VM, and file backups.
* [Proxmox Backup Server](https://proxmox.com/en/products/proxmox-backup-server/overview) - Enterprise backup solution for backing up and restoring VMs, containers, and physical hosts ([download](https://proxmox.com/en/downloads/proxmox-backup-server), [docs](https://pbs.proxmox.com/docs/installation.html)).
* [ProxSave](https://proxsave.dev/) - Proxmox PBS & PVE system files backup. Save your entire environment and restore it at any time.
* [pve-zsync](https://pve.proxmox.com/wiki/PVE-zsync) - Official ZFS replication helper for copying VM and container datasets between hosts.
* [SEP sesam for Proxmox Virtual Environment](https://www.sep.de/solutions/proxmox-hypervisor/) - Efficient data protection for virtual machines running on Proxmox VE.
* [Storware Backup\&Recovery](https://storware.eu/solutions/virtual-machine-backup-and-recovery/proxmox-ve-backup-and-recovery/) - Comprehensive data protection for virtual machines, containers, and files on Proxmox VE.
* [Veeam Backup for Proxmox](https://www.veeam.com/blog/veeam-backup-for-proxmox.html) - Well-known Enterprise backup solution.
* [Vinchin Backup & Recovery](https://www.vinchin.com/proxmox-backup.html) - Secure data protection and disaster recovery for VMs, cloud instances, databases, Exchange, and unstructured data ([trial](https://www.vinchin.com/vinchin-software-documentation-downloads.html), [docs](https://helpcenter.vinchin.com/)).

## CLI & Community Tools

* [Proxmox VE Helper-Scripts](https://github.com/community-scripts/ProxmoxVE) ⭐ 29,483 | 🐛 16 | 🌐 Shell | 📅 2026-09-03 - Community-driven initiative that simplifies the setup of Proxmox Virtual Environment (VE).
* [ProxMenux](https://github.com/MacRimi/ProxMenux) ⭐ 2,929 | 🐛 11 | 🌐 TypeScript | 📅 2026-09-03 - Management tool for Proxmox VE that simplifies system administration through an interactive menu.
* [PVE-mods](https://github.com/Meliox/PVE-mods) ⭐ 1,900 | 🐛 21 | 🌐 Shell | 📅 2026-08-23 - Small collection of scripts and mods for Proxmox Virtual Environment (PVE).
* [Proxmox-Enhanced-Configuration-Utility (PECU)](https://github.com/Danilop95/Proxmox-Enhanced-Configuration-Utility) ⭐ 966 | 🐛 10 | 🌐 Shell | 📅 2026-05-17 - Versatile Bash script to simplify and optimize configuration and management of Proxmox VE systems.
* [pvetui](https://github.com/devnullvoid/pvetui) ⭐ 718 | 🐛 12 | 🌐 Go | 📅 2026-08-31 - Terminal User Interface for Proxmox Virtual Environment.
* [PVE Scripts Local](https://github.com/community-scripts/ProxmoxVE-Local) ⭐ 373 | 🐛 8 | 🌐 TypeScript | 📅 2026-09-03 - Local web UI to browse and run Proxmox VE Helper-Scripts without curl-to-bash from the site.
* [dockur/proxmox](https://github.com/dockur/proxmox) ⭐ 305 | 🐛 4 | 🌐 Shell | 📅 2026-08-30 - Full Proxmox VE node running inside a Docker container, for labs and CI.
* [cv4pve-cli](https://github.com/Corsinvest/cv4pve-cli) ⭐ 85 | 🐛 0 | 🌐 C# | 📅 2026-07-14 - kubectl-style remote CLI for Proxmox VE with multi-cluster contexts and shell completion.
* [Proxmox Manager](https://github.com/TimInTech/proxmox-manager) ⭐ 71 | 🐛 1 | 🌐 Shell | 📅 2026-08-31 - Single-file Bash tool for managing Proxmox VMs and containers.
* [proxtagger](https://github.com/reginleif88/proxtagger) ⭐ 50 | 🐛 0 | 🌐 Python | 📅 2026-05-12 - Lightweight, open-source web interface to bulk manage Proxmox VM and container tags.
* [Proxmox VMID Updater](https://github.com/sannier3/proxmox-vmid-updater) ⭐ 13 | 🐛 0 | 🌐 Shell | 📅 2026-06-29 - Interactive Proxmox VM/LXC ID renaming script with automatic logging, safety checks, and storage path updates.

## Cluster Tools

* [ProxLB](https://github.com/credativ/ProxLB) ⭐ 162 | 🐛 9 | 🌐 Python | 📅 2026-08-31 - Application to optimize the distribution of virtual machines across Proxmox cluster nodes for enhanced efficiency and performance.
* [ProxCLMC](https://github.com/credativ/ProxCLMC) ⭐ 37 | 🐛 1 | 🌐 Rust | 📅 2026-05-12 - Lightweight tool to determine the maximum CPU compatibility level supported across all nodes in a Proxmox VE cluster for live migration.

## Desktop Apps

### macOS

* [ProxmoxBar](https://github.com/ryzenixx/proxmoxbar-macos) ⭐ 178 | 🐛 3 | 🌐 Swift | 📅 2026-09-02 - Native macOS menu bar app for monitoring and controlling Proxmox VE resources.

## Documentation

* [10 Ways to Ruin Your Proxmox Setup - And How Not To](https://github.com/SwamiRama/10-ways-to-ruin-proxmox) ⭐ 159 | 🐛 1 | 📅 2026-01-05 - Book about 10 common mistakes and how to avoid them.
* [free-pmx](https://free-pmx.pages.dev/) - Insights and guides on Proxmox VE.
* [Proxmox VE Documentation](https://pve.proxmox.com/pve-docs/) - Official Proxmox VE Documentation.
* [Proxmox VE Wiki](https://pve.proxmox.com/wiki/Main_Page) - Official Proxmox VE Wiki.
* [Thomas Krenn Proxmox Wiki](https://www.thomas-krenn.com/de/wiki/Kategorie:Proxmox) - Several articles and howtos related to Proxmox VE.

## Forums

* [Discord: Proxcord](https://discord.gg/w9Y5UPz4FG) - Unofficial Discord server for Proxmox VE.
* [Proxmox Support Forum](https://forum.proxmox.com/) - Proxmox Community Forum.
* [Reddit: Proxmox](https://www.reddit.com/r/Proxmox/) - Main subreddit regarding the Proxmox hypervisor.

## Guest Automation

* [pve-microvm](https://github.com/rcarmo/pve-microvm) ⭐ 369 | 🐛 1 | 🌐 Shell | 📅 2026-09-03 - Firecracker-like microVMs for Proxmox VE — KVM isolation, under 200ms boot.
* [osx-proxmox](https://github.com/lucid-fabrics/osx-proxmox-next) ⭐ 268 | 🐛 0 | 🌐 Python | 📅 2026-08-27 - One-command macOS VM automation for Proxmox 9 with TUI wizard, recovery image auto-download, and AMD/Intel CPU support for Sonoma, Sequoia, and Tahoe.
* [valheim-proxmox](https://github.com/PawelSzymanski89/valheim-proxmox) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2026-08-04 - One-command Valheim dedicated server LXC with a web panel for players, bans, worlds, backups and mods
* [proxmox-guestos-customization](https://github.com/RobertLukan/proxmox-guestos-customization) ⭐ 2 | 🐛 10 | 🌐 Python | 📅 2026-08-26 - Community Sysprep sidecar to clone and customize Windows templates on Proxmox VE (hostname, network, AD/workgroup) via the QEMU guest agent.

## Infrastructure as Code

* [Terraform Provider for Proxmox](https://github.com/bpg/terraform-provider-proxmox) ⭐ 2,214 | 🐛 112 | 🌐 Go | 📅 2026-09-03 - Terraform provider which adds support for Proxmox solutions.
* [Ansible Role - Proxmox](https://github.com/lae/ansible-role-proxmox) ⭐ 689 | 🐛 20 | 🌐 Python | 📅 2026-07-13 - Ansible role for installing and configuring Proxmox VE clusters.
* [Proxmox-GitOps](https://github.com/stevius10/Proxmox-GitOps) ⭐ 580 | 🐛 0 | 🌐 Ruby | 📅 2026-08-30 - Self-contained GitOps environment for provisioning and orchestrating Linux Containers (LXC) on Proxmox VE.
* [Cluster API Provider for Proxmox VE (CAPMOX)](https://github.com/ionos-cloud/cluster-api-provider-proxmox) ⭐ 478 | 🐛 118 | 🌐 Go | 📅 2026-09-03 - Kubernetes-style declarative APIs for cluster creation, configuration, and management on Proxmox VE.
* [Pulumi Proxmox VE](https://github.com/muhlba91/pulumi-proxmoxve) ⭐ 226 | 🐛 25 | 🌐 Go | 📅 2026-09-03 - Pulumi provider for creating and managing Proxmox VE resources.
* [Hashicorp packer-plugin-proxmox](https://github.com/hashicorp/packer-plugin-proxmox) ⭐ 223 | 🐛 94 | 🌐 Go | 📅 2026-07-16 - Official HashiCorp Packer plugin for building Proxmox VM templates.
* [Ansible Collection - community.proxmox](https://github.com/ansible-collections/community.proxmox) ⭐ 142 | 🐛 88 | 🌐 Python | 📅 2026-08-24 - Canonical Ansible collection for managing Proxmox VE clusters, VMs, and containers.
* [packer-plugin-proxmox](https://github.com/natrontech/packer-plugin-proxmox) ⭐ 8 | 🐛 0 | 🌐 Go | 📅 2026-06-22 - Packer plugin for Proxmox Builder.
* [OpenTofu Provider for Proxmox](https://search.opentofu.org/provider/bpg/proxmox/latest) - OpenTofu provider which adds support for Proxmox solutions

## Inventory

* [Netbox-SSOT](https://github.com/bl4ko/netbox-ssot) ⭐ 74 | 🐛 8 | 🌐 Go | 📅 2026-08-31 - Microservice that syncs objects from multiple sources (including Proxmox) into NetBox as automatic SSOT
* [iTop CMDB: Data collector for Proxmox](https://www.itophub.io/wiki/page?id=extensions:combodo-proxmox-data-collector) - Synchronize Proxmox managed devices into iTop.
* [netbox Enterprise Proxmox VE Integration](https://netboxlabs.com/docs/integrations/platform-integrations/proxmox-ve/) - Synchronization of Proxmox Virtual Environment (Proxmox VE) infrastructure into NetBox.
* [netbox-proxbox](https://www.emersonfelipesp.com/netbox-proxbox) - Netbox Plugin for integration between Proxmox and Netbox.
* [Proxmox Virtual Environment CMDB importer](https://www.versio.io/en/import-proxmox-cmdb-configuration-item.html) - Import, historize and process virtualized infrastructure configuration items into Versio.io.

## Management

* [AtlasPVE](https://atlaspve.com) - Safety-first control panel for Proxmox VE: shows what each action touches before you run it, guarded host updates (dry-run, pre-snapshot, boot-guard), storage and topology maps, built-in watchdog ([live demo](https://demo.atlaspve.com)).
* [Convoy](https://convoypanel.com/) - Traditional server management platform for interacting with Proxmox-based virtual machines ([docs](https://convoypanel.com/docs/project/introduction.html)).
* [CV4PVE-ADMIN](https://corsinvest.it/cv4pve-admin-proxmox/) - The easiest and most effective solution to monitor your multiple Proxmox VE cluster in a single web portal.
* [MultiPortal](https://multiportal.io/) - One platform to deploy, manage, and scale environments effortlessly, cut the complexity boost efficiency, and take control of your infrastructure.
* [PegaProx](https://pegaprox.com/) - Powerful datacenter management UI for Proxmox VE environments. Unified multi-cluster control, intelligent load balancing, and seamless cross-cluster migrations – all in one beautiful interface.
* [ProxCenter](https://www.proxcenter.io/) - Modern web interface for monitoring, managing, and optimizing Proxmox VE infrastructure. Multi-cluster management, cross-hypervisor migration, workload balancing, and more — from a single pane of glass.
* [Proxmox Datacenter Manager](https://www.proxmox.com/en/downloads/proxmox-datacenter-manager) - Server management software to provide a unified overview of all nodes and clusters that Proxmox VE users have in their virtualized environments ([docs](https://pdm.proxmox.com/docs/introduction.html)).
* [Tainer](https://tainer.sh/) - A cloud dashboard for Proxmox VE. Deploy, manage, and monitor LXC containers and VMs from anywhere — no ports to open. Free tier available.

## Migration

* [ProxMigrate](https://github.com/AthenaNetworks/ProxMigrate) ⭐ 56 | 🐛 0 | 🌐 Go | 📅 2026-08-16 - Powerful, user-friendly command-line tool for migrating virtual machines between Proxmox VE servers.
* [Migrate to Proxmox VE](https://pve.proxmox.com/wiki/Migrate_to_Proxmox_VE) - Official guide for moving VMs to Proxmox VE, including the ESXi import wizard.

## Mobile Apps

### Android

* [Proxmox VE Android App](https://play.google.com/store/apps/details?id=com.proxmox.app.pve_flutter_frontend\&hl=en) - Official native mobile app for managing Proxmox VE.
* [ProxMan](https://play.google.com/store/apps/details?id=com.windium.proxman\&hl=en) - Lightweight Proxmox VE & Backup Server Management in Your Pocket.
* [ProxMate Backup for Proxmox](https://play.google.com/store/apps/details?id=com.itss.proxmatebackup\&hl=en) - Get a quick and easy overview of your Proxmox Backup Server.
* [ProxMon - A Proxmox VE client](https://play.google.com/store/apps/details?id=dev.reimu.proxmon\&pcampaignid=web_share) - View Proxmox nodes, storage pools, VMs, and containers' statuses.

### iOS

* [Reeve](https://github.com/JoshuaShunk/reeve) ⭐ 59 | 🐛 5 | 🌐 Swift | 📅 2026-07-13 - Native SwiftUI app for iOS and MacOS to monitor, manage, and automate a Proxmox VE homelab.
* [Proxmox VE Companion](https://apps.apple.com/de/app/proxmox-ve-companion/id6748314140) - Official native mobile app for managing Proxmox VE.
* [ProxMan](https://proxman.app) - Application designed for managing Proxmox VE virtualization infrastructure and Proxmox Backup Server environments.
* [ProxMate Backup](https://apps.apple.com/de/app/proxmate-backup/id6618157722) - Manage Proxmox Backup Servers.
* [ProxMate iOS](https://apps.apple.com/de/app/proxmate/id6470526961?platform=iphone) - Manage your Proxmox Server.
* [ProxMobo: Proxmox VE & PBS Management](https://proxmobo.app/) - Powerful monitoring and management app for Proxmox VE and Proxmox Backup Server.

## Monitoring

* [Pulse](https://github.com/rcourtman/Pulse) ⭐ 6,665 | 🐛 35 | 🌐 Go | 📅 2026-09-02 - Real-time monitoring for Proxmox VE, Proxmox Mail Gateway, PBS, and Docker infrastructure with alerts and webhooks.
* [Prometheus Proxmox VE Exporter](https://github.com/prometheus-pve/prometheus-pve-exporter) ⭐ 1,449 | 🐛 35 | 🌐 Python | 📅 2026-09-02 - Exporter that exposes information gathered from Proxmox VE nodes for use by the Prometheus monitoring system.
* [PVE-UPS](https://github.com/ffind-dev/pve-ups) ⭐ 202 | 🐛 5 | 🌐 Python | 📅 2026-08-31 - GUI-based UPS shutdown appliance for Proxmox VE - a NUT alternative with a web wizard and no config files
* [check\_pve](https://github.com/nbuchwitz/check_pve) ⭐ 134 | 🐛 10 | 🌐 Python | 📅 2026-02-05 - Icinga check command for Proxmox VE via API.
* [pbs-exporter](https://github.com/natrontech/pbs-exporter) ⭐ 59 | 🐛 9 | 🌐 Go | 📅 2026-08-31 - Prometheus exporter for Proxmox Backup Server.
* [CheckMK](https://checkmk.com/blog/proxmox-monitoring) - Proxmox Monitoring: How to Do it Efficiently with Checkmk.
* [Datadog](https://docs.datadoghq.com/integrations/proxmox/) - Observability and security platform used to monitor applications, infrastructure, logs, networks, user experience, and cloud environments at any scale.
* [Grafana: Proxmox via Prometheus](https://grafana.com/grafana/dashboards/10347-proxmox-via-prometheus/) - Standard Grafana dashboard for the Prometheus Proxmox VE exporter.
* [LPAR2RRD](https://lpar2rrd.com/Proxmox-monitoring.php) - Server Performance Monitoring Tool - agentless monitoring, all data is gathered from Proxmox API.
* [ManageEngine OpManager](https://www.manageengine.com/network-monitoring/proxmox-monitoring.html) -  Network and IT‑infrastructure monitoring platform.
* [Netdata](https://www.netdata.cloud/integrations/data-collection/containers-and-vms/proxmox-ve/) - Real-time monitoring for infrastructure ranging from IoT devices to hybrid cloud environments with Proxmox VE support.
* [PandoraFMS](https://pandorafms.com/blog/proxmox-ve-monitoring/) - Proxmox VE monitoring with Pandora FMS.
* [Proxmox Atlas](https://proxmox-atlas.net/) - One dashboard. Every cluster. Real-time metrics, anomaly detection, and capacity planning.
* [VictoriaMetrics](https://victoriametrics.com/blog/proxmox-monitoring-with-dbaas/) - The High-Performance, Open Source Time Series Database & Monitoring Solution.
* [XorMon](https://xormon.com/server/monitoring/Proxmox/Proxmox-monitoring.php) - Unified performance monitoring across servers, virtualization platforms, storage systems, databases, containers, and cloud environments.
* [Zabbix](https://www.zabbix.com/de/integrations/proxmox) - Template for monitoring Proxmox with Zabbix.

## Proxmox VE

* [Proxmox Virtual Environment](https://proxmox.com/en/products/proxmox-virtual-environment/overview) - Complete, open-source server management platform for enterprise virtualization. It tightly integrates the KVM hypervisor and Linux Containers (LXC), software-defined storage and networking functionality, on a single platform ([download](https://proxmox.com/en/downloads/proxmox-virtual-environment/iso), [docs](https://pve.proxmox.com/pve-docs/chapter-pve-installation.html), [forum](https://forum.proxmox.com/)).

## Reporting

* [cv4pve-report](https://github.com/Corsinvest/cv4pve-report) ⭐ 55 | 🐛 2 | 🌐 C# | 📅 2026-06-01 - Export Proxmox VE infrastructure to a navigable Excel, HTML or JSON report - like RVTools for Proxmox.
* [Proxmox Report Generator](https://github.com/AungThuMyint/ProxmoxReportGenerator) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2026-06-11 - Report PDF Generator For Your Proxmox Virtual Environment.

## Smarthome

* [Proxmox VE Custom Integration for Home Assistant](https://github.com/dougiteixeira/proxmoxve) ⭐ 962 | 🐛 43 | 🌐 Python | 📅 2026-08-14 - This integration allows you to poll various data and controls from your Proxmox VE instance.
* [Proxmox Extended Sensors (v4)](https://github.com/Javisen/proxmox_sensors) ⭐ 63 | 🐛 14 | 🌐 Python | 📅 2026-08-17 - Detailed monitoring & control system for Proxmox VE & PBS in Home Assistant.
* [Proxmox Suits](https://github.com/Sundancer78/proxmox-suits) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2026-02-01 - Home Assistant integration for monitoring Proxmox VE and Proxmox Backup Server (PBS) with tasks, datastores, and IEC (GiB) sensors.

## Security

* [Proxmox Hardening Guide](https://github.com/HomeSecExplorer/Proxmox-Hardening-Guide) ⭐ 552 | 🐛 0 | 📅 2026-02-09 - Security hardening guides for PVE and PBS, built on CIS Debian Benchmark with Proxmox specific best practices.
* [proxmox-ftagent](https://github.com/Flowtriq/proxmox-ftagent) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2026-06-29 - One-command LXC deployment of the Flowtriq DDoS detection agent on Proxmox VE, with automatic dependency and systemd service setup.
* [Proxmox VE Security Advisories](https://forum.proxmox.com/threads/proxmox-virtual-environment-security-advisories.149331/) - List of security advisories since 2024-01-01 for the Proxmox Virtual Environment.
* [Proxmox VE Security Reporting](https://pve.proxmox.com/wiki/Security_Reporting) - How to report security issues to the Proxmox security team.

## Storage

* [TrueNAS Proxmox VE Storage Plugin](https://github.com/WarlockSyno/TrueNAS-Proxmox-VE-Storage-Plugin) ⚠️ Archived - High-performance storage plugin for Proxmox VE that integrates TrueNAS SCALE via iSCSI, featuring live snapshots, ZFS integration, and cluster compatibility.
* [Proxmox VE Plugin for Pure Storage as Multipath iSCSI Source](https://github.com/kolesa-team/pve-purestorage-plugin) ⭐ 42 | 🐛 14 | 🌐 Perl | 📅 2026-05-03 - Integration of Pure Storage arrays with Proxmox Virtual Environment (VE) using multipath iSCSI or Fibre Channel (FC).
* [Proxmox VE Plugin for HPE Nimble Storage (iSCSI)](https://github.com/brngates98/pve-nimble-plugin) ⭐ 8 | 🐛 0 | 🌐 Perl | 📅 2026-07-20 - Integration of HPE Nimble Storage arrays with Proxmox Virtual Environment (VE) over iSCSI. It uses the Nimble REST API to create and manage volumes and presents them as VM disks with optional multipath.
* [Snapbridge](https://github.com/abdoufermat5/snapbridge) ⭐ 0 | 🐛 0 | 🌐 Rust | 📅 2026-04-16 - Rust CLI for managing Proxmox snapshots on NetApp ONTAP-backed storage.
* [Dell PowerStore: Deploying Proxmox Virtual Environment](https://infohub.delltechnologies.com/en-us/t/dell-powerstore-deploying-proxmox-virtual-environment-white-paper/) - White paper on deploying and configuring Proxmox Virtual Environment on Dell PowerStore with shared storage.
* [Everpure: Technology Integrations - Proxmox](https://support.everpuredata.com/access?dita:id=m_proxmox) - Guidance on how to leverage Everpure FlashArray with iSCSI, FC or NFS.
* [Setting Up Highly Available Storage for Proxmox Using LINSTOR](https://linbit.com/blog/setting-up-highly-available-storage-for-proxmox-using-linstor-the-linbit-gui/) - Guide to DRBD-based highly available storage for Proxmox using LINSTOR and the LINBIT GUI.
* [Netapp: Proxmox VE with ONTAP](https://docs.netapp.com/us-en/netapp-solutions/proxmox/proxmox-ontap.html) - Netapp ONTAP storage can serve the needs of Proxmox VE host environments as well as for guest file, block and object storage demands.
* [StorPool Storage Powering Proxmox Virtual Environments](https://storpool.com/proxmox-virtual-environment) - Ultra-Fast, Reliable, and Scalable Block Storage as a Service for Proxmox Environments.

## Trainings

* [Croit Academy](https://www.croit.io/academy/topics/proxmox) - Proxmox VE trainings and workshops by working engineers.
* [Fast Lane](https://www.flane.de/en/courses/proxmox) - Hands-on Proxmox training courses.
* [Proxmox VE Training Courses](https://www.proxmox.com/en/services/training-courses/training) - Official Proxmox VE training courses from Proxmox Server Solutions GmbH.
* [Udemy: Proxmox VE courses](https://www.udemy.com/courses/search/?src=ukw\&q=Proxmox\&ratings=4.5\&lang=en\&lang=de) - Online learning platform with several Proxmox VE training courses.

## Tutorials, Blogs & Video

* [Lawrence Systems](https://www.youtube.com/c/LawrenceSystems/search?query=proxmox) - Enterprise and security-focused Proxmox VE videos.
* [Proxmox Server Solutions](https://www.youtube.com/@ProxmoxVe) - Official YouTube channel for releases, webinars, and product features.
* [ServeTheHome](https://www.servethehome.com/tag/proxmox-ve/) - Hardware and Proxmox VE guides ([YouTube](https://www.youtube.com/c/ServeTheHomeVideo)).
* [Techno Tim](https://technotim.live/tags/proxmox/) - Homelab blog and videos covering clusters, backups, and helper scripts ([YouTube](https://www.youtube.com/c/TechnoTimLive)).
* [VirtualizationHowTo](https://www.virtualizationhowto.com/tag/proxmox-ve/) - Proxmox VE tutorials and tool roundups.

## VDI

* [Kasm Workspaces](https://docs.kasm.com/docs/latest/how-to/autoscale/autoscale_providers/proxmox) - Configuring autoscaling for Kasm Workspaces on Proxmox.
* [PVE-VDIClient](https://github.com/joshpatten/PVE-VDIClient) ⭐ 1,088 | 🐛 44 | 🌐 Python | 📅 2026-04-10 - Proxmox based VDI client.

## VPS control panels

* [Proxmox VE VPS For WHMCS](https://www.modulesgarden.com/products/whmcs/proxmox-ve-vps) - High-powered module that automates every step of the virtual server provisioning process, from initial setup to ongoing management.
* [SolusVM](https://solusvm.com/) - Virtual infrastructure management solution to facilitate choice, simplicity, and performance for ISPs and enterprises.
* [Virtualizor](https://www.virtualizor.com/) - Web based VPS Control Panel to deploy and manage VPS on servers with a single click. Supports KVM, Xen, OpenVZ, Proxmox, Virtuozzo, LXC, and more ([docs](https://www.virtualizor.com/docs/)).

## Contributing

Contributing guidelines can be found [here](https://github.com/alexgoesgit/awesome-proxmox-ve-virtualization/blob/main/contributing.md) ⭐ 81 | 🐛 0 | 📅 2026-09-02.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-03._
