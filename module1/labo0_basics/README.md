

|Deployment|Public IPv4|Connection method|Screenshot|Instance terminated?|
|-|-|-|-|-|
|1|3.101.31.94|EC2 Connect|deployment1\_4|Yes|
|2|54.193.160.134|EC2 Connect|deployment2\_4|Yes|
|3|54.177.143.218|SSH|deployment3\_3|Yes|





Deployment 1 \& 2 was easy to launch using the web browser. Created the instance template on the first attempt and used it thereafter. 

CPU tells you how much of the allocated processing power is currently in use. Memory tells you how much operating system and application memory is consumed versus free.

Disk tells you how heavily your instance reads from and writes to Amazon EBS (Elastic Block Store) volumes or instance store disks, along with storage free space.

Uptime tells you how long the virtual machine or operating system has been running continuously since its last boot or reboot.

It became easier after run 1 with the instance template made. I did have an error with the ssh login. After putting in primary information I had to respond "Yes" to allow source access. I also had to remember to incorporate the security keys in the code. The launch template has been confirmed since I used it three times.  

