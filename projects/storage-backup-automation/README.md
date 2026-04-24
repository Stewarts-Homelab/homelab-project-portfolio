# Storage & Backup Automation System

## Overview

This project focuses on building a reliable storage and backup system using multiple drives and automated processes. The goal was to ensure data integrity, redundancy, and efficient file management in a Linux environment.

---

## Objectives

* Configure and manage multiple storage drives (NVMe, SSD, HDD)
* Automate backups to prevent data loss
* Monitor drive health and system reliability
* Troubleshoot file system and permission issues

---

## Technologies Used

* Linux (Ubuntu)
* rsync
* cron jobs
* SMART monitoring tools
* EXT4 file system

---

## Key Implementations

### 1. Multi-Drive Storage Setup

* Configured and mounted multiple drives for different use cases
* Organized storage for media, backups, and system data

### 2. Automated Backups

* Implemented rsync for incremental backups
* Scheduled backup jobs using cron
* Verified data transfer and backup consistency

### 3. Drive Health Monitoring

* Used SMART tools to monitor disk health
* Checked for potential failures and performance issues

### 4. File System & Permissions Management

* Configured mount points and permissions
* Troubleshot access issues across directories

---

## Challenges & Troubleshooting

* File permission issues preventing access to data
* Mount configuration inconsistencies
* Managing data across multiple drives without duplication

---

## Results

* Reliable backup system with automated scheduling
* Improved data organization and storage efficiency
* Increased understanding of Linux storage systems

---

## Skills Demonstrated

* Linux system administration
* Storage management and organization
* Backup automation and scheduling
* Troubleshooting file systems and permissions
