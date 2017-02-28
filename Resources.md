Homelab Resources.

I have combined the resources I found interesting from /homelab, /datahorder, /homeserver and /selfhosted as well as anywhere else that had tools of interest.

My goal is to build an enterprise class network in my basement, with all the tools I find useful or interesting as well as the data tools that I am either using on a daily basis, or those I am experimenting with.  BigData is my current obsession, while my day job is managment I will always be an engineer/architect at heart.

I will try to keep track of the things I learn here and share them with the community.

One thing to note, I have no attachment to free software.  While I prefer well executed and well maintained OSS tools, I am also not tied to them.  If I was building an Enterprise network some things would need to be paid for.

That being said, there are also tons of things that can be done to manage licensing costs at home, and as I find them I will be happy to share any of the tricks I have learned along the way.

BigData Tools:
Hadoop
Horton Works
Solr
Pentaho
HCI

Databases:
MS SQL
Postgure SQL
MySQL
Hbase
Elastic
InnoDB
Cassandra


Object Store:
CEPH
HCP

Visualization:
Grafana
Banana

Home Tools (These are the things that I find particularly useful to a home user that may not have a place in the Enterprise)
Plex
Sonarr
Sabnzbd
Couchpotato
Sickbeard
Headphones
Mylar
LazyLibrarian
Pyhole

Monitoring Tools











 
Homelab Dashboard
Posts about dashboards have been growing lately and here are some of the best that were kind enough to provide us with their sources.
User	Screenshot	Source
/u/gabisonfire http://imgur.com/a/GhCNH	https://github.com/Gabisonfire/dashboard-q
/u/lastditchefrt	http://i.imgur.com/5zQdao4.png	https://github.com/d4rk22/Network-Status-Page
/u/_SleepingBag_	http://i.imgur.com/Ql9ZM4W.png	https://github.com/jsank/homelabdash
/u/NiknakSi	https://niknak.org/extras/sysinfo	TBA
/u/DainBramaged	http://imgur.com/jYNlUEQ	https://github.com/gordonturner/BigBoard
/u/michaelh4u	https://i.imgur.com/XkZwMKj.png	https://github.com/michaelh4u/homelabfrontpage
/u/spigotx	http://imgur.com/a/1zMht	https://github.com/spigotx/HomeLab2
/u/SirMaster	https://nicko88.com/	https://github.com/dashbad/plex-server-status
/u/yourofl10	http://imgur.com/a/AyROa	TBA
/u/TheBobWiley	http://imgur.com/a/oU6d3	https://github.com/TheBobWiley/ManageThis-LandingPages
/u/0110010001100010	http://i.imgur.com/iwtQcsL.jpg	https://github.com/danodemano/monitoring-scripts
/u/mescon & /u/SyNiK4L	https://i.imgur.com/gqdVM6p.jpg	https://github.com/mescon/Muximux
/u/ak_rex	http://i.imgur.com/a/RJkrT	https://github.com/ak-rex/homelab-dashboard
 
Or build yours from scratch: PRTG API, ELK, Grafana, freeboard, JumpSquares
 
Some other resources: Custom Monitoring Scripts by /u/0110010001100010
 
Credits to /u/apt64 for his original post
= Pi specific =
Pi-hole Prevents ads from even reaching you by blocking dns queries. Works as a relay between your isp's dns server (or whichever you choose). Can also work as a local dns.
RetroPie From their website: The RetroPie Project is a collection of works that all have the overall goal to turn the Raspberry Pi into a dedicated retro-gaming console.
raspnode Tutorials for installing cryptocurrency nodes on a Raspberry Pi. Participate in the Bitcoin, Litecoin, or Ethereum network. Full nodes, SPV wallets, cold storage, offline transaction signing.
flightradar24 is a flight tracking service that provides you with real-time info about thousands of aircraft around the world.
The Plane Finder is the easiest and most accurate way to share your ADS-B and MLAT data with us.
PiAware is the world's largest flight tracking data company and provides over 10,000 aircraft operators and service companies as well as over 12,000,000 passengers with global flight tracking solutions.
 
