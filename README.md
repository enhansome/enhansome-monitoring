# Awesome-Monitoring with stars

> A curated list of awesome resources for monitoring tools.

* [awesome](https://github.com/sindresorhus/awesome) ⭐ 497,735 | 🐛 102 | 📅 2026-08-18
* [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) ⭐ 33,609 | 🐛 60 | 🌐 Ruby | 📅 2024-06-02

***

## Contents

* [DC Monitoring](#dc-monitoring)
  * [Nagios](#nagios)
  * [Zabbix](#zabbix)
  * [Ganglia](#ganglia)
  * [Zenoss](#zenoss)
  * [Opserver](#opserver)
  * [Netdata](#netdata)
  * [HertzBeat](#hertzbeat)
* [Nagios Monitoring](#nagios-monitoring)
  * [Icinga](#icinga)
  * [Naemon](#naemon)
  * [Shinken](#shinken)
  * [Centreon](#centreon)
  * [Opsview](#opsview)
  * [Check\_mk](#check_mk)
  * [Sensu](#sensu)
  * [Cabot](#cabot)
  * [Server Density](#server-density)
  * [PagerDuty](#pagerduty)
  * [Nagios Monitoring Plugins](#nagios-monitoring-plugins)
  * [Nagios Monitoring Addons](#nagios-monitoring-addons)
* [Zabbix Monitoring](#zabbix-monitoring)
  * [Zabbix Monitoring Plugins](#zabbix-monitoring-plugins)
  * [Zabbix Monitoring Addons](#zabbix-monitoring-addons)
* [APM Monitoring](#apm-monitoring)
  * [collector](#collector)
  * [backend](#backend)
  * [alerting](#alerting)
  * [dashboard](#dashboard)
* [Distributed Tracing](#distributed-tracing)
  * [OpenTelementry](#opentelementry)
  * [Zipkin](#zipkin)
  * [Sentry](#sentry)
  * [Jaeger](#jaeger)
  * [Pinpoint](#pinpoint)
  * [Skywalking](#skywalking)
* [API](#api)
  * [super-devops](#super-devops)
  * [go-devops](#go-devops)
* [Incident management](#incident-management)
* [Contributing](#contributing)
* [License](#license)

***

## DC Monitoring

Tranditional Data Center Monitoring tools.

### Nagios

* [Nagios](https://www.nagios.org/) - Nagios Is The Industry Standard In IT Infrastructure Monitoring.
* [Nagios enterprise](https://www.nagios.com/) - IT Infrastructure Monitoring World Class Network, Server and Log Monitoring Software.
* [Nagios exchange](https://exchange.nagios.org/) - Nagios official exchange website.
* [Nagios core github](https://github.com/NagiosEnterprises/nagioscore) ⭐ 2,040 | 🐛 206 | 🌐 C | 📅 2026-08-07 - Nagios core written in C.
* [Nagios chinese](https://sourceforge.net/projects/nagios-cn/files/?source=navbar) - Nagios chinese document.
* [Nagios](http://canuxcheng.com/devops/Monitoring_Nagios.html) - Blog.

### Zabbix

> Zabbix is the ultimate enterprise-level software designed for real-time monitoring of millions of metrics collected from tens of thousands of servers, virtual machines and network devices. Zabbix is Open Source and comes at no cost.

* [Zabbix](https://www.zabbix.org) - The Ultimate Enterprise-class Monitoring Platform.
* [Zabbix enterprise](http://www.zabbix.com/) - Zabbix enterprise website.
* [Zabbix core](https://zabbix.org/wiki/Get_Zabbix) - Zabbix core written in C.
* [Zabbix github](https://github.com/zabbix) - Zabbix github.

### Ganglia

> Ganglia is a scalable distributed monitoring system for high-performance computing systems such as clusters and Grids.

* [Ganglia](http://ganglia.info/) - Ganglia is a scalable distributed monitoring system for high-performance computing systems.
* [Ganglia core github](https://github.com/ganglia/monitor-core) ⭐ 496 | 🐛 86 | 🌐 C | 📅 2022-01-23 - Ganglia written in C.
* [Ganglia github](https://github.com/ganglia) - Related source code.

### Zenoss

> Zenoss works with the world's largest companies to ensure their IT services and applications are always on. As the global leader in hybrid IT monitoring and analytics software, Zenoss provides complete visibility for cloud, virtual and physical IT environments.

* [Zenoss](https://www.zenoss.org/) - The Hybrid IT Monitoring Platform.
* [Zenoss enterprise](https://www.zenoss.com/) - Zenoss enterprise website.
* [Zenoss core sf](https://sourceforge.net/projects/zenoss/) - Zenoss core written in C.
* [Zenoss github](https://github.com/zenoss) - Zenoss github.

### Opserver

* [Opserver](http://opserver.org/) - Stack Exchange's monitoring system.
* [Opserver github](https://github.com/opserver/Opserver) ⭐ 4,565 | 🐛 76 | 🌐 C# | 📅 2024-11-30 - Opserver written in C#.

### Netdata

> netdata is a system for distributed real-time performance and health monitoring. It provides unparalleled insights, in real-time, of everything happening on the system it runs (including applications such as web and database servers), using modern interactive web dashboards.

* [netdata](http://my-netdata.io/) - Get control of your servers. Simple. Effective. Awesome.
* [netdata github](https://github.com/firehol/netdata) ⭐ 80,229 | 🐛 395 | 🌐 Go | 📅 2026-08-19 - Netdata written in C.

### HertzBeat

> HertzBeat is an open-source, real-time monitoring system with custom-monitor and agentless. Support web service, database, os, middleware and more.

* [HertzBeat](https://www.hertzbeat.com/) - The open-source, real-time monitoring system.
* [HertzBeat github](https://github.com/dromara/hertzbeat) ⭐ 7,364 | 🐛 316 | 🌐 Java | 📅 2026-08-18 - HertzBeat github.

***

## Nagios Monitoring

Monitoring tools based on nagios.

### Icinga

* [Icinga](https://www.icinga.org/) - Monitoring core with features and REST API.
* [Icinga exchange](https://exchange.icinga.org/) - Icinga2 official exchange website.
* [Icinga2 core github](https://github.com/Icinga/icinga2) ⭐ 2,232 | 🐛 488 | 🌐 C++ | 📅 2026-08-19 - Icinga2 core written in C++.
* [Icinga chinese](https://sourceforge.net/projects/icinga-cn/files/) - Icinga2 chinese document.

### Naemon

> Naemon is the new monitoring suite that aims to be fast, stable and innovative while giving you a clear view of the state of your network and applications.

* [Naemon](http://www.naemon.org/) - Networks, Applications and Event Monitor.
* [Naemon core github](https://github.com/naemon/naemon-core) ⭐ 171 | 🐛 49 | 🌐 C | 📅 2026-08-04 - Next generation of nagios core written in C.

### Shinken

> Shinken is a monitoring framework. It's a Python Nagios® Core total rewrite enhancing flexibility and large environment management.

* [Shinken](http://www.shinken-monitoring.org/) - Flexible and scalable monitoring framework.
* [Shinken core github](https://github.com/naparuba/shinken) ⭐ 1,136 | 🐛 228 | 🌐 Python | 📅 2024-04-26 - Shinken core written in Python.
* [Shinken exchange github](https://github.com/shinken-monitoring) - Shinken exchange.

### Centreon

> Centreon is a network, system, applicative supervision and monitoring tool.

* [Centreon plugins github](https://github.com/centreon/centreon-plugins) ⭐ 335 | 🐛 114 | 🌐 Perl | 📅 2026-08-19 - Centreon plugins.
* [Centreon core github](https://github.com/centreon/centreon-engine) ⚠️ Archived - Centreon core written in C++.
* [Centreon](https://www.centreon.com) - An industry reference for open source monitoring.

### Opsview

> Powerful monitoring for IT networks large and small, visualize all aspects of your IT at a glance.

* [Opsview](https://www.opsview.com/) - Comprehensive coverage, rapid resolution, elegant visualization.
* [Opsview core](https://www.openhub.net/p/opsview) - Opsview core written in Perl.

### check\_mk

> Check\_MK is comprehensive IT monitoring solution in the tradition of Nagios.

* [Check\_mk](http://mathias-kettner.de/check_mk.html) - Check\_mk is open source and pure python code.
* [check\_mk exchange](http://mathias-kettner.com/check_mk_exchange.php?HTML=yes) - Check\_mk plugins.
* [check\_mk core git](http://git.mathias-kettner.de/git/?p=check_mk.git;a=tree) - Check\_mk core written in Python.

### Sensu

* [Sensu](https://sensu.io/) - Monitoring for today's infrastructure.
* [Sensu github](https://github.com/sensu/sensu) ⚠️ Archived - Sensu core written in Ruby.
* [Sensu Assets](https://bonsai.sensu.io/) - Sensu plugins.
* [Sensu-plugins github](https://github.com/sensu-plugins) - Sensu plugins source code.

### Cabot

* [cabot github](https://github.com/arachnys/cabot) ⭐ 5,672 | 🐛 166 | 🌐 JavaScript | 📅 2023-09-10 - Self-hosted, easily-deployable monitoring and alerts service.

### Server Density

* [server density](https://www.serverdensity.com/) - Server monitoring.
* [server density github](https://github.com/serverdensity) - Related source code.

### PagerDuty

* [pagerduty](https://www.pagerduty.com/) - Digital Operations Management.
* [pagerduty github](https://github.com/PagerDuty) - Related source code.

### Nagios Monitoring Plugins

> The Monitoring Plugins Development Team, maintain a bundle of more than fifty standard plugins for Icinga, Naemon, Nagios, Shinken, Sensu, Centreon and Opsview.

* [monitoring-plugins](https://www.monitoring-plugins.org/) - Monitoring plugins official website.
* [monitoring-plugins github](https://github.com/monitoring-plugins) - Monitoring plugins source code.

#### Develop Plugins

> How to develop plugins for your own service.

* [monitoring plugin development guidelines](https://www.monitoring-plugins.org/doc/guidelines.html) - Plugins development document official website.

#### Plugins API

* [monitoring-plugins perl](https://github.com/monitoring-plugins/monitoring-plugin-perl) ⭐ 42 | 🐛 6 | 🌐 Perl | 📅 2021-02-02 - Official Perl module for plugins.
* [arguspy](https://github.com/crazy-canux/arguspy) ⭐ 1 | 🐛 6 | 🌐 Python | 📅 2022-12-26 - A set of Python API for write your monitoring plugins.
* [arguspy docs](http://arguspy.readthedocs.io/en/latest/) - Document for arguspy.

#### Monitoring Windows server

* [check\_wmi\_plus.pl](http://www.edcint.co.nz/checkwmiplus/) - Plugin for windows monitoring use WMI.

#### Monitoring OS X

* [OSX-Monitoring-Tools](https://github.com/jedda/OSX-Monitoring-Tools) ⚠️ Archived - Plugins used to monitoring Mac system.

#### Monitoring Linux/Unix

* [check\_hpasm.pl](https://github.com/lausser/check_hpasm) ⭐ 17 | 🐛 23 | 🌐 Perl | 📅 2025-01-13 - For Hpasm.
* [check\_fujitsu\_health.pl](https://github.com/lausser/check_fujitsu_health) ⭐ 3 | 🐛 0 | 🌐 Perl | 📅 2022-05-04 - For fujitsu.

#### Monitoring Network

* [check\_nwc\_health.pl](https://github.com/lausser/check_nwc_health) ⭐ 153 | 🐛 135 | 🌐 Perl | 📅 2026-08-10 - For nwc.

#### Monitoring Storage

* [check\_raid.pl](https://github.com/glensc/nagios-plugin-check_raid) ⭐ 144 | 🐛 40 | 🌐 Perl | 📅 2024-06-27 - For raid.
* [check\_tl\_health.pl](https://github.com/lausser/check_tl_health) ⭐ 8 | 🐛 0 | 🌐 Perl | 📅 2023-02-10 - For tl.
* [check\_sstcam.pl](https://github.com/lausser/check_sstcam) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2010-02-26 - For sstcam.

#### Monitoring Virtualization

* [check\_vmware\_esx.pl](https://github.com/BaldMansMojo/check_vmware_esx) ⭐ 122 | 🐛 17 | 🌐 Perl | 📅 2023-07-12 - For vmware.
* [check\_wmware\_api.pl](https://github.com/op5/check_vmware_api) ⭐ 42 | 🐛 1 | 🌐 Perl | 📅 2020-02-06 - For vmware.

#### Monitoring Cloud Computing

* [openstack nagios plugins](https://github.com/cirrax/openstack-nagios-plugins) ⭐ 22 | 🐛 0 | 🌐 Python | 📅 2024-05-03 - Monitoring openstack.

#### Monitoring BigData

#### Monitoring Database

* [check\_postgres.pl](https://github.com/bucardo/check_postgres) ⭐ 602 | 🐛 103 | 🌐 Perl | 📅 2025-01-02 - For postgres.
* [check\_mongodb.py](https://github.com/mzupan/nagios-plugin-mongodb) ⭐ 342 | 🐛 97 | 🌐 Python | 📅 2025-11-03 - For mongodb.
* [check\_mssql\_health.pl](https://github.com/lausser/check_mssql_health) ⭐ 38 | 🐛 38 | 🌐 Perl | 📅 2026-07-21 - For mssql.
* [check\_oracle\_health.pl](https://github.com/lausser/check_oracle_health) ⭐ 37 | 🐛 25 | 🌐 Perl | 📅 2024-01-08 - For oracle.
* [check\_mysql\_health.pl](https://github.com/lausser/check_mysql_health) ⭐ 35 | 🐛 21 | 🌐 Perl | 📅 2023-02-27 - For mysql.
* [check\_db2\_health.pl](https://github.com/lausser/check_db2_health) ⭐ 9 | 🐛 7 | 🌐 Perl | 📅 2021-07-09 - For db2.

#### Monitoring Log

* [check\_logfiles.pl](https://github.com/lausser/check_logfiles) ⭐ 48 | 🐛 44 | 🌐 Perl | 📅 2025-12-15 - For logfile.
* [check\_multi](https://github.com/flackem/check_multi) ⭐ 41 | 🐛 11 | 🌐 M4 | 📅 2020-10-17
* [check\_generic](https://github.com/flackem/check_generic) ⭐ 6 | 🐛 1 | 🌐 Perl | 📅 2012-08-18
* [check events](https://github.com/pewo/nagios-plugins) ⭐ 0 | 🐛 1 | 🌐 Perl | 📅 2024-03-09

#### Monitoring Application

* [check\_ssl\_cert](https://github.com/matteocorti/check_ssl_cert) ⭐ 417 | 🐛 16 | 🌐 Shell | 📅 2026-08-04 - For CA.
* [nagios-plugins-rabbitmq](https://github.com/nagios-plugins-rabbitmq/nagios-plugins-rabbitmq) ⭐ 194 | 🐛 24 | 🌐 Perl | 📅 2024-01-04 - For rabbitmq.
* [check\_graphite\_data.py](https://github.com/etsy/nagios_tools) ⚠️ Archived - For graphite.
* [check\_elasticsearch.py](https://github.com/anchor/nagios-plugin-elasticsearch) ⭐ 109 | 🐛 20 | 🌐 Python | 📅 2017-08-02 - For ES.
* [ceph-nagios-plugins](https://github.com/valerytschopp/ceph-nagios-plugins) ⭐ 81 | 🐛 17 | 🌐 Python | 📅 2024-03-03 - For ceph.
* [nagios-jenkins-plugin](https://github.com/jonlives/nagios-jenkins-plugin) ⭐ 42 | 🐛 14 | 🌐 Perl | 📅 2022-05-10 - For jenkins.
* [check\_sap\_health.pl](https://github.com/lausser/check_sap_health) ⭐ 15 | 🐛 8 | 🌐 Perl | 📅 2026-01-16 - For sap.
* [check\_mailbox\_health.pl](https://github.com/lausser/check_mailbox_health) ⭐ 3 | 🐛 0 | 🌐 Perl | 📅 2022-08-19 - For mailbox.
* [Celery-Nagios-Plugin](https://github.com/wilhelm-murdoch/Celery-Nagios-Plugin) - For celery.

#### Monitoring Languages

* [nagios\_erlang](https://github.com/lethain/nagios_erlang) ⭐ 41 | 🐛 1 | 🌐 Shell | 📅 2016-06-02 - Monitoring erlang

#### Monitoring SNMP

* [nagios snmp plugins](http://nagios.manubulon.com/) - For snmp.
* [nagios snmp plugins SF](https://sourceforge.net/projects/nagios-snmp/) - For snmp.

#### Misc

* [nagios plugins](https://github.com/HariSekhon/nagios-plugins) ⭐ 1,152 | 🐛 90 | 🌐 Python | 📅 2026-02-03 - HariSekhon's plugins.
* [nagios plugins](https://github.com/willixix/naglio-plugins) ⭐ 77 | 🐛 26 | 🌐 Perl | 📅 2020-06-08 - Willixix's plugins.
* [nagios plugins](https://github.com/MonitoringPlug/monitoringplug) ⭐ 61 | 🐛 4 | 🌐 C | 📅 2020-05-16 - MonitoringPlug's plugins.
* [nagios plugins](https://github.com/opinkerfi/nagios-plugins) ⭐ 58 | 🐛 15 | 🌐 Perl | 📅 2022-01-04 - opinkerfi's plugins.
* [nagios plugins](https://github.com/Inuits/monitoring-plugins) ⭐ 48 | 🐛 9 | 🌐 Perl | 📅 2025-03-27 - Inuits's plugins.
* [nagios plugins](https://github.com/kumina/nagios-plugins-kumina) ⭐ 41 | 🐛 1 | 🌐 Perl | 📅 2016-03-22 - kumina's plugins.
* [nagios plugins](https://github.com/innogames/igmonplugins) ⭐ 26 | 🐛 10 | 🌐 Python | 📅 2026-08-03 - innogames's plugins.
* [nagios plugins](https://github.com/Voxer/nagios-plugins) ⭐ 24 | 🐛 1 | 🌐 Shell | 📅 2015-04-16 - Voxer's plugins.
* [nagios plugins](https://github.com/appfirst/nagios-plugins) ⭐ 20 | 🐛 3 | 🌐 Python | 📅 2021-04-26 - appfirst's plugins.
* [nagios plugins](https://github.com/AppliedTrust/nagios-plugins) ⚠️ Archived - AppliedTrust's plugins.
* [zplugin](https://github.com/crazy-canux/zplugin) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2018-10-13 - Tons of plugins monitoring your business.

### Nagios Monitoring Addons

> This is the addon can be used for Nagios, Naemon, Icinga, Shinken, Centreon and Opsview.

* [nagios-addons github](https://github.com/NagiosEnterprises) - Nagios addons.
* [naemon-addons github](https://github.com/naemon) - Naemon addons.
* [icinga-addons github](https://github.com/Icinga) - Icinga addons.
* [shinken-addons github](https://github.com/shinken-monitoring) - Shinken addons.

#### Agent

* [NSCP github](https://github.com/mickem/nscp) ⭐ 287 | 🐛 52 | 🌐 C++ | 📅 2026-08-19 - NSCP source code.
* [NRPE github](https://github.com/NagiosEnterprises/nrpe) ⭐ 275 | 🐛 46 | 🌐 C | 📅 2026-06-11 - Nagios Remote Plugin Executor for Linux.
* [NCPA github](https://github.com/NagiosEnterprises/ncpa) ⭐ 207 | 🐛 222 | 🌐 Shell | 📅 2026-08-19 - Nagios Cross Platform Agent.
* [SNClient github](https://github.com/ConSol-Monitoring/snclient) ⭐ 75 | 🐛 15 | 🌐 Go | 📅 2026-08-19 - SNClient source code
* [NRPE\_NT SF](https://sourceforge.net/projects/nrpent/) - Nagios Remote Plugin Executor for Windows.
* [NSCP](http://nsclient.org/) - NSClient++.
* [SNClient](https://omd.consol.de/docs/snclient/) - SNClient - Cross Platform Agent (Linux, Windows, OSX)

#### Event broker

* [NDOUtils github](https://github.com/NagiosEnterprises/ndoutils) ⭐ 51 | 🐛 3 | 🌐 C | 📅 2025-03-11 - Nagios Data Output Utils, for Nagios.
* [naemon-livestatus github](https://github.com/naemon/naemon-livestatus) ⭐ 28 | 🐛 5 | 🌐 C++ | 📅 2026-06-19 - For Naemon.
* [mod-livestaus github](https://github.com/shinken-monitoring/mod-livestatus) ⭐ 15 | 🐛 40 | 🌐 Python | 📅 2019-10-01 - For Shinken.
* [IDOUtils github](https://github.com/Icinga) - Icinga Data Output Utils, for Icinga.
* [MK Livestatus](http://mathias-kettner.com/checkmk_livestatus.html) - For nagios/check\_mk.
* [MK Livestatus git](http://git.mathias-kettner.de/git/?p=check_mk.git;a=tree;f=livestatus;hb=HEAD) - Livesttus source code.

#### Distributions

* [gearman github](https://github.com/gearman/gearmand) ⭐ 763 | 🐛 50 | 🌐 C++ | 📅 2026-08-17 - Gearmand source code. A gearman job server written in C++.
* [ConSol OMD git](https://github.com/consol-monitoring/omd) ⭐ 194 | 🐛 23 | 🌐 Shell | 📅 2026-08-18 - OMD source code.
* [consol mod-gearman github](https://github.com/sni/mod_gearman) ⭐ 125 | 🐛 4 | 🌐 C | 📅 2026-08-04 - Mod-gearman source code. A gearman wroker written in C.
* [NRDP github](https://github.com/NagiosEnterprises/nrdp) ⭐ 50 | 🐛 9 | 🌐 PHP | 📅 2026-08-14 - Nagios Remote Data Processor, as a replacement for NSCA.
* [NSCA github](https://github.com/NagiosEnterprises/nsca) ⭐ 48 | 🐛 5 | 🌐 C | 📅 2024-08-01 - Nagios Service Check Acceptor, for nagios/naemon/icinga.
* [NSCA-ng github](https://github.com/weiss/nsca-ng) ⭐ 25 | 🐛 1 | 🌐 C | 📅 2026-05-25 - NSCA-ng source code.
* [op5 merlin github](https://github.com/op5/merlin) ⭐ 22 | 🐛 11 | 🌐 C | 📅 2026-07-30 - Merlin source code.
* [MK OMD](http://omdistro.org/) - The Open Monitoring Distribution, for Nagios/Naemon/Icinga/Shinken/check\_mk.
* [MK OMD git](http://git.mathias-kettner.de/git/?p=omd.git;a=tree) - OMD source code.
* [ConSol OMD](https://omd.consol.de/docs/omd/) - The Open Monitoring Distribution, for Naemon/Icinga/Prometheus/Grafana/InfluxDB/Victoriametrics.
* [NSCA-ng](http://www.nsca-ng.org/) - Next Generation of NSCA.
* [DNX](http://dnx.sourceforge.net/) - Distributed Nagios eXecutor, for Nagios/Naemon.
* [DNX github](https://github.com/DNX-Project/DNX) - DNX source code.
* [gearman](http://gearman.org/) - Gearman official website.
* [consol mod-gearman](http://www.mod-gearman.org/) - Gearman worker for Nagios/Naemon.
* [op5 merlin](https://kb.op5.com/display/MERLIN/Distributed+%28Merlin%29+Home) - For Nagios/Naemon.

#### Visualization

* [icingaweb2 github](https://github.com/Icinga/icingaweb2) ⭐ 839 | 🐛 219 | 🌐 PHP | 📅 2026-08-12 - For Icinga.
* [nagstamon github](https://github.com/HenriWahl/Nagstamon) ⭐ 458 | 🐛 141 | 🌐 Python | 📅 2026-07-29 - Nagstamon source code.
* [consol thruk github](https://github.com/sni/Thruk) ⭐ 442 | 🐛 96 | 🌐 Perl | 📅 2026-08-18 - Thruk source code.
* [nagdash github](https://github.com/lozzd/Nagdash) ⭐ 292 | 🐛 24 | 🌐 PHP | 📅 2020-04-17 - Dashboard interface for nagios.
* [nagvis github](https://github.com/NagVis/nagvis) ⭐ 121 | 🐛 77 | 🌐 PHP | 📅 2026-08-11 - Nagvis source code.
* [mod-webui github](https://github.com/shinken-monitoring/mod-webui) ⭐ 79 | 🐛 25 | 🌐 JavaScript | 📅 2025-01-10 - For Shinken.
* [op5 Ninja github](https://github.com/op5/ninja) ⭐ 31 | 🐛 11 | 🌐 PHP | 📅 2026-07-14 - Ninja source code.
* [nagmap github](https://github.com/hecko/nagmap/) ⭐ 27 | 🐛 0 | 🌐 PHP | 📅 2018-06-25 - Integration of nagios/icinga into google maps.
* [op5 Ninja](https://kb.op5.com/display/GUI/GUI+%28Ninja%29+Home) - For Nagios/Naemon.
* [consol thruk](http://www.thruk.org/) - Webinterface for Nagios/Naemon/Icinga/Shinken.
* [nagstamon](https://nagstamon.ifw-dresden.de/) - Nagios status viewer on windows.
* [coffeesaint](https://www.vanheusden.com/java/CoffeeSaint/) - Java based nagios status viewer.
* [coffeesaint github](https://github.com/flok99/CoffeeSaint) - Coffeesaint source code.
* [nagvis](http://www.nagvis.org/) - Draw map from event brokers.
* [realopinsight](http://realopinsight.com/) - Realopinsight.
* [realopinsight github](https://github.com/RealOpInsightLabs/realopinsight-workstation) - Realopinsight source code.

#### Metric Storage

* [statsd github](https://github.com/etsy/statsd) ⭐ 18,074 | 🐛 90 | 🌐 JavaScript | 📅 2025-05-20 - Daemon for easy but powerful stats aggregation.
* [graphite-whisper github](https://github.com/graphite-project/whisper) ⭐ 1,262 | 🐛 8 | 🌐 Python | 📅 2025-12-01 - Graphite whisper.
* [rrdtool github](https://github.com/oetiker/rrdtool-1.x) ⭐ 1,114 | 🐛 163 | 🌐 C | 📅 2026-08-07 - Rrdtool source code.
* [rrdtool](http://oss.oetiker.ch/rrdtool/) - Round Robin Database Tool, store perfomance data.

#### Metric Forwarding

* [graphios github](https://github.com/shawn-sterling/graphios) ⭐ 288 | 🐛 47 | 🌐 Python | 📅 2017-07-27 - A program to send nagios perf data to graphite(carbon)/statsd/librato/influxdb.
* [nagflux github](https://github.com/Griesbacher/nagflux) ⭐ 71 | 🐛 20 | 🌐 Go | 📅 2022-11-26 - A connector which copies performancedata from Nagios / Icinga(2) / Naemon to InfluxDB
* [ledbetter github](https://github.com/github/ledbetter) ⚠️ Archived - Script that scrapes alert statistics from Nagios and reports them to Graphite.

#### Metric Graphing

* [Graphite web github](https://github.com/graphite-project/graphite-web) ⭐ 6,104 | 🐛 23 | 🌐 JavaScript | 📅 2026-08-10 - Graphite web.
* [Graphite carbon github ](https://github.com/graphite-project/carbon) ⭐ 1,531 | 🐛 13 | 🌐 Python | 📅 2026-05-08 - Graphite carbon.
* [pnp4nagios github](https://github.com/lingej/pnp4nagios) ⭐ 153 | 🐛 37 | 🌐 PHP | 📅 2023-05-09 - Php4nagios source code.
* [nagiosgraph](http://nagiosgraph.sourceforge.net/) - Create graphs and store data in rrdtool.
* [nagiosgraph SF](https://sourceforge.net/projects/nagiosgraph/) - Nagiosgraph source code.
* [pnp4nagios](http://docs.pnp4nagios.org/) - Create graphs and store rrdtool.

#### Configuration

* [adagios github](https://github.com/opinkerfi/adagios) ⭐ 332 | 🐛 78 | 🌐 HTML | 📅 2024-11-07 - Adagios source code.
* [nconf github](https://github.com/nconf/nconf) ⭐ 76 | 🐛 28 | 🌐 PHP | 📅 2019-08-06 - Nconf source code.
* [nagios.vim](https://github.com/crazy-canux/nagios.vim) ⭐ 1 | 🐛 0 | 🌐 Vim Script | 📅 2025-06-22 - Vim plugin for Nagios.
* [icinga2.vim](https://github.com/crazy-canux/icinga2.vim) ⭐ 1 | 🐛 0 | 🌐 VimL | 📅 2016-06-12 - Vim plugin for Icinga2.
* [nconf](http://www.nconf.org/dokuwiki/doku.php) - Enterprise Nagios configurator.
* [adagios](http://adagios.org/) - Web based nagios configuration.

#### Procedure

* [dokuwiki](https://www.dokuwiki.org/dokuwiki/) - Dokuwiki.
* [dokuwiki github](https://github.com/splitbrain/dokuwiki) ⭐ 4,703 | 🐛 470 | 🌐 PHP | 📅 2026-08-16 - Dokuwiki source code.

#### Business Process Intelligence

* [nagiosBPI github](https://github.com/NagiosEnterprises/nagiosbpi) ⭐ 8 | 🐛 4 | 🌐 PHP | 📅 2017-06-19 - NagiosBPI.
* [BP github](https://github.com/booboo-at-gluga-de/bp-addon) ⭐ 1 | 🐛 0 | 🌐 Perl | 📅 2015-02-01 - BP source code.
* [BP](http://bp-addon.monitoringexchange.org/) - BP.

#### SNMP

* [NSTI github](https://github.com/NagiosEnterprises/nsti) ⭐ 15 | 🐛 11 | 🌐 HTML | 📅 2018-06-06 - NSTI.
* [nagios-mib github](https://github.com/nagios-plugins/nagios-mib) ⭐ 6 | 🐛 1 | 🌐 Makefile | 📅 2020-02-21 - This is the initial set of MIBs for Nagios to allow traps sent from Nagios to be recognized by other NMSes.

#### Addons API

* [nagios-api github](https://github.com/zorkian/nagios-api) ⭐ 587 | 🐛 19 | 🌐 Python | 📅 2019-05-17 - A REST-like, JSON interface to nagios.
* [pynag github](https://github.com/pynag/pynag) ⭐ 178 | 🐛 22 | 🌐 Python | 📅 2024-03-29 - Pynag source code.
* [nagiosharder github](https://github.com/railsmachine/nagiosharder) ⭐ 116 | 🐛 8 | 🌐 Ruby | 📅 2018-03-27 - Ruby API for scraping nagios.
* [nagiosvshell github](https://github.com/NagiosEnterprises/nagiosvshell) ⭐ 34 | 🐛 5 | 🌐 PHP | 📅 2019-11-05 - Nagios v-shell PHP interface.
* [nagrestconf github](https://github.com/mclarkson/nagrestconf) ⭐ 12 | 🐛 20 | 🌐 Perl | 📅 2018-06-09 - Nagrestconf.
* [pynag](http://pynag.org/) - API for managin nagios configuration and write plugins.
* [nagrestconf](http://nagrestconf.smorg.co.uk/) - A REST interface and configuration GUI for nagios.

#### Misc

* [nagios-herald github](https://github.com/etsy/nagios-herald) ⚠️ Archived - Nagios-herald source code.
* [cucumber github](https://github.com/auxesis/cucumber-nagios) ⭐ 255 | 🐛 28 | 🌐 Ruby | 📅 2022-10-19 - Cucumber source code.
* [chef-nagios-cookbook github](https://github.com/schubergphilis/nagios) ⭐ 124 | 🐛 10 | 🌐 Ruby | 📅 2026-07-30 - Chef nagios cookbook.
* [cucumber](http://cucumber-nagios.org/) - Cucumber.
* [nagios-herald](https://codeascraft.com/2014/06/06/introducing-nagios-herald/) - Customizing nagios alerts.

***

## Zabbix Monitoring

> Monitoring tools based on Zabbix.

### Zabbix Monitoring Plugins

### Zabbix Monitoring Addons

***

## APM Monitoring

Application Performance Monitoring.

Modern Monitoring tools for devops, container(kubernetes), microservice and serverless.

### Collector

Traces, Metrics, Logs.

Metrics

* [telegraf github](https://github.com/influxdata/telegraf) ⭐ 17,757 | 🐛 385 | 🌐 Go | 📅 2026-08-19 - TICK stack, The plugin-driven server agent for collecting & reporting metrics.
* [node-exporter github](https://github.com/prometheus/node_exporter) ⭐ 13,704 | 🐛 322 | 🌐 Go | 📅 2026-08-19 - Prometheus stack, Exporter for machine metrics.
* [falcon-plus github](https://github.com/open-falcon/falcon-plus) ⚠️ Archived - An open-source and enterprise-level monitoring system.
* [collectd github](https://github.com/collectd/collectd) ⭐ 3,367 | 🐛 785 | 🌐 C | 📅 2026-05-29 - collectd written in C.
* [tcollector github](https://github.com/OpenTSDB/tcollector) ⭐ 510 | 🐛 25 | 🌐 Python | 📅 2024-06-10 - Data collection framework for OpenTSDB
* [collectd](http://collectd.org/) - The system statistics collection daemon.

Logs

* [promtail github](https://github.com/grafana/loki) ⭐ 28,762 | 🐛 1,742 | 🌐 Go | 📅 2026-08-19 - log agent for loki.
* [logstash github](https://github.com/elastic/logstash) ⭐ 14,926 | 🐛 2,252 | 🌐 Java | 📅 2026-08-18 - Transport and process your logs, events, or other data, Elastic stack.
* [fluent github](https://github.com/fluent/fluentd) ⭐ 13,578 | 🐛 139 | 🌐 Ruby | 📅 2026-08-17 - Fluentd is an open-source logging solution to unify data collection and consumption.
* [beats github](https://github.com/elastic/beats) ⭐ 12,640 | 🐛 1,065 | 🌐 Go | 📅 2026-08-19 - Lightweight shippers for Elasticsearch & Logstash, Elastic stack.
* [fluent-bit](https://github.com/fluent/fluent-bit) ⭐ 8,045 | 🐛 769 | 🌐 C | 📅 2026-08-19 - Fast and Lightweight Logs and Metrics processor for Linux, BSD, OSX and Windows.

Traces

* [javamelody github](https://github.com/javamelody/javamelody) ⭐ 3,039 | 🐛 39 | 🌐 Java | 📅 2026-07-27 - The source code.
* [kamon github](https://github.com/kamon-io/Kamon) ⭐ 1,426 | 🐛 202 | 🌐 Scala | 📅 2026-01-19 - The source code.
* [new relic github](https://github.com/newrelic) - New relic written in Ruby.

### Backend

Some all-in-one APM service provide backend service.

Metrics

* [prometheus github](https://github.com/prometheus/prometheus) ⭐ 65,752 | 🐛 882 | 🌐 Go | 📅 2026-08-19 - Prometheus stack.
* [influxdata github](https://github.com/influxdata/influxdb) ⭐ 31,705 | 🐛 2,149 | 🌐 Rust | 📅 2026-08-18 - TICK stack.
* [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics/) ⭐ 17,566 | 🐛 767 | 🌐 Go | 📅 2026-08-19 - VictoriaMetrics stack.
* [hertzbeat github](https://github.com/dromara/hertzbeat) ⭐ 7,364 | 🐛 316 | 🌐 Java | 📅 2026-08-18 - An open-source, real-time monitoring system with custom-monitor and agentless.
* [OpenTSDB github](https://github.com/OpenTSDB/opentsdb) ⭐ 5,068 | 🐛 538 | 🌐 Java | 📅 2024-12-12 - OpenTSDB source code.
* [kairosDB github](https://github.com/kairosdb/kairosdb) ⭐ 1,762 | 🐛 141 | 🌐 Java | 📅 2026-03-05 - KairosDB source code.
* [influxdata](https://influxdata.com) - influxdb, written in go.
* [prometheus](https://prometheus.io/) - The Prometheus monitoring system and time series database.
* [OpenTSDB](http://opentsdb.net/) - OpenTSDB, written in java.
* [kairosDB](http://kairosdb.github.io/) - KairosDB.

Logging

* [elasticsearch github](https://github.com/elastic/elasticsearch) ⭐ 77,843 | 🐛 5,965 | 🌐 Java | 📅 2026-08-19 - Elastic stack.
* [loki github](https://github.com/grafana/loki) ⭐ 28,762 | 🐛 1,742 | 🌐 Go | 📅 2026-08-19 - Loki: like Prometheus, but for logs.
* [elasticsearch](https://www.elastic.co/cn/products/elasticsearch) - Open Source, Distributed, RESTful Search Engine, written in java.

Tracing

* [tempo github](https://github.com/grafana/tempo) ⭐ 5,442 | 🐛 173 | 🌐 Go | 📅 2026-08-19 - Grafana Tempo is a high volume, minimal dependency distributed tracing backend.
* [javamelody github](https://github.com/javamelody/javamelody) ⭐ 3,039 | 🐛 39 | 🌐 Java | 📅 2026-07-27 - The source code.
* [kamon github](https://github.com/kamon-io/Kamon) ⭐ 1,426 | 🐛 202 | 🌐 Scala | 📅 2026-01-19 - The source code.
* [new relic github](https://github.com/newrelic) - New relic written in Ruby.

### Alerting

* [grafana github](https://github.com/grafana/grafana) ⭐ 76,306 | 🐛 3,327 | 🌐 TypeScript | 📅 2026-08-19 - Grafana alerting.
* [alertmanager github](https://github.com/prometheus/alertmanager) ⭐ 8,587 | 🐛 443 | 🌐 Go | 📅 2026-08-19 - Prometheus stack, Prometheus Alertmanager, written in go.
* [kapacitor github](https://github.com/influxdata/kapacitor) ⭐ 2,374 | 🐛 833 | 🌐 Go | 📅 2026-08-10 - TICK stack, written in go.
* [x-pack](https://www.elastic.co/cn/products/x-pack) - Elastic stack.
* [Bosun](http://bosun.org/) - Time Series Alerting Framework.
* [Bosun github](https://github.com/bosun-monitor) - Bosun written in Go.

### Dashboard

* [grafana github](https://github.com/grafana/grafana) ⭐ 76,306 | 🐛 3,327 | 🌐 TypeScript | 📅 2026-08-19 - Grafana stack.
* [kibana github](https://github.com/elastic/kibana) ⭐ 21,251 | 🐛 14,272 | 🌐 TypeScript | 📅 2026-08-19 - Elastic stack.
* [chronograf github](https://github.com/influxdata/chronograf) ⭐ 1,567 | 🐛 50 | 🌐 TypeScript | 📅 2026-08-11 - TICK stack.

***

## Distributed Tracing

### OpenTelementry

all-in-one.

OpenCensus and OpenTracing have merged to form OpenTelemetry.

* [opentelementry](https://opentelemetry.io/) - High-quality, ubiquitous, and portable telemetry to enable effective observability.
* [opentelementry github](https://github.com/open-telemetry)

### Zipkin

* [zipkin github](https://github.com/openzipkin/zipkin) ⭐ 17,454 | 🐛 175 | 🌐 Java | 📅 2026-08-06 - A distributed tracing system.

### Jaeger

* [Jaeger](https://www.jaegertracing.io/)
* [Jaeger github](https://github.com/jaegertracing) - Distributed Tracing System

### Sentry

* [Sentry](https://sentry.io/welcome/) - Sentry provides open-source and hosted error monitoring that helps all software
  teams discover, triage, and prioritize errors in real-time.
* [Sentry github](https://github.com/getsentry/sentry) ⭐ 44,575 | 🐛 2,231 | 🌐 Python | 📅 2026-08-19 - Sentry is cross-platform application monitoring, with a focus on error reporting.

### Pinpoint

* [pinpoint github](https://github.com/pinpoint-apm/pinpoint) ⭐ 13,864 | 🐛 533 | 🌐 Java | 📅 2026-08-19 - APM, (Application Performance Management) tool for large-scale distributed systems.

### SkyWalking

all-in-one

* [skywalking](https://skywalking.apache.org/) - Application performance monitor tool for distributed systems, especially designed for microservices, cloud native and container-based (Kubernetes) architectures.
* [skywalking github](https://github.com/apache/skywalking) ⭐ 24,924 | 🐛 21 | 🌐 Java | 📅 2026-08-15

### Uptrace

all-in-one

* [Uptrace](https://uptrace.dev/get/open-source-apm.html) - application performance monitoring tool that supports distributed tracing, metrics, and logs. You can use it to monitor applications and set up automatic alerts to receive notifications via email, Slack, Telegram, and more.
* [Uptrace github](https://github.com/uptrace/uptrace) ⭐ 4,264 | 🐛 48 | 🌐 Go | 📅 2026-08-13

***

## API

### super-devops

* [super-devops](http://super-devops.readthedocs.io/en/latest/) - Tons of devops tools for devops related project.
* [super-devops github](https://github.com/crazy-canux/super-devops) ⭐ 10 | 🐛 17 | 🌐 Python | 📅 2025-08-09

### go-devops

* [go-devops](https://godoc.org/github.com/crazy-canux/go-devops) - Tons of devops tools for devops related project.
* [go-devops github](https://github.com/crazy-canux/go-devops) ⭐ 9 | 🐛 12 | 🌐 Go | 📅 2023-05-11

***

## Incident management

### Open Source Incident Managemenet

* [harpia](https://github.com/harpia-io/harpia) ⭐ 24 | 🐛 0 | 🌐 Shell | 📅 2023-08-15 - Centralized management of alerts from monitoring systems, with the ability to reduce noise, automate actions and enhance valuable information

***

## Contributing

[Contribution guide](CONTRIBUTING.md)

***

## Authors

[Authors](AUTHORS.md)

***

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-19._
