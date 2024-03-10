Enterprise Network Design for an Engineering College

The network infrastructure for the engineering college is designed to provide reliable connectivity and security across its four main blocks: Engineering Branches, Labs, Administrative, and 
Server Room.


Engineering Branches Block:-
============================

This block accommodates five engineering branches, each with 60 students:

1) Civil Branch, 2) Mechanical Branch, 3) Electrical and Electronics Engineering (EEE) Branch 4)Electronics and Communication Engineering (ECE) Branch 5) Computer Science and Engineering (CSE) Branch


Labs Block:-
=============

This block houses five specialized labs, each with a capacity for 60 host devices:

1) Thermodynamics Lab, 2) DC Motors Lab, 3) Basic Electrical Engineering (BEE) Lab, 4)Digital Electronics, (DE) Lab 5) Java Lab


Administrative Block:-
======================

This block supports administrative functions with five departments:

1) HR Department, 2) Staff Room, 3) Examination Departmentb, 4)Accounts Department, (DE) Lab 5) Finance Department


Server Room Block:-
===================

This block hosts critical servers for network operations:

1)DNS Server, 2) DHCP Server, 3) Email Server,



Network Architecture:-
======================

The network model follows a hierarchical design with three layers:

Core Layer:- Four routers connect the blocks, facilitating high-speed interconnection and routing.
------------

Implementation Layer:- Four Layer 3 switches handle intra-block routing and provide efficient communication within each block.
----------------------

Application Layer:- Layer 2 switches and host devices are deployed throughout the campus for local network access.
-------------------


Network Features:-
==================

VLAN Segmentation:- I impleted two separate vlan's for each department for ensures efficient traffic isolation and management.
-------------------

VTP Protocol:- I implemented vtp protocol in l-3 and l-2 switch for Centralized VLAN management and simplifying VLAN configuration and propagation.
--------------

Inter-VLAN Routing:- I implemented Switch Virtual Interfaces (SVIs) to facilitate communication between VLANs, enhancing network flexibility.
-------------------

Routing Protocol:- I implemented ospf for dynamic routing in the core and implementation layers, ensuring optimal traffic flow.
-----------------

Authentication:- I implemented MD5 authentication secures routing protocols, mitigating the risk of unauthorized access and spoofing.
---------------

DHCP Services:- I imlemented dhcp protocol via DHCP servers for network configuration and management.
---------------

DHCP Snooping:- I imlemented DHCP Snooping for Protection against DHCP spoofing, safeguarding network integrity.
---------------

SSH Protocol:- Secure remote access to Layer 3 switches and routers is enabled through SSH, enhancing network security.
--------------

Port Security:- I employ port security mechanisms in l-2 switches to prevent MAC address spoofing and detect rogue devices.
--------------

Basic Configuration:-
---------------------

Passwords are configured for console login and privilege mode access on all devices.
Service password encryption is implemented to encrypt all passwords stored in the configuration.