= Download Automation =
Torrent clients: Transmission, qBittorrent, uTorrent(sorry), Azureus, rTorrent, TransmissionQT to name a few Most torrent clients will support a "Black Hole" function where it will monitor a specific folder for .torrent files and automatically download them.
CouchPotato is an wesome PVR for usenet and torrents. Just fill in what you want to see and CouchPotato will add it to your "want to watch"-list. Every day it will search through multiple NZBs & Torrents sites, looking for the best possible match. If available, it will download it using your favorite download software.
SickBeard is a PVR for newsgroup users (with limited torrent support). It watches for new episodes of your favorite shows and when they are posted it downloads them, sorts and renames them, and optionally generates metadata for them.
SickRage Automatic Video Library Manager for TV Shows. It watches for new episodes of your favorite shows, and when they are posted it does its magic.
Sonarr is a PVR for Usenet and BitTorrent users.
FlexGet is a multipurpose automation tool for content like torrents, nzbs, podcasts, comics, series, movies, etc.
sabnzbd makes Usenet as simple and streamlined as possible by automating everything we can.
nzbget is a binary downloader, which downloads files from Usenet based on information given in nzb-files.
headphones is an automated music downloader for NZB and Torrent, written in Python. It supports SABnzbd, NZBget, Transmission, µTorrent and Blackhole.
 
= Virtualization =
XenServer is an open source project and community managed by Citrix. The project develops open source software for securely running multiple operating systems and applications on a single device, enabling hardware consolidation and automation to reduce costs and simplify IT management of servers and applications.
vmWare vSphere is a free bare-metal hypervisor that virtualizes servers so you can consolidate your applications on less hardware. - See more at: http://www.vmware.com/products/vsphere-hypervisor/#sthash.nxaz6a9Y.dpuf
Proxmox is a complete open source server virtualization management software. It is based on KVM virtualization and container-based virtualization and manages KVM virtual machines, Linux containers (LXC), storage, virtualized networks, and HA clusters.
VirtualBox is a general-purpose full virtualizer for x86 hardware, targeted at server, desktop and embedded use.
SmartOS is a hypervisor lean enough to run entirely in memory, powerful enough to run as much as you want to throw at it.
KVM is a full virtualization solution for Linux on x86 hardware containing virtualization extensions (Intel VT or AMD-V).
oVirt is free, open-source virtualization management platform. It was founded by Red Hat as a community project on which Red Hat Enterprise Virtualization is based.
 
= Monitoring =
Nagios is a powerful monitoring system that enables organizations to identify and resolve IT infrastructure problems before they affect critical business processes.
OMD avoids the tedious work of manually compiling and integrating Nagios addons while at the same time avoiding the problems of pre-packaged installations coming with your Linux distribution
Pandorafms is the most flexible monitoring software in the market. With a single tool, Pandora FMS can monitor everything: infrastructure, applications, services, and business progress.
PRTG Monitoring is a network monitoring software that is powerful and easy to use. Free for 100 sensors.
Zabbix is the ultimate enterprise-level software designed for real-time monitoring of millions of metrics collected from tens of thousands of servers, virtual machines and network devices.
Observium is a low-maintenance auto-discovering network monitoring platform supporting a wide range of device types, platforms and operating systems.
LibreNMS is a fully featured network monitoring system that provides a wealth of features and device support.
Cacti is a complete network graphing solution designed to harness the power of RRDTool's data storage and graphing functionality.
Munin surveys all your computers and remembers what it saw. It presents all the information in graphs through a web interface.
ZenOSS is an award winning, open source monitoring product that automatically discovers resources, without the use of agents, and provides visibility across all aspects of your IT environment whether physical, virtual or in the cloud.
AlienVault OSSIM is an open source security information and event management system. OSSIM combines Snort, OpenVAS, Nagios, OSSEC, and other tools into a single portal with log collection and correlation.
Graylog Centralize and aggregate all your log files for 100% visibility. Use our powerful query language to search through terabytes of log data to discover and analyze important information.
 
