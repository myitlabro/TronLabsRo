We have both VM’s and bare metal machines.

We started with a main and a backup node, both virtualized. The bare metal servers hosting these virtual servers are forming a private cloud that is currently collocated in a Tier 3 Green Data Center.

**Physical servers**
A computing cluster of four nodes, each a HP Proliant with 24 Cores Xeon, 272 GB RAM, 8 TB (Raid10) + 1 TB (SSD). 
Total capacity is 96 logical CPU Cores, 1.06 TB of RAM and 18 TB of Storage.

**Virtualized servers**
For the main and backup node, our servers have the following configuration:
16-24 vCPU, 128 GB of RAM, 512 GB SSD, 10 gbps network connectivity.

**Network**
The private cloud network uplink bandwidth was increased to 4 gbps via a LACP port trunk into the core switch.


**Planned hardware expansion for Q4 2018**
Deployment of the second computing cluster till end of the year. We have the current equipment ready for Data Center delivery and monitor the usage closely. 

We also plan to continuously invest into additional hardware expansion.

**Update 13.09.2018**
We have completed a storage expansion to 16 TB. It was necesarry in order to deploy additional full nodes.

**Update 21.09.2018**
We have completed the hardware expansion ahead of Q4. It was not necesarry, but I had a lot of fun doing it.
