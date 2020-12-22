# Palo Alto PanOS Virtual Firewall

# Image Availability

Images in qcow can be downloaded from https://support.paloaltonetworks.com with a proper account and entitlement.

# Notes

I tested with 10.0.1, but this could possibly work with any PA FW version that can be downloaded or converted to qcow format. 8.x and 9.x included. 

I am able to boot the firewall and configure it. Entitlements to PA-VM-50 firewalls are fairly cheap (appx. $200 USD) to purchase and would let you use 100% of the PA firewall technology in your lab.

There is a Node Definition provided as well, which lets you have the PA-FW appear as a firewall in your topology, however from a CML standpoint this boots as a server, and importing the image and attaching it to the default Server profile will work as well.