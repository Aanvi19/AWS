Placement group types ---

1.cluster --- all the instances will be placed in one AZ , for this if any instance goes down for hardware failure all instance gonna be stop. it will use for low latency, high bandwidth, implement for big data size.
(Packs instances close together inside an Availability Zone for low-latency, high-throughput node-to-node communication.)

2.spread   -- here all the instances will be placed in multiple AZ with partition way in different AZ , every insatce will get different hardware so if one goes down other ones will be remain safe,upto 7 instance can be placed in a partition table, 
(Strictly places a small group of instances across distinct underlying hardware to reduce correlated failures.)

3.spread with partition table --- in this there will be 7 partition on each AZ, this placement will be based on the physical rack, but it will be connected to each other, hardware will be independent.
(Spreads instances across logical partitions so that groups in one partition do not share hardware with groups in different partitions.)

**How to create placement group**
```
go to ec2 > below go to the network security group > under that choose placement groups > then click on create placement group > give a name under this Placement group settings section> choose the option you want ( cluster, spread, partition)
```
note : for cluster just let it be on default format

spread --- Spread level > No restrictions > create group
partition -- choose Number of partitions > as much you want upto 7 > then create group 

**How to place instances into this placement group**
```
go to launch instance > under advanced there is a option "placement groups"> choose which one you want to which created in placement groups.
```
