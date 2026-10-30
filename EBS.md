EBS -- Elastic Block Storage

**How to create EBS**
```
ec2 > go to ebs section > choose volume > Create Volume > volume type gp3 >Size - as per desire > iops - 3000 > Throughput (MiB/s) -- 125 > AZ (Availaibility Zone) of the instace have to choose > create volume.
```

**How to attached ebs to instance**
```
select the ebs > click on action > choose attach volume > then choose Instance > Device name >attach volume
```
**For detach**
```
select the ebs > click on action > choose detach volume > then choose Instance > Device name > detach volume
```
