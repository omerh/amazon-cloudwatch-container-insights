## k8s/1.3.6
- Upgrade cloduwatch-agent image version to cloudwatch-agent:1.247347.6b250880
- Fix container insight pod metric missing when using containerd runtime
## k8s/1.3.4
- Upgrade cloudwatch-agent image version to cloudwatch-agent:1.247347.4b250525
- Fix container insight pod metric missing when using docker systemd cgroup driver
## k8s/1.3.0
- Release Fluent-Bit for ContainerInsights log collection
## k8s/1.2.4
- Update config to support the haproxy-ingress from version 0.0.27 to latest (https://artifacthub.io/packages/helm/haproxy-ingress/haproxy-ingress)
- Update container insights k8s envname "REGION"
## k8s/1.2.3
- Merge cloudwatch-agent-prometheus image into cloudwatch-agent image 
- Upgrade cloudwatch-agent image version to 1.247346.0b249609
## k8s/1.2.2
- Upgrade cloudwatch-agent image version to 1.247345.36b249270

## k8s/1.2.1
- Update cloudwatch-agent with Prometheus monitoring ECS CloudFormation Template

## k8s/1.2.0
- Support cloudwatch-agent with Prometheus monitoring for ECS and K8S

## k8s/1.1.1
- Upgrade cloudwatch-agent image version to 1.245315.0

## k8s/1.1.0
- Upgrade cloudwatch-agent image version to 1.231221.0
- Support some other features like AWS SDK Metrics, EMF, etc

## k8s/1.0.1
- Upgrade cloudwatch-agent image version to 1.230621.0
- Upgrade fluentd image vesrion to v1.7.3-debian-cloudwatch-1.0
- Increase fluentd memory limit from 200MB to 400MB

## k8s/1.0.0 (2019-08-22)
- Initial version of Container Insights K8s
