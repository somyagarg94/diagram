# Resilience

## Designing for Resiliance through Development/Testing

- Multiple Environments, Scratch > Dev > QA > UAT
- microservice metrics, CPU, Memory, network
- Performance Testing  **TODO**
- Chaos Engineering **TODO**

## EKS

- Spare capacity for Horizontal Pod Autoscaling buffer **TODO**
- Cluster AutoScaling
- Nodes in 3 Zones in every VPC


## K8s

Built into helm chart deployment:

- Pod Disruption Budgets
- health checks
- Horizontal Pod Autoscaling
- Multiple Replicas of each containers
- Real Request / Limits (from performance testing ) **TODO**
- Istio: Circuit Breaking **TODO**

## AWS Managed Services in HA config for complex and stateful services

- Kafka
- Redis Cache
- Postgres RDS
- Cassandra (Key Spaces)

For public endpoints using AWS WAF/Shield
