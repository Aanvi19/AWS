**How to create a elstic IP**
```
go to ec2>then Network security section >choose elastic ip> choose Elastic IP addresses > then under this section Network border group choose the region > just click on the allocate option then.
```

**Now attached the elastic ip to the ec2**
```
click on the elastic ip you created > click on the action > choose Associate Elastic IP address > In Resource type choose instance > under Instance choose the instance type >
under Private IP address choose the private ip of the instace > Associate.
```

**Now de-attached the elastic ip to the ec2**
```
click on the elastic ip > go to action > choose Dissociate Elastic IP address
```

**Relaease the elastic ip**
```
go to the elastic ip > choose the action > choose Release Elastic IP addresses > click on release
```

Note : Num of free elastic ip allocation are 5. we do elastic ip for attaching it to our instance for fix public ip purpose.
