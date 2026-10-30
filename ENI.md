ENI --- Elastic Network Interface

Logical component in a VPC that represent a virtual network card.

ENI can have the following attributes --
1.primary private ipv4 , one or more secondary ipv4.
2. 1 elastic ip per private (ipv4)
3. 1 public ipv4
4.one or more security groups.

we can create ENI Independently and attached them to ec2 for failover.
it bound to a specific AZ.

**ENI Creation**
```
ec2 > go to Network & Security > under this choose Network Interfaces > click Create network interface >Give name > choose Subnet >Interface type ENA > Private IPv4 address auto assign > create network interface
```

**atached eni with ec2**
```
click on the ENI you created > go to action > attach >choose the instance you want to attach > attach.
```

**Now need to remove**
```
click on the ENI you created > go to action > detached >choose the instance you want to detach > detach.
```
**for checking the eni has attached or detach**
```
go to ec2 > choose the instance > go to network section  > under Network Interfaces section you can see
```
