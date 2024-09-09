# cloud-cli-cheatsheet
Cheatsheet of useful commands. Aim to show where region is or isn't needed.

## AWS

### S3
* List files in a bucket
```
aws s3 ls s3://bucketname/path/of/folder/in/bucket/
```

### EC2
* Connect to an AWS instance using SSM (note - need to install plugin)
```
aws ssm start-session --target <instance ID> --region <region>
```

## Azure


## Kubernetes
