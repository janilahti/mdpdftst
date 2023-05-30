# Introduction to Radiator® AAA Server

This document describes how to install and configure the Radiator® AAA Server (later Radiator) from Radiator Software.

RADIUS is the de facto standard protocol for authenticating users and recording accounting information. It is commonly used by Wireless Access Points (APs), Terminal Servers, and Network Access Servers (NAS), whenever a user logs on and off network access devices or dial-up Internet service. It is supported and used by most vendors, such as Cisco, Ericsson, Huawei, Juniper, Ruckus, Aruba, Alcatel-Lucent, 3Com, and US Robotics. See RFCs 2865 and 2866 for more details about the RADIUS protocol.

Radiator is a highly configurable and extensible RADIUS, TACACS+, and Diameter server that allows you to easily customise and control how to authenticate users and record accounting information. You can easily integrate Radiator with current and legacy systems and software. Radiator includes special features not found in other servers, such as user name rewriting and vendor-specific RADIUS attributes.

Radiator can authenticate users from passwords held in:

* Remote RADIUS servers (proxying)
* SQL databases, including Oracle, Microsoft SQL Server, PostgreSQL, MySQL, MariaDB, SQLite, Firebird, Sybase, Informix and others
* SQL databases that support ODBC
* LDAP
* Microsoft Active Directory
* RSA Securid
* VASCO Digipass
* YubiKey
* Duo Security
* SIP2, the 3M Standard Interchange Protocol (SIP) 2.0
* RAdmin, the RADIUS User Administration system from Radiator Software
* Flat files
* DBM files
* Unix password files and similar formats
* iPASS Roaming Network
* RSA Mobile
* Freeside billing system
* Platypus ISP billing system from ispbilling.com
* Emerald ISP billing system from IEA
* BillMax Unix ISP billing system
* Other ISP billing packages
* PAM
* TacacsPlus
* Your own legacy user database
* External programs
* Any external one-time password system
* Most external SOAP-based authentication methods
* Hotel Property Management Systems
* Other methods contributed by Radiator users

Radiator can record user accounting information in:

* Flat files in standard RADIUS detail file format
* Unix wtmp format files
* SQL databases, including Oracle, Microsoft SQL Server, PostgreSQL, MySQL, MariaDB, SQLite, Firebird, * Sybase, Informix and others
* SQL databases that support ODBC
* Remote RADIUS servers
* RAdmin, the RADIUS User Administration system from Radiator Software
* Platypus ISP billing system from ispbilling.com
* Emerald ISP billing system from IEA
* BillMax Unix ISP billing system
* Other ISP billing packages
* Your own legacy usage database
* External programs

Radiator provides external interfaces for the following protocols:

* RADIUS (including WiMAX). A full suite of load balancing modules is included.
* TACACS+
* SNMP
* Telnet
* HTTP
* Diameter
* RadSec

Radiator works with a wide range of EAP (Extensible Authentication Protocol) methods, such as the following:

* TLS
* TTLS
* PEAP
* pwd
* MD5
* MSCHAPV2
* OTP
* GTC
* LEAP
* FAST
* PAX
* PSK
* SIM
* AKA
* AKA'

Radiator runs on the following platforms:

* Most Unix and Linux hosts
* Windows 7/8/8.1/10/11
* Windows Server 2008/2012/2016/2019/2022
* macOS

Radiator is written entirely in Perl and is therefore highly portable. Full source code is supplied.
You need to be familiar with system administration to install Radiator. You also need to have a basic understanding of RADIUS and your network's authentication and accounting requirements in order to configure RADIUS.

'Radiator' and the Radiator logo are registered trademarks of Open System Consultants Pty. Ltd., a subsidiary of Radiator Software Oy.
