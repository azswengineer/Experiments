# <System> Run Book

## Table of Contents

1. **[Table of Contents](#table-of-contents)**
2. **[System Overview](#system-overview)**
	- [General Overview](#general-overview)
	- [Contributing Applications, Daemons, and Services](#contributing-applications-daemons-and-services)
	- [Hours of Operation](#hours-of-operation)
	- [Service Execution Design](#service-execution-design)
	- [Client Execution Design](#client-execution-design)
	- [Infrastructure and Network Design](#infrastructure-and-network-design)
	- [Resilience, Fault Tolerance, and High-Availability](#resilience-fault-tolerance-and-high-availability)
	- [Required Resources](#required-resources)
		- [<System> Servers](#<system>-servers)
			- [DFW-1 Servers](#dfw-1-servers)
			- [DFW-2 Servers](#dfw-2-servers)
			- [TYO-1 Servers](#tyo-1-servers)
			- [??? Servers](#???-servers)
		- [Diagnostic Systems](#diagnostic-systems)
			- [ElasticSearch Resources](#elasticsearch-resources)
			- [Kibana Resources](#kibana-resources)
			- [Diagnostic Management Resources](#diagnostic-management-resources)
		- [Monitoring Systems](#monitoring-systems)
		- [Client Resources](#client-resources)
	- [Expected Traffic and Load](#expected-traffic-and-load)
		- [Hot or Peak Periods](#hot-or-peak-periods)
		- [Warm Periods](#warm-periods)
		- [Cool or Quiet Periods](#cool-or-quiet-periods)
	- [Tools](#tools)
3. **[Security and Access Control](#security-and-access-control)**
	- [Login Design](#login-design)
	- [Security Administration](#security-administration)
4. **[System Configuration](#system-configuration)**
	- [System Runtime Environment Definitions](#system-runtime-environment-definitions)
	- [Label Printers](#label-printers)
	- [Local Considerations](#local-considerations)
		- [DFW-1 Configuration](#dfw-1-configuration)
		- [DFW-2 Configuration](#dfw-2-configuration)
		- [TYO-1 Configuration](#tyo-1-configuration)
		- [??? Configuration](#???-configuration)
5. **[Configuration Management](#configuration-management)**
	- [System Backup and Restore](#system-backup-and-restore)
		- [Backup Requirements](#backup-requirements)
			- [Backup Exclusions](#backup-exclusions)
		- [Backup Procedures](#backup-procedures)
		- [Restore Procedures](#restore-procedures)
6. **[Monitoring and Alerting](#monitoring-and-alerting)**
	- [Diagnostics and the Diagnostic Service](#diagnostics-and-the-diagnostic-service)
		- [ElasticSearch](#elasticsearch)
		- [Kibana](#kibana)
		- [Automated Alerts](#automated-alerts)
	- [User Error Messages](#user-error-messages)
	- [Health Checks](#health-checks)
7. **[Operational Tasks](#operational-tasks)**
	- [Deployment](#deployment)
		- [Yum Deployment](#yum-deployment)
			- [Yum Promotion](#yum-promotion)
			- [Yum Update](#yum-update)
			- [Verifying a Yum Update](#verifying-a-yum-update)
		- [Staging and Qualification](#staging-and-qualification)
			- [Staging Readiness Gate](#staging-readiness-gate)
			- [Staging Verification](#staging-verification)
			- [Updating this RunBook](#updating-this-runbook)
		- [UAT Verification](#uat-verification)
			- [UAT Readiness Gate](#uat-readiness-gate)
			- [UAT Process](#uat-process)
		- [Production Deployment](#production-deployment)
			- [Production Readiness Gate](#production-readiness-gate)
			- [Production Deployment](#production-deployment)
		- [Post-Deployment Verification](#post-deployment-verification)
		- [Backout and Recovery](#backout-and-recovery)
	- [Batch Processing](#batch-processing)
	- [Power Procedures](#power-procedures)
	- [Routine Checks](#routine-checks)
	- [Troubleshooting](#troubleshooting)
8. **[Maintenance Tasks](#maintenance-tasks)**
	- [Maintenance Procedures](#maintenance-procedures)
		- [Log Rotation](#log-rotation)
		- [Routine Restart](#routine-restart)
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

### Client Execution Design

### Infrastructure and Network Design

### Resilience, Fault Tolerance, and High-Availability

### Required Resources

#### <System> Servers

##### DFW-1 Servers

##### DFW-2 Servers

##### TYO-1 Servers

##### ??? Servers

#### Diagnostic Systems

##### ElasticSearch Resources

##### Kibana Resources

##### Diagnostic Management Resources

#### Monitoring Systems

#### Client Resources

### Expected Traffic and Load

#### Hot or Peak Periods

#### Warm Periods

#### Cool or Quiet Periods

### Tools

## Security and Access Control

### Login Design

### Security Administration

## System Configuration

### System Runtime Environment Definitions

### Label Printers

### Local Considerations

#### DFW-1 Configuration

#### DFW-2 Configuration

#### TYO-1 Configuration

#### ??? Configuration

## Configuration Management

### System Backup and Restore

#### Backup Requirements

##### Backup Exclusions

#### Backup Procedures

#### Restore Procedures

## Monitoring and Alerting

### Diagnostics and the Diagnostic Service

#### ElasticSearch

#### Kibana

#### Automated Alerts

### User Error Messages

### Health Checks

## Operational Tasks

### Deployment

#### Yum Deployment

##### Yum Promotion

##### Yum Update

##### Verifying a Yum Update

#### Staging and Qualification

##### Staging Readiness Gate

##### Staging Verification

##### Updating this RunBook

#### UAT Verification

##### UAT Readiness Gate

##### UAT Process

#### Production Deployment

##### Production Readiness Gate

##### Production Deployment

#### Post-Deployment Verification

#### Backout and Recovery

### Batch Processing

### Power Procedures

### Routine Checks

### Troubleshooting

## Maintenance Tasks

### Maintenance Procedures

#### Log Rotation

#### Routine Restart

## Failure and Recovery Procedures

### Failover

### Recovery

### Troubleshooting Failover and Recovery

## Contact Details


