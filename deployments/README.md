# BOSH Deployment for mongodb

To use this bosh deployment manifest :

```
bosh target BOSH_HOST
bosh login
git clone ssh://git@stash.hybris.com:7999/idefix/bosh-deployment-mongodb.git
cd bosh-deployment-mongodb
bosh deployment mongodb-aws-ec2-manifest.yml
bosh deploy
```

** if you want to deploy to bosh-lite, you can use the warden/manifest _mongodb-warden-manifest.yml_.

The environments are divided by subnets:

- mongodb-dev: 10.10.120.0/24
- mongodb-test: 10.10.121.0/24
- mongodb-staged: 10.10.122.0/24
- mongodb-dprod: 10.10.123.0/24
