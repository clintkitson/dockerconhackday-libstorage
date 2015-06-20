# dockerconhackday-libstorage



With the recent Docker 1.7 addition of the storage proxy API, the world of storage is now at Docker's finger tips.  But to enable Docker to function autonomously in this environment it requires the right abstractions and knowledge of storage devices.  This is critical path for allowing Docker to natively control storage devices.

This project will be focused on enabling Docker to discover common external storage devices and underlying cloud platform devices (EC2, OpenStack, Ceph, ScaleIO, multipath, and others), identify empty devices, format if necessary, and mount them to a specified mount point.
