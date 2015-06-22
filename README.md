
Medic OS
========

About
-----

Medic OS is a size-optimized Linux-based operating system, designed specifically
for Medic Mobile's distributed web applications. It currently runs on VMware,
VirtualBox, Hyper-V, Xen (including Amazon EC2 and Openstack), and Linux
chroot/container environments. A port for ARM v6 and ARM v7 machines (such
as the Raspberry Pi and Beaglebone Black) is in progress.

Medic OS provides a Busybox-based userspace environment, Erlang runtime,
CouchDB, Node.js, OpenSSH, a Java runtime environment, couchdb-lucene, Gammu,
gammu-json, and a number of other smaller utilities and modules. The full
compressed Medic OS distribution is less than one hundred megabytes.

Releases
--------

There is no general release at this time. For more information, please contact
Medic Mobile at http://medicmobile.org.


Getting Started with the OS
---------------------------

1. download a pre-built ISO from [here][1]
2. boot from the ISO in a virtual machine
3. point your browser to the IP address of the VM - this should be displayed at startup
4. set up an admin password


SSH access
----------

SSH access is available on port 33696.  Username is `vm`, and password is the admin password set up in _Getting Started_.


[1]: http://TODO
