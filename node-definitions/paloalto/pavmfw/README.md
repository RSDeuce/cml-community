# Palo Alto PanOS Virtual Firewall Node Definitions

This directory contains a node definition for the Palo Alto VM-50 Virtual Firewall

# Image Availability

Images can be downloaded from https://support.paloaltonetworks.com with a proper account and entitlement.

## Description

This node definition provides for a Palo Alto Firewall node with two default (required) interfaces, and the ability to add 8 additional interfaces. 

Please note that the firewall takes some time to load, and will present with a login prompt "PA-HDF" that will not accept the admin / admin default credentials. The Prompt PA-VM must appear, which indicates the firewall is ready. A default IP of 192.168.1.1 is present and can be changed. 

Initial setup must be performed at the first login. Instructions below.

https://docs.paloaltonetworks.com/pan-os/10-0/pan-os-admin/getting-started/integrate-the-firewall-into-your-management-network/perform-initial-configuration.html