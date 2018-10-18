# AWS Sceptre

It creates: 
- A VPC with public subnets.
- ECS Cluster with a Load Balancer.

## Requirements

- pip

## How to Install

```bash
$ pip install -r requirements.txt
```

# How to run

First, export `AWS_SECRET_KEY_ID` and `AWS_SECRET_ACCESS_KEY` or `AWS_PROFILE`, then execute:

```bash
$ sceptre launch-env prod
```
