Buildpack for meteor projects which are already locally compiled.

Based on https://github.com/cloudfoundry-community/cf-meteor-buildpack

Simply build your app locally
```
meteor build /some/path/deploy
```
And push it to bluemix
```
cd /some/path/deploy
cf push app -b https://github.w3ibm.bluemix.net/danielius-lt/cf-meteor-pb-buildpack.git
```

