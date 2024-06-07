# Kmesh Roadmap

This document defines a high level roadmap for Kesh development and upcoming releases.
Community and contributor involvement is vital for successfully implementing all desired items for each release.
The [milestones defined in GitHub](https://github.com/kmesh-net/kmesh/milestones) represent the most up-to-date plans.
The roadmap below outlines Kmesh's 2024 feature plan.

## 2024 Q1
- Support deploying kmesh with helm
- Support sliced L4 and L7 management
- Support byPass to facilitate fault isolation
- Support original source address based authorization

## 2024 Q2
- Support transparent telemetry both for L4 and L7, including accesslog, metrics and traces
- Support consistent hash loadbalancing
- Added e2e test framework and supplement some test cases
- Support dns resolution typed service 
- Automatically manage worklaods after kmesh restarted or upgraded

## 2024 Q3
- Locality aware load balancing
- Circuit breaker and ratelimiting
- Support Bpf extensibility 
- Dynamic log level setting

## 2024 Q4
- Multi cluster/network support
- mTLS support
- Provide high performance ingress gateway
