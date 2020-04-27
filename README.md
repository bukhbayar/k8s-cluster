## Testing K8S cluster on AWS with kops


Due to make it easy to transfer to different pipelines like bamboo or gitlab, did avoid using github action features, and tried to use more shell scripting ...



Note: if you are using LoadBalancer on AWS, just make sure run this
```
$ aws iam create-service-linked-role --aws-service-name elasticloadbalancing.amazonaws.com
```

More information :
`https://kops.sigs.k8s.io/getting_started/aws/`