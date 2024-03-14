Enterprise Network Design for an Engineering College
====================================================

The network infrastructure for the engineering college is designed to provide reliable connectivity and security across its four main blocks: Engineering Branches, Labs, Administrative, and 
Server Room.


Engineering Branches Block:-
---------------------------

This block accommodates five engineering branches, each with 60 students:

1) Civil Branch, 2) Mechanical Branch, 3) Electrical and Electronics Engineering (EEE) Branch 4)Electronics and Communication Engineering (ECE) Branch 5) Computer Science and Engineering (CSE) Branch


Labs Block:-
------------

This block houses five specialized labs, each with a capacity for 60 host devices:

1) Thermodynamics Lab, 2) DC Motors Lab, 3) Basic Electrical Engineering (BEE) Lab, 4)Digital Electronics, (DE) Lab 5) Java Lab


Administrative Block:-
---------------------

This block supports administrative functions with five departments:

1) HR Department, 2) Staff Room, 3) Examination Departmentb, 4)Accounts Department, (DE) Lab 5) Finance Department


Server Room Block:-
------------------

This block hosts critical servers for network operations:

1)DNS Server, 2) DHCP Server, 3) Email Server,



Network Architecture:-
======================

The network model follows a hierarchical design with three layers:

Core Layer:- 
------------
Four routers connect the blocks, facilitating high-speed interconnection and routing.


Implementation Layer:- 
----------------------
Four Layer 3 switches handle intra-block routing and provide efficient communication within each block.


Application Layer:- 
-------------------
Layer 2 switches and host devices are deployed throughout the campus for local network access.

Network Infrastructure :-
========================

Inter-VLAN Routing:-
-------------------
Implemented using switch virtual interfaces (SVIs) for seamless communication between VLANs.

Routing Protocol:-
------------------
OSPF deployed for dynamic routing in core and implementation layers, ensuring optimal traffic flow.

Security Measures:-
------------------
MD5 authentication, DHCP snooping, SSH protocol, and port security implemented to safeguard network integrity.

Dynamic IP Assignment:-
-----------------------
DHCP servers configured in each router to dynamically assign IP addresses to host devices.

Remote Access:-
---------------
SSH protocol enabled for secure remote login to L3 switches and routers.

Basic Configuration:-
--------------------
Configures passwords for console login and privilege mode access on all devices. Encrypts all passwords stored in the configuration with service password encryption.


Network Features:-
==================

VLAN Segmentation:-
-------------------
Ensures efficient traffic isolation and management with two separate VLANs for wired and wireless traffic in each department.

VTP Protocol:-
--------------
Centralizes VLAN management and simplifies VLAN configuration and propagation.

Inter-VLAN Routing:-
--------------------
Facilitates communication between VLANs using Switch Virtual Interfaces (SVIs).

Routing Protocol (OSPF):-
-------------------------
Implements OSPF for dynamic routing in the core and implementation layers, ensuring optimal traffic flow.

Authentication (MD5):-
----------------------
Secures routing protocols, mitigating the risk of unauthorized access and spoofing.

DHCP Services:-
---------------
Configures DHCP servers for network configuration and management.

DHCP Snooping:-
---------------
Protects against DHCP spoofing, safeguarding network integrity.

SSH Protocol:-
--------------
Enables secure remote access to Layer 3 switches and routers, enhancing network security.

Port Security:-
---------------
Implements port security mechanisms in Layer 2 switches to prevent MAC address spoofing and detect rogue devices.








