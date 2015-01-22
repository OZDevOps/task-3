# task-3
Start hadoop instance via Vagrant and AWS ec2

I have no enough memory to test Hadoop, so start them on AWS directly.

### set the environment, you can put it in ~/.profile

```
export AWS_ACCESS_KEY="XXXX"
export AWS_SECRET_KEY="XXXX+uN1AY"
export AWS_KEYNAME="aws.key.pair"
export AWS_KEYPATH='/Downloads/aws.key.pem'
export AWS_DEFAULT_REGION="us-west-2"
export AWS_REGION=us-west-2
```

then 

    source ~/.profile

### install AWS plug-in in Vagrant

    vagrant plugin install vagrant-aws


### install hostmanager plugin
 
    vagrant plugin install vagrant-hostmanager

### check the instance status and start them with `vagrant up`

    vagrant status
