# BOSH Deployment for mongodb

To use this bosh deployment manifest :

```
bosh target BOSH_HOST
bosh login
git clone ssh://git@stash.hybris.com:7999/idefix/bosh-release-mongodb.git
cd bosh-release-mongodb
bosh deployment deployments/aws/ec2/us-east/dev/mongodb-aws-ec2-us-dev.yml
bosh deploy
```

** if you want to deploy to bosh-lite, you can use the warden/manifest _mongodb-warden-manifest.yml_.

The environments are divided by subnets:

- mongodb-dev-z1: 10.10.120.0/24
- mongodb-test-z1: 10.10.121.0/24
- mongodb-staged-z1: 10.10.122.0/24
- mongodb-staged-z2: 10.10.125.0/24
- mongodb-dprod-z1: 10.10.123.0/24
