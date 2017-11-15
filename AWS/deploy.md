# deploy a node app to AWS Elastic Beanstalk

## Install the AWSEB-CLI
This example uses brew. 
```
brew install awsebcli
```
It can also be installed using pip
```
pip install awsebcli --upgrade --user
```

## Init EB
Init an EB instance in your app root directory
```
eb init
```
There are going to be a ton of stuff to plug in here. For detailed info, visit https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/eb-cli3-configuration.html

## EB Environment
```
eb create name-env
```
That command will take a while while it spins up


##### References
https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/eb-cli3.html

https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/eb-cli3-install.html