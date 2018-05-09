# ElasticSearch Diagnostics Run Book

## Table of Contents

1. **[Table of Contents](#table-of-contents)**
2. **[System Overview](#system-overview)**
	- [General Overview](#general-overview)
	- [Contributing Applications, Daemons, and Services](#contributing-applications-daemons-and-services)
	- [Hours of Operation](#hours-of-operation)
	- [Service Execution Design](#service-execution-design)
	- [Infrastructure and Network Design](#infrastructure-and-network-design)
	- [Resilience, Fault Tolerance, and High-Availability](#resilience-fault-tolerance-and-high-availability)
	- [Required Resources](#required-resources)
		- [ElasticSearch Resources](#elasticsearch-resources)
		- [Kibana Resources](#kibana-resources)
		- [Management Resources](#management-resources)
	- [Expected Traffic and Load](#expected-traffic-and-load)
		- [Hot or Peak Periods](#hot-or-peak-periods)
		- [Warm Periods](#warm-periods)
		- [Cool or Quiet Periods](#cool-or-quiet-periods)
	- [Tools](#tools)
3. **[Security and Access Control](#security-and-access-control)**
	- [X-Pack](#x-pack)
4. **[System Configuration](#system-configuration)**
	- [ElasticSearch Configuration](#elasticsearch-configuration)
		- [ElasticSearch Deployment Template](#elasticsearch-deployment-template)
	- [Kibana Configuration](#kibana-configuration)
		- [Kibana Deployment Template](#kibana-deployment-template)
	- [LogStash Configuration](#logstash-configuration)
		- [LogStash Deployment Template](#logstash-deployment-template)
5. **[Configuration Management](#configuration-management)**
	- [System Backup and-Restore](#system-backup-and-restore)
		- [Backup Requirements](#backup-requirements)
			- [Backup Exclusions](#backup-exclusions)
		- [Backup Procedures](#backup-procedures)
		- [Restore Procedures](#restore-procedures)
6. **[Monitoring and Alerting](#monitoring-and-alerting)**
	- [Monitoring Requirements](#monitoring-requirements)
		- [ElasticSearch Monitoring](#elasticsearch-monitoring)
		- [Kibana Monitoring](#kibana-monitoring)
		- [LogStash Monitoring](#logstash-monitoring)
	- [Common Errors](#common-errors)
	- [Health Checks](#health-checks)
7. **[Operational Tasks](#operational-tasks)**
	- [Deployment](#deployment)
		- [Local VMs](#local-vms)
		- [Azure](#azure)
		- [Deployment Backout and Recovery](#deployment-backout-and-recovery)
	- [Routine Checks](#routine-checks)
	- [Troubleshooting](#troubleshooting)
8. **[Maintenance Tasks](#maintenance-tasks)**
	- [Maintenance Procedures](#maintenance-procedures)
		- [Log Rotation](#log-rotation)
		- [Failure Testing](#failure-testing)
			- [Chaos Monkey](#chaos-monkey)
9. **[Failure and Recovery Procedures](#failure-and-recovery-procedures)**
	- [Failover](#failover)
	- [Recovery](#recovery)
	- [Troubleshooting Failover and Recovery](#troubleshooting-failover-and-recovery)
10. **[Contact Details](#contact-details)**


## System Overview

### General Overview

### Contributing Applications, Daemons, and Services

### Hours of Operation

### Service Execution Design

### Infrastructure and Network Design

### Resilience, Fault Tolerance, and High-Availability

### Required Resources

#### ElasticSearch Resources

#### Kibana Resources

#### Management Resources

### Expected Traffic and Load

#### Hot or Peak Periods

#### Warm Periods

#### Cool or Quiet Periods

### Tools

## Security and Access Control

### X-Pack

## System Configuration

### ElasticSearch Configuration

#### ElasticSearch Deployment Template

### Kibana Configuration

#### Kibana Deployment Template

### LogStash Configuration

#### LogStash Deployment Template

## Configuration Management

### System Backup and Restore

#### Backup Requirements

##### Backup Exclusions

#### Backup Procedures

#### Restore Procedures

## Monitoring and Alerting

### Monitoring Requirements

#### ElasticSearch Monitoring

#### Kibana Monitoring

#### LogStash Monitoring

### Common Errors

### Health Checks

## Operational Tasks

### Deployment

#### Local VMs

#### Azure

#### Deployment Backout and Recovery

### Routine Checks

### Troubleshooting

## Maintenance Tasks

### Maintenance Procedures

#### Log Rotation

#### Failure Testing

##### Chaos Monkey

## Failure and Recovery Procedures

### Failover

### Recovery

### Troubleshooting Failover and Recovery

## Contact Details


