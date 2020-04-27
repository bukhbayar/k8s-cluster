## Testing K8S cluster on AWS with kops


Due to make it easy to transfer to different pipelines like bamboo or gitlab, I tried to avoid using github action features, and used more shell scripting.

Please feel free to correct me if I am doing something wrong here :)

Note: if you are using LoadBalancer on AWS, just make sure run this
```
$ aws iam create-service-linked-role --aws-service-name elasticloadbalancing.amazonaws.com
```

More information :
`https://kops.sigs.k8s.io/getting_started/aws/`