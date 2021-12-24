# minio-as-raid

RAID is hard to deploy, config and cannot ensure data can be recover when some disk is dead.

Multi clustor of minio has that ability. 

This project want to explor a way to easily deploy a multi-clutor(instance) minio and mount it into system.


1. Auto mount minio to device
2. Auto start(deploy) multi minio for different hard devices
3. Manage interface to add/delete hard device
