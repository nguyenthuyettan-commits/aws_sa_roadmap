# 🌐 VPC & Subnet Topology Design for PV***

This document details the baseline network architecture designed for PV***'s enterprise cloud modernization footprint on AWS.

## 1. Network Architecture Diagram

Below is the logical subnet segmentation blueprint designed to isolate public-facing web interfaces from internal HR, Legal, and Financial workloads.

![PV*** VPC Network Topology](../diagrams/pv***-vpc-topology.png)

## 2. IP Addressing & CIDR Allocation Strategy

To prevent routing conflicts with PV***'s existing on-premise infrastructure, the `10.0.0.0/16` block was chosen as the dedicated cloud footprint.

| Subnet Name | Purpose | Zone | CIDR Block | Available IPs | Type |
| :--- | :--- | :--- | :--- | :--- | :--- |
| `vpc-pv***-prod` | Primary Production Network | ap-southeast-1 | `10.0.0.0/16` | ~65,536 | VPC Scope |
| `subnet-pv***-public-1a` | Public Load Balancers / Web Portals | ap-southeast-1a | `10.0.1.0/24` | 251 | Public |
| `subnet-pv***-private-hr-1a` | Internal HR Workflows & Legal Apps | ap-southeast-1a | `10.0.2.0/24` | 251 | Private |

## 3. Verification Metrics

*   [x] VPC `vpc-pv***-prod` successfully instantiated via AWS Console.
*   [x] Subnet ranges mapped and verified to avoid overlap boundaries.
