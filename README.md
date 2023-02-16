# localstack

- [AWS Service Feature Coverage](https://docs.localstack.cloud/user-guide/aws/feature-coverage/)

## Docker Compose

```
docker-compose up
```

```
curl http://localhost:4566/_localstack/health
```

```json
{
  "features": {
    "initScripts": "initialized"
  },
  "services": {
    "acm": "available",
    "apigateway": "available",
    "cloudformation": "available",
    "cloudwatch": "available",
    "config": "available",
    "dynamodb": "available",
    "dynamodbstreams": "available",
    "ec2": "available",
    "es": "available",
    "events": "available",
    "firehose": "available",
    "iam": "available",
    "kinesis": "available",
    "kms": "available",
    "lambda": "available",
    "logs": "available",
    "opensearch": "available",
    "redshift": "available",
    "resource-groups": "available",
    "resourcegroupstaggingapi": "available",
    "route53": "available",
    "route53resolver": "available",
    "s3": "available",
    "s3control": "available",
    "secretsmanager": "available",
    "ses": "available",
    "sns": "available",
    "sqs": "available",
    "ssm": "available",
    "stepfunctions": "available",
    "sts": "available",
    "support": "available",
    "swf": "available",
    "transcribe": "available"
  },
  "version": "1.4.1.dev"
}
```

### sqs

- https://stackoverflow.com/a/70063706
- https://docs.localstack.cloud/references/init-hooks/

```
docker-compose up sqs
```

## Notes

### Colima

```
$ colima status
INFO[0000] colima is running using QEMU
INFO[0000] arch: x86_64
INFO[0000] runtime: docker
INFO[0000] mountType: sshfs
INFO[0000] socket: unix://$HOME/.colima/default/docker.sock
```