= Media Center =
Plex organizes your video, music, and photo collections and streams them to all of your screens.
Kodi, if a free and open source (GPL) software media center for playing videos, music, pictures, games, and more.
Emby brings all of your home videos, music, and photos together into one place.
OpenMediaVault is the next generation network attached storage (NAS) solution based on Debian Linux. It contains services like SSH, (S)FTP, SMB/CIFS, DAAP media server, RSync, BitTorrent client and many more.
PlexPy is a tool to easily monitor and receive notify playback events from Plex.
MediaGoblin is a free software media publishing platform that anyone can run. You can think of it as a decentralized alternative to Flickr, YouTube, SoundCloud, etc.
 
= Remote access =
Guacamole is a clientless remote desktop gateway. It supports standard protocols like VNC and RDP.
Chrome Remote Desktop allows users to remotely access another computer through Chrome browser or a Chromebook.
mRemoteNG is a fork of mRemote, an open source, tabbed, multi-protocol, remote connections manager. mRemoteNG adds bug fixes and new features to mRemote.
 
= VOIP =
Elastix is an Open Source Software to establish Unified Communications. About this concept, Elastix goal is to incorporate all the communication alternatives, available at an enterprise level, into a unique solution.
Asterisk is an open source framework for building communications applications. Asterisk turns an ordinary computer into a communications server.
FreePBX is a web-based open source GUI (graphical user interface) that controls and manages Asterisk (PBX)
 
= Networking =
pfSense is an open-source firewall/router computer software distribution based on FreeBSD.
Open vSwitch is a production quality, multilayer virtual switch licensed under the open source Apache 2.0 license.
SophosUTM Complete Unified Threat Management protection for your network, web, email, applications, and users.
SohposXG is a fully equipped software version of the Sophos XG firewall, available at no cost for home users.
feeloadbalancer is offering the Free LoadMaster to help small companies and developers by providing them with a robust and proven load balancing option.
NetWorx is a simple and free, yet powerful tool that helps you objectively evaluate your bandwidth consumption situation.
VyOS is a community fork of Vyatta, a Linux-based network operating system that provides software-based network routing, firewall, and VPN functionality.
freeIPA is an integrated Identity and Authentication solution for Linux/UNIX networked environments.
Metiix Blockade Network-Wide Malware, Tracking, & Ad Blocking (Can also run on Raspbian)
OpenVPN is an open-source software application that implements virtual private network (VPN) techniques for creating secure point-to-point or site-to-site connections in routed or bridged configurations and remote access facilities. It uses a custom security protocol that utilizes SSL/TLS for key exchange.
Smoothwall is a Free and Open Source firewall that includes its own security-hardened GNU/Linux operating system and an easy-to-use web interface.
ClearOS is an operating system for your Server, Network, and Gateway systems. It is designed for homes, small to medium businesses, and distributed environments. ClearOS is commonly known as the Next Generation Small Business Server, while including indispensable Gateway and Networking functionality.
 
= File Servers/Storage/RAID =
DrivePool is a disk pooling software
DriveBender is the class leading storage pooling technology for Microsoft Windows. Developed by Division-M, Drive Bender allows for file redundancy via file duplication, and unlike RAID, does not require any proprietary drive format or complicated setup. (Now free)
CloudExtender is local Windows storage, powered by the cloud... with optional, state of the art TNO (trust no one) file encryption built right in. Create a Windows drive or folder that maps directly to your favorite storage platform in minutes.
SnapRAID is a backup program for disk arrays. It stores parity information of your data and it recovers from up to six disk failures.
flexRAID is a family of storage data protection products that provide great flexibility and various innovations. The current product line includes: RAID over File System (RAID-F) Transparent RAID (tRAID).
freeNAS is an operating system that can be installed on virtually any hardware platform to share computer data storage over a computer network.
Rockstor is a free and open source NAS(Network Attached Storage) solution. It's a software solution and can be installed on any hardware or a virtual machine satisfying these minimum requirements.
nas4free The NAS4Free operating system can be installed on virtually any hardware platform to share computer data storage over a computer network.
Xpenology is the name of a Linux boot image, which allows to run operating system Sinology DSM on almost any hardware (not just Synology).
owncloud is a self-hosted file sync and share server.
openFiler provides a simple way to deploy and manage networked storage.
openATTIC openATTIC combines open source storage tools in such a way that their entire functionality can be managed through a central interface. Carefully matched components ensure both stability and security. Its open interface enables you to integrate openATTIC to provisioning, monitoring and backup systems.
 
