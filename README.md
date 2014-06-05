# BOSH Release for mongodb

## Table of Contents
* [Usage](#usage)
* [Releases](#releases)
<br />
<br />


### <a name="usage"></a>Usage

To use this bosh release, first upload it to your bosh:

```
bosh target BOSH_HOST
git clone ssh://git@stash.hybris.com:7999/idefix/bosh-release-mongodb.git
cd bosh-release-mongodb
bosh upload release
```

### <a name="releases"></a>Releases
<table>
<tr>
  <th>Date</th>
  <th>Name</th>
  <th>Version</th>
  <th>Kafka</th>
  <th>Comment</th>
</tr>
<tr>
  <td>2014-05-29</td>
  <td>mongodb-hybris</td>
  <td>1</td>
  <td>mongodb 2.6.1</td>
  <td>Initial release</td>
</tr>
<tr>
  <td>2014-06-02</td>
  <td>mongodb-hybris</td>
  <td>2</td>
  <td>mongodb 2.6.1</td>
  <td>replica set support</td>
</tr>
<tr>
  <td>2014-06-04</td>
  <td>mongodb-hybris</td>
  <td>3</td>
  <td>mongodb 2.6.1</td>
  <td>multi zone support</td>
</tr>
<tr>
  <td>2014-06-05</td>
  <td>mongodb-hybris</td>
  <td>4</td>
  <td>mongodb 2.6.1</td>
  <td></td>
</tr>
</table>
