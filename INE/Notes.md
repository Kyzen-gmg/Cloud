# Cloud Foundations
COURSE DURATION: 3h 40m

Provisioning
Maintaining
Deletion

## Pricing Models
Capacity vs Consumption
Data transfer and Transactional costs (Egress/exfil costs)

## Cost Optimization
Azure - Advisers
AWS - Cost anomaly detection
Google - Recommender

Sizing vs Autoscale (Automated sizing depending on crtiteria set (load))

## Cloud Resource Responsibility
Everything below is Vendors Responsibility, while above = customers.
```
        Workload
        Services
    Virtual Machine
---- Management Plane ----
    Virtualization
    Physical Infrastructure
    Physical Facility
```

IAS
```
Virt
Phys. Infra.
Phys. Fac.
```

Vnet/VPC - Network
VMs/EC2 - Image

## Platform as a service

## Scalability vs Availability
- Regional Computing

# Cloud Management Concepts
COURSE DURATION: 1h 51m

## Management Responsibility
```
        Workload
        Services
        Virtual Machine
        Management Plane
        Virtualization
        Physical Infrastructure
        Physical Facility
```

IAS
Customer is responsibile for VM and up

PAS
Customer is responsible for Workload and up

SAS
Provider is responsible for Everything, Customer usually will still have the option to modify the workload; usage, IAM, adhering to best practices, and compliance.

## Security Responsibility
- Provider Responsibility
Physical Security
Infrastructure Security
Platform Security
Identity System Security
Standards Compliance

- Customer Responsibility
Identity Security
Data Security
Application Security
Standards Compliance

## Cloud Monitoring
- Resource Monitoring
- System Monitoring
    Azure Monitor
    AWS Cloudwatch
    Google Cloud Monitoring



# Fundamentals of Cloud Identity, Security, and Compliance
COURSE DURATION: 4h 38m

## Attack Targets
SaaS Identities
Cloud platform Identities
S3 Buckets or similar resources
Services (Email, Control Plane, API, Compute Instances)

## Attack Methods
Misconfigurations
Account Hijacking
Service Hijacking
Malware

Revoke
Reset
Review
Remediate
Return