= Cameras =
iSpy is the world’s most popular open source video surveillance application.
ZoneMinder is intended for use in single or multi-camera video security applications.
motioneyeOS is a Linux distribution that turns your single board computer into a video surveillance system.
Blue Iris is security camera manager. It's not free (60$ for the full version) but it was highly recommended and there doesn't seem to be any comparable free alternatives.
 
= Documentation =
DokuWiki is a simple to use and highly versatile Open Source wiki software that doesn't require a database.
gollum is a simple, Git-powered wiki with a sweet API and local frontend.
BookStack is a simple, self-hosted, easy-to-use platform for organising and storing information.
phpIPAM is an open-source web IP address management application (IPAM).
Paperwork aims to be an open-source, self-hosted alternative to services like Evernote ®, Microsoft OneNote ® or Google Keep ®.
 
= Dynamic DNS =
duckdns free dynamic DNS hosted on Amazon VPC
afraid Free DNS Hosting, Dynamic DNS Hosting, Static DNS Hosting, subdomain and domain hosting.
No-IP's mission is to provide useful, reliable and powerful services that help home users, small and large businesses and even fortune 500 companies take control over all aspects of their DNS and domain services.
Hurricane Electric DNS allows you to easily manage and maintain your forward and reverse DNS.
 
= Backup =
xapi-back is a simple backup tool for XenServer or XCP – xen hypervisors using xapi toolstack. xapi-back is a command line tool with simple and clear interface (command + options). Tool is written in python.
Veeam Endpoint Backup Free provides a simple solution for backing up Windows-based desktops and laptops.
FOG is a free, open source computer cloning solution.
ERPXE is a complete PXE solution featuring a broad range of recovery tools and various OS installations in one box.
 
= Creating network diagrams =
draw.io Free online diagram creating with export/save functions!
Gliffy Create professional-quality Flowcharts, Wireframes, UML diagrams, and more.
rackdiag Simple diagrams for racks.
blockdiag Simple diagrams for networks.
RackTables is a nifty and robust solution for datacenter and server room asset management.
 
= Guides =
IConrad's how to be a Linux sysadmin
gex80's how to be a Windows sysadmin
 
= Misc =
Pushover Send notifications to your mobile device using a simple curl request.
Awesome-selfhosted Collection of self-hosted softwares
Awesome-sysadmin Collection of system administrating tools
Visio Cafe is an independent non-profit web site for the gathering together of IT industry Visio collections.
Rancher is a software platform for deploying a private container service.
GateOne is an HTML5-powered terminal emulator and SSH client
squid is a caching proxy for the Web supporting HTTP, HTTPS, FTP, and more. It reduces bandwidth and improves response times by caching and reusing frequently-requested web pages.
Gogs is a painless self-hosted Git service.
LetsEncrypt is a new Certificate Authority. It’s free, automated, and open.
Certbot Automatically enable HTTPS on your website with EFF's Certbot, deploying Let's Encrypt certificates.
freedcamp is a social work collaboration platform with emphasis in project management. I use it to manage what I want to do on my homelab.
SpiceWorks Multiple Free IT tools, from network monitoring to inventory.
 
That's all I could come up with on top of my head + some research, passing over to you guys so we can get a nice complete list!
 
Let's try and stick with free(or mostly) softwares, let me know if you guys feel otherwise.
