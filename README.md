# JS Build AWS Deploy
A Docker image useful for building js applications and deploying them on aws

## Example Usage
```
$ docker run --rm -it -v ~/project/path:/usr/src/app wbm/js-build-aws-deploy /bin/bash
$ npm install
$ npm run build:dev
$ aws s3 sync ./dist s3://$MY_BUCKET --delete
```

## Installed Packages
* Node v6.10.0 + NPM(get version of npm)
* AWS CLI
