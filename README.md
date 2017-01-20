# swerverless
A tiny starter package to get you going using [apex](http://apex.run) to manage your AWS Lambda projects

If you don't already have ~/.aws/config and ~/.aws/credentials set up,
copy the sample.aws.config and sample.aws.credentials files and modify
them as appropriate.

Install apex: `$ curl https://raw.githubusercontent.com/apex/apex/master/install.sh | sh`

Then, set the profile environment variable and initilize apex:

`$ export AWS_PROFILE=myapp-prod`

`$ apex init`

`$ apex deploy`